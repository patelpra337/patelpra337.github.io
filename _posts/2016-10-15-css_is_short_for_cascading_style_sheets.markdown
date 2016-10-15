---
layout: post
title:  "CSS is short for Cascading Style Sheets"
date:   2016-10-15 19:33:33 +0000
---


CSS is short for Cascading Style Sheets, and is the preferred way for setting the look and feel of a website. The style sheets define the colour, size and position of text and other HTML tags, while theHTML files define the content and how it is organised. Separating them allows you to change the colour scheme without having to rewrite your entire web site.

The cascading means that a style applied to a parent element will also apply to all children elements within the parent. For example, setting the colour of body text will mean all headings and paragraphs within the body will also be the same colour.

Specifying and Using Styles

There are three main ways of including a style sheet for a web page or site:

Setting the sytle="?" attribute of a tag, called inline styles
Using the <sytle> tag within the HTML header tag
Creating and linking to an external CSS file
Basic style sheets usually modify the appearance of html tags such as <body> and <p>. When using CSS files or style sheets within the header, we can also define classes of styles and apply them to any element using the class="?" attribute, but this is beyond the scope of this simple guide.

A lot of coding best practices emphasize keeping code lean and well organized. The general practices within CSS are no different. The goal is to write well-structured and standards-compliant markup. 

CSS files can become quite extensive, spanning hundreds of lines. These large files can make finding and editing our styles nearly impossible. 

Organize code with comments, CSS files can become quite extensive, spanning hundreds of lines. These large files can make finding and editing our styles nearly impossible. Let’s keep our styles organized in logical groups. Then, before each group, let’s provide a comment noting what the following styles pertain to.  

When writing CSS, it is important to place each selector and declaration on a new line. Then, within each selector we’ll want to indent our declarations.

CSS is a vast styling language and you can do so much with it. With so many selectors, properties and elements things can get a little messy.  But for better result you should keep your CSS code simple and clean. There are so many CSS tools and tricks that can improve and optimize our web projects. 

Below, a small collection of better practices those in your web design:

Make it readable
Keep it consistent
Start with a framework
Use a reset
Organize the styleshee with a top-down structure
Combine elements
Create your HTML first
Use multiple clasess
Use the right doctype
Use shorthand
Comment your CSS
Understand the differences between block vs. inline elements
Alphabetize your properties
Use CSS compressors
Make use of generic classes
Validate your CSS 
Use multiple stylesheets

Cheet-Sheet:

Using Styles
An external CSS file

<head>
<link rel="stylesheet" type="text/css" href="style.css" title="style">
</head>

Within the html header

<head>
<style type="text/css">
 h1 {
    color:red;
    }
</style>
</head>

Inline in the HTML

<p style="color:red;">Some red text</p>


Text Styles	

text-align: left;	Horizontal Alignment - left | center | right
text-decoration: underline;	Text Decorations - eg. none | underline | line-through
font-family: fontname;	Font Face (Typeface) - eg. Verdana, Arial, Helvetica
font-size: 16pt;	Font Size or Height - eg. 12pt | 15px
font-weight: bold;	Font Weight (Boldness) - eg. bold | normal | 200

Size and Layout	

width: 400px;	Width of HTML element - eg. 100px | 50%
height: 100%;	Height of HTML element - eg. 20px | 100%
margin: 5px;	Margin - space around an element, or distance between two elements
margin-top: 1px;	Top Margin. Also try -bottom: -left: or -right:
padding: 5px;	Padding - distance between an elements contents and its border
padding-top: 1px;	Top Padding. Also try -bottom: -left: or -right:

Colours & Borders	

color: red;	Element Colour - eg. red | #FF0000
background-color: white;	Background Colour of element
background-image: url(image.gif);	Background Colour of element
border-color: yellow;	Border Colour of element
border: 1px solid blue;	Width, style and colour of border defined together

CSS Lists	

list-style: none;	Clear existing bullet types set by html list tags


