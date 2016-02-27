---
navigation: Notes
title: Dev Notes
description: install flatCore in less than 5 minutes
keywords: requirements, server, php, pdo
---

### Templates

Einige Templates werden direkt aus flatCore angesteuert. Diese Templates müssen sich also im Ordner <code>styles/deinTempate/templates/</code> befinden.

List of required Template Files:

* index.tpl ... Ist das erste Template welches geladen wird. Von hier aus kannst du all deine anderen Template-Dateien verknüpfen.
* 404.tpl ... Wird beim HTTP-Statuscode 404 angezeigt (Seite nicht gefunden)
* registerform.tpl ... Enthält das Formular um sich als Benutzer zu registrieren.
* profile_main.tpl ... Hier können Benutzer ihr Profil aktualisieren.
* status_message.tpl ... Hier werden Systemmeldungen ausgegeben.
* statusbox.tpl ... Hier werden die Links zum ACP (bei Administatoren) oder zum Profil angezeigt.
* loginbox.tpl ... Zeigt das Formular zur Anmeldung (kann im ACP deaktiviert werden).
* searchresults.tpl ... Zeigt die Suchergebnisse an.
* password.tpl ... Das Formular um sein Passwort zurückzusetzen.

### Modules

Der bewusst minimalistisch gehaltene Kern von flatCore bedeutet nicht, dass es für umfangreichere Projekte bzw. Aufgaben nicht geeignet wäre. Eben, um den Kern des Systems so einfach wie nur möglich zu halten, wurde von Beginn an auf eine leicht zu bediehnende Schnittstelle für Module und Plugins gesorgt.

Ein Modul ist eine Ansammlung von Bibliotheken und Scripts o.ä. und kann über das Backend gesteuert, administriert, aktiviert, deaktiviert ... werden.
Module müssen sich im Ordner <code>modules/</code> befinden.

### Plugins

Ein Plugin ist ein PHP Script, welches per include() z.B. per 

		[script]plugin.php[/script]

in eine Seite eingebunden wird.
Plugins müssen sich im Ordner <code>content/plugins/</code> befinden.

### Hacking
