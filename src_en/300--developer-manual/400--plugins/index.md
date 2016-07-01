---
navigation: Plugins
title: Create your own MPlugins
description: Manuals and Notes for creating Plugins
keywords: plugins, php, sqlite
---

# What is a Plugin

A Plugin is nothing else than a simple PHP Script file. All files, which are located in the folder ```/content/plugins/``` are listet in the ACP at the Plugin section.

## Some Tipps & Tricks

Let's start with a simple example Plugin:

```PHP
<?php
/**
 * this plugin prints only hello world
 * file: /content/plugins/hw.php
 */

$plugin = array();
$plugin['title'] = 'Your Title';
$plugin['description'] = '<p>Your Desription</p>';
$plugin['version'] = '1.0';
$plugin['author'] = 'Jon Doe, example.com';

if(FC_SOURCE == 'frontend') {
	echo 'Hello World';
}
?>
```

Now write in the Editor the Shortcode ```[plugin=hw.php][/plugin]``` and the Plugin's Code will will be executed exactly at this point. In this example, the Shortcode is simply replaced by "Hello World". The Informations from ```$plugin``` will be shown in the plugins listing at the ACP.

You can pass variables and values to your Plugin. The Shortcode ```[plugin=hw.php]foo=bar[/plugin]``` means in your Plugin ```$foo = 'bar'```

### Here are some useful snippets

```PHP
if(FC_SOURCE !== 'backend') {
	// execute your Code only in the frontend
}

//Prevent direct access
if(!defined("FC_CORE_DIR")) {
	 header("Location: ../../index.php");
}

// get the current URL without domain
global $fct_slug;

```

