---
navigation: Themes
title: flatCore Developer - Themes und Templates
description: Die Optik wird per Templates gesteuert. Was man beim erstellen eines eigenen Templates beachten sollte findest Du hier.
keywords: Templates, Themes, Smarty, HTML, CSS, JavaScript
---

## Das Templatesystem

Als Templatesystem kommt smarty zum Einsatz. Wer ein eigenes Template erstellen möchte, sollte sich also zunächst mit der smarty Dokumentation vertraut machen.

### Besonderheiten

Ein Template ist nicht nur für das Aussehen Deiner Website verantwortlich, sondern kann auch die Optik bzw. die Funktionen des Editors tinyMCE steuern. Damit kannst Du erreichen, dass sich die WYSIWYG Ansicht so nah als möglich am Original-Layout (also dem Frontend) orientiert.

Zwei Dateien sind dafür maßgeblich verantwortlich:

* styles/deinTemplate/css/editor.css
* styles/deinTemplate/js/tinyMCE_config.js

Die CSS Datei ist für das Aussehen der Inhalte im Editor verantwortlich. Dies ist der einfachste Weg, den Editor an Dein Layout anzupassen. Die JavaScript Datei ist für die Konfiguration zuständig. Weitere Informationen findest Du in der tinyMCE Dokumentation.

### Die Templates (.tpl Dateien)

Einige Templates werden direkt aus flatCore angesteuert. Diese Templates müssen sich also im Ordner styles/deinTempate/templates/ befinden.

* __index.tpl__ ... Ist das erste Template welches geladen wird. Von hier aus kannst du all deine anderen Template-Dateien verknüpfen.
* __404.tpl__ ... Wird beim HTTP-Statuscode 404 angezeigt (Seite nicht gefunden)
* __registerform.tpl__ ... Enthält das Formular um sich als Benutzer zu registrieren.
* __profile\_main.tpl__ ... Hier können Benutzer ihr Profil aktualisieren.
* __status\_message.tpl__ ... Hier werden Systemmeldungen ausgegeben.
* __statusbox.tpl__ ... Hier werden die Links zum ACP (bei Administatoren) oder zum Profil angezeigt.
* __loginbox.tpl__ ... Zeigt das Formular zur Anmeldung (kann im ACP deaktiviert werden).
* __searchresults.tpl__ ... Zeigt die Suchergebnisse an.
* __password.tpl__ ... Das Formular um sein Passwort zurückzusetzen.