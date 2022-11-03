
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
