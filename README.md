
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

The HTML <cite> tag defines the title of a creative work ( e.g. a book, 
a poem, a song, a movie, a painting, a sculpture, etc.).

Note: A person's name is not the title of a work.

The text in the <cite> element usually renders in italic.

Example

```html
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

HTML <bdo> for Bi-Directional Override

BDO stands for Bi-Directional Override.

The HTML <bdo> tag is used to override the current text direction.

Example
```html
<bdo dir="rtl">This text will be written from right to left</bdo>
```

HTML Quotation and Citation Elements


## 12 HTML Comments

HTML comments are not displayed in the browser, but they can help 
document your HTML source code.

HTML Comment Tag

You can add comments to your HTML source by using the following syntax.

```html
<!-- Write your comments here -->
```

Add Comments
Hide Content

Hide Inline Content

Comments can be used to hide parts in the middle of the HTML code.

Example
```html
<p>This <!-- great text --> is a paragraph.</p>
```

## 13 HTML Colors

HTML colors are specified with predefined color names, or with rgb, HEX,
HSL, RGBA, or HSLA values.

Color Names

In HTML, a color can be specified by using a color name.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:Tomato;">Tomato</h1>
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
<h1 style="background-color:Gray;">Gray</h1>
<h1 style="background-color:SlateBlue;">SlateBlue</h1>
<h1 style="background-color:Violet;">Violet</h1>
<h1 style="background-color:LightGray;">LightGray</h1>

</body>
</html>


```

HTML supports 140 standard color names.

Background Color

We can set the background color for HTML elements.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:DodgerBlue;">Hello World</h1>

<p style="background-color:Tomato;">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
</p>

</body>
</html>


```

Text Color

We can set the color of text.

Example

```html
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

Border Color

We can set the color of borders.

Example

```html
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```

Color Values

In HTML, colors can also be specified using RGB values, HEX values, HSL values,
RGBA values, and HSLA values.

The following three <div> elements have their background color set with RGB,
HEX, and HSL values.

The following two <div> elements have their background color set with RGBA and
HSLA values, which add an Alpha channel to the color (here we have 50% transparency).

Example

```html
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>

<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>

```
Or

```html

<!DOCTYPE html>
<html>
<body>

<p>Same as color name "Tomato":</p>

<h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
<h1 style="background-color:#ff6347;">#ff6347</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>

<p>Same as color name "Tomato", but 50% transparent:</p>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>

<p>In addition to the predefined color names, colors can be specified using RGB, HEX, HSL, or even transparent colors using RGBA or HSLA color values.</p>

</body>
</html>



```

## 14 HTML RGB and RGBA Colors

An RGB color value represents RED, GREEN, and BLUE light sources.
An RGBA color value is an extension of RGB with an Alpha channel (opacity).


RGB Color Values

In HTML, a color can be specified as an RGB value, using this formula.
rgb( red, green, blue )

Each parameter (red,green,and blue) defines the intensity of the color
with a value between 0 and 255.

This means that there are 256x256x256 = 16777216 possible colors!

For example, rgb(255,0,0) is displayed as red, because red is set to
its highest value(255), and the other two (green and blue) are set to 0.

Another example, rgb(0,255,0) is displayed as green, because green is
set to its highest value (255), and the other two ( red and blue ) are
set to 0.

To display black, set all color parameters to 0, like this: rgb(0,0,0).

To display white, set all color parameters to 255, like this: rgb(255,255,255).

Experiment by mixing the RGB values below.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0)</h1>
<h1 style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255)</h1>
<h1 style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113)</h1>
<h1 style="background-color:rgb(238, 130, 238);">rgb(238, 130, 238)</h1>
<h1 style="background-color:rgb(255, 165, 0);">rgb(255, 165, 0)</h1>
<h1 style="background-color:rgb(106, 90, 205);">rgb(106, 90, 205)</h1>

</body>
</html>

```

Shades of Gray

Shades of gray are often defined using equal values for all three parameters.

Example 

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:rgb(60, 60, 60);">rgb(60, 60, 60)</h1>
<h1 style="background-color:rgb(100, 100, 100);">rgb(100, 100, 100)</h1>
<h1 style="background-color:rgb(140, 140, 140);">rgb(140, 140, 140)</h1>
<h1 style="background-color:rgb(180, 180, 180);">rgb(180, 180, 180)</h1>
<h1 style="background-color:rgb(200, 200, 200);">rgb(200, 200, 200)</h1>
<h1 style="background-color:rgb(240, 240, 240);">rgb(240, 240, 240)</h1>

</body>
</html>

```

RGBA Color Values

RGBA color values are an extension of RGB color values with an Alpha 
channel - which specifies the opacity for a color.

An RGBA color value is specified with:

rgba(red, green, blue, alpha)

The alpha parameter is a number between 0.0 (fully transparent) and 1.0 
(not transparent at all ).

Experiment by mixing the RGBA values below.

Example 

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.2);">rgba(255, 99, 71, 0.2)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.4);">rgba(255, 99, 71, 0.4)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.6);">rgba(255, 99, 71, 0.6)</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.8);">rgba(255, 99, 71, 0.8)</h1>
<h1 style="background-color:rgba(255, 99, 71, 1);">rgba(255, 99, 71, 1)</h1>

</body>
</html>

```

## 15 HTML HEX Colors

A hexadecimal color is specified with: #RRGGBB, where the RR(red), GG(green)
and (BB)blue hexadecimal integers specify the components of the color.

HEX Color Values

In HTML, a color can be specified using a hexadecimal value in the form .
#rrggbb
where rr(red),gg(green) and bb(blue) are hexadecimal values between 00 and
ff( same as decimal 0 - 255 ).

For example, #ff0000 is displayed as red, because red is set to its highest 
value (ff), and the other two (green and blue) are set to 00.

Another example, #00ff00 is displayed as green, because green is set to
its highest value (ff), and the other two (red and blue) are set to 00.

To display black, set all color parameters to 00, like this : #000000.

To display white, set all color parameters to ff, like this : #ffffff.

Experiment by mixing the HEX values below.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:#ff0000;">#ff0000</h1>
<h1 style="background-color:#0000ff;">#0000ff</h1>
<h1 style="background-color:#3cb371;">#3cb371</h1>
<h1 style="background-color:#ee82ee;">#ee82ee</h1>
<h1 style="background-color:#ffa500;">#ffa500</h1>
<h1 style="background-color:#6a5acd;">#6a5acd</h1>

</body>
</html>

```

Shades of Gray

Shades of gray are often defined using equal values for all three parameters.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:#404040;">#404040</h1>
<h1 style="background-color:#686868;">#686868</h1>
<h1 style="background-color:#a0a0a0;">#a0a0a0</h1>
<h1 style="background-color:#bebebe;">#bebebe</h1>
<h1 style="background-color:#dcdcdc;">#dcdcdc</h1>
<h1 style="background-color:#f8f8f8;">#f8f8f8</h1>

</body>
</html>

```

## 16 HTML HSL and HSLA Colors

HSL stands for hue, saturation, and lightness.

HSLA color values are an extension of HSL with an Alpha channel(opacity).

HSL Color Values

In HTML, a color can be specified using hue, saturation, and lightness (HSL)
in the form:

hsl(hue, saturation, lightness)


Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, 
and 240 is blue.

Saturation is a percentage value. 0% means a shade of gray, and 100% is the
full color.

Lightness is also a percentage value. 0% is black, 100% is white.

Experiment by mixing the HSL values below.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h1>
<h1 style="background-color:hsl(240, 100%, 50%);">hsl(240, 100%, 50%)</h1>
<h1 style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%)</h1>
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>
<h1 style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%)</h1>
<h1 style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%)</h1>

</body>
</html>


```

Saturation

Saturation can be described as the intensity of a color.
100% is pure color, no shades of gray.
50% is 50% gray, but you can still see the color.
0% is completely gray; you can no longer see the color.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h1>
<h1 style="background-color:hsl(0, 80%, 50%);">hsl(0, 80%, 50%)</h1>
<h1 style="background-color:hsl(0, 60%, 50%);">hsl(0, 60%, 50%)</h1>
<h1 style="background-color:hsl(0, 40%, 50%);">hsl(0, 40%, 50%)</h1>
<h1 style="background-color:hsl(0, 20%, 50%);">hsl(0, 20%, 50%)</h1>
<h1 style="background-color:hsl(0, 0%, 50%);">hsl(0, 0%, 50%)</h1>

<p>With HSL colors, less saturation mean less color. 0% is completely gray.</p>

</body>
</html>

```

Lightness

The lightness of a color can be described as how much light you want
to give the color, where 0% means no light(black), 50% means 50% light
(neither dark nor light), and 100% means full lightness(white).

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:hsl(0, 100%, 0%);">hsl(0, 100%, 0%)</h1>
<h1 style="background-color:hsl(0, 100%, 25%);">hsl(0, 100%, 25%)</h1>
<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%)</h1>
<h1 style="background-color:hsl(0, 100%, 75%);">hsl(0, 100%, 75%)</h1>
<h1 style="background-color:hsl(0, 100%, 90%);">hsl(0, 100%, 90%)</h1>
<h1 style="background-color:hsl(0, 100%, 100%);">hsl(0, 100%, 100%)</h1>

<p>With HSL colors, 0% lightness means black, and 100 lightness means white.</p>

</body>
</html>

```

Shades of Gray

Shades of gray are often defined by setting the hue and saturation to
0, and adjusting the lightness from 0% to 100% to get darker/lighter
shades.

Example

```html
<!DOCTYPE html>
<html>
<body>

<h1 style="background-color:hsl(0, 0%, 20%);">hsl(0, 0%, 20%)</h1>
<h1 style="background-color:hsl(0, 0%, 30%);">hsl(0, 0%, 30%)</h1>
<h1 style="background-color:hsl(0, 0%, 40%);">hsl(0, 0%, 40%)</h1>
<h1 style="background-color:hsl(0, 0%, 60%);">hsl(0, 0%, 60%)</h1>
<h1 style="background-color:hsl(0, 0%, 70%);">hsl(0, 0%, 70%)</h1>
<h1 style="background-color:hsl(0, 0%, 90%);">hsl(0, 0%, 90%)</h1>

</body>
</html>

```

HSLA Color Values

HSLA color values are an extension of HSL color values, with an 
Alpha channel - which specifies the opacity for a color.















