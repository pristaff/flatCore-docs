---
title: install flatCore CMS
description: install flatCore CMS in less than five Minutes
keywords: install, PHP, mod_rewrite, SQLite
---

## Technical requirements

The system does not require any extraordinary components.

* PHP 5.5+
* with PDO/SQLite Module

PDO/SQLite is supposed to be active by default.

So far successfully tested webhosts are (alphabetical order):

* 1und1 - http://hosting.1und1.de/
* all-inkl.com - http://all-inkl.com
* domainFactory - https://www.df.eu/de/webhosting/
* Hosteurope - https://www.hosteurope.de
* Strato - https://www.strato.de

## Install

Download latest stable Version from http://www.flatcore.org or latest Build from https://github.com/flatCore/flatCore-CMS

The installation takes only a few minutes.

### mod_rewrite

__Important:__ for using mod_rewrite you have to rename the file ___htaccess__ in __.htaccess__. Filenames that begin with a dot are reserved for the system itself (on Windows or Mac OS you can't name the file .htaccess). Therefore, upload the file first and rename it direct on the webserver.

### Sequence

* Upload all the files to your Server
* Navigate in your Browser to the /install/ directory.
* Enter the desired information for an administrator.
* Hit the Install Button
* If it is installed successfully, navigate to the directory /acp/ and log in with your access data.