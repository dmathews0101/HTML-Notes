
## 01 HTML Notes

HTML - Hypertext Markup Language.
It is markup language or web pages.
HTML is used to create websites.

```html
<h2>HTML Code</h2>

<pre>

<!DOCTYPE html>
<html>
<head>
<title>Sample HTML code</title>
</head>
<body>

<p>Hello World!</p>

</body>
</html>

</pre>
```

## 02 HTML Introduction

What is HTML ?
HTML describes the structure of a web page. HTML consists of a series of 
elements. HTML elements tell the browser how to display the content. HTML 
elements label pieces of content such as "this is a heading", "this is a 
paragraph", "this is a link", etc.

A Simple HTML Document
What is an HTML Element?
HTML History

## 03 HTML Editors

Learning HTML using Notepad or TextEdit
W3Schools Spaces

## 04 HTML Basic Examples

HTML Documents

Example

```html

<!DOCTYPE html>
<html>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph paragraph.</p>

</body>
</html>

```

The <!DOCTYPE> Declaration
HTML Headings
HTML Paragraphs

HTML Links

HTML links are defined with the <a> tag.

Example

```html
<a href="https://dmathews0101.github.io/HTML-Notes/">This is a link</a>
```

The link's destination is specified in the href attribute. Attributes are 
used to provide additional information about HTML elements.

HTML images

```html
<img src="mountain-lake.jpg" alt="Mountain Lake image" width="1920" height="1279">
<h3>
Photo Credit : Photo by <a href="https://unsplash.com/@ansgarscheffold?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Ansgar Scheffold</a> on <a href="https://unsplash.com/s/photos/mountain-lake?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
</h3>  
```

Displaying image from README.md file

![Mountain Lake](mountain-lake.jpg)

How to view HTML Source
View HTML Source Code

Inspect an HTML Element
We can also edit the HTML or CSS on-the-fly in the Elements or Styles panel 
that opens.

## 05 HTML Elements

An HTML element is defined by a start tag, some content, and an end tag.

HTML Elements
The HTML element is everything from the start tag to the end tag. Some HTML 
elements have no content (like the <br> element). These elements are called
empty elements. Empty elements do not have an end tag!

Nested HTML Elements

Example :
```html
<p>This is a <br> paragraph with a line break.</p>
```

HTML is not case sensitive
HTML Tag Reference

## 06 HTML Attributes

HTML attributes provide additional information about HTML elements.

HTML Attributes
All HTML elements can have attributes. Attributes provide additional 
information about elements. Attributes are always specified in the start 
tag. Attributes usually come in name/value pairs like: name="value".

The href Attribute
The <a> tag defines a hyperlink. The href attribute specifies the URL of the
page the link goes to:

```html
<a href="https://www.w3schools.com">Visit W3Schools</a>
```

The src Attribute

The <img> tag is used to embed an image in an HTML page. The src attribute 
specifie the path to the image to be displayed.

```html

<img src="car.jpg">
Photo Credit : Photo by <a href="https://unsplash.com/@greg_rosenke?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Greg Rosenke</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

```
Displaying image from README.md file

![Car](car.jpg)

Absolute URL, Relative URL

The width and height attributes
The alt attribute

The style Attribute
The style Attribute is used to add styles to an element, such as color, 
font, size, and more.

Example
```html
<p style="color:red;">This is a red paragraph.</p>
```

The lang Attribute
We should always include the lang attribute inside the <html> tag, to 
declare the language of the Web page. This is meant to assist search 
engines and browsers.

The following example specifies English as the language.

```html
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```

Country codes can also be added to the language code in the lang 
attribute. So, the first two characters define the language of the
HTML page, and the last two characters define the country.

The following example specifies English as the language and the 
United States as the country

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```

The title attribute
The title attribute defines some extra information about an element.
The value of the title attribute will be displayed as a tooltip
when you mouse over the element.

Example
```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

We suggest : Always use lowercase attributes
We suggest : Always Quote Attribute Values

Sometimes you have to use quotes. This example will not display
the title attribute correctly, because it contains a space:

Example
```html
<p title=About W3Schools>
```

Single or Double Quotes?
Chapter Summary
HTML Attribute Reference

## 07 HTML Headings

HTML headings are titles or subtitles that you want to display on a webpage.

HTML Headings

Example
```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

Headings are important
Bigger Headings
Each HTML heading has a default size. However, you can specify the size for any
heading with the style attribute, using the CSS font-size property.

Example
```html
<h1 style="font-size:60px;">Heading 1</h1>
```

HTML Tag Reference

## 08 HTML Paragraphs

A paragraph always starts on a new line, and is usually a block of text.

HTML Paragraphs

Example
```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

HTML Display
HTML Horizontal Rules

Example
```html
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```

HTML Line Breaks

Example
```html
<p>This is<br>a paragraph<br>with line breaks.</p>
```

The Poem Problem

```html
Solution - The HTML <pre> Element

The HTML <pre> element defines preformatted text. The text inside a <pre> 
element is displayed in a fixed-width font (usually Courier), and it 
preserves both spaces and line breaks.
```

Example
```html
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```

HTML Tag Reference

## 09 HTML Styles

The HTML style attribute is used to add styles to an element, such as color,
font, size, and more.

```html
<!DOCTYPE html>
<html>
<body>

<p>I am normal</p>
<p style="color:red;">I am red</p>
<p style="color:blue;">I am blue</p>
<p style="font-size:50px;">I am big</p>

</body>
</html>
```

The HTML Style Attribute

Setting the style of an HTML element, can be done with the style attribute.
The HTML style attribute has the following syntax:

```html
<tagname style="property:value;">
```

The property is a CSS property. The value is a CSS value.

Background Color

The CSS background-color property defines the background color for
an HTML element.

Example:

Setting the background color for a page to powderblue.

```html
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```

Example

Setting the background color for two different elements.

```html
<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
```

Text Color

The CSS color property defines the text color for an HTML element.

```html
<h1 style="color:blue;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```

Fonts

The CSS font-family property defines the font to be used for an HTML element.

Example

```html
<h1 style="font-family:verdana;">This is a heading</h1>
<p style="font-family:courier;">This is a paragraph.</p>
```

Text Size

The CSS font-size property defines the text size for an HTML element.

Example

```html
<h1 style="font-size:300%;">This is a heading</h1>
<p style="font-size:160%;">This is a paragraph.</p>
```

Text Alignment

The CSS text-align property defines the horizontal text alignment for an
HTML element.

Example
```html
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```

Chapter Summary

## 10 HTML Text Formatting

HTML contains several elements for defining text with a special meaning.

Example

```html
<!DOCTYPE html>
<html>
<body>

<p><b>This text is bold</b></p>
<p><i>This text is italic</i></p>
<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

</body>
</html>
```

HTML Formatting Elements

Formatting elements were designed to display special types of text:

<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text

HTML <b> and <strong> Elements
HTML <i> and <em> Elements
HTML <small> Element
HTML <mark> Element
HTML <del> Element
HTML <ins> Element
HTML <sub> Element
HTML <sup> Element

HTML Text Formatting Elements

## 11 HTML Quotation and Citation Elements

In this chapter we will go through the <blockquote>, <q>, <abbr>, <address>
<cite>, and <bdo> HTML elements.

Example
```html
<!DOCTYPE html>
<html>
<body>

<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature.
The world's leading conservation organization,
WWF works in 100 countries and is supported by
1.2 million members in the United States and
close to 5 million globally.
</blockquote>

</body>
</html>

```

HTML <blockquote> for Quotations

The HTML <blockquote> element defines a section that is quoted from another
source. Browsers usually indent <blockquote> elements.

Example
```html
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature.
The world's leading conservation organization,
WWF works in 100 countries and is supported by
1.2 million members in the United States and
close to 5 million globally.
</blockquote>
```

HTML <q> for Short Quotations

The HTML <q> tag defines a short quotation. Browsers normally insert quotation
marks around the quotation.

Example
```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

HTML <abbr> for Abbreviations

The HTML <abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS",
"Mr.","Dr.","ASAP","ATM".

Making abbreviations can give useful information to browsers, translation systems
and search-engines.
Tip:Use the global title attribute to show the description for the abbreviation/
acronym when you mouse over the element.

Example
```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

HTML <address> for Contant Information

The HTML <address> tag defines the contact information for the author/owner
of a document or an article. The contact information can be an email
address, URL, physical address, phone number, social meadia handle, etc.
The text in the <address> element usually renders in italic, and browsers
will always add a line break before and after the <address> element.

Example :
```html
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

HTML <cite> for Work Title







