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



