```
Qun. What is HTML Tag?
Ans: An HTML tag is a piece of code that tells the browser what to display and how to display it on a webpage.

Example of a Tag: <p>This is a paragraph.</p>

Qun. what is Semantic Tag? and it's type.
Ans:A semantic tag in HTML is a tag that clearly describes its meaning to both the browser and the developer.These tags help with SEO (Search Engine Optimization) and improve code readability.

Some example of Semantic tag:
1.<p> tag: With the help of this tag, we can define a paragraph of text.
It automatically adds some space before and after the text block in the browser.
Syntax:
<p>This a paragraph</p>

2.<a> tag:With the help of this tag, we can create a hyperlink to the web page. The hyperlink can be done with the help of another file in a different location.
 Syntax:<p>Your paragraph text here.</p>
   <a href="url">Link Text</a>

3.<ul> tag:With the help of this tag, we can create an unordered list.
It displays list items with bullet points by default.
Syntax:

<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
4.<ol> tag: This tag is used for the creation of the ordered list. The ordered list can be numerical or alphabetical. Inside the <ol> tag, we can create the list using the <li> tag. It will then follow the order.

Syntax:
<ol>  
<li>First Item</li>  
<li>Second Item</li>  
<li>Third Item</li>  
</ol

5.<li> tag: With the help of this tag, we can represent the list of items on the web page. It contains an ordered list (an unordered or a menu) as a parent element.

Syntax:
<ul>  
<li>List Item 1</li>  
  <li>List Item 2</li>  
<li>List Item 3</li>  
</ul> 

6.<table> tag: With the help of this tag, we can define the data in a tabular format in HTML. It will create a two-dimensional table that has some rows and columns.

Syntax:
<table>  
  <!-- Table content goes here -->  
</table>

7.<tr> tag: With the help of this tag, we can define a row in an HTML table.
It is used inside the <table> tag and contains table cells like <td> or <th>.

Syntax:
<tr>
  <td>Data 1</td>
  <td>Data 2</td>
</tr>

8.<td> tag:With the help of this tag, we can define the table's cell. A table row may consist of more than one <td> element. The default alignment is left in this element.

Syntax:

<tr>  
  <td>Table cell content</td>  
</tr>

9.<th> tag:With the help of this tag, we can define a header cell in an HTML table.
Text inside <th> is bold and centered by default. It is usually used in the first row.

Syntax:

<tr>
  <th>Heading 1</th>
  <th>Heading 2</th>
</tr>

10.<img> tag: With the help of this tag, we can embed an image into the current web page. It links an image to the image without directly inserting it into the web page.

Syntax:
<img src="image-url" alt="alternative-text"> 

11.<form> tag: With the help of this tag, we can receive the information from the user.

Syntax:
<form action="form-handler-url" method="HTTP-method">  
<111!-- Form controls go here -->  
</form>  

12.<inpur> tag: With the help of this tag, we can enable interactive control in the form. It also depends on the various fields of the attribute type.

Syntax:
<input type="input-type" name="input-name" value="default-value">  

Qun. What is Formatting tags? and it's type.
Ans: HTML provides many predefined elements that are used to change the formatting of text. The formatting can be used to set the text styles (like – bold, italic, or emphasized, etc.), highlight the text, make text superscript and subscript, etc.
or 
Formatting tags** in HTML are used to **change the appearance of text** — like making it bold, italic, underlined, or styled in other ways. These tags help emphasize content, highlight important parts, or display special formatting like code or math formulas.

Types of Formatting Tags:


1. <b> – With the help of this tag, we can make the text bold without any additional significance.
example:-
<b>This is bold text.</b>


2. <i> – With the help of this tag, we can make any content italicized. It Highlights an important term, phrase, or technical term.
example:-
<i>This is italic text.</i>


3. <u> – With the help of this tag, we can underline the text.
It is used to highlight words or phrases with a line below the text.
example:-
<u>This is underlined text.</u>

4. <s> –With the help of this tag, we can render the text with a strikethrough or a line through it. We can use this tag when Things are no longer accurate or relevant.
example:-
<s>This text is no longer valid.</s>

5. <strong> – With the help of this tag, we can define the content as very important. The browser will display that element in bold.
example:-
<strong>This is important!</strong>


6. <em> – With the help of this tag, we can emphasize a particular word or phrase within a sentence. It converts the normal word or sentence into italic and semantic styles.
example:-
<em>This word is emphasized.</em>


7. <sup> – With the help of this tag, we can display any text as the superscript of the inline element.
example:-
2<sup>nd</sup>  →  2nd


8. <sub> – With the help of this tag, we can display subscript text, which appears slightly below the normal text line.
It is commonly used in chemical formulas.
example:-
H<sub>2</sub>O  →  H₂O

9. <pre> – With the help of this tag, we can declare the block of pre-formatted text on the web page the pre-formatted character, such as spaces, line breaks, tabs, etc.

example:-
<pre>
This is    preformatted
   text with spaces
</pre>


10. <code> – With the help of this tag, we can insert a particular code fragment, which might be HTML or CSS code.
example:-
<code>console.log("Hello World");</code>

11. <h1> to <h6>:
With the help of this tag, we can define the web page's heading. It also makes the heading as large and bold by default. the <h1> headings are displayed in the largest font, whereas the <h6> headings are displayed in the smallest font.

Syntax:

<h1>Heading level 1</h1>  
<h2>Heading level 2</h2>  
<h3>Heading level 3</h3>  
<h4>Heading level 4</h4>  
<h5>Heading level 5</h5>  
<h6>Heading level 6</h6>  


Qun. What is Structure Tags? and it's type.
Ans: Structure Tags are HTML tags that define the layout and structure of a web page.
They help browsers and developers understand the main parts of a page.
These tags do not style the content — they just give it a proper structure.

**Why Use Structure Tags?**
->For organized content layout.
->Improves SEO (search engine optimization).
->Makes the website more accessible and readable for screen readers and devices.

**Common Types of Structure Tags**

1.<html> – Root of the HTML document With the help of this tag, all other elements are contained by it. It is also known as the root of the HTML element.

Syntax:
<!DOCTYPE html>  
<html>  
<!-- HTML content goes here -->  
</html>  

2.<head> – Metadata container (not visible content) With the help of this tag, we can specify the header part of the header section of the code. It contains all the information regarding the document.

Syntax:

<head>  
  <!-- Head content goes here -->  
</head>

3.<body> – Main visible content container With the help of this tag, we can define the web page's main content. The body tag includes text, paragraphs, headings, images, tables, links, and videos.

Syntax:
<body>  
  <!-- Content goes here -->  
</body>  
<strong> </strong>

4.<header> – Top section (like logo, title, nav) With the help of this tag, we can define the webpage's header. It also contains information regarding the title and heading of the document and section.

Syntax:
<header>  
  <!-- Header content goes here -->  
</header>  

5.<nav> – Navigation links (menus, links) With the help of this tag, we can represent the section of navigational links in a document. Some examples of nav tags are Menus, tables of contents, indexes, etc.

Syntax:
<nav>  
<!-- Navigation links or menus go here -->  
</nav>

6.<main> – Main content area (only one per page) With the help of this tag, we can make an ordinary element the most important element. We have to write this tag inside the <body> tag.

Syntax:
<main>  
<!-- Main content goes here -->  
</main>  

7.<section> – Group of related content and With the help of this tag, we can create the header and footer or any other section on the web page.

Syntax:
<section>  
  <!-- Content goes here -->  
</section>  

8.<article> – Independent, self-contained contentWith the help of this tag, we can represent a piece of content that is used to be distributed to other websites without being a part of this. With the help of <article> tag, we can display entire blog posts, news articles, or similar content, etc.

Syntax:
<article>  
<!-- Content goes here -->  
</article>

9.<aside> – Side content (ads, widgets, tips)With the help of this tag, we can define the content related to the web page's main content, but they are not constituted to the web page.

Syntax:
<aside>  
<!-- Content goes here -->  
</aside

10.<footer> – Bottom section (copyright, links) With the help of this element, we can represent the footer part in the root element.

Syntax:
<footer>  
<!-- Footer content goes here -->  
</footer>

11.<div> – Generic container (used for layout, no meaning by itself) With the help of this tag, we can create a generic container that can hold the flow of the content. It also does not have the default rendering.

Syntax:
<div>  
<!-- Content goes here -->  
</div> 


Qun. difference between Tag and Element.
Ans: 
Tags:
-> Tags are always enclosed in angle brackets ( < and > ). 
-> They can be opening tags (e.g., <p>) marking the start of an element or closing tags (e.g., </p>) marking the end of an element. 
-> Some tags are self-closing (e.g., <img>) and don't require a closing tag. 

Elements:
-> An element is typically composed of an opening tag, optional attributes, content, and a closing tag. 
-> Elements provide structure and meaning to a webpage, allowing browsers to interpret and display content correctly. 
-> For example, the element <p>This is a paragraph.</p> consists of the opening <p> tag, the content "This is a paragraph.", and the closing </p> tag. 
 