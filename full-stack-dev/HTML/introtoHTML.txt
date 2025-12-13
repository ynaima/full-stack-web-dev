html -> HyperText Markup Language is used to create the foundation of the website( the structure,
skeleton of the website)
CSS -> is used to design the website, give it different shapes and colors and make it presentable
javaScript -> is used to to handle events when a button is clicked as well as store and manipulate data.

start with h1 and continue to h6 for headings in order for each level of heading
each heading tag has an opening and a closing tag <h1>Heading 1</h1>
headings html tags should not be used to make text big and bold

not recommended to use more than one h1 heading because it is the highest level.

to create paragraphs we use the <p> </p> element.

what are HTML void elements?
these are self -closing tags. they are called void because they do not have content section. they are self-closing tags because they
do not have a closing and opening taggs.
for example. <hr/> - for creating a horizontal line , <br/> creates a new line feed. it could also be written as just <br> or <hr>


so far what we learned:
<h1> to <h6> elements, <br/>, <hr/>, <p> 
creating the project movie randing using the above what we have learned so far.

project requirements

THE ANATOMY OF HTML
any tag has a closing and a opening tag.
self closing tags do not have a closing tag.
<opening tag> content </closing tag>



Elements with opening and closing tags
<h1> to <h6>  
<center> </center>   -> takes content to the centre of the page




Elements that are self closing tags/void elements
<br> -> creates a new line by breaking up text
<hr> -> draws a horizontal line
<img src= "url/>



html attributes 
->each html element can have many attributes and the attributes appear in the opening tag with one space from the html element
<element attribute = value>
-> google what attributes each element has
<!-- this is a comment ..>




what is boiler plate code (it is like a code template) (get it by typing ! and then enter)

<!DOCTYPE html>      ---- shows The version of the html that is being used to make the website(html5 document)
<html lang="en">     ------ shows that it is the start of the html page 

<head>            --- this is the html tag holds the information about the webpage
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>          - tells the title of the page
</head>

<body>                       --- this is the second tag that shows the body of the html document. inside here we can have many other tags.

</body>                       ---- this shows the end of the html document.

</html>                 ----shows the end of the html page



The meta tag
The meta tag is used to show metadata that cannot displayed by other meta related tags such as title, script, liks, base and style
 
meta can have different attributes and it is used to display information about the webpage.
This information includes description(which when the webpage is browsed it comes up as a brief introduction of what the site is about)
then author and keywords that identify the site, and viewport for displaying the page on different screen sizes.

<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>


to format html text
<b> - Bold text
<strong> - Important text    --- use the <strong> because it makes it bold and also it conveys importance
<i> - Italic text
<em> - Emphasized text        -- used the <em> tag because it italicizes the text and also conveys importance.
<mark> - Marked text         - used to show a text that has been highlighted or marked
<small> - Smaller text       -- used to show a text that is smaller
<del> - Deleted text         -- used to show a text that has been deleted
<ins> - Inserted text         -- used to show a text that has been inserted
<sub> - Subscript text        -- used to show a text that is a subscript
<sup> - Superscript text      -- shows a text that is a superscript


creates a horizontal line 
 <hr font="4" noshading>



