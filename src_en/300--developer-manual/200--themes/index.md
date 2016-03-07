---
navigation: Themes
title: Create your own Themes
description: Manuals and Notes for creating Themes, Templates and Styles
keywords: templates, plugins, server, php, smarty
---

### Templates & Styles

<p class="alert alert-info">This Page is not complete. <a class="nowrap" href="https://github.com/flatCore/flatCore-docs/blob/master/{$filepath_orig}">Feel free to contribute/improve this file</a>.</p>

The used Template Engine of flatCore is Smarty - [Dokumentation](http://www.smarty.net/documentation).

#### Folder and File structure

All Themes are located in the directory <code>/styles/</code> in the Root of flatCore.

* theme-folder
		* css (Directory for your CSS files)
		* images (Directory for your images)
					* preview.png (Preview of the Theme)
		* js  (Directory for JavaScript files)
		* php  (Directory for PHP Scripts)
					* definitions.php
					* index.php
					* options.php
		* templates  (Directory for .tpl Files - see list below)
		* info.xml (File with Theme informations)
		* readme.html (Readme-File for your Theme)

#### The file /themes/xyz/definitions.php

Overwrite Variables from the Original-Source <code>/core/definitions.php</code>.

#### The file /themes/xyz/index.php

This file extends the basic Text Parser. You can inject your Code by the function <code>theme_text_parser()</code>

```php
/**
 * example
 * return the whole page in uppercase
 */
function theme_text_parser($str) {
	
	$str = strtoupper($str);

	return $str;
}

```

#### The file /themes/xyz/options.php

This file has an impact on both the frontend and the backend.



### The .tpl files

Some templates may be addressed directly by flatCore. These templates must therefore located in the directory <code>styles/yourTempate/templates/</code>.

#### List of required Template Files:

* __index.tpl__ ... The first template which is loaded. From here you can link to all your other template files.
* __404.tpl__ ... Displayed when an HTTP status code 404 (Page not found)
* __registerform.tpl__ ... The form new users can sign up
* __profile\_main.tpl__ ... The Profile page.
* __status\_message.tpl__ ... The system messages are displayed here.
* __statusbox.tpl__ ... Here are the links to the Backend (for Administrators) or the profile page.
* __loginbox.tpl__ ... Displays the registration form (can be disabled in the preferences).
* __searchresults.tpl__ ... Displays the search results.
* __password.tpl__ ... The form to reset the password.