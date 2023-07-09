![professional-programmer-working-late-dark-office_1098-18705](https://github.com/sujitmemane/Frontend-Interview-Preparation/assets/114643903/05bad5df-15c7-4ac8-8e49-242d2d4f961b)

# 🌟 Welcome to the Frontend Interview Preparation Repository! 🚀 
VISITOR COUNT : ![Visitor Count](https://profile-counter.glitch.me/{sujitmemane}/count.svg)


This repository makes frontend interview preparation a breeze. It contains a comprehensive collection of real interview questions covering various frontend topics. 💡

You can contribute and share your own interview questions to help fellow developers. Let's build a collaborative and supportive environment! Practice with these questions to enhance your skills and boost your confidence. This repository is suitable for both beginners and experienced developers, ensuring everyone can benefit from it. 


Share your interview experiences and learn from others in the vibrant community. 
Prepare for your frontend interviews with this amazing collection of questions. Good luck! 🔥


## HTML

HTML stands for HyperText Markup language. It is a standard text formatting language used for developing web pages released in 1993. HTML is a language that is interpreted by the browser and it tells the browser what to display and how to display. It defines the strucure of web page.

Ready to ace that frontend interview? Let's start with HTML - the backbone of all web pages. It defines the structure and formatting of a website. Check out these top interview questions!

1. What is HTML ?
    
    HTML stands for HyperText Markup Language and it is the standard language used for creating web pages. It is a markup language used to define the structure, content, and presentation of a web page. HTML tags are used to create elements such as headings, paragraphs, links, and images.
    
2. What is the difference between HTML elements and tags?
    
    
    | Elements | Tags |
    | --- | --- |
    | The element is an individual component of the HTML web page or document that consists of a start tag, its attributes, an end tag, and everything in between.  |  HTML tag (either opening or closing) marks the start or end of an element. |
    |  They usually contain a start tag, content, and an end tag. | They begin with < symbol and end with > symbol. Whatever is written inside < and > are called tags. |

3.  Do all HTML tags have an end tag?
    
    No, all HTML tags do not have an end tag. For example, the <br> tag is used to break the line, and <image> tag is used to insert an image into a document. They are considered self-closing tags and do not require an end tag. HTML elements which do not have closing tags or do not need to be closed are Void elements.
    

1.  What are HTML Attributes?
    
    HTML attributes provide additional information about HTML elements. They are defined directly after the tag name. They only appear in opening tags and not in closing tags.HTML attributes usually contain name/value pairs like name=”value”
    

1. What is semantic HTML?
    
    Semantic HTML involves using specific HTML tags that accurately describe the purpose and content of elements on a web page, enhancing its structure and meaning. By utilizing semantic HTML, search engines can better understand and index the content, potentially improving the website's visibility in search results. Additionally, semantic HTML improves accessibility for users with disabilities by providing clearer navigation and comprehension of the website's content.
    

1. What is the difference between a block-level element and an inline element?
    
    
    | Block-Level Elements | Inline Elements |
    | --- | --- |
    | They start on a new line. | Do not start on a new line and can begin within a line. |
    | Stretch to fill the full width available to them. | Take up as much width as necessary. Its width only extends as far as it is defined by its tags. |
    | They have a top and a bottom margin. | Inline elements do not have a top and a bottom margin.  |
    
    
2. What is the difference between LocalStorage and SessionStorage Objects?
    
    
    | LocalStorage Object | SessionStorage Object |
    | --- | --- |
    | It stores the data without an expiry date. | Stores the data for only one session. |
    | The data can be shared between multiple windows of the browser. | Data is accessible only in the current window of the browser. |
    |  Data is not deleted when the browser window closes. | The data is deleted if the browser window closes. |

1.  What is HTML5? What are some of its new features that were not present in HTML?
    
    HTML5 is the latest version of the Hypertext Markup Language. Some of the new features of HTML5 are :
    
    - HTML5 supports SVG, canvas, and other virtual vector graphics. In HTML, vector graphics can only be used with Flash, VML (Vector Markup Language), or Silverlight.
    - HTML5 allows JavaScript to run within a web browser. The previous version allowed JavaScript to run in the browser interface thread.
    - HTML5 is not based on SGML. It comes with enhanced parsing rules for improved compatibility.
    - In HTML5, web SQL databases are used to store data temporarily. Previously, only the browser cache was used.
    - Some elements have been removed – applet, isindex, noframes, acronym, dir, font, frame, frameset, and big are removed.
    - New elements have been added – time, summary, aside, audio, command, and data.
    
2. What is a meta tag?
    
    A meta tag in HTML is an element that provides metadata or additional information about a web page. It is placed within the head section of an HTML document and does not have any visible content on the page. Meta tags are used to convey details such as the page's title, description, keywords, author, character encoding, and viewport settings. Search engines and web browsers utilize these meta tags to understand and display information about the webpage.
    
3. What are HTML entities?
    
    A Group of characters that represent reserved and invisible characters in HTML are known as HTML entities. These strings start with an ampersand(&) symbol and end with a semicolon(;). They can also replace some characters that are challenging to type on a standard keyboard.
    
    
    Few entity symbols and their number are mentioned in below table:
   
    | Character | Symbol | Entity Name | Entity Number |
    | --- | --- | --- | --- |
    | < | Less than | &lt; | &#60; |
    | > | Greater than | &gt; | &#62; |
    | “ | Double quotation mark | &quot; | &#34; |
    | © | Copyright | &copy; | &#169; |
    | ® | Registered Trademark | &reg; | &#174; |
    | & | Ampersand | &amp; | &#38; |



---

## CSS
CSS stands for Cascading Style Sheet. It’s a style sheet language that determines how the elements/contents in the page are looked/shown. CSS is used to develop a consistent look and feel for all the pages.

Ready to ace that frontend interview? Let's start with CSS - the styling wizard of all web pages. It defines the visual appearance and layout of a website. Check out these top interview questions!



   1. What is CSS and what is its purpose?
    CSS stands for Cascading Style Sheets. It is a styling language used to describe the presentation of a document written in HTML. Its purpose is to separate the content
    from the design, allowing developers to control the appearance of web pages.
         
2. How do you include CSS in an HTML document?
    
    CSS can be included in an HTML document using three different methods:
    
    - Inline: Apply styles directly to an HTML element using the "style" attribute.
    - Internal: Embed CSS code within the HTML document using the "style" tag in the head section.
    - External: Link an external CSS file to the HTML document using the "link" tag in the head section.
    
3. What is the difference between class and ID selectors in CSS?
    
     Class selectors are used to target multiple HTML elements that share the same class attribute, while ID selectors target a unique element based on its ID attribute. In CSS, you can apply a class selector to multiple elements, but an ID selector should be unique within the document.
    

1. Explain the CSS box model.
    
    A rectangle box is wrapped around every HTML element. The box model is used to determine the height and width of the rectangular box. The CSS Box consists of Width and height (or in the absence of that, default values and the content inside), padding, borders, margin.
    
    - Content: The actual content of the element, such as text or images.
    - Padding: The space between the content and the border.
    - Border: A line that surrounds the padding and content.
    - Margin: The space between the border and neighboring elements.

1. Explain the CSS "position" property and its different values.
    
    The "position" property specifies the positioning method of an element. The commonly used values are:
    
    - "static" (default): The element follows the normal flow of the document.
    - "relative": The element is positioned relative to its normal position.
    - "absolute": The element is positioned relative to its nearest positioned ancestor.
    - "fixed": The element is positioned relative to the browser window and remains fixed even when scrolling.
    - "sticky": The element is positioned based on the user's scroll position, acting like a combination of "relative" and "fixed."

1. What are the key differences between the "inline" and "block" display properties in CSS?
    
    
    
    
    | Property | Inline | Block |
    | --- | --- | --- |
    | Default behavior | Elements are displayed in a line, and they do not force line breaks. | Elements start on a new line and take up the full width available. |
    | Width and height | Width and height properties have no effect. | Width and height properties can be specified, affecting element size. |
    | Margin and padding | Horizontal margins and paddings have effect, but do not push other elements away. Vertical margins and paddings have no effect. | Margins and paddings affect spacing around the element on all sides. |
    | Line breaks | Inline elements do not create line breaks and flow alongside other inline elements. | Block elements create line breaks and start on a new line. |
    | Content flow | Inline elements allow content to flow around them, respecting the surrounding text. | Block elements do not allow content to flow around them. |
    | Nesting behavior | Inline elements can be nested within other inline elements. | Block elements cannot be nested within inline elements. |
    
2. What are the differences between adaptive design and responsive design?
    
    | Adaptive Design | Responsive Design |
    | --- | --- |
    | Adaptive design focuses on developing websites based on multiple fixed layout sizes. | Responsive design focuses on showing content on the basis of available browser space. |
    | When a website developed using adaptive design is opened on the desktop browser, first the available space is detected and then the layout with most appropriate sizes are picked and used for the display of contents. Resizing of browser window has no affect on the design. | When a website developed using responsive design is opened on a desktop browser and when we try to resize the browser window, the content of the website is dynamically and optimally rearranged to accomodate the window. |
    | Usually, adaptive designs use six standard screen widths - 320 px, 480 px, 760 px, 960 px, 1200 px, 1600 px. These sizes are detected and appropriate layouts are loaded. | This design makes use of CSS media queries for changing styles depending on the target devices properties for adapting to different screens. |
    | It takes a lot of time and effort to first examine the options and realities of the end users and then design best possible adaptive solutions them. | Generally, Responsive design takes much less work to build and design fluid websites that can accomodate content from screen depending on the screen size. |
    | Gives a lot of control over the design to develop sites for specific screens. | No much control over the design is offered here. |

1. What are the limitations of CSS?
    
    Disadvantages of CSS are given below:
    
    - **Browser Compatibility:** Some style selectors are supported and some are not. We have to determine which style is supported or not using the @support selector).
    - **Cross Browser issue:** Some selectors behave differently in a different browser).
    - **There is no parent selector:** Currently, Using CSS, you can’t select a parent tag.

1. Difference between reset vs normalize CSS?. How do they differ?
    
    Reset CSS: CSS resets aim to remove all built-in browser styling. For example margins, paddings, font-sizes of all elements are reset to be the same.
    
    Normalize CSS: Normalize CSS aims to make built-in browser styling consistent across browsers. It also corrects bugs for common browser dependencies.
    

1. What are Pseudo elements and Pseudo classes?
    
    **Pseudo-elements** allows us to create items that do not normally exist in the document tree, for example ::after.
    
    **Pseudo-classes** select regular elements but under certain conditions like when the user is hovering over the link.
