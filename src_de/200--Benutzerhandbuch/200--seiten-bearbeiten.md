---
navigation: Seiten bearbeiten
title: Seiten anlegen, bearbeiten, löschen
description: flatCore CMS - Seiten anlegen, bearbeiten, löschen
keywords: acp, bearbeiten, löschen, erstellen
---

# Seiten anlegen, bearbeiten, löschen

### Position/Reihenfolge

Hier wird die Position festgelegt, an der die Seite einsortiert wird. Seiten können als Startseite, Hauptnavigation oder als Unterseite definiert werden. Die Reihenfolge bestimmt, wie der Name schon sagt, die Reihenfolge in der die Seiten später aufgelistet werden.

### Link-Name

Gebe hier den Text ein, der in der Hauptnavigation bzw. in den Untermenüs als Name der Seite angezeigt werden soll.

### Permalink

Sollte die mod_rewrite Funktion (Datei config.php) aktiviert sein, benötigt flatCore diese Angabe um die Seite zuzuordnen.

Beispiel:

Permalink = news/ lädt die Seite <code>deinedomain.de/news/</code>

### Titel

Der Seitentitel wird zum einen in der Titelleiste des Browsers angezeigt. Zum anderen kann der Titel, je nach verwendetem Template, auch im Inhalt der Seite angezeigt werden.

### Inhalt

Über den Tab Inhalt und Extra-Inhalt werden, wie der Name schon sagt, die Inhalte der Seite gespeichert. Der WYSIWYG-Editor erleichtert Dir die Eingabe von formatierten Texten, sowie Bilder und Grafiken. Der optionale Inhalt ist dem eigentlichen Inhalt untergeordnet. Je nach Template kann dieser an unterschiedlichen Stellen erscheinen. Das Standard-Template "blucent" lädt den optionalen Inhalt in die rechte Spalte, unterhalb der Unternavigation.

### Author

Gebe hier Deinen Namen ein (Author dieser Seite). Bei einer neuen Seite erscheint hier automatisch Dein Name, sofern Du ihn in Deinem Profil hinterlegt hast. Beim bearbeiten einer bestehenden Seite, erscheint der bereits gespeicherte Name.

### Schlüsselwörter

Die Schlüsselwörter (Keywords) werden durch Kommata getrennt eingegeben.

### Beschreibung

Beschreibe den Inhalt Deiner Seite, kurz & knackig. Tipp: Google zeigt die ersten 160 Zeichen aus diesem Text in den Suchergebnissen.

### Robots

Hier legst Du fest, ob Suchmaschinen Deine Seite auslesen dürfen (noindex, index, nofollow, all).

### Sonstige (HTML)

Hier können weitere HTML Kopfdaten eingetragen werden z.B. um externe Javascript- oder CSS Dateien zu laden.

### Styles (CSS)

Hier kannst Du weitere CSS Definitionen hinterlegen (diese CSS Angaben gelten dann nur für diese Seite).

### Einstellungen

Diese Einstellungen beeinflussen die Funktion der Seite maßgeblich (Sprache, Templates, Module, Status, Benutzergruppen und Bearbeitung erlauben).

### Sprache

Bei mehrsprachigen Websites können mit dieser Angabe die Seiten nach Sprachen getrennt werden. Damit eine Sprache in der Auswahl erscheint, muss diese Sprachdatei auch installiert sein.

### Eigenes Template

Hier erscheinen alle installierten Templates. Du kannst also jeder Seite ein eigenes Layout zuordnen. Modul In dieser Auswahl erscheinen die installierten Module. Sobald ein Modul ausgewählt wurde, wird der vom Modul generierte Inhalt an den eigentlichen Inhalt der Seite angehängt.

### Status

* Öffentliche Seiten<br>sind für alle Besucher sichtbar. Sie werden in der Sitemap gelistet, in den Suchergebnissen aufgeführt und in den Cache-Files gespeichert.
* Unsichtbare Seiten<br>können von jedem (der die URL kennt) aufgerufen werden. Unsichtbare Seiten erscheinen nicht in den Suchergebnissen, der Sitemap oder den Listen "Zuletzt aktualisiert" etc.
* Private Seiten<br>können nur von Administratoren bzw. von bestimmte Benutzergruppen eingesehen werden.
* Entwürfe<br> sind nur aus dem ACP heraus aufrufbar. Sie werden also weder bei der Suche noch in der Sitemap gelistet. Außerdem können nur Administratoren darauf zugreifen. Diese Funktion kann bei nicht ganz fertigen Seiten bzw. zu Präsentationszwecken hilfreich sein.

### Benutzergruppe auswählen

Solltest Du mit Benutzergruppen arbeiten, kannst Du einzelne Seiten einer bestimmten Gruppe zuordnen. Damit ist diese Seite nur für Mitglieder dieser Benutzergruppe sichtbar (Administratoren haben natürlich generell zugriff auf alle Seiten).

### Bearbeitung erlauben

Administratoren, welche eigentlich keine neuen Seiten anlegen bzw. besetehende bearbeiten dürfen, erhalten hiermit Zugriffsrechte für diese einzelne Seite.