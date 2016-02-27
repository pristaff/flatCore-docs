---
navigation: Languages
title: Languages
description: The language files can be easily edited or expanded.
keywords:
---

# Language files

All language files are located in the directory <code>/lib/lang/</code>.

A language file consists of the files dict-backend.php (the ACP), dict-frontend.php (for the frontend) and dict-install.php (for the installation process). Furthermore there must be a the file index.php which contains the description of the language file:

```php
<?php
/**
 * language file | german
 */
$lang_sign = "de";
$lang_desc = "Deutsch";
?>
```

The translations are stored in the following format:
```php
$lang['key'] = "String";
```

### Expand / edit language files

It is not recommended to edit the language files (except, of course, improvements on the GitHub repository). In case of an update these changes would be overwritten.

The default language files can be expanded in a simple manner. Save a new language file in /content/plugins/.

Example: <code>/content/plugins/lang_en.php</code>

The content must be structured in the same way as the default language files, (array $lang).

Example:

```php
// file: /content/plugins/lang_en.php
$lang['crumpy_cat'] = "Crumpy Cat";
```
```php
// file: /content/plugins/lang_de.php
$lang['crumpy_cat'] = "Mürrische Katze";
```