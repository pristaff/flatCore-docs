---
navigation: Datenbanken
title: Datenbanken
description: flatCore CMS und PDO/SQLite
keywords: Datenbanken, SQLite
---

# Datenbanken

## Die Standard Datenbanken

flatCore legt nahezu alle Daten in SQLite Datenbanken ab. Diese befinden sich im Ordner /content/SQLite/.

## Mehrere Datenbanken nutzen

Um eine flatCore-Installation auf verschiedenen Domains einzusetzen, gibt es die Möglichkeit die Inhalte auf verschiedene Datenbanken zu verteilen. Bei der Standardinstallation werden die Inhalte in die Datei /content/SQLite/content.sqlite gespeichert. Um mehrere Datenbanken zu nutzen kannst du folgendermaßen vorgehen.

1. Dupliziere die Datei und benenne sie um.
2. Erstelle bzw. modifiziere die Datei /content/config.php. Hier muss ein Array mit den Content Dateien rein. Achte darauf, dass diese Dateien auch wirklich existieren.
3. Lege fest, wann welche der Datenbanken im Frontend aktiv ist.

Beispiel:

```php
// Datei config.php
// Datenbanken für das ACP bereitstellen
$fc_content_files = array (
 array (
 'file' => 'content.sqlite3',
 'desc' => 'Standard SQLite Datenbank'
 ),
 array (
 'file' => 'content_copy.sqlite3',
 'desc' => 'Eine Kopie der Datenbank'
 )
);
```

Im ACP wird nun automatisch angezeigt, welche Datenbank gerade aktiv ist. Du kannst die Datenbank jederzeit Wechseln.

Nun kannst Du in der Datei config.php noch Regeln für das Frontend hinterlegen.

Beispiel:

```php
// Datei config.php
if($_SERVER['HTTP_HOST'] == 'subdomain.example.com') {
   $fc_db_content = FC_CONTENT_DIR . "/SQLite/content_copy.sqlite3";
}
```

In der Datenbank-Datei sind folgende Dinge gespeichert:

* RSS-Feeds
* Alle Seiten
* Textbausteine (sowohl die Systemabhängigen Einträge als auch die Snippets, welche man frei anlegen kann)
* Einstellungen

Es ist also sehr einfach, mehrere Domains mit einer flatCore-Installation zu betreiben. Die Benutzerdatenbank bleibt im übrigen unberührt. Alle Benutzeraccounts haben also für beide (oder mehrere) Domains Gültigkeit.

Voraussetzung für diese Funktion ist Version
<code>$fc_version_build = '45';</code>