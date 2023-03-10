<p align="left">
  <img width="150" height="150" src="https://github.com/0xsyr0/Obsidian-Snippets/blob/main/images/obsidian.png">
</p>

# Obsidian Snippets

A collection of `Obsidian.md` snippets for generating engagement reports.

## Snippet Folder Path

Create a `.css`file like in the following example.

```c
.obsidian/snippets/<SNIPPET_NAME>.css
```

Then enable it in the `Appearance`tab in the settings.

## Line Break

```html
<br/>
```

## Multiple Line Break

```html
<pre>




</pre>
```

## Align Text Justified

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

## Page Break

```html
<div style="page-break-after: always; visibility: hidden">
\pagebreak
</div>
```
