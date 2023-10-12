# html-dump-files
Brushing up on HTML basics



_____

Fundamental Topics:

## WHAT is HTML 

#### HTML is an acronym for Hyper Text Markup Language 

Is a most basic building block for "webpage" creation
It is used to define the structure of a webpage
it does so through the use of "tags" or elements.
They describe what should be in the structure for example
<p></p> would be a paragraph tag.
HYPERTEXT also refers to the links that connect pages to each other
or to other websites(like anchor tags <a></a>).

So structure not styling the styling is handled by CSS(Cascading style sheets).

_________

## HTML Structure and Syntax:

HTML consists of a series of Elements,

Typical structure is text surrounded by a pair of angle brackets(<>)
tags/elements are case-insensitive so can be uppercase or mixture
but the recommended practice is to use lower-case

Here is the parts that make up a title element

title === the name and type of element 
< >   === angle brackets
/     === closing forward slash(indicates the end of the tag)
THE TITLE OF THE ARTICLE  ==== the text that will display on the tab of the browser


When they are combined the look like this


< title >                  |----> opening tag <br />
 THE TITLE OF THE ARTICLE  |----> the text that would appear on the page <br />
< title />                 |----> closing tag <br />

<title> THE TITLE OF THE ARTICL </title> <br />

The above is called an ELEMENT.

_________

## HTML Elements 

ELEMENTS can also have attributes, which can give extra information about the elelemnt

here is thesame title element with a class attribute added to it.
The class attribute allows you to give the element non-inique identifier 
that can be used to target it with specific style information and other things
some attributes have no value like the"required"attribute.

### Attributes that set a value always have
1. A space between it and the element name <br />
2. the attribute name followed by an equal sign <br />
3. the attribute value wrapped by opening and closing quotation marks <br />

< title class=""main title">   |----> opening tag with a class attribute <br />
 THE TITLE OF THE ARTICLE      |----> the text that would appear on the page <br />
< title />                     |----> closing tag


### Nesting elements and the anatomy of a full HTML document


Nesting elements can be done in hyper text markup and refers to having one elelment 
within another.

for example here is a <p/> tag(paragraph) with an additional tag inside of it that would make the text apear bold

<p> this is a story about a cat named <strong> Bobby <strong /> <p/>

this element would have the HTML document displae the above sentence with the 
name Bobby in bold text.


### <!doctype html>  
Around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML
but these days it is a required preamble intended to make sure the document behaves correctly


### < html lang="en-US" >     
Wraps the content on the entire page sometimes refered to as the root element

### < head >
Container that will hold things you want ot add to the page like link/ref to style sheets 
Includes things like keywords and a page description that you want to appear in search results,
CSS to style our content, character set declarations, and more.

### < meta charset="utf-8" / >
This element sets the character set your document should use the one noted here 
UTF-8 includes most characters(others examples  include ASCii)

### < meta name="viewport" content="width=device-width" / >
Ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.

### <title>My test page</title> 
This sets the title of your page as previously explored
### < body > 
Will typically contain the content you wish to display (the title tag could also be nested within this)


## A full HTML document
![htmlpage](https://github.com/WintonDeVilliers/html-dump-files/assets/65846344/71e40531-d915-4426-96ce-bc8822f87b29)




## A form using HTML would look like this  (without any styling in CSS ) .
![formhtml](https://github.com/WintonDeVilliers/html-dump-files/assets/65846344/7cf47210-5ccf-4bf7-a97c-43b039b4a32c)














