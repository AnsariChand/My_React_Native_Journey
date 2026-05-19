**Day - 2 Lesson - 2 What is HTML**

**Step 1**

HTML stands for HyperText Markup Language. It's the code that defines the structure and content of a webpage. This is your code editor, where you'll write HTML.

Find line 1 in the editor and type this text:

Welcome to freeCodeCamp
When you are done, click the "check your code" button to see if it's correct.

**Step 2**
HTML is made up of elements. The first one you will use is the h1 element:

<h1>Welcome to freeCodeCamp</h1>
It starts with an opening tag (<h1>), ends with a closing tag (</h1>), and has the text it will display in between the tags.

Turn your Welcome to freeCodeCamp text into an h1 element by adding an opening tag in front of it, and a closing tag after it.

**Step 3**
Notice that the HTML you write in the editor shows up in the preview. In this workshop, you will write the HTML for a partial curriculum webpage.

Below your h1 element, type the following on the empty line:

Full-Stack Curriculum

**Step 4**
An h1 element is the main heading of a webpage and you should only use one per page. h2 elements represent subheadings. You can have multiple per page and they look like this:

<h2>This is a subheading.</h2>
Turn the Full-Stack Curriculum text into an h2 element by surrounding it with opening and closing h2 tags.

**Step 5**
Below the other two lines of text, add:

Learn the skills to become a full-stack developer

**Step 6**
When you need to add a paragraph to a webpage, you can use the p element like this:

<p>This is a paragraph element.</p>
Turn Learn the skills to become a full-stack developer into a paragraph element.

**Step 7**
There are six heading elements in HTML: h1 through h6. They're used to show the importance of sections on your webpage, with h1 being the most important and h6 the least.

Below your p element, add an h3 heading with the text:

Introduction to HTML

**Step 8**
Notice that each heading looks a little different in the preview. Same with the paragraph.

Next, add another p element that displays the following text:

HTML represents the content and structure of a webpage

**Step 9**
You're getting the hang of it. Next, add another h3 element at the bottom of the editor with the text:

Introduction to CSS

**Step 10**
While HTML defines the structure and content of a webpage, CSS is used to add style — things like colors, fonts, spacing, and layout.

Below the h3 you just added, add another paragraph element with the text:

CSS is used to style a webpage

**Step 11**
Finally, JavaScript makes your webpage interactive — it lets you tell the page what to do when someone clicks a button, submits a form, or many other things.

For the last step of the workshop, add another h3 and p element to the page describing JavaScript.

First, add an h3 element with the text:

Introduction to JavaScript
Then, below that h3 element, add a p element with the following text:

JavaScript adds interactivity to a webpage

**Day -2 Lesson - 2 Understanding Attributes in Html**
**What Role Does HTML Play on the Web?**

HTML, which stands for Hypertext Markup Language, is a markup language for creating web pages. When you visit a website and see content like paragraphs, headings, links, images, and videos; that's HTML.

Here is a small example using HTML elements. Try editing some of the text in the editor and see the changes update in the preview window.

<h1>Main heading element</h1>
<p>I am a paragraph element.</p>

HTML represents the content and structure of a webpage through the use of elements. Most elements will have an opening tag and a closing tag. Sometimes those tags are referred to as start and end tags. In between those two tags, you will have the content. This content can be text or other HTML elements.
ere is another example of a paragraph element. Change the text in the editor to say I love coding! and see the results in the preview window.

<p>I am a paragraph element.</p>

Both opening and closing tags start with a left angle bracket (<), and end with a right angle bracket (>), with the tag name placed between these angle brackets. While HTML tag names are case-insensitive, it is a widely accepted convention and best practice to write them in lowercase.

Here is a closer look at just the opening and closing paragraph tags:

<p>
</p>

What distinguishes an opening tag from a closing tag is the forward slash (/) placed immediately after the left angle bracket in a closing tag. Some HTML elements do not have a closing tag. These are known as void elements.

Here is an example of an image element which is a void element:
<img>

Notice that this image element does not have the closing tag and it does not have any content. Void elements cannot have any content and only have a start tag.

Sometimes you will see void elements that use a / before the > like this:

<img />

While many code formatters like Prettier, will choose to include the / in void elements, the HTML spec states that the presence of the / "does not mark the start tag as self-closing but instead is unnecessary and has no effect of any kind".

In real world development, you will see both forms so it is important to be familiar with both.

If you wanted to display an image, you will need to include a couple of attributes inside your image element. An attribute is a special value used to adjust the behavior for an HTML element.

Here is an example of an image element with a src attribute. Update the value of the src attribute to "https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" and you will see the image change to two cats peacefully sleeping.

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg" />

The src attribute is used to specify the location for that image. For image elements, it's good practice to include another attribute called the alt attribute. The alt attribute is used to provide short, descriptive text for the images.

Here's an example of an image element with the src and alt attributes. Try breaking the image by updating the src value to "https://.freecodecamp.org/curriculum/cat-photo-app/cats.jpg". You will see the image disappear and only the alt text show.

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch." />

So, you might be wondering if HTML by itself is enough to build a website. Well, the answer is: it depends. If you're building a small practice project that only displays text and images, HTML alone might be sufficient. However, if you're creating a modern professional website, you will need to have HTML, CSS, and JavaScript.

HTML is for the content and structure. CSS is for styling. JavaScript is for adding interactivity to your web pages. A good analogy for this is to compare HTML, CSS, and JavaScript with a complete building.

HTML represents the blocks, concrete, and irons that make up the walls. It's the foundation that makes the building strong. CSS represents the interior and exterior design that makes the house look beautiful. JavaScript represents the electrical and water system that ensures uninterrupted access to water and electricity.

**Questions**
What does HTML stand for?
HyperText Maker Language
HyperText Marker Language
HyperText Markdown Language
HyperText Markup Language

Which of the following is the correct syntax for a closing tag?
<;p>

<p>
</p>
<///p/>

which of the following is a valid attribute used inside the img element?
src
bold
closing
div

**What Are Attributes, and How Do They Work?**
An attribute is a value placed inside the opening tag of an HTML element. Attributes provide additional information about the element or specify how the element should behave. Here is the basic syntax for an attribute:
<element attribute="value"></element>

The attribute name is followed by an equal sign (=) and a value in quotes. The value can be a string or a number, depending on the attribute.

This first example uses the href and target attributes. The href attribute specifies the URL of a link and the target attribute specifies where to open the link.

Note: The a element, also known as the anchor element, is used to create hyperlinks. The text between the opening and closing a tags is the clickable part users select to navigate.

Enable the interactive editor and change the href="https://www.freecodecamp.org/news/" to href="https://www.freecodecamp.org". Now when you click on the link in the interactive editor, you will see the freeCodeCamp homepage in a new browser tab.
<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>

Without the href attribute, the link would not work because there would be no destination URL. So you must include this href attribute to make the link functional. The target="\_blank" enables the link to open in a new browser tab. You will learn more about the target attribute in future lessons

Other common attributes are the src, and alt, or alternative, attribute - which is used to specify the source of an image and provide alternative descriptive text for the image, respectively.

Enable the interactive editor and change the src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" to src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg". Then change the alt="Two tabby kittens sleeping together on a couch." to alt="Two cats running in the dirt.".

<img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch." />

Similar to the href attribute, the src attribute is required because it specifies the image file to be displayed. The alt attribute is not required, but it is recommended for accessibility purposes. Accessibility means making sure that everyone, including those with disabilities, can use and understand things like websites, apps, and physical spaces. You will learn more about accessibility in the upcoming lessons.

Some attributes are a little unique with their syntax like the checked attribute.

Enable the interactive editor and try clicking on the checkbox in the preview window to see it alternate between a checked and unchecked state.
<input type="checkbox" checked />

In the following example, we have an input element with the type attribute set to checkbox. Inputs are used to collect data from users, and the type attribute specifies the type of input. In this case, this input is a checkbox. You will learn more about how inputs work in the upcoming lessons.

The checked attribute is used to specify that the checkbox should be checked by default. The checked attribute does not require a value. If it is present, the checkbox will be checked by default. If the attribute is not present, the checkbox will be unchecked. This is known as a boolean attribute. You will learn more about booleans in general when you get to the JavaScript section.

Enable the interactive editor and try removing the checked attribute from the input. You will see that the checkbox is no longer checked by default.
<input type="checkbox" checked />

There are several common boolean attributes you will encounter in HTML, such as disabled, readonly, and required. These attributes are used to specify the state of an element, such as whether it is disabled, read-only, or required.

Here is an example of a text input element that is disabled by default. Enable the interactive editor and try clicking on the input element in the preview window. Now remove the disabled attribute from the input element and you will see that the input is no longer disabled by default. You should now be able to click on it and type inside the field.

<input type="text" disabled>
HTML has many attributes that can be used to customize the behavior and appearance of elements on a webpage. Understanding how to use attributes is essential for creating interactive and accessible web content. Over the next few lessons, you will learn about more HTML attributes and how to use them effectively in your web development projects.

**Debug a Pet Adoption Page**
Sally, a pet adoption store owner, has built her first web page but there are some issues.

Your job is to fix all of the errors so Sally can continue building her page.

Objective: Fulfill the user stories below and get all the tests to pass to complete the lab.

User Stories:

Sally wants to use an image of some cats but it is not displaying correctly. You will need to fix the following in the img element:
Replace the href attribute with the correct attribute for the image source.
Replace the att attribute with the correct attribute representing short, descriptive text for images.
Remove the </img> closing tag because img elements are void elements and don't have closing tags.
Sally wants to use some links to direct users to the dog and cat pages. But the links are not working correctly. You will need to fix the following in the a elements:
Replace both src attributes with the correct attributes used to specify URLs.
Tests:
Waiting:1. Your img element should have a src attribute instead of the href attribute.
Waiting:2. Your img element should have an alt attribute instead of the non-existent att attribute.
Waiting:3. Your img element should not have a </img> closing tag.
Waiting:4. Your a element with the text Visit cats page needs to have an href attribute instead of a src attribute.
Waiting:5. Your a element with the text Visit dogs page needs to have an href attribute instead of a src attribute.

**Understanding the HTML Boilerplate**
What Is the Role of the Link Element in HTML, and How Can It Be Used to Link to External Stylesheets?
Let's learn about the link element, and how to use it to link to external stylesheets.

The link element is used to link to external resources like stylesheets and site icons. Here is the basic syntax for using the link element for an external CSS file:

<link rel="stylesheet" href="./styles.css" />

The rel attribute is used to specify the relationship between the linked resource and the HTML document. In this situation, we need to specify that this linked resource is a stylesheet.

It is considered best practice to separate your HTML and CSS in different files. Developers will use the link element for their external CSS file instead of writing everything in the HTML document.

The href attribute is used to specify the location of the URL for the external resource.

The dot followed by a forward slash in the example tells the computer to look in the current folder, or directory, for the styles.css file.

The link element should be placed inside the head element as seen in the following example:

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Examples of the link element</title>
  <link rel="stylesheet" href="./styles.css" />
</head>

Often times you will see multiple link elements inside a professional codebase that link to different stylesheets, fonts, and icons. Here is an example of using the link element to link to an external Google Font called Playwright Cuba:

<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Playwrite+CU:wght@100..400&display=swap"
  rel="stylesheet"
/>

Google Fonts are a set of free and open source custom fonts that you can use inside any project. You can choose which fonts you would like to use and Google will provide you with the necessary HTML and CSS code. In this example, the preconnect value for the rel attribute tells the browser to create an early connection to the value specified in the href attribute. This is done to speed up loading times for these external resources.

Another common use case for the link element is to link to icons. Here is an example of linking to a favicon:

<link rel="icon" href="favicon.ico" />

A favicon, which is short for favorite icon, is a small icon typically displayed in the browser tab next to the site title. A lot of websites will use a favicon to display their brand icon.

What is the role of the link element in HTML?
It is used to link to external resources like stylesheets and site icons.

What is the role of the rel attribute inside the link element?
It is used to specify the relationship between the linked resource and the HTML document.

What is a favicon?
A small icon typically displayed in the browser tab next to the site title.

What Is an HTML Boilerplate, and Why Is It Important?

Let's learn about the HTML boilerplate.

What is the HTML boilerplate, you ask? It's like a ready-made template for your webpages. Think of it as the foundation of a house. A boilerplate includes the basic structure and essential elements every HTML document needs. It saves you time and helps ensure your pages are set up properly. Here is an example:

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta
       name="viewport"
       content="width=device-width, initial-scale=1.0" />
    <title>freeCodeCamp</title>
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
  </body>
</html>

Let's break down the key parts of this boilerplate. First, there is the DOCTYPE declaration:

<!DOCTYPE html>

It tells browsers which version of HTML you're using.

Next, comes the html tag:

<!DOCTYPE html>
<html lang="en">
  <!--All other elements go inside here-->
</html>

This wraps around all your content, and can specify the language of your page. Inside the html tag, you'll find two main sections - a head, and a body:

<!DOCTYPE html>
<html lang="en">
  <head>
    <!--Important metadata goes here-->
  </head>
  <body>
    <!--Headings, paragraphs, images, etc. go inside here-->
  </body>
</html>
The head section contains important behind-the-scenes information:
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document Title Goes Here</title>
  <link rel="stylesheet" href="./styles.css" />
</head>

Your site's metadata, contained in meta elements, has details about things like character encoding, and how websites like Twitter should preview your page's link. Your site's title, found in the title element, determines the text that appears in the browser tab or window. Finally, you'll typically link your page's external stylesheets in the head section using link elements.

The body section is where all your content goes:

<body>
  <h1>I am a main title</h1>
  <p>Example paragraph text</p>
</body>

Now, why is a boilerplate important? It ensures your pages are structured correctly and work well across different browsers. Using a boilerplate helps you avoid common mistakes and follow best practices. It's a great starting point for any web project. Remember, you can customize your own boilerplate to fit your needs. As you gain experience, you might add your own preferred elements or meta tags. As you continue to improve your personal boilerplate, you'll find that it saves you time when starting new projects.

Next time you start a new HTML file, consider using a boilerplate. It will definitely give you a solid foundation to build on.

Where would you set the character encoding for your page?
A meta element in the head.

Where would you set the language for your page?
In the opening html tag.

What purpose does a boilerplate serve?
Provides a starting structure for your websites.

Ensures you are not missing any essential elements.

Ensures you are not missing any essential elements.

**What Is UTF-8 Character Encoding, and Why Is It Needed?**
UTF-8, or UCS Transformation Format 8, is a standardized character encoding widely used on the web. Character encoding is the method computers use to store characters as data. Essentially, all text on a web page is a sequence of characters stored as one or more bytes. In computing, a byte is a unit of data consisting of 8 bits, or binary digits. UTF-8 supports every character in the Unicode character set - and this includes characters and symbols from all writing systems, languages, and technical symbols. Here is an example of using the meta element with the charset attribute to set the character encoding to UTF-8:

<meta charset="UTF-8" />
By setting the character encoding to UTF-8, it will ensure that the accented "e" character (é) is displayed correctly on the page. Here is an extended code example of using the UTF-8 character encoding:
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Examples of the UTF-8 encoding</title>
  </head>
  <body>
    <p>Café</p>
  </body>
</html>
For each new project you create, you should include this meta element with the charset attribute set to UTF-8.

Questions

Which attribute is used to set the UTF-8 character encoding for HTML documents?
