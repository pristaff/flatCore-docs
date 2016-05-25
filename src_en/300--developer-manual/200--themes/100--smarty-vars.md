---
navigation: Smarty
title: Smarty Vars
description: A list of Smarty variables and their function
keywords: Templates, Themes, Smarty
---

<p class="alert alert-info">
<strong>Important:</strong> This list is not yet complete, but is constantly expanding.
</p>
 
<table class="table">
<thead>
	<tr>
		<th>Variable</th>
		<th>Template</th>
		<th>Type</th>
		<th>Assignment/Content</th>
	</tr>
</thead>
<tbody>
<tr class="even"><td>$SCRIPT_NAME</th><td>global</th>
<td>string</td>
<td>File name of the current script</td>
</tr>
<tr class="odd"><th>$arr_bcmenue</th><th>global</th>
<td>array</td>
<td>The breadcrumb navigation</td>
</tr>
<tr class="even"><th>$arr_lastedit</th><th>global</th>
<td>array</td>
<td>Most recently updated pages</td>
</tr>
<tr class="odd"><th>$arr_menue</th><th>global</th>
<td>array</td>
<td>Main navigation</td>
</tr>
<tr class="even"><th>$arr_mostclicked</th><th>global</th>
<td>array</td>
<td>The most popular pages</td>
</tr>
<tr class="odd"><th>$body_template</th><th>global</th>
<td>string</td>
<td>File name of the current Template</td>
</tr>
<tr class="even"><th>$button_login</th><th>global</th>
<td>string</td>
<td>Text/Button</td>
</tr>
<tr class="even"><th>$fc_end_time</th><th>global</th>
<td>string</td>
<td>Timestamp</td>
</tr>
<tr class="odd"><th>$fc_inc_dir</th><th>global</th>
<td>string</td>
<td>The Root Directory</td>
</tr>
<tr class="even"><th>$fc_pageload_time</th><th>global</th>
<td>string</td>
<td>Load time</td>
</tr>
<tr class="odd"><th>$fc_sitemap</th><th>global</th>
<td>string</td>
<td>Sitemap (&lt;ul&gt;&lt;li&gt;...&lt;/li&gt;&lt;/ul&gt;</td>
</tr>
<tr class="even"><th>$fc_start_time</th><th>global</th>
<td>string</td>
<td>Timestamp</td>
</tr>
<tr class="odd"><th>$homelink_status</th><th>global</th>
<td>string</td>
<td>CSS Class ("active ...)</td>
</tr>
<tr class="even"><th>$label_login</th><th>global</th>
<td>string</td>
<td>Text/Button</td>
</tr>
<tr class="odd"><th>$label_psw</th><th>global</th>
<td>string</td>
<td>Text/Button</td>
</tr>
<tr class="odd"><th>$languagePack</th><th>global</th>
<td>string</td>
<td>Replaced by the abbreviation of the current language pack (de, en ...)</td>
</tr>
<tr class="even"><th>$legend_login</th><th>global</th>
<td>string</td>
<td>Text</td>
</tr>
<tr class="odd"><th>$link_home</th><th>global</th>
<td>string</td>
<td>URL of the homepage</td>
</tr>
<tr class="even"><th>$link_register</th><th>global</th>
<td>string</td>
<td>Text</td>
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
<td>Page ID</td>
</tr>
<tr class="even"><th>$page_content</th><th>global</th>
<td>string</td>
<td>Content of the current page</td>
</tr>
<tr class="odd"><th>$page_extracontent</th><th>global</th>
<td>string</td>
<td>Content of the current page</td>
</tr>
<tr class="even"><th>$page_global_extracontent</th><th>global</th>
<td>string</td>
<td>Content of the current page (from Preferences)</td>
</tr>
<tr class="odd"><th>$page_head_enhanced</th><th>global</th>
<td>string</td>
<td>&nbsp;</td>
</tr>
<tr class="even"><th>$page_keywords</th><th>global</th>
<td>string</td>
<td>Tags</td>
</tr>
<tr class="odd"><th>$page_meta_author</th><th>global</th>
<td>string</td>
<td>Content of the current page (Author)</td>
</tr>
<tr class="even"><th>$page_meta_date</th><th>global</th>
<td>string</td>
<td>Last updated</td>
</tr>
<tr class="odd"><th>$page_meta_description</th><th>global</th>
<td>string</td>
<td>Meta Descriptions</td>
</tr>
<tr class="even"><th>$page_meta_enhanced</th><th>global</th>
<td>string</td>
<td>Meta Tags</td>
</tr>
<tr class="odd"><th>$page_meta_keywords</th><th>global</th>
<td>string&nbsp;</td>
<td>Keywords</td>
</tr>
<tr class="even"><th>$page_meta_robots</th><th>global</th>
<td>string</td>
<td>Meta Tag "Robots"</td>
</tr>
<tr class="odd"><th>$page_thumbnail</th><th>global</th>
<td>string</td>
<td>Thumbnail</td>
</tr>
<tr class="even"><th>$page_title</th><th>global</th>
<td>string</td>
<td>Page title</td>
</tr>
<tr class="odd"><th>$prefs_pagesglobalhead</th><th>global</th>
<td>string</td>
<td>Extended header information (from Preferences)</td>
</tr>
<tr class="even"><th>$prefs_pagesubtitle</th><th>global</th>
<td>string</td>
<td>Page subtitle (from Preferences)</td>
</tr>
<tr class="odd"><th>$prefs_pagetitle</th><th>global</th>
<td>string</td>
<td>Title (from Preferences)</td>
</tr>
<tr class="even"><th>$show_forgotten_psw_link</th><th>global</th>
<td>string</td>
<td>Link: Forgot Password</td>
</tr>
<tr class="odd"><th>$show_register_link</th><th>global</th>
<td>string</td>
<td>Link: "Register"</td>
</tr>
<tr class="even"><th>$status_msg</th><th>global</th>
<td>string</td>
<td>Message</td>
</tr>
<tr class="odd"><th>$textlib_footer</th><th>global</th>
<td>string</td>
<td>Text/Footer (from Preferences)</td>
</tr>
<tr class="odd"><th>$lang_*</th><th>global</th>
<td>string</td>
<td>
<p>All entries from the language files can be used in the templates.</p>
<p>Example:<br>Language file: <code>$lang['legend_login'] = "Anmelden";</code><br>Template: <code>$lang_legend_login</code></p>
</td>
</tr>
<tr class="odd"><th>&nbsp;</th><th>&nbsp;</th>
<td>&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr class="odd"><th>$user_nick</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Username of the current user</p>
</td>
</tr>
<tr class="odd"><th>$get_firstname</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Firstname</p>
</td>
</tr>
<tr class="odd"><th>$get_lastname</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Lastname</p>
</td>
</tr>
<tr class="odd"><th>$get_street</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Street</p>
</td>
</tr>
<tr class="odd"><th>$get_nr</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Number</p>
</td>
</tr>
<tr class="odd"><th>$get_zip</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>Zip</p>
</td>
</tr>
<tr class="odd"><th>$get_city</th><th>profile_main.tpl</th>
<td>string</td>
<td>
<p>City</p>
</td>
</tr>
<tr class="odd"><th>$send_about</th><th>profile_main.tpl</th>
<td>string</td>
<td>Text "About me"</td>
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
