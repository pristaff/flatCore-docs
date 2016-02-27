---
navigation: Sprachen
title: flatCore Developer - Sprachen bearbeiten oder erweitern
description: Die Sprachdateien können einfach bearbeitet oder erweitert werden.
keywords: Datenbanken, SQLite
---

# Sprachdateien

Alle Sprachdateien befinden sich im Ordner <code>/lib/lang/**</code>.

Eine Sprachdatei besteht aus den Dateien dict-backend.php (für das ACP), dict-frontend.php (für das Frontend) und dict-install.php (für den Installationsvorgang). Außerdem muss sich im Ordner eine index.php mit der Beschreibung der Sprachdatei befinden:

```php
<?php
/**
 * language file | german
 */
$lang_sign = "de";
$lang_desc = "Deutsch";
?>
```

Die Übersetzungen sind als array() nach folgendem Muster abgelegt:
```php
$lang['key'] = "String";
```

### Sprachdateien erweitern/bearbeiten

Es ist nicht zu empfehlen, die Sprachdateien zu bearbeiten oder zu erweitern (ausgenommen sind natürlich Verbesserungen über das GitHub Repository). Bei einem Update würden diese Änderungen wieder überschrieben werden.

Die Standard-Sprachdateien können auf einfache Art und Weise erweitert und/oder überschrieben werden. Dazu muss lediglich im Verzeichnis /content/plugins/ eine Datei angelegt werden.

Beispiel: <code>/content/plugins/lang_de.php</code>

Der Inhalt muss nach dem gleichen Schema wie die Standard-Sprachdateien aufgebaut sein, also ein Array $lang.

Beispiel: <code>$lang['foo'] = 'bar';</code>

