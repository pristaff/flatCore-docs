---
navigation: Database
title: Databases
description: flatCore CMS and PDO/SQLite
keywords: Database, SQLite, PDO
---

# Databases

## The default Database

flatCore stores nearly all data in SQLite3 databases. These are located in the directory /content/SQLite/.

## Use more than one database

To use one flatCore installation on different domains, it is possible to distribute the content in different databases. The default database file is located in <code>/content/SQLite/content.sqlite</code>. To access multiple databases, you can proceed as follows.

1. Duplicate the file <code>content.sqlite3</code> and rename it.
2. Create or modify the file <code>/content/config.php</code> to Determine when and which the database is active (see the Example below).

Example:

```php
// File /content/config.php
// Databases
$fc_content_files = array (
 array (
 'file' => 'content.sqlite3',
 'desc' => 'Default SQLite Database'
 ),
 array (
 'file' => 'content_copy.sqlite3',
 'desc' => 'Just a Copy'
 )
);
```

In the Backend you can choose now which database is currently active. You can change the database at any time.

Now you can define your rules for the frontend.

Example:

```php
// File /content/config.php
if($_SERVER['HTTP_HOST'] == 'subdomain.example.com') {
   $fc_db_content = FC_CONTENT_DIR . "/SQLite/content_copy.sqlite3";
}
```

In the database file <code>content.sqlite3</code> are stored the following contents:

* RSS-Feeds
* All Pages
* Snippets
* Preferences


The user database <code>user.sqlite3</code> remains unaffected. So all Admin/User-Accounts are active in both (or more) installations.
