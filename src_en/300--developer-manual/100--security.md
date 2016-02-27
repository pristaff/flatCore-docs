---
navigation: Security
title: More Security for flatCore
description: The safety of flatCore can be increased with little effort effectively. Here are some tips.
keywords: Database, SQLite, .htaccess
---

### The folder "content"

flatCore it's generated data will be stored in the directory /content/. So, this folder needs full read and write rights (CHMOD777). To prevent unauthorized read or write access to this directory you can

* protect it via .htaccess (recommended)
* put the folder outside the document root (don't forget to adapt the paths in config.php).

```php
define('FC_CONTENT_DIR', "content");
```

#### General information

All passwords are encrypted while stored in the database, but you should exercise some creativity in choosing your passwords.