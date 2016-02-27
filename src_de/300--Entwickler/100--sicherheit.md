---
navigation: Sicherheit
title: flatCore Developer - Mehr Sicherheit für flatCore
description: Die Sicherheit von flatCore kann mit wenigen Handgriffen effektiv erhöht werden. Hier einige Tipps.
keywords: Datenbanken, SQLite, .htaccess
---

### Der Ordner "content"

In diesem Verzeichnis werden alle Daten von flatCore gespeichert. Dieser Ordner benötigt also Schreibrechte (CHMOD777). Um einen unerlaubten Schreib- oder Lesezugriff auf dieses Verzeichnis zu verhindern kann man

* Den Ordner per .htaccess Datei schützen
* Den Ordner außerhalb des Document Root ablegen<br>Wird der Ordner /content/ verschoben, müssen die Pfade in der Datei config.php angepasst werden.

<pre>define('FC_CONTENT_DIR', "content");</pre>

#### Allgemeine Hinweise

Alle Passwörter werden zwar verschlüsselt in der Datenbank abgelegt, dennoch sollte man bei der Wahl seiner Passwörter etwas Kreativität walten lassen. Tools wie z.B. 1Password sind hier wirklich sehr zu empfehlen.