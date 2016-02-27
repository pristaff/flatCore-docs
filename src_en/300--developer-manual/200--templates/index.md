---
navigation: Templates
title: Create your own Template
description: Manuals and Notes for creating Templates and Styles
keywords: templates, plugins, server, php, pdo
---

### Templates & Styles

This file is not complete. Feel free to contribute to improve the documentation.



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