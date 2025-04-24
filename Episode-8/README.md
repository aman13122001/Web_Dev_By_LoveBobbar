````
Qun. What is forms ?
Ans: An HTML form is a section of a document which contains controls such as text fields, password fields, checkboxes, radio buttons, submit button, menus etc.

An HTML form facilitates the user to enter data that is to be sent to the server for processing such as name, email address, password, phone number, etc.

Qun. What is Form Tag?
Ans: The HTML <form> element provide a document section to take input from user. It provides various interactive controls for submitting information to web server such as text field, text area, password field, etc. 

Note: The <form> element does not itself create a form but it is container to contain all required form elements, such as <input>, <label>, etc.

Syntax:

<form>  
//Form elements  
</form>  
 

** Some Attributes **
1.type:- It is used to specify the type of the input element. Its default value is text.

2.value:- It is used to specify the value of the input element.

3.plaseholder:- Placeholder attribute is used to specify hint that describes the expected value of an input field.

4.name:- It is used to specify the name of the input element.
5.alt:- 	
It is used to provide alternate text for the user, if they cannot view the image.

6.step:- It is used to specifies the legal number intervals for an input field
*** Type of input ***

1.text:- The type="text" attribute of input tag creates textfield control also known as single line textfield control. The name attribute is optional, but it is required for the server side component such as JSP, ASP, PHP etc

Example:-

<form>  
    First Name: <input type="text" name="firstname"/> <br/>  
    Last Name:  <input type="text" name="lastname"/> <br/>  
 </form>

2.password:- The password is not visible to the user in password field control.

Example:-
<form>  
    <label for="password">Password: </label>  
              <input type="password" id="password" name="password"/> <br/>  
</form>

3.email:- The email field in new in HTML 5. It validates the text for correct email address. You must use @ and . in this field.

Example:-

<form>  
    <label for="email">Email: </label>  
              <input type="email" id="email" name="email"/> <br/>  
</form> 

4.radio:- The radio button is used to select one option from multiple options. It is used for selection of gender, quiz questions etc.

If you use one name for all the radio buttons, only one radio button can be selected at a time.

Using radio buttons for multiple options, you can only choose a single option at a time.

Example:- <form>  
    <label for="gender">Gender: </label>  
              <input type="radio" id="gender" name="gender" value="male"/>Male  
              <input type="radio" id="gender" name="gender" value="female"/>Female <br/>  
</form> 

5.checkbox:- The checkbox control is used to check multiple options from given checkboxes.

<form>  
Hobby:<br>  
              <input type="checkbox" id="cricket" name="cricket" value="cricket"/>  
                 <label for="cricket">Cricket</label> <br>  
              <input type="checkbox" id="football" name="football" value="football"/>  
                 <label for="football">Football</label> <br>  
              <input type="checkbox" id="hockey" name="hockey" value="hockey"/>  
                 <label for="hockey">Hockey</label>  
</form>

6.submit:- HTML <input type="submit"> are used to add a submit button on web page. When user clicks on submit button, then form get submit to the server.

Syntax:

<input type="submit" value="submit"> 

7.file:- The <input> element with type "file" is used to select one or more files from user device storage. Once you select the file, and after submission, this file can be uploaded to the server with the help of JS code and file API.

Example:
<form>  
     <label>Select file to upload:</label>  
     <input type="file" name="newfile">  
     <input type="submit" value="submit">  
</form>  

8.image:-The <input> type "image" is used to represent a submit button in the form of image.

Example:-

<form>  
    <label>User id:</label><br>  
     <input type="text" name="name"><br><br>  
     <input type="image" alt="Submit" src="login.png"  width="100px">  
  </form>  

9.date:- The <input> element of type "date" generates an input field, which allows a user to input the date in a given format. A user can enter the date by text field or by date picker interface.

Example:- 

<form>  
    Select Start and End Date: <br><br>  
      <input type="date" name="Startdate"> Start date:<br><br>  
      <input type="date" name="Enddate"> End date:<br><br>  
     <input type="submit">  
</form>

10.number:- The <input> element type number creates input filed which allows a user to enter the numeric value. You can also restrict to enter a minimum and maximum value using min and max attribute.

Example:
<form>  
    <label>Enter your age: </label>  
    <input type="number" name="num" min="50" max="80">  
     <input type="submit">  
</form>

11.search:- The <input> type "search" creates an input filed which allows a user to enter a search string. These are functionally symmetrical to the text input type, but may be styled differently.

Example:
<form>  
    <label>Search here:</label>  
    <input type="search" name="q">  
    <input type="submit" value="search">  
</form>

*** form Elemnets ***

1.input :- The HTML <input> element is fundamental form element. It is used to create form fields, to take input from user. We can apply different input filed to gather different information form user. Following is the example to show the simple text input.

Example:
<body>  
  <form>  
     Enter your name  <br>  
    <input type="text" name="username">  
  </form>  
</body>  

2.label:-The <label> tag is used to specify a label for an <input> element of a form. It adds a label to a form control such as text, email, password, textarea etc. It toggles the control when a user clicks on a text within the <label> element.

If you click on the label tag, it will focus on the text control. To do so, you need to have for attribute in label tag that must be same as id attribute of input tag.

Syntax:
<label> form_content... </label>
3.select:- In HTML, with the help of a select tag, we can create the dropdown list while creating the form where the user can choose one of the options from the given option. 


4.option:-HTML <option> tag is used to define options in a dropdown list within <select> or <datalist> element. A dropdown list must have at least one <option> element.

Example:-
<select name="dishes" id="selection1">
        <option value="maggi">Maggi</option>
        <option value="kurkure">Kurkure</option>
        <option value="chips">Chips</option>
</select>

5.button:-The <button> tag is used to create a clickable button within HTML form on your webpage. You can put content like text or image within the <button>........</button> tag.

Example:-
<button name="button" type="button">Click Here</button>  

6.textarea:-The <textarea> tag in HTML is used to insert multiple-line text in a form. The size of <textarea> can be specify either using "rows" or "cols" attribute or by CSS.

Example:-

<textarea name="textarea" id="textarea" cols="30" rows="10" placeholder="Enter test here.."></textarea>

7.fieldset:- The <fieldset> element in HTML is used to group the related information of a form. This element is used with <legend> element which provide caption for the grouped elements.

Example:

 <form>  
     <fieldset>  
      <legend>User Information:</legend>  
      <label for="name">Enter name</label><br>  
      <input type="text" id="name" name="name"><br>  
      <label for="pass">Enter Password</label><br>  
      <input type="Password" id="pass" name="pass"><br>  
      <input type="submit" value="submit">  
</fieldset>  
</form>

8.legend:-HTML <legend> tag is used to insert a title or caption to its parent element such as <fieldset>. The <legend> element must be the first child of <fieldset > element.

By using <legend> tag with <form> elements, it is easy to understand the purpose of grouped form elements.

Syntax

<fieldset>  
<legend> Content........<legend>    
<!-- other content -->  
</fieldset> 

9.image:- Defines a graphical submit button.

Example:- 
<label for="">Image Button:</label>
       
        <input type="image" id="imageButton1" name="imageButton1" alt="Click here" src="pngtree-vector-down-arrow-icon-png-image_956433.jpg" height="30px" width="30px">