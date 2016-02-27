---
navigation: Textvorlagen
title: Textvorlagen
description: Textvorlagen bearbeiten und verwenden
keywords: acp, textvorlagen
---

# Textvorlagen

Wenn man bestimmte Textphrasen mehr als einmal benötigt, kann diese als Textvorlage (Snippet) gespeichert werden.
Diese Texvorlagen findet man unter ACP | Seiten | Textvorlagen.

Der WYSIWYG-Editor kann hier deaktiviert werden. Dies ist hilfreich, wenn man komplexe HTML Strukturen hinterlegen möchte.

In den Seiteninhalt wird dieser Inhalt per snippet Tag eingebunden. In diesem Beispiel heißt die Textvorlage "signatur".

<code>[snippet]signatur[/snippet]</code>

Auch in den Templates können Snippets verwendet werden. Dazu wird der Prefix `$fc_snippet_*` verwendet.
```
/* Textvorlage: signatur */
$fc_snippet_signatur
```
