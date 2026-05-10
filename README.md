# HTML 
HTML Stands for HyperText Mark Language.It was developed by Tim Berners-Lee in 1991 at the CERN research institute in Switzerland. This is an Standard Language used to create and design web pages.It uses tags and attributes to provide structure and format to the webpages.HTML tags are also used for structure the content of web pages like text, images, audio, video, links , forms, tables etc.
HTML is called Markup Language because it use tags to structure the content of the web pages and tags is also called Markup.
<br>
HTML files can be saved with .html or .htm extension.
<br>
HTML is also called browser Language because browser understand HTML.
<br>
HyperText -> Text that contains links to other pages.

Markup Language -> Uses tags to define the structure of content.

<b>Basic Structure of an HTML Web Page: </b>

```bash
<!DOCTYPE html>
<html>
<head>
    <title>This is a simple web page</title>
</head>
<body>
    <h1>Welcome to  HTML</h1>
    <p>This is a simple paragraph</p>
</body>
</html>

```
Explanation of this code:

```bash
<!DOCTYPE html> ->  Declares HTML5 document type

<html> ->  Root element of the webpage

<head> ->  Contains metadata (title, styles, scripts)

<title> ->  Title shown in browser tab

<body> ->  Main content of the webpage

<h1> ->  Heading

<p> ->  Paragraph

```

<b>Features of HTML :</b>

```bash

1. Simple and Easy to Learn -> HTML is very simple and easy to understand because it uses basic tags and does not require complex programming knowledge.

2. Platform Independent -> HTML runs on any operating system like Windows, Linux, macOS and any devices.Only requires browser to run the html. 

3. Tag-Based Language -> HTML uses tags to define elements and structure of a web page

4. Supports Hyperlinks -> HTML allows linking one web page to another using hyperlinks.

5. Supports Text Formatting -> HTML provides tags(like <b> for bold, <i> for italic, <u> for underline) to format text appearance.

6. Case Insensitive Language -> HTML tags are not case-sensitive.

7. Lightweight -> HTML files are small in size and load quickly.

```

# web page basics :

A web page is a document available on the internet that is written using HTML (HyperText Markup Language) and viewed through a web browser. It can contain text, images, videos, links, and other multimedia elements.
<br>
In simple words we can say that A web page is a single page of a website that contains information such as text, images, links, videos, forms etc.

<b>Basic Components of a Web Page :</b>

```bash

1. HTML 

2. CSS 

3. JavaScript

```

<b>There are two types of web pages</b>

<b>1. Static Web Page :</b>
<br>
A static web page is a web page whose content remains fixed and unchanged for every user. It is created using HTML and CSS only.

Example:

```bash
<!DOCTYPE html>
<html>
<body>
    <h1>Welcome</h1>
    <p>This is a static web page.</p>
</body>
</html>

```

<b>2. Dynamic web Page</b>
<br>
A dynamic web page is a web page whose content changes automatically based on user input, time, or database.Technologies Used like HTML, CSS, JavaScript, Backend languages (PHP, Python, Node.js), Database (MySQL, MongoDB).

Example:

```bash
<!DOCTYPE html>
<html>
<body>

<h1 id="demo"></h1>

<script>
document.getElementById("demo").innerHTML = "Hello User!";
</script>

</body>
</html>

```

#  set up a web page 
Setting up a web page means creating, saving, and preparing an HTML document so it can be viewed in a web browser. It is the first step in web development.For Setting up a web page it require Text Editors(like VS Code, NotePad), a web browse(Like Chrome, Edge) and Basic knowledge of HTML.

<b>Here are the steps to set up an web page</b>

1. Open a Text Editor  -> Open any editor like Notepad or VS Code. This is where you will write HTML code.

2. Make a file using .html extension in your text editor like filename index.html.

3. Write HTML Code 

```bash
<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first web page.</p>
</body>
</html>

```

4. Save the file

5. Add styling if you want like this:

```bash
<style>
body {
    background-color: lightyellow;
    font-family: Arial;
}
</style>

```

6. You can run this code by double click on file and click on open with and the tap on browser.It runs and web page show on a web browser.


# Display a web page in a web browser :
Displaying a web page means opening and viewing an HTML file using a web browser. A browser reads the HTML code and converts it into a visible format (text, images, layout) for the user.

<b>Here are the steps to display a web page in a web browser </b>

1. Create an HTML File -> Write HTML code and save it with .html extension.

```bash
<!DOCTYPE html>
<html>
<head>
    <title>My Page</title>
</head>
<body>
    <h1>Hello World</h1>
    <p>This is my web page.</p>
</body>
</html>

```

2. Save the File.

3. open the file in browser :

  Right-click on file
  <br>
  Select Open with -> Browser.


# Paragraph 
A paragraph in HTML is a block of text used to display content in a structured and readable format. It is created using the <p> tag.

Example:

```bash
<!DOCTYPE html>
<html>
<body>

<p>This is the first paragraph.</p>
<p>This is the second paragraph.</p>

</body>
</html>

```

# br Tag 
The <br> (Break) tag is used in HTML to insert a line break, meaning the content after it moves to the next line without starting a new paragraph.It is an empty (self-closing) tagBasically it used for start a new line.

Example:

```bash
<!DOCTYPE html>
<html>
<body>

<p>Hello<br>World</p>

</body>
</html>

```

# Insert Blank Spaces in HTML :
The Problem in HTML is In HTML, multiple spaces are not displayed by default.No matter how many spaces you write, the browser shows only one space.
<br>
So, if you want to insert multiple blank space you can use &nbsp; (non-breaking space). it insert extra blank spaces in HTML.

Example :

```bash
<!DOCTYPE html>
<html>
<body>

<p>Hello&nbsp;&nbsp;&nbsp;World</p>

</body>
</html>

```
# Headings in HTML 
Headings in HTML are used to define titles and subtitles on a web page. They help organize content and make it easy to read.

HTML provides six levels of headings, from h1 to h6.

<b>Syntax:</b>

```bash
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Smaller Heading</h3>
<h4>...</h4>
<h5>...</h5>
<h6>Smallest Heading</h6>

```
<b>Example:</b>

```bash
<!DOCTYPE html>
<html>
<head>
    <title>Heading</title>
</head>
<body>

<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6</h6>

</body>
</html>

```

# Preformatted Text in HTML :
Preformatted text in HTML is text that is displayed exactly as written in the code, including spaces, tabs, and line breaks. It is created using the pre tag.

Syntax:

```bash
<pre>
   Your text here
</pre>

```

Example;

```bash
<!DOCTYPE html>
<html>
<body>

<pre>
Name:   Nitish Kumar
City:   Panipat
Course: BCA
</pre>

</body>
</html>

```

# Comments in HTML:
A comment in HTML is a piece of code that is not displayed in the web browser but is used by developers to add notes, explanations, or reminders within the HTML document. Comments help improve code readability and make it easier to understand the structure and purpose of the code. They are especially useful during development and debugging, as they allow programmers to temporarily disable parts of code without deleting them.

syntax:

```bash
<!-- single line comment -->

<!-- Multi line 
 comment-->

 ```

 Example:

 ```bash
 <!DOCTYPE html>
<html>
<body>

<!-- This is a heading -->
<h1>Welcome to My Website</h1>

<!-- This is a paragraph -->
<p>This is my first web page.</p>

<!-- Commenting multiple lines
     helps explain the code -->

</body>
</html>

```

# Special Characters in HTML: 
Special characters in HTML are symbols that either have a predefined meaning in HTML (like <, >) or cannot be typed directly using a keyboard. To display these characters correctly on a web page, we use character entities. These entities ensure proper rendering and prevent conflicts with HTML tags.

<b>Common Special Characters</b>

```bash
| Character | Entity Name | Entity Number |
| --------- | ----------- | ------------- |
| <         |  &lt;       |  &#60;        |
| >         |  &gt;       |  &#62;        |
| &         |  &amp;      |  &#38;        |
| Space     |  &nbsp;     |  &#160;       |
| "         |  &quot;     |  &#34;        |
| ©         |  &copy;     |  &#169;       |

```

Syntax:

```bash
&entity_name;
or
&#entity_number;

```

Example:

```bash
<!DOCTYPE html>
<html>
<body>

<p>5 &lt; 10</p>
<p>AT&amp;T Company</p>
<p>&copy; 2026 My Website</p>

</body>
</html>


<!--OutPut-->

5 < 10
AT&T Company
© 2026 My Website

```

# Text Formatting in HTML
Text formatting in HTML refers to the use of different tags to change the appearance and importance of text. It helps make content more readable, attractive, and meaningful. Formatting tags can make text bold, italic, underlined, highlighted, or displayed as superscript and subscript.

<b>Common Formatting Tags</b>

```bash
| Tag        | Function        |
| ---------- | --------------- |
|  <b>       | Bold text       |
|  <strong>  | Important text  |
|  <i>       | Italic text     |
|  <em>      | Emphasized text |
|  <u>       | Underlined text |
|  <mark>    | Highlight text  |
|  <small>   | Smaller text    |
|  <del>     | Deleted text    |
|  <ins>     | Inserted text   |
|  <sub      | Subscript       |
|  <sup>     | Superscript     |

```

Example:

```bash
<!DOCTYPE html>
<html>
<body>

<p><b>Bold Text</b></p>
<p><i>Italic Text</i></p>
<p><u>Underlined Text</u></p>
<p><strong>Important Text</strong></p>
<p><em>Emphasized Text</em></p>
<p>H<sub>2</sub>O</p>
<p>10<sup>2</sup> = 100</p>

</body>
</html>

```
output:

```bash
Bold Text
Italic Text
Underlined Text
Important Text
Emphasized Text
H₂O
10² = 100

```

# Emphasize Text
The emphasize tag in HTML is used to emphasize text, making it stand out in a sentence. It usually displays text in italic form and indicates importance or stress on certain words. It also improves accessibility because screen readers give special emphasis while reading.

syntax:

```bash
<em>Text</em>

```

Example:

```bash
<p>This is <em>important</em> text.</p>

```

# Superscript and Subscript:
Superscript and subscript tags are used to display text above or below the normal line. sup is used for superscript (above line), while sub is used for subscript (below line). These are commonly used in mathematical formulas, chemical equations, and scientific expressions.

syntax:

```bash
<sup>text</sup>
<sub>text</sub>

```

Example:

```bash
<p>H<sub>2</sub>O</p>
<p>10<sup>2</sup> = 100</p>


<!--output-->

H₂O
10² = 100

```

# Font Style and Size
Font style and size in HTML control the appearance of text, including its typeface, size, and look. Earlier, the font tag was used, but now CSS is preferred. It helps improve readability and design of web pages by customizing how text appears.

Syntax (Using CSS)

```bash
<p style="font-family: Arial; font-size: 20px;">Text</p>

```

Example:

```bash
<p style="font-family: Arial; font-size: 24px;">Styled Text</p>

```

# List in HTML 
A list in HTML is used to organize information in a structured and readable format. It groups related items together, making content easier to understand. HTML provides different types of lists such as ordered, unordered, and description lists, each used for different purposes in web pages.

<b>Types of List in HTML</b>

<b>1. Ordered list :</b>
<br>
An ordered list is a type of list where items are displayed in a numbered sequence or order. It is used when the order of items is important, such as steps in a process or instructions.

Syntax:

```bash
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>

```

Example:

```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <title>List in HTML</title>
</head>
<body>
    <!--Ordered list-->
    <h3>Fruites</h3>
    <ol>
        <li>Apple</li>
        <li>Mango</li>
        <li>PineApple</li>
    </ol>
</body>
</html>


```

<b>2. Unordered List</b>
<br>
An unordered list is used to display items without any specific order. Items are usually marked with bullets. It is useful when the sequence of items does not matter.

syntax:

```bash
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

```

Example:

```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <title>List in HTML</title>
</head>
<body>
    <!--Unordered list-->
    <h3>Morning Routine</h3>
    <ul>
      <li>Wake up</li>
      <li>Brush teeth</li>
      <li>Go to college</li>
    </ul>
</body>
</html>

```

<b>3. Definition list </b>
<br>
A definition list in HTML is used to display a list of terms along with their descriptions. It is useful for creating glossaries, dictionaries, or question-answer type content. This list is created using the dl tag, where each term is defined using dt and its description is given using dd.

Syntax:

```
<dl>
  <dt>Term</dt>
  <dd>Description</dd>
</dl>

```

Example:

```bash
<!DOCTYPE html>
<html>
<body>

<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language used to create web pages.</dd>

  <dt>CSS</dt>
  <dd>Used to style and design web pages.</dd>

  <dt>JavaScript</dt>
  <dd>Used to add interactivity to web pages.</dd>
</dl>

</body>
</html>

```

output:

```bash
HTML
   HyperText Markup Language used to create web pages.
CSS
   Used to style and design web pages.
JavaScript
   Used to add interactivity to web pages.

```

# Add an Image
In HTML, images are added to a web page using the img tag. It is used to display pictures, graphics, or icons. The image source is specified using the src attribute, and alternative text is provided using the alt attribute for accessibility.

Syntax:

```bash

<img src="image.jpg" alt="description" width="" height="">

```

Example:

```bash
<img src="flower.jpg" alt="Flower Image" width="300" height="300">

```

# Background Image
A background image is used to set an image as the background of a web page or an element. It enhances the visual design of the page. Background images are usually applied using CSS rather than HTML attributes.

syntax:

```bash
<body style="background-image: url('bg.jpg');">

```
Example:

```bash
<body style="background-image: url('bg.jpg');">
<h1>Welcome</h1>
</body>

```

# Image Border
An image border is used to create a line around an image to highlight or separate it from other content. Borders improve the appearance and structure of a webpage and are usually applied using CSS.

syntax:

```bash
<img src="img.jpg" style="border: 2px solid black;">

```

Example:

```bash
<img src="flower.jpg" style="border: 3px solid red;">

```







