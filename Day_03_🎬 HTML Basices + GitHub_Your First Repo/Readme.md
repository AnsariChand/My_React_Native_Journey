What is HTML?
Html Stands for Hyper Text Markup Language
Html is the Standard markup Language for creating web pages
Html describes the structure of a web page
Html consists of a series of elements

HTML stands for Hyper Text Markup Language. Every website on the internet uses HTML & CSS. Most also use JavaScript.

In a website, HTML is the structure, CSS is the style, and JavaScript is the functionality.

HTML Structure
Here is the HTML that makes up a very basic webpage:

<!DOCTYPE html>
<html>
<head>
  <title>My First Website!</title>
</head>
<body>
  <p>This is an amazing website!</p>
  <img src="cat-picture.jpg" alt="The internet is powered by cat pictures.">
</body>
</html>

Let's break things down even more.

**Elements**
Html is made up of HTML elements. An elements is an individual component of HTML.

Here is an HTML element from the code above:

<P> This is an amazing website!</p>

**Tags**
Html tags mark the beginning and end of an element (and are considered part of the element). tags are containers. They tell you something about the content between the opening & closing tags.

In the element above, the tags are <p> (Opening tag) and </p> (closing tag). You will notice that the closing tag has a /. This Particular tag is a P aragraph tag. it Specifies a paragraph in the HTML document. The Words between the opening and closing tags are a paragraph.

**kinds of Elements**
Elements can be either container elements (they hold content ) or stand-alone elements, Sometimes called self-closing elements.

Paragraph elements are containers: <p> Hi, I contain content </p>

Image elements are stand-alone:<img src="beau.jpg" />

Notice in the stand-alone img element, there is no closing tag but there is a / before the final angle bracket.

**Attributes**
Attributes provide additional information about HTML elements.
Attributes tags include class, id, Style, Lang, and Src(Source).

Here is an example of an HTML element with the attribute tag id:

<p id="Info"> This is an amazing Website! </p>

Some things to note about attributes:

-> Attributes are positioned inside the opening tag, before the right bracket.

-> Attributes are paired with values (in this example, the Value is info).

-> key/Value pairs are an important concept in Programming.

-> Attributes are selected fron a pre-defined set of Possible attributes depending on the element.

-> Values are assigned to attributes and they must be contained inside quotation marks.

Here is another example of an element with at atrribute:

<Div class="Container">
   A Bunch of Stuff!

  </Div>

**Nesting**
Html elements 'nest' inside of one another. The element that opens first closes last.

When nesting elements, Spaces and tabs are often used to show the level of nesting. However, the Spacing is not required and is only used to make HTML easier to read for Humans.

Here is an example of some HTML with a few levels of nesting elements:

<Body>
  <Div class="outer-div">
   <p>This is an amazing website</p>
     <a href="https://www.freecodecamp.org">freecodecamp</a>
    <Div class="inner-div">
       <ol>
        <li>Thing 1 </li>
        <li>Thing 2 </li>
        <li>Thing 3 </li>
      </ol>
    </Div>
 </div>
</body>

**Common HTML Tags**
Here are some common tags that are in almost all HTML documents.

**doctype**: This is the first element on every HTML page. It tells the browser to expect HTML and what version to use. For the newest version of HTML, the element should look like this: **<!doctype html>**

**html** After the doctype, all page content must be contained in the **<html>** tags.

**Head** This element contains the page title and metadata.

**body** This element contains all the Visible content in a page.

**title** this optional element is the name of your page. IT is a always nested in the **Head** tag.

**Div** This tag is one of the most used tags. It is used to create a basic container of other HTML or Content.

**p** A Paragraph or section of Body Copy.

**h1-h6** These designate different levels of headings or titles.

**Ol** Create an ordered (Numbered) list.
**Ul** Create an Unordered List.

**lI** List element.

**Links**
Links
Anchor elements ( <a></a>) are used to link to other sites on the web or within your project.

This element links to another website:

<a href="https://freecodecamp.com">freeCodeCamp</a>

This element links to another page of your website:

<a href="about.html">About Me</a>

The <link> element is a different type of link. Unlike the anchor element, it specifies relationships between the current document and an external resource.

It is often used to link a CSS file with an HTML file so that the external CSS file is used to style the HTML.

Here is an example:

<link src="main.css" rel='stylesheet' />

Comments
Like any other good coding language, HTML offers comments. They operate like comments in any other language. They are ignored by the browser engine.

<!-- Hello, I am a comment. -->

Tables
Tables are a way to represent complex information in a grid format. They are made of rows and columns.

Tables are compound elements (similar to lists) they are made up of several elements.

table: Table element.

tr: Table row.

td: Table cell.

th: Table header cell (optional).

Here is an example of a table. First you will see the HTML. Then you will see how the HTML displays.

<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Favorite Animal</th>
  </tr>
  <tr>
    <td>Beau</td>
    <td>Carnes</td>
    <td>cow</td>
  </tr>
  <tr>
    <td>Quincy</td>
    <td>Larson</td>
    <td>dog</td>
  </tr>
</table>
Firstname	Lastname	Favorite Animal
Beau	Carnes	cow
Quincy	Larson	dog
Trivia time!
What is wrong with this code?
<html>
    <head>
    <body>
    </head>

    </body>

</html>
Show Answer

Closing head tag should be before opening body tag.
What is wrong with this code?

<html>
  <head>
    <title>The best site ever!!
  </head>
  <body>    
    <p>Check out this great content.</p>
  </body>
</html>
Show Answer

There is no closing title tag.
What is wrong with this code?

<p id=content>Check out this great content.</p>
Show Answer

There should be quotation marks around the value "content".
Conclusion
You've now learned the basics of HTML syntax.
