# BLOCK and INLINE display
## Block
- Generates line breaks before and after the element creating block of content.
- Has default width 100% of parent
- Block-Level Elements:

- <address> 
- <article>
- <aside>
- <blockquote>
- <div>
- <dl> (Definition List)
- <fieldset>
- <figcaption>
- <figure>
- <footer>
- <form>
- <h1> to <h6> (Heading Elements)
- <header>
- <hr> (Horizontal Rule)
- <main>
- <nav>
- <ol> (Ordered List)
- <p> (Paragraph)
- <pre> (Preformatted Text)
- <section>
- <table>
- <ul> (Unordered List)

## Inline
- No line breaks
- No default width
- Top,bottom padding or margin no efect but left right works
inline content can only have other inline elements or text
## Inline-Level Elements:

<a> (Anchor)
<abbr> (Abbreviation)
<acronym> (Acronym)
<b> (Bold)
<br> (Line Break)
<code> (Code)
<em> (Emphasis)
<i> (Italic)
<img> (Image)
<label>
<q> (Quotation)
<span>
<strong> (Strong Importance)
<sub> (Subscript)
<sup> (Superscript)
<textarea>
<time>
<var> (Variable)

## Flex
- Used to create flexible containers
- Enables a flexible layout for its child elements. 
- When a container is set to display: flex;, it becomes a flex container, and its direct child elements become flex items.
-  Operates along two axes: the main axis and the cross axis. 
- By default, the main axis runs horizontally from left to right, and the cross axis runs vertically from top to bottom.

- **Properties for Alignment**
 ### justify-content###:
 - *space-between* The first item is flush with the start, the last is flush with the end
 - *stretch* stretch; Distribute items evenly Stretch 'auto'-sized items to fit the container 

 ### align-content ###
 - Sets the distribution of space between and around content items along a flexbox's cross-axis or a grid's block axis.

 ### Align-items ###
 - align-items property sets the align-self value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

#### margins ####
- Margins create extra space around an element
- It defines the space between an element's borders and the adjacent elements.

#### padding ####
- control the inner spacing of an element. 
- It defines the space between the element's content and its borders.