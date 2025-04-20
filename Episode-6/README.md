````
Qun. What is Emmet?
Ans: Emmet is a code expansion tool.
-> It helps you write short expressions (abbreviations) and expand them into full HTML or CSS code.
-> Supported in most modern code editors, like VS Code, Sublime Text, etc.


🔹 Why Use Emmet?
💨 Fast coding: Write less, get more.

📄 Auto-complete HTML structures.

🧠 No need to remember full syntax.

💼 Increases productivity for front-end developers.


Qun. What id and class?

Ans: Id: The id attribute is used to specify the unique ID for an element of the HTML document. It allocates the unique identifier which is used by the CSS and the JavaScript for performing certain tasks.

Syntax: 
<tag id="value">

Class: The HTML class attribute is used to specify a single or multiple class names for an HTML element. The class name can be used by CSS and JavaScript to do some tasks for HTML elements. You can use this class in CSS with a specific class, write a period (.) character, followed by the name of the class for selecting elements.
A class attribute can be defined within <style> tag or in separate file using the (.) character

Syntax: 
<tag class="ghf"> content </tag>  

*** Example  of Emmet ***

1. p>img 
    <p>
        <img src="" alt="">
    </p>

2. p>p>p>p>p 
    <p>
        <p>
            <p>
                <p></p>
            </p>
        </p>
    </p>
3.  p>h1 
    <p>
        <h1></h1>
    </p>
    
4. article+section 
    <article></article>
    <section></section>

5.  p+h3+article 
    <p>this is my first paragraph</p>
    <h3>this is my fist heading</h3>
    <article>this my first article</article>

6.  p>a 
    <p>
        <a href=""></a>
     </p>
7. p+a 
     <p></p>
     <a href=""></a>

 8. p>lorem7 
     <p>Lorem ipsum dolor sit, amet consectetur adipisicing.</p>

9. p{I read in MCA} 
     <p>I read in MCA</p>

10. a{Click here}
     <a href="">Click here</a>



<!-- Class and id attribute   -->
      
 1. p#paer1 
     <p id="para1"></p>

2. article#article 

    <article id="article"></article>
    
3. section#aman 
    <section id="aman"></section>

4. p.pare 
 <p class="para"></p>

5. article.dog 
 <article class="dog"></article>

6. section.dog.cat.lion 
 <section class="dog cat lion"></section>


*** list Created by Emmet ***

 1. p>ul>li*4 
<p>
    <ul>
        <li>a</li>
        <li>b</li>
        <li>c</li>
        <li>d</li>
    </ul>
</p>

first Way of doing this using '>'

<!--section>p>p>p  -->
<section>
    <p>
        <p>
            <p></p>
        </p>
    </p>
</section>

Seconf Way of doing this using '*'
<!-- section>p*3 -->
<section>
    <p></p>
    <p></p>
    <p></p>
</section>

*** Table Created by Emmet ***

1. table>tr>td*5 

<table>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

2. table>(tr>td*4)*2 
<table>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>

*** Multiple operater use in Emmet ***
1. header+main+footer 
    <header></header>
    <main></main>
    <footer></footer>


2. section(ul>li*2)+footer 
<section></section>
<ul>
    <li></li>
    <li></li>
</ul>
<footer></footer>


Qun. What is Div?
Ans:  Generic container (used for layout, no meaning by itself) With the help of this tag, we can create a generic container that can hold the flow of the content. It also does not have the default rendering.

Syntax:
<div>  
<!-- Content goes here -->  
</div>


Qun. What is Block and inline Elements in HTML?
Ans: Block Element: A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

Two commonly used block elements are: <p> and <div>.

The <p> element defines a paragraph in an HTML document.

The <div> element defines a division or a section in an HTML document. 

Here are the block-level elements in HTML:

<address>,<article>,<aside>,<blockquote>,<canvas>,<dd>,<div>,<dl>,<dt>,<fieldset>,<figcaption>,<figure>,<footer>,<form>,<h1>-<h6>,<header>,<hr>,<li>,<main>,<nav>,<noscript>,<ol>,<p>,<pre>,<section>,<table>,<tfoot>,<ul>,<video>.

Inline Element: An inline element does not start on a new line.
-> An inline element only takes up as much width as necessary.
-> This is a <span> element inside a paragraph.

Example
<span>Hello World</span>

Here are the inline elements in HTML:

<a>,<abbr>,<acronym>,<b>,<bdo>,<big>,<br>,<button>,<cite>,<code>,<dfn>,<em>,<i>,<img>,<input>,<kbd>,<label>,,<map>,<object>,<output>,<q><samp>,<script>,<select>,<small>,<span>,<strong>,<sub>,<sup>,<textarea>,<time>,<tt>,<var>.


Qun. how we can change the block element into Inline element?
Ans: by using display: inline we can do that.

Qun. how we can change the Inline element into block element?
Ans: by using display: block we can do that. 