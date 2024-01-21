# Display Types in HTML and CSS

## Block and Inline Display

### Block

A **block element** generates line breaks before and after itself, creating a block of content. It typically has a default width of 100% of the parent container. Here is a list of block-level HTML elements:

- `<address>`
- `<article>`
- `<aside>`
- `<blockquote>`
- `<div>`
- `<dl>` (Definition List)
- `<fieldset>`
- `<figcaption>`
- `<figure>`
- `<footer>`
- `<form>`
- `<h1>` to `<h6>` (Heading Elements)
- `<header>`
- `<hr>` (Horizontal Rule)
- `<main>`
- `<nav>`
- `<ol>` (Ordered List)
- `<p>` (Paragraph)
- `<pre>` (Preformatted Text)
- `<section>`
- `<table>`
- `<ul>` (Unordered List)

### Inline

An **inline element** does not create line breaks before or after itself. It does not have a default width and allows content to flow without interruption. Here are some inline-level HTML elements:

- `<a>` (Anchor)
- `<abbr>` (Abbreviation)
- `<acronym>` (Acronym)
- `<b>` (Bold)
- `<br>` (Line Break)
- `<code>` (Code)
- `<em>` (Emphasis)
- `<i>` (Italic)
- `<img>` (Image)
- `<label>`
- `<q>` (Quotation)
- `<span>`
- `<strong>` (Strong Importance)
- `<sub>` (Subscript)
- `<sup>` (Superscript)
- `<textarea>`
- `<time>`
- `<var>` (Variable)

## Flex

**Flex** is used to create flexible containers, enabling a flexible layout for its child elements. When a container is set to `display: flex;`, it becomes a flex container, and its direct child elements become flex items. Flex operates along two axes: the main axis and the cross axis.

### Properties for Alignment

- **justify-content:**
  - `space-between`: The first item is flush with the start, the last is flush with the end.
  - `stretch`: Distribute items evenly. Stretch 'auto'-sized items to fit the container.
- **align-content:**
  - Sets the distribution of space between and around content items along a flexbox's cross-axis or a grid's block axis.
- **align-items:**
  - Sets the `align-self` value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

### Margins

**Margins** create extra space around an element, defining the space between an element's borders and the adjacent elements.

### Padding

**Padding** controls the inner spacing of an element, defining the space between the element's content and its borders.
