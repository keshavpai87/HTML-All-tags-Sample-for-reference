**Frontend has 3 parts :**
**HTML** - Structure/layout of the page - Hyper Text Markup Language
**CSS** - Style - Cascading Style Sheets
**JS** - Logic

**Basics of HTML **: 
**Hyper Text Markup Language**
Defines the code that is used to structure a web page and its content
The components used to design the structure of website are called HTML Tags
Right click on the page and click on Inspect to see the configuration of each element on the page

**INDEX.HTML** is the entry point for any website. 
In case, we need to have a different entry point, we need to specifically mention it

<DOCTYPE HTML> - Informs the browser that we are using HTML5
<html> - Root of an HTML document
<head> - Container for metadata
<body> - Contains all the data rendered by the browser
  
Comment : <!-- This is a comment -->

HTML is not case-sensitive
  
<h1>...<h6> refers to the heading tags
<p> - Refers to a paragraph
If the content inside the tag is long enough, we can select the content and then go to settings->command pallete->Toggle Word Wrap

Anchor Tag(<a>) - Used to add links to your page
There are 2 types of URL : 
1. Absolute URL - Accessing directly from the Internet
2. Relative URL - Accessing from our local folder


**There are 2 types of tags in HTML :**
1. Semantic Tags : These are the tags which can be understood by reading the name of the tags
	i. 	header
	ii.	main
	iii.footer

2. Non Semantic Tags
	i.	div - Is a container used for other HTML Elements. By default the height of a div is ZERO. Its called a Block Element. It occupies full width
	ii.	span
	
**<aside>** -> Mainly used to show some ads on the website

**Inline ELements :**
Inline Elements like SPAN takes width as much as its required, Block Elements occupy full Width
Span, br, img, a, i, b, sub, sup

**Lists :** 
i. Ordered - Sequence of numbers
ii. Unordered - bullets

We can have nested lists as well within ordered and unordered lists

**Tables : **
<tr> - used to display table row
<td> - used to display table data
<th> - used to display table header
<thead> - To wrap the header details inside this tag
<tbody> - To wrap the contents/data inside this tag
<caption> - To display a caption above the table
colspan = 2 : Occupies 2 columns
rowspan = 2 : Occupies 2 rows

**Forms :** 
Forms are used to collect the data from the User
Eg : Login, Register, Profile
Syntax:
<form>
	Form Content
</form>

<form action="login.php">
Action refers to where the data goes on Submission

**iframe** is used to display a website inside a website
