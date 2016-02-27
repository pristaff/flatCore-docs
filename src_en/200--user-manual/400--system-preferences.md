---
navigation: System & Preferences
title: System & Preferences
description: Here are the system settings such as the default theme.
keywords: acp, system, einstellungen
---

Here you can specify the settings for the entire page. Nearly all the entries are self-explanatory.

#### Page title / Subtitle

The default page title (can be overwritten in each page). Depending on the active template, this information may appear at different locations.

#### System E-Mail

This information will be used for shipping the system emails. For example, when the confirmation link will be sent to a new user.


#### Global Headers (HTML)

Here you can, for example, link Javascript libraries or save CSS specifications. This information is loaded into each page. A typical example would be the Google Analytics code.


#### Backup

All database files can be downloaded to the local computer by a single click. For security reasons, there is no upload function for these files. To activate a backup again, the SQLite file(s) must be uploaded via FTP to the directory <code>/content/SQLite/</code>.

To save space, older statistics databases (<code>logfile***. Sqlite3</code>) can be deleted directly from the here.

***

## Updates

#### Auto Update __(Beta)__

Once an update is available, you see a message in the ACP / settings. Clicking on __Update__ starts the script. This function updates __all__ necessary directories and files. Also "blucent" the default template will be completely replaced.

#### Manual Update (recommended)

A manual update is done in a few minutes.

* Download the latest version from http://www.flatCore.org or [GitHub](https://github.com/flatCore/flatCore-CMS).
* Replace all directories and files through the current<br>__Exceptions:__<br> The directory /content/ - here are stored all your data. The directory /styles/ - if you use your own themes, you may only replace the folder /styles/blucent/.
* Open your browser and navigate to the directory /install/ (if you are not logged in, you need the user data of an administrator to start the script).


