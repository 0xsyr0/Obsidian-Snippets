<p align="left">
  <img width="150" height="150" src="https://github.com/0xsyr0/Obsidian-Snippets/blob/main/images/obsidian.png">
</p>

# Obsidian Snippets

A collection of `Obsidian.md` snippets for generating engagement reports.

## Table of Contents

- [Basics](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#basics)
	- [Tags](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#tags)
	- [Snippet Folder Path](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#snippet-folder-path)
- [Plugins](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#plugins)
- [Formatting](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#formatting)
	- [Line Break](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#line-break)
	- [Multiple Line Breaks](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#multiple-line-breaks)
	- [Align Text Justified](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#align-text-justified)
	- [Page Break](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#page-break)
 - [Templates](https://github.com/0xsyr0/Obsidian-Snippets/blob/main/README.md#templates)

## Basics

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

- Admontion
- Advanced Tables
- Better Word Count
- Code Block Enhancer
- Editor Syntax Highlight
- File Explorer Note Count
- Git
- Iconize
- Icons

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

## Templates

```c
![](banner.png)

Tags: #<TAG> #<TAG> #<TAG>

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
