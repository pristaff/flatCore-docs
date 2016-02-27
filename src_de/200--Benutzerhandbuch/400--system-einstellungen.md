---
navigation: System & Einstellungen
title: System und Einstellungen
description: Hier werden System-Einstellungen wie z.B. das Standard-Layout festgelegt.
keywords: acp, system, einstellungen
---

#### Seitentitel & Untertitel

Werden neue Seiten erstellt und keine Seitentitel vergeben, wird dieser als "Ersatz" angezeigt. Je nach verwendetem Template können diese Angaben an unterschiedlichen Stellen erscheinen.

#### E-Mail

Diese Angaben werden für den Versand der System E-Mails verwendet. Z.B. wenn der Bestätigungslink an einen neuen Benutzer versendet wird.

#### Benutzereinstellungen

Hier kannst du festlegen ob sich neue Benutzer registrieren können und ob der Link zum Registrierungsformular öffentlich ist.

#### Uploads

Diese Regeln gelten für das Upload-Formular.

#### Globale Headerangaben (HTML)

Hier kannst du z.B. Javascript Bibliotheken verlinken oder CSS Angaben speichern. Diese Angaben werden in jede einzelne Seite geladen. Ein typisches Anwendungsbeispiel wäre der Google Analytics Code.

#### Layout & Design

Hier kannst Du das Standard-Template sowie ein Thumbnail für deine Seiten auswählen. Sowohl das Template als auch das Thumbnail kann in jeder einzelnen Seite wieder überschrieben werden.

Unterstützt das ausgewähle Theme erweiterte Optionen, erscheinen diese im Formular darunter.

#### Datensicherung

Hier können die Datenbanken auf den lokalen Rechner heruntergeladen werden. Aus Sicherheitsgründen gibt es jedoch keine Upload-Funktion für diese Datenbanken. Um ein Backup wieder zu aktivieren, muss die SQLite-Datei(en) per FTP in das Verzeichnis /content/SQLite/ kopiert werden.

Um Speicherplatz zu sparen, kann man ältere Statistik-Datenbanken (logfile***.sqlite3) direkt aus dem ACP löschen.

***

## flatCore aktualisieren

#### Automatisches Update __(Beta)__

Sobald ein Update für deine installierte Version verfügbar ist, wird dir im ACP in den Einstellungen eine Meldung angezeigt. Mit einem Klick auf __Update__ wird das Script gestartet. Diese Funktion aktualisiert __alle__ benötigten Verzeichnisse und Dateien. Auch das Template "blucent" wird hier aktualisiert bzw. komplett ersetzt.

#### Manuelles Update (empfohlen)

Ein manuelles Update ist in wenigen Minuten erledigt.

* Die aktuelle Version von hier oder [GitHub](https://github.com/flatCore/flatCore-CMS) laden.
* Alle Verzeichnisse und Dateien durch die aktuellen ersetzen<br>__Ausnahmen:__<br> Das Verzeichnis /content/ - hier sind alle deine Daten gespeichert. Das Verzeichnis /styles/ - wenn Du eigene Themes gespeichert hast, darfst du hier nur den Ordner /styles/blucent/ ersetzen.
* Im Browser das Verzeichnis /install/ aufrufen (falls Du nicht angemeldet bist, musst du hier die Benutzerdaten eines Administrators eingeben um das Script zu starten).


