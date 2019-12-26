Introduction to  HTML
•	HTML document Structure
empty tags and container tags
•	HTML Syntax
Fundamental Elements
•	Using block-level tags to create paragraphs and headings
block level elements and inline elements
p, h1-h6
•	The quote tag
<q>Build a future where people live in harmony with nature.</q>
•	Strong and emphasis tags
<em>Emphasized text</em><br>
<strong>Strong text</strong><br>
•	Character entities
&nbsp; &lt; &gt; &quot;
•	The comment tag
<!-- these are comments -->

Making Unordered (bulleted) lists
<!-- circle square none -->
<ul style="list-style-type:disc;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul> 
•	Making Ordered (numbered) lists
<ul>
    <li>Apple</li>
    <li>Mango</li>
    <li>Orange</li>
</ul>
•	Making Definition lists
A description list, with terms and descriptions
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
•	Creating a nested list and the importance of nesting
Links
•	The anchor tag
•	Linking from page to page and within pages
<a href="#link1">mylink</a>
•	Path statements – the importance of folders and files
•	Email links
<a href = "mailto:mail@gmail.com">Send Email</a>
Images and Videos
•	Web image formats
•	How images are used in web design
<img src="smiley.gif" alt="Smiley face" height="42" width="42">
•	The img tag
•	Clickable images
<span>Open image link in a new tab: 
    <a href="http://www.google.com">
     <img src="diagrams/web-image-formats.png" alt="web image" height="42" width="42">" />
    </a>
   </span>
<p>The Sky is <span style="color:blue">blue</span> always.</p>
•	Embedding videos
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
Forms
•	Creating the ability to collect user data
  <input type="text" name="firstname" value="test">
•	Making text fields, radio buttons, and check boxes
  <input type="radio" name="gender" value="male"> Male<br>

•	Making drop down menus

<select multiple>
  <option value="java">Java</option>
  <option value="dbms">DBMS</option>
</select>
Tables
•	The table, tr, and td tags
•	The th tag
•	The caption tag
•	Spanning multiple rows and columns
•	The thread, tbody, and tfoot tags
•	Div Tag
•	Span Tag

<style>
caption {
    text-align:left;
}
</style>
<table style="width:100%">
<caption>Whatever goes here!</caption>
  <tr>
    <th>Firstname</th>
  </tr>
  <tr>
    <td>Jill</td>
   </tr>
</table>

 <tr>
    <td>test</td>
    <td rowspan="2">value</td>
  </tr>
  <tr>
    <td>test</td>
  </tr>

Meta Tags
•	 Meta Tags and various attributes 
  <meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">
    <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
•	Meta Headers



