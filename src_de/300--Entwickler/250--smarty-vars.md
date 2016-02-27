---
navigation: Smarty
title: Smarty Variablen
description: Eine Liste der Smarty-Variablen und deren Funktion
keywords: Templates, Themes, Smarty
---

<p class="alert alert-info">
<strong>Achtung:</strong> Diese Liste ist noch nicht vollständig, wird aber ständig erweitert.
</p>
 
<table class="table">
<thead>
	<tr>
		<th>Variable</th>
		<th>Template</th>
		<th>Art</th>
		<th>Funktion/Inhalt</th>
	</tr>
</thead>
<tbody>
<tr class="even"><td>$SCRIPT_NAME</th><td>global</th>
<td>string</td>
<td>Der Dateiname des aktuellen Scripts</td>
</tr>
<tr class="odd"><th>$arr_bcmenue</th><th>global</th>
<td>array</td>
<td>Die Brotkrümelnavigation</td>
</tr>
<tr class="even"><th>$arr_lastedit</th><th>global</th>
<td>array</td>
<td>Die zuletzt aktualisierten Seiten</td>
</tr>
<tr class="odd"><th>$arr_menue</th><th>global</th>
<td>array</td>
<td>Die Hauptnavigation</td>
</tr>
<tr class="even"><th>$arr_mostclicked</th><th>global</th>
<td>array</td>
<td>Die Seiten mit den meißten Hits</td>
</tr>
<tr class="odd"><th>$body_template</th><th>global</th>
<td>string</td>
<td>Der Dateiname des aktuellen Templates</td>
</tr>
<tr class="even"><th>$button_login</th><th>global</th>
<td>string</td>
<td>Beschriftung/Button</td>
</tr>
<tr class="even"><th>$fc_end_time</th><th>global</th>
<td>string</td>
<td>Zeitstempel</td>
</tr>
<tr class="odd"><th>$fc_inc_dir</th><th>global</th>
<td>string</td>
<td>Das Root Verzeichnis</td>
</tr>
<tr class="even"><th>$fc_pageload_time</th><th>global</th>
<td>string</td>
<td>Ladezeit</td>
</tr>
<tr class="odd"><th>$fc_sitemap</th><th>global</th>
<td>string</td>
<td>Sitemap (&lt;ul&gt;&lt;li&gt;...&lt;/li&gt;&lt;/ul&gt;</td>
</tr>
<tr class="even"><th>$fc_start_time</th><th>global</th>
<td>string</td>
<td>Zeitstempel</td>
</tr>
<tr class="odd"><th>$homelink_status</th><th>global</th>
<td>string</td>
<td>CSS Klasse ("active ...)</td>
</tr>
<tr class="even"><th>$label_login</th><th>global</th>
<td>string</td>
<td>Beschriftung/Button</td>
</tr>
<tr class="odd"><th>$label_psw</th><th>global</th>
<td>string</td>
<td>Beschriftung/Button</td>
</tr>
<tr class="odd"><th>$languagePack</th><th>global</th>
<td>string</td>
<td>Wird durch das Kürzel des aktuellen Sprachpakets ersetzt (de, en ...)</td>
</tr>
<tr class="even"><th>$legend_login</th><th>global</th>
<td>string</td>
<td>Beschriftung</td>
</tr>
<tr class="odd"><th>$link_home</th><th>global</th>
<td>string</td>
<td>Adresse&nbsp;zur Startseite</td>
</tr>
<tr class="even"><th>$link_register</th><th>global</th>
<td>string</td>
<td>Beschriftung</td>
</tr>
<tr class="odd"><th>$login_box</th><th>global</th>
<td>string</td>
<td>&nbsp;</td>
</tr>
<tr class="even"><th>$msg_register</th><th>global</th>
<td>string</td>
<td>Message</td>
</tr>
<tr class="odd"><th>$p</th><th>global</th>
<td>string</td>
<td>Die Seiten ID</td>
</tr>
<tr class="even"><th>$page_content</th><th>global</th>
<td>string</td>
<td>Inhalt der aktuellen Seite</td>
</tr>
<tr class="odd"><th>$page_extracontent</th><th>global</th>
<td>string</td>
<td>Optionaler Inhalt der aktuellen Seite</td>
</tr>
<tr class="even"><th>$page_global_extracontent</th><th>global</th>
<td>string</td>
<td>Optionaler Inhalt (Systemeinstellungen)</td>
</tr>
<tr class="odd"><th>$page_head_enhanced</th><th>global</th>
<td>string</td>
<td>&nbsp;</td>
</tr>
<tr class="even"><th>$page_keywords</th><th>global</th>
<td>string</td>
<td>Die "Tag Wolke"</td>
</tr>
<tr class="odd"><th>$page_meta_author</th><th>global</th>
<td>string</td>
<td>Der Author der aktuellen Seite</td>
</tr>
<tr class="even"><th>$page_meta_date</th><th>global</th>
<td>string</td>
<td>Datum der letzten Aktualisierung</td>
</tr>
<tr class="odd"><th>$page_meta_description</th><th>global</th>
<td>string</td>
<td>Meta Descrition der aktuellen Seite</td>
</tr>
<tr class="even"><th>$page_meta_enhanced</th><th>global</th>
<td>string</td>
<td>Meta Tags der aktuellen Seite</td>
</tr>
<tr class="odd"><th>$page_meta_keywords</th><th>global</th>
<td>string&nbsp;</td>
<td>Keywords der aktuellen Seite</td>
</tr>
<tr class="even"><th>$page_meta_robots</th><th>global</th>
<td>string</td>
<td>Meta Tag "Robots"</td>
</tr>
<tr class="odd"><th>$page_thumbnail</th><th>global</th>
<td>string</td>
<td>Thumbnail der aktuellen Seite</td>
</tr>
<tr class="even"><th>$page_title</th><th>global</th>
<td>string</td>
<td>Seitentitel der aktuellen Seite</td>
</tr>
<tr class="odd"><th>$prefs_pagesglobalhead</th><th>global</th>
<td>string</td>
<td>Erweiterte Header-Angaben (Systemeinstellungen)</td>
</tr>
<tr class="even"><th>$prefs_pagesubtitle</th><th>global</th>
<td>string</td>
<td>Seiten-Untertitel</td>
</tr>
<tr class="odd"><th>$prefs_pagetitle</th><th>global</th>
<td>string</td>
<td>Seitentitel (Systemeinstellungen)</td>
</tr>
<tr class="even"><th>$show_forgotten_psw_link</th><th>global</th>
<td>string</td>
<td>Link zur Seite "Passwort vergessen"</td>
</tr>
<tr class="odd"><th>$show_register_link</th><th>global</th>
<td>string</td>
<td>Link zur Seite "Registrieren"</td>
</tr>
<tr class="even"><th>$status_msg</th><th>global</th>
<td>string</td>
<td>Message</td>
</tr>
<tr class="odd"><th>$textlib_footer</th><th>global</th>
<td>string</td>
<td>Text im Footer (Systemeinstellungen)</td>
</tr>
<tr class="odd"><th>$lang_*</th><th>global</th>
<td>string</td>
<td>
<p>Alle Einträge aus den Sprachdateien können in den Templates verwendet werden.</p>
<p>Beispiel:<br>Sprachdatei: <code>$lang['legend_login'] = "Anmelden";</code><br>Template: <code>$lang_legend_login</code></p>
</td>
</tr>
<tr class="odd"><th>&nbsp;</th><th>&nbsp;</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr class="odd"><th>$user_nick</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Benutzername des aktuellen Benutzers</p>
</td>
</tr>
<tr class="odd"><th>$get_firstname</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Vorname</p>
</td>
</tr>
<tr class="odd"><th>$get_lastname</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Nachname</p>
</td>
</tr>
<tr class="odd"><th>$get_street</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Straße</p>
</td>
</tr>
<tr class="odd"><th>$get_nr</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Hausnummer</p>
</td>
</tr>
<tr class="odd"><th>$get_zip</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Postleitzahl</p>
</td>
</tr>
<tr class="odd"><th>$get_city</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Stadt</p>
</td>
</tr>
<tr class="odd"><th>$send_about</th><th>profile_main.tpl</th>
<td>string</td>
<td>Freitext "Über mich"</td>
</tr>
<tr class="odd"><th>&nbsp;</th><th>&nbsp;</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr class="odd"><th>&nbsp;</th><th>&nbsp;</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr class="odd"><th>&nbsp;</th><th>&nbsp;</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr class="odd"><th>&nbsp;</th><th>&nbsp;</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
</tbody>
</table>