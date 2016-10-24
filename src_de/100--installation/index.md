---
navigation: Installation
title: flatCore installieren
description: Installiere flatCore in weniger als 5 Minuten
keywords: requirements, server, php, pdo
---

## Technische Voraussetzungen

Das System benötigt keine ausergewöhnichen Komponenten.

* PHP 5.5 oder neuer
* aktiviertes PDO/SQLite Modul

PDO/SQLite ist Standardmäßig aktiviert.

Bisher erfolgreich getesteten Webhoster sind (alphabetische Reihenfolge):

* 1und1 - http://hosting.1und1.de/
* all-inkl.com - http://all-inkl.com
* domainFactory - https://www.df.eu/de/webhosting/
* Hosteurope - https://www.hosteurope.de
* Strato - https://www.strato.de

## flatCore installieren

Die Installation dauert nur wenige Minuten.

### mod_rewrite

__Wichtig:__ Damit mod_rewrite funktioniert, muss die Datei ___htaccess__ in __.htaccess__ umbenannt werden. Dateinamen die mit einem Punkt beginnen sind bei den meißten Systemen für das System selbst vorbehalten. Darum ist es am einfachsten Du benennst die Datei erst um, wenn Du sie auf den Server kopiert hast.

### Die Installation

* Alle Dateien auf den Server kopieren (kann auch in ein Unterverzeichnis sein).
* Im Webbrowser das Verzeichnis /install/ aufrufen und den Anweisungen folgen.
* Die gewünschten Daten für einen Administrator eingeben.
* Auf "Installation starten" klicken.
* War die Installation erfolgreich, führt der nächste Weg in das ACP. Im Browser das Verzeinis /acp/ aufrufen und mit den Zugangsdaten des Administrators anmelden.