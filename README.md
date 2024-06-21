<p align="left">
  <img width="150" height="150" src="images/obsidian.png">
</p>

# Obsidian Snippets

A collection of `Obsidian.md` snippets for generating engagement reports.

## Table of Contents

- [Basics](#basics)
	- [Tags](#tags)
	- [Snippet Folder Path](#snippet-folder-path)
- [Plugins](#plugins)
- [Formatting](#formatting)
	- [Line Break](#line-break)
	- [Multiple Line Breaks](#multiple-line-breaks)
	- [Align Text Justified](#align-text-justified)
	- [Page Break](#page-break)
 	- [Center Images](#center-images)
  	- [Center Headlines](#center-headlines)
 - [Templates](#templates)

## Basics

### Shortcuts

| Combination | Command |
| --- | --- |
| Ctrl+p | Command Prompt Menu |

### Tags

```yaml
---
tags:
  - <TAG>
  - <TAG>
  - <TAG>
---
```

### Snippet Folder Path

Create a `.css`file like in the following example.

```c
.obsidian/snippets/<SNIPPET_NAME>.css
```

Then enable it in the `Appearance`tab in the settings.

## Plugins

* Admonition
* Advanced Tables
* Better Word Count
* Calendar
* Code Block Enhancer
* File Explorer Note count
* Full Calendar
* Git
* Iconize
* Icons
* Kanban
* Paste URL into selection
* Table of Contents
* TagFolder
* Tag Wrangler

## Formatting

### Line Break

```html
<br/>
```

### Multiple Line Breaks

```html
<pre>




</pre>
```

### Align Text Justified

```css
/* reading mode */
.markdown-preview-view p {
	text-align: justify;
	text-justify: inter-word;	
}

/* source view and live preview */
.markdown-source-view.mod-cm6 .cm-line {
	text-align: justify;
	text-justify: inter-word;	
}
```

### Page Break

```html
<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>
```

### Center Images

```css
img[alt*="center"] {
    display: block;
    margin-left: auto;
    margin-right: auto;
}
```

```css
![[image.png | center | 256]]
```

### Center Headlines

```c
<center><h1>TEXT</h1></center>
```

## Templates

```c
---
Category: "[[<CATEGORY>]]"
tags:
  - <TAG>
  - <TAG>
  - <TAG>
---

![](banner.png)

## Table of Contents

- [[#<HEADING_2>]]
  - [[#<HEADING_3>]]
  - [[#<HEADING_3>]]
  - [[#<HEADING_3>]]
  - [[#<HEADING_3>]]
- [[#<HEADING_2>]]
- [[#<HEADING_2>]]
- [[#<HEADING_2>]]

## <HEADING_2>

### <HEADING_3>

#### <HEADING_4>
```
