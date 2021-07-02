
# What is CSS?

## CSS (Cascading Style Sheets) allows you to create great-looking web pages, 
but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.
# 1. CSS syntax
CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."

The following code shows a very simple CSS rule that would achieve the styling described above:

h1 {
    color: red;
    font-size: 5em;
}

A CSS stylesheet will contain many such rules, written one after the other.

h1 {
    color: red;
    font-size: 5em;
}

p {
    color: black;
}
Copy to Clipboard
You will find that you quickly learn some values, whereas others you will need to look up. The individual property pages on MDN give you a quick way to look up properties and their values when you forget, or want to know what else you can use as a value.

# What is CSS?

## CSS (Cascading Style Sheets) allows you to create great-looking web pages, 
but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.
# 1. CSS syntax
CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."

The following code shows a very simple CSS rule that would achieve the styling described above:

h1 {
    color: red;
    font-size: 5em;
}

A CSS stylesheet will contain many such rules, written one after the other.

h1 {
    color: red;
    font-size: 5em;
}

p {
    color: black;
}
Copy to Clipboard
You will find that you quickly learn some values, whereas others you will need to look up. The individual property pages on MDN give you a quick way to look up properties and their values when you forget, or want to know what else you can use as a value.



# How To Add CSS




* Three Ways to Insert CSS

## There are three ways of inserting a style sheet:

- External CSS


Example
External styles are defined within the <link> element, inside the <head> section of an HTML page:

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
  
  
  
  
- Internal CSS
  
  
  
  
  Example
Internal styles are defined within the <style> element, inside the <head> section of an HTML page:

<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

- Inline CSS

  
  <!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>

  
  
  
  
  
  # CSS color Property
  Example
Set the text-color for different elements:

body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}
  
  
  
  # CSS reference

  
  
 ##  Basic rule syntax
Style rule syntax
style-rule ::=
    selectors-list {
      properties-list
    }
  
  
  
 ## Selectors
The following are the various selectors, which allow styles to be conditional based on various features of elements within the DOM.

1. Basic selectors
Basic selectors are fundamental selectors; these are the most basic selectors that are frequently combined to create other, more complex selectors.

2. Universal selector *, ns|*, *|*, |*
Type selector elementname
Class selector .classname
ID selector #idname
Attribute selector [attr=value]
Grouping selectors
Selector list A, B
Specifies that both A and B elements are selected. This is a grouping method to select several matching elements.
  
  
  
  
  
  
  
  
  # CSS Tools: Reset CSS
  
  
  aThe reset styles given here are intentionally very generic. There isn't any default color or background set for the body element, for example. I don't particularly recommend that you just use this in its unaltered state in your own projects. It should be tweaked, edited, extended, and otherwise tuned to match your specific reset baseline. Fill in your preferred colors for the page, links, and so on.

In other words, this is a starting point, not a self-contained black box of no-touchiness.

If you want to use my reset styles, then feel free! It's all explicitly in the public domain (I have to formally say that or else people ask me about licensing). You can grab a copy of the file to use and tweak as fits you best. If you're more of the copy-and-paste type, or just want an in-page preview of what you'll be getting, here it is.

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
  
