# HTML-Interview-Prep
1.  What is the difference between HTML and XHTML?  
A. HTML and XHTML are both languages in which web pages are written HTML is SGML standard generalized markup language based and XHTML is XML extensible markup language based at XHTML was derived from HTML to confirm to XML standards XHTML is stricter in terms of tags when compared to HTML for example in HTML all tags and attributes are not necessarily to be in Lower or upper case while in XHTML every tag and attribute should be in lowercase. File format used for HTML are .html, .htm
file format used for XHTML are .xml, .xhtml, .xht  

2.  What are the new form elements in HTML5?  
A. Following are the list of new form elements in HTML5
- data list 
- output tag 
- Keygen tag 
- progress tag
- meter tag  

3.  What is DOM? How does the DOM work?  
A.  When a web page is loaded browser creates a document object model DOM of the webpage. It is constructed as a tree of objects. When we want to access HTML elements with JavaScript, you have to find it first. 
There are couple of ways to do this:
- finding HTML elements by ID
- finding HTML elements by tag name
- finding HTML elements by class name
- finding HTML elements by HTML object collection  

4.  What does a DOCTYPE html do?  
A. doctype stands for document type declaration. It informs the web browser about the type and version of HTML used in building the web document. This helps the Browser to handle it properly.   

5.  What are the building blocks of HTML5?  
A. 
- Semantics:
allows us to described more precisely what our content is. 
- Connectivity:
allows us to communicate with the server in new and innovative way.
- offline and storage:
allows web pages to store data on the client side locally and operate offline more effectively. 
- Device access:
allows for the uses of various input and output devices. 
- Styling:
letting authors write more sophisticated themes.  

6.  What is the difference between a span and a div?  
A. Div tag is known as division tag. It is used in HTML to make divisions of content on the web pages like text, images, headers, footers, navbar, etc.
span tag is a generic inline container for inline elements and contents. it is used to group elements for styling purposes by using class aur IDs. Span is very similar to div tag the difference is span is inline element and Div is block level element.  

7.  Name 5 common block-level and inline HTML elements?  
A. 
- Five block level elements  
div  
Image  
heading tag  
paragraph tag  
ul, li   
- Five inline elements  
Span  
Anchor  
Button  
Strong  
Progress  

8.  What are semantic and non-semantic elements?  
A. Semantic tags are those who clearly describes its meaning to the browser and developers. 
For example, H1 and H2, aside and nav, header and footer.
non semantic tags are those who does not clearly describes its meaning to browser or developer.  
for example, span and div.  

9.  Why you would like to use semantic tag?  
A. Semantic tag introduces meaning to the web page rather than just presentation for example <p> tag indicates that the enclosed text is paragraph. This is both semantic and presentational because people know what paragraphs are and browser know how to display them. Adding semantic text to your document you provide additional information about that document which aids in communication. Specifically semantic text makes it clear to browser what the meaning of a web page and its content is.   

10.  What are the semantic tags available in HTML5?  
A.		
  - Article
  - aside
  - Nav
  - Details
  - Figcaption
  - Footer
  - Header
  - Main
  - Mark
  - Section
  - Summary
  -Time 
 
11.  What are optional closing tag?  
A. These are those tags which are not required to close necessarily because it is implied that a new tag would not be able to started without closing it.
For example, HTML, head, body, li, option, etc.  

12.  What is a self-closing tag?  
A. Text which does not required closing are called as self-closing tags.
for example, 		img, br, hr, input, etc.
note: forward slash is optional in HTML5.   

13.  What is the purpose of main element?  
A. Main element represents the main content section of the body of a document or application. The main content section consists of content that is directly related to or expands upon the Central topic of a document or central functionality of an application or document.   

14.  When should you use section, div or article?  
A. 
- section:  
it is used when two headers or footers or any other section of documents are needed.   
- Div:  
it is used to make divisions of content on web pages.   
- Article:  
on a webpage with a single piece of content a single article element can be used to contain the main content and set it off from the rest of the page.   

15.  How to make page responsive?  
A. We can give text and images relative sizes to its parent element or to its viewport. 
In addition to resize text and images we can use media queries to create a responsive page.   

16.  What is Character Encoding?  
A. Words and sentences in text are created from characters.
characters that are needed for a specific purpose are grouped into a character set also called as repertoire, to refer to characters in an unambiguous way each character is associated with a number called a code point.   
we can visualise this by assuming that all characters are stored in computers using a special code. a character encoding provides a key to unlock that is to crack the code. It is set of mapping between the bytes in the computer and the characters in the character set.
Without the key data looks like garbage.   

17.  What is the purpose of meta tags?  
A. The meta tag defines meta data about an HTML document. Metadata is information about data.  
meta tag always goes inside the head element and are typically used to specify character set, description, keywords, documents and viewport settings.   

18.  What is the purpose of the alt attribute on images?  
A. The "alt" attribute of image tag is used to specify the alternate text for an image it is useful when the image is not displayed to give alternative information of an image.  

19.  What is difference between Select and DataList?  
A. select input element presents options for the users which they need to select one of them. on the other hand, data list presents a list of suggested values to the associated input from text field and users are free to select one of those suggested values a type in their own value.  

20.  What is desktop first and mobile first design approach?  
A. The term mobile first means that when developing a website, we start writing the CSS for smaller viewport sizes first. And then Use CSS media queries to alter the experience for larger screens and vice versa.   

21.  What are data-* attributes good for?  
A. data-* attributes allow us to store extra information on standard semantic HTML elements without other hacks such as non-standard attributes or extra properties on Dom. It implies that data should be associated with a particular element but not need to have any defined meaning.   

22.  Explain about HTML Canvas?  
A. HTML Canvas element is used to draw Graphics on the fly via JavaScript. 
The Canvas element only a container for graphics. you must use JavaScript to actually draw the graphics.   
Canvas has several methods for drawing paths, boxes, circle, text and adding images.   

23.  What is difference between SVG and Canvas?  
A. Svg is a language for describing 2D graphics in XML. Canvas draws 2D Graphics on the fly with JavaScript. Svg is XML based which means that every element is available within the svg dom.  
Canvas is rendered pixel by pixel. In Svg every shape is remembered as an object.   

24.  Explain Drag and Drop in HTML5?  
A. Drag and drop is a very common feature it is when you grab an object and drag it to a different location.   

25.  Describe the difference between a cookie, session Storage and local Storage?  
A. 
- Cookies:  
cookies store small amount of data that has to be sent back to the server with JavaScript subsequent requests and their expiration can be set from either server or client. They are primarily used for server-side reading.   
Capacity - 4kb  
accessible from- any window  
expiration- manually set  
storage location- browser and server  
sent with request- yes  
block able by users – yes  
editable by users- yes  
- Local storage:  
local storage stores a large amount of data on the client’s computer in a key-value pair format and has no expiration date. Data is never transferred to the server and is accessible via JavaScript and HTML5.   
Capacity- 10 MB  
accessible from- any window  
expiration- never  
storage location- browser only  
sent with request- no  
block able by user- yes  
editable by users- yes  
- Session storage:  
session storage stores a large amount of data on clients Computer only for the current session, expiring the data on tab close, data is never transferred to the server and is accessible client side from the same tab.  
capacity- 5mb  
accessible- same tab  
expiration- on tab close  
storage location- browser only  
sent with requests- no  
block able by user- yes  
editable by user- yes  
 
26.  List the APIs available in HTML5?  
A.
- Canvas element for immediate mode 2d drawing  
- Drag and drop  
- cross document messaging  
- timed media playback  
- offline web applications  
- document editing  
- browser history management  
- web workers  
- web storages  
- audio API  
- video API  
- history  
- file  
More commonly used API  
- high resolution time API  
- navigation timing API  
- network information API  
  
  
27.  What does async and defer refer in script tag? Describe the difference between <script>, <script async> and <script defer>?  
A. 
- Defer:  
while parsing the code it tells the browser that it should download the JavaScript right now but it should not block the parsing of HTML file and execute the JavaScript after everything is parsed considering the order executing the JavaScript.   
  
- Async:  
it is same as defer but only difference is that it executes the JavaScript right after downloading it. While does not block the parsing of HTML file. It is used where JavaScript is independent of HTML code. It does not consider the order of scripts and executes the one which is downloaded first.   
- script:  When reading the HTML code from top to bottom when Browser reaches this line it is stop parsing HTML file and starts downloading script executes it once downloaded. After the execution browser resumes the HTML parsing.   
- script async:  While reading the code when Browser reaches this line, it starts downloading the JS file while does not block or pause the HTML parsing & execute the script as soon as it is downloaded, no matter if HTML file is downloaded completely or not, it also does not consider the sequence of JavaScript it, executes the script whichever downloads first and so on.   
- script defer: It tells the browser that it should download the scripts right now but that it should not pause or block the parsing of HTML file and execute the JS after everything is parsed, and also considers the sequence of the JavaScript.     
  
  
  
 
28.  Define semantic markup. What are the semantic meanings for section, article, aside, nav, header, footer Also explain when/how should each be used in structuring html markup?  
A.   
  
A semantic element clearly describes its meaning to both the browser and the developer.   
- Section:  
it defines the section in a document. 
A section is a thematic grouping of content typically with the heading. 
Section can be used in chapters, introductions, news items, contact information.   
- Article:  
this element specifies independent self-contained content.
article should make sense on its own and it should be possible to destroy independently from the rest of the website. 
article can be used in forum posts, blog posts, user comments, product cards, newspaper articles.   
- Aside:  
it defines some content aside from the content placed like sidebar.
it should be indirectly related to the its surrounding content  
- nav:  
it defines a set of navigation links.
It should not contain all links of a document. it is intended only for Major block of navigation links.   
- Header:  
it represents a container for introductory content or a set of navigational links.
it contains one or more heading elements, logo or icon, authorship information.  
- Footer:  
it defines a footer for a document or section.
it contains authorship info, copyright info, contact info, site map, back to top links, related documents.
