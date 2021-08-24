HTML5/CSS- Rodrigo Albarrán


What is doctype?
R: It is an instruction to the web browser about which version of html is using, also ensures that the web page will be the same for different browsers.

What are the different positions in CSS?
R: this property specifies the type of position method for  the element will use, those are: static, relative, fixed, absolute and sticky.


How would you create a menu in which each element takes the same portion of space from its container, and if you change its size, it still remains the same space for each one.
R: For this case I would probably use the property of fixed, ny this the own default properties will be determine according with the position of the page. then I'll create a list in order to make the menu, given it a class in order to fixed it on CSS, such as:
<ul class="menu">
<li> a</li>
<li> b</li>
<li> c</li>
</ul>
.menu {
  position: fixed;
}

What cross browsers issues have you run into and how did you deal with them?
R:
DOCTYPE Error - This usually involves some kind of faulty rendering due to missing a basic line in the code. Browsers with outdated versions such as Internet Explorer 8.0 often check for the Doctype. If that is missing, the site is improperly rendered. Doctype is checked because a browser operates in two modes – Strict Mode and Quirks Mode.
Outdated Browser Detection - his common cross browser compatibility issue occurs due to obsolete Javascript. Solution : However, one can remove the browser detection by using Modernizer, a set of “superfast tests” that enumerate all browser features, thus facilitating a seamless experience. Modernizer lets developers direct a site to focus on features rather than browsers.
What does the float property do?
R: This property specifies if an element should float on the left, right or not.
How do you clear a floated element?
R: One way to clear a floated element is to use a empty dive method, such as 
<div style="clear: both;"></div>. 
How do you change the direction of HTML text?
R: A way to change the direction of the thex is by setting in the text align in CSS
    <p style="direction: rtl|ltr|initial;"> Text </p>
Explain how the new HTML5 features work:
semantic tags: these are tags that accurately describe the purpose of an element and type of content that is inside them. They work by simplifying the way we can write the code, instead of creating so many classes we can simply call these semantic tags.
Attributes: As we know html have some elements that are marked up by tags, some of this elements may contain some attributes to set up properties of an element.
Connectivity: This is a functionality in html5, this permits the end users be able to view and work with published resources using parallel  html5 client that runs inside a web browser. Client that runs inside a web browser. Parallels HTML5 Client works similarly to a platform-specific Parallels Client application with the exception that end users don't have to install any additional software on their computers.
work offline: html5 works with a cache mechanism that allows the browser to automatically saves the html file and all the resources that needs to display it properly on the local machine, so that the browser can still access the web page. 
Storage: this feature allows web applications to store data locally within the user browser. Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server. Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.
device access: The features that html5 includes, allows different devices be able to access and adds multimedia capabilities that weren't before. For this case the software interacts with the hardware via APIs (this are some kind of request from the software to hardware), letting new devices be able to interact with any html5 file.
Styling: The styling can be performed in to ways, by linking the html file with an html file, or by defining in the html file a style tag. Inside the style element, should be specified how html elements should be render in a browser. 
performance & integration: Part of a good user experience is ensuring the content the content is quick to load and responsive to interaction with the user. This is known as web performance; the components of performance, from web page loading and rendering, including how your content makes it into your browser to be viewed.
The feature of integration permits html5 be able to interact with different web sources or environments.
How can you generate a public key in html?
R: Using the tag element "<keygen>"which generates a public-private key pair and sends the public key to the server with form of submission.
What are <label> elements used for?
R: This tag elements are used to provide usability improvement fo mouse users i.e, if a user clicks on the text within the "”<label>"element, it toggles the control.
What is XHTML?
R: extensible hypertext markup language(xhtml) it mirrors or extends versions of html, the language in which web pages are formulated.
Are there any optional tags?
R: the option element tags is used to define an item in a <select>, <optgroup> or a <datalist> element.
When would you use a <div>, <section>, or <article> tag?
R: If the content of the element is not semantically related , we should use <div>, if the semantically related content is also able to be self conditioned, then use an <article>. Otherwise, use a <section>.
What are the benefits of using the <audio> or <video> tag over flash components?
R: As I look for, flash it'’ hard on it's way out; the <video> and <audio> elements tags, support is ubiquos, inclusion mobile devices. So almost everything that Flash could do, HTML can do too.
How can you apply CSS to only a part of the HTML document?
R: By using a <div> and giving it a class and giving format on CSS to that class.
What are the new features introduced by CSS3?
R: the new features of CSS3 are
Subgrid
Flexbox gaps
The content-visibility property
The contain-intrinsic-size property
The :is() and :where() pseudo-classes
Compare CSS2 and CSS3: CSS3 provides JavaScript and mobile development features with additional features such as transitions, gradients, and more. 
How can you highlight text in HTML?
R: this can be done by using the tag <mark>.
What is responsive design?
R: responsive design refers about creating web pages that look good on all devices, this means that the web page can adjust for different screen sizes.
What is progressive enhancement?
R: is a methodology that allows developers to focus on building the best possible web pages while balancing the issues inherent in those websites being accessed by multiple unknown user-agents.
What is graceful degradation?
R: is the practice of building your web functionality so that it provides a certain level of user experience in more modern browsers, but it will also degrade gracefully to a lower level of user experience in older browsers.
Explain how CSS3 animations work.
R: the way how the animation in CSS work is by defining keyframes, when the you specify CSS styles inside the keyframes rule, the animation will gradually change from the current style to the new style at certain times.
Explain how transitions work
R:CSS transitions allow property changes in CSS values to occur smoothly over a specified duration. This smoothing animates the changing of a CSS value when triggered by a mouse click, focus or active state, or any changes to the element (including even a change on the element’s class attribute).
Explain the different CSS units of measurement. 
This are:
Centimeters
Milimeters
Quarter-milimeters
Inches
Picas
Points
Pixels 
Which one do you prefer to use and why?
R: I personally oscilate between points and pixels, this according to the task I'’ working on, the reason I was following the tutorial instructions.
How do you capitalize using only CSS?
R: By placing 
p{ text-transform: uppercase;  }
What are the possible values for the display rule and what do they do?
R: inline, block, contents, flex grid, inline-block, inline-flex, inline-grid, inline-table, list-item, run-in, table, table-caption, table-column-group, table-header-group, table-footer-group, table-row-group, table-cell, table-column, table-row, none, initial, inherit
What is the difference between display:block and display:inline-block?
R: the main difference between display: block and display: inline-block, is that the last one does not add a line-break after the element, so the element can sit next to other elements.
What is a class and an id?
R:
The class attribute is often used to point to a class name in a style sheet.
The id attribute is used to specify a unique id for an HTML element.
When would you use an id instead of a class?
When you want to specify a unique element in the HTML
When would you use a class instead of an id?
When you want to use a generalized element for the file.
Which selector is faster, id or class?
Id
How do you target a direct child element?
R: by concatenating section.querySelector(section + "> div") a string with an object. 
Can you target a single, specific element with a particular class? 
R: Only if you know the other classes, you can use the :not pseudo-class:
When would this be useful? 
R: when you know the rest of the classes
What is the use of the data-* attribute?
R: is used to store custom data private to the page or application. The data-*attribute give us the ability toembed custom data attributes on all HTML elements.
What is the difference between display:none and visibility:hidden?
R: 
Display:none  means that the tag in question will not appear on the page at all (although you can still interact with it through the dom)
Visibility:hidden means that unlike display:none, the tag is not visible, but the space is allocated for it on the page.
Does overflow: hidden create a new block formatting context?
R: for this case the overflow property specifies weather to clip the content or add scrollbars when the content of an element is too big to fit in the specified area. The hidden value, indicates that the overflow property is clipped and the rest of the content will be invisible. 
Is it possible to use percentages in border widths?
R: No, borders doesn't support percentage.
Is it possible to use percentages in margins?
R: yes it's possible 
How do you reset a CSS style?
R: It could be by performing a hard reset, this can be done by setting the properties 
{padding:0; margin:0; border: 0; outline: 0;}.
If you have a way of dividing an interface horizontally and vertically, could any layout be made?
R:If this happens the interface may look dived in half horizontally, and on the first half i will be divided vertically.
How can you store data on the browser?
R: There are two ways to store data in a browser, via API, without using cookies. The two ways to storage information:
Local Storage- stores data with no expiration date
SessionStorage- stores data for one session (data is lost with the browser tab is closed)
What debug tools are available for CSS?
R: Web developer extension, Firebug (only for firefox), Google developer tools, we CSS validation Service, CSS Lint.
How do you make a mobile-first approach?
R: is a tenet of progressive enhancement. It is the ideology that mobile design, as the hardest, should be done first. Once the mobile design questions are answered, designing for other devices will be easier.
Explain how the box-model works.
R: the box model is essentially a box that wraps around every element of the HTML file. 
What are the properties related to it?
Content 
Padding 
Border
Margin
What is flexbox? Have you used it?
R: It's a flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.
Yes I use it for the HTML task
What are media queries?
R:  this are features in CSS which allows you to specify when certain CSS rules should be applied. 
What is the use of only?
R:The only keyword is used to prevent older browsers that do not support media queries with media features from applying the specified styles.
Does the screen keyword apply to the device’s physical screen or the browser’s viewport? 
R: is used to set the screen size of a media query. The screen size can be set by using max-width and min-width. The screen size differs from screen to screen.
What are pseudo-classes and pseudo-elements?
R:
Pseudo-classes - is a keyword added to a selector that specifies a special state of the selected element(s).
Pseudoelements- is a keyword added to a sector that  lets you style a specific part of the selected element.
Name a few pseudo-classes and what they are used for.
R: 
:active - select the activ link
:empty - select every <p> element that has no children
:hover selects links on mouse
Explain how CSS shorthand syntax works for padding/margin. 
R: the shorthand properties let you set values of multiple properties simultaneously, for padding or margin 
How do they behave when defining 1, 2, 3, or 4 values
The 1-value syntax: border-width: 1em — The unique value represents all edges
The 2-value syntax: border-width: 1em 2em — The first value represents the vertical, that is top and bottom, edges, the second the horizontal ones, that is the left and right ones.
The 3-value syntax: border-width: 1em 2em 3em — The first value represents the top edge, the second, the horizontal, that is left and right, ones, and the third value the bottom edge
The 4-value syntax: border-width: 1em 2em 3em 4em — The four values represent the top, right, bottom and left edges respectively, always in that order, that is clock-wise starting at the top (The initial letter of Top-Right-Bottom-Left matches the order of the consonant of the word trouble: TRBL) (You can also remember it as the order that the hands would rotate on a clock: 1em starts in the 12 o'clock position, then 2em in the 3 o'clock position, then 3em in the 6 o'clock position, and 4em in the 9 o'clock position).
How is an HTML5 form implemented?
R: A form is a component of a Web page that has form controls, such as text fields, buttons, checkboxes, range controls, or color pickers. In order to implement a form it needs to scope a list of specifications according to the formed we're working on.
How are key-value pairs sent to the server?
R: String yourURL = "www.yourwebserver.com?value1=one&value2=two";
URL url = new URL(yourURL);
URLConnection connection = url.openConnection();
BufferedReader in = new BufferedReader(
new InputStreamReader(connection.getInputStream()));
response = in.readLine();
How is a field declared mandatory?
R:On each form, mandatory fields must be clearly indicated:
A distinctive sign (“*” symbol, “mandatory” mention, etc.) must be provided in the label of each mandatory field.
If a symbol is used to declare mandatory fields, a statement placed at the beginning of the form must indicate that the symbol stands for a mandatory field.
How is a field set to be mandatory AND avoid having the browser validate?
R: validation is to tell the browser which fields you want validated but don’t do the  implementation by yourself. As you define what state your input field is in you also asks the browser to validate the field client-side based on the type of input field.
<form>
	<input type="text" required /><br />
	<input type="submit" value="Submit now" />
</form>
Describe how to improve page load times when you have 20 js files, 20 css files, and 20 images.
R: For this case we can use different techniques such as 
Avoiding use importa, and use link tag
Use a content delivery network (CDN) to increase the number of simultaneous HTTP connections and replicate files to other locations around the world
Organize CSS into smaller files (partials) with clear responsibilities. It’s easier to remove a carousel widget if the CSS is clearly defined in widgets/_carousel.css.
Adding vast quantities of CSS from StackOverflow or BootStrap may produce quick results, but it will also bloat your codebase with unused junk.
How can an inline style be overridden?
R: this can be done by using the important keyword beside the  rule on CSS.
Explain how to implement a carousel using CSS / CSS3
R:
First we begin by setting in a horizontal row by a flexbox
By using overflow and making swipable with -webkit-overflow-scrolling is easy.
Making the slides line up by using scroll-snap-type
Finally by adding a couple of jump-links, it improves the navigation for it, it can be smother if we add scroll behavior.
How can the performance of a web page be measured?
R: Tools like PageSpeed Insights can measure a website’s performance. You can enter a URL and get a performance report in seconds. The report contains scores about how your website is performing, both for mobile and desktop. This is a good start for getting an idea about what you are already doing well and what could be improved. By implementing APIs connect with your own site, in order to have a description of the performance of the web page.
Describe different ways in which a web page can be optimized.
R:
Optimize the size of images on your website
Reduce the number of plugins
Minimize the number of JavaScript and CSS files
Implement Gzip Compression
Reduce the use of web fonts
Is there a performance difference between the different selectors?
R: this performance can be examine through different browsers, also it will depend on the sintaxis of the css.
How do you optimize CSS selectors? 
R: by improving the sintaxis of it
Which selector is the fastest?
R: any class will be quicker than any selector
What are the different CSS filters you can use ?
R: blur, brightness, contrast, contrast , drop-shadow, grayscale, hue-rotate, invert, opacity, saturate, sepia.
What is specificity? 
R: If there are two or more conflicting CSS rules that point to the same element, the browser follows some rules to determine which one is most specific and therefore wins out.
How do you calculate it?
R: Start at 0, add 1000 for style attribute, add 100 for each ID, add 10 for each attribute, class or pseudo-class, add 1 for each element name or pseudo-element. The specificity of A is 1 (one element)
The specificity of B is 101 (one ID reference and one element)
The specificity of C is 1000 (inline styling)
Since 1 < 101 < 1000, the third rule (C) has a greater level of specificity, and therefore will be applied.
How would you use sprites?
R:set the same background-image on several CSS classes and set the background position and dimensions of the individual classes to display a single portion of the sprite. 
How can you load CSS resources conditionally?
You can however put the file in /public directory. Meteor won't touch it there, and you will be able to load it at will by adding <link/> tag to your page head.
What is gzipping? How is it used?
R: They way It can be compressed a css file,
click on the UPLOAD & COMPRESS FILE(S) tab and choose the CSS file you want to compress. Click on the red Select More Files link to upload more than one file. If you choose to upload and compress multiple CSS files they will be combined into one bigger script.
Mention any CSS framework that you have used.
Boostrap
How do you serve a page in multiple languages?
use the Content-Language header to show the browser which languages the document contains (e.g. Content-Language: de-DE, en-CA by a German and English mixed language page). In the HTML you can define a global language with <html lang="de"> or an element specific language with <p lang="fr">Ceci est du texte</p>. If you want it to be linkable, then the URL should contain the language too, otherwise it is ok to send it only in headers. For server side frameworks and CMS-s there are i18n modules, which support multi language content
Explain what standard and quirks mode are.
R:
quirks mode - layout emulates nonstandard behavior in Navigator 4 and Internet Explorer 5. This is essential in order to support websites that were built before the widespread adoption of web standards. 
standards mode - the behavior is (hopefully) the behavior described by the HTML and CSS specifications, there are only a very small number of quirks implemented.
Have you used <meta> tags? Explain if you have.
R: yes I have use them, for specify some information about the data I will use in de HTML file.
Describe what happens when you type a URL into a browser
R: When you type a "URL" into a browser the first thing that happens is that the Domain Name Server, matches the URL to an IP address. Then the browser send an HTTP request to the server sends back an HTTP response. The browser begins rendering the HTML on the page while also requests any additional reosurses such as CSS, JavaScript, Images, etc.
When sending form data, what is the difference between the GET and POST methods?
R: GET is used to retrieve remote data, and POST is used to insert/update remote data. GET retrieves a representation of the specified resource and include all required data in the URL.
Explain what is bootstrap and how do you make use of it.
R: Bootstrap is a free and open source front end development framework for the creation of websites and web apps, it's open-source and free to use, yet features numerous HTML and CSS templates for UI interface elements such as buttons and forms. 
In order to make use of bootstrap, we need to including a CDN, by using a link tag with the next link "<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
" for CSS or anothe way can be by downloading the bootstrap file and calling locally. 
Once you have included Bootstrap in your project using any of the above methods, you can use all the components available in bootstrap easily.
Explain its key features such as the grid system, glyphs, responsive design, etc.
R:Boostrap manages several grid systems that can be implemented for different cases according with the things the user needs
Default grid system: for this case the system can work with the live grid (utilizes 12 columns, making for a 940px wide container without responsive features enabled. With the responsive CSS file added, the grid adapts to be 724px and 1170px wide depending on your viewport. Below 767px viewports, the columns become fluid and stack vertically.) Basic grid (For a simple two column layout, create a .row and add the appropriate number of .span* columns. As this is a 12-column grid, each .span* spans a number of those 12 columns, and should always add up to 12 for each row (or the number of columns in the parent).)
Fluid grid system: Live fluid grid (The fluid grid system uses percents instead of pixels for column widths. It has the same responsive capabilities as our fixed grid system, ensuring proper proportions for key screen resolutions and devices.) Basic Fluid grid (Make any row "fluid" by changing .row to .row-fluid. The column classes stay the exact same, making it easy to flip between fixed and fluid grids.)
Also bootstrap have around 250 glyphs to use, this are icons that can be call in sour html file.
Responsive web design is a preferable alternative and an efficient way to target a wide range of devices with much less efforts. Bootstrap 4 powerful mobile first flexbox grid system creating the responsive and mobile friendly websites and applications has become much easier. Its five tier grid classes provides better control over the layout as well as how it will be rendered on different types of devices like mobile phones, tablets, laptops and desktops, large screen devices, and so on.
How would you plan creating a CSS framework similar to bootstrap?
R: For this we need to focus on on making a responsive grid, typography, reusable multiple colored elements/components. For this first we need to create a file app.scss which hold all the code of our framework. Next we need to create a base style for our class btn. Wherever we use the btn class, the element will get the base style as defined above. Now, let’s focus on how we can create theme colored buttons with bootstrap like classes such as btn-primary, btn-secondary etc. For this, will have to loop through our colors map.
For the responsive grid, we defined the number of columns, breakpoints and the basic style for our container (grid) & row. Then, we looped through the breakpoints and, with the help of media queries, created column styles for each of our breakpoints. We, then looped through the columns to create a style for every column.
What is your opinion on bootstrap?
According with the professor of the FrontEnd class, html is like the structure of a house and the materials, css it's like the blue prints. For this case working with Boostrap it's like having a interior decorator working with walmart products, makes work on the easy way they can be done.
What version of bootstrap have you used?
The four version 
What is the difference between bootstrap 3 and 4?
R:The main differences between Bootstrap3 and Bootstrap4 are
Global Changes- on 4, they change from 	LESS to SASS for source CSS files.
Grid Systems - Bootstrap 4 presence of up to 5 grid system (*, sm, md, lg, xl). While bootstrap 3 has 4 grid system (xs, sm, md, lg).
Navigation - Bootstrap 4 navigation component rewrite with flexbox. Thus, it has been simplified in Bootstrap 4 to a great extent. Moreover, introduced a few additions class like nav-link, nav-item. Also, navigation bar styles added in Bootstrap 4.
Images and Media Objects - Media objects are used flexbox so you can use other flexbox classes.
Media Objects (Media objects are used flexbox so you can use other flexbox classes.), Tables (Bootstrap 4 added a new .table-dark class. Also table header modifiers classes .thead-default and .thead-inverse introduced.),  Buttons, Forms, Groups, Dropdowns.
Give a comparison between bootstrap and foundation.
R:Meanwhile Bootstrap: is simple and flexible HTML, CSS, and JS for popular UI components and interactions. Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web. The main features that bootstrap have are: preprocesors, one framework on every device and full features(such as documentation, documents and jquery plugins.) 
On the other hand the most advanced responsive front-end framework in the world. Foundation is the most advanced responsive front-end framework in the world. You can quickly prototype and build sites or apps that work on any kind of device with Foundation, which includes layout constructs (like a fully responsive grid), elements and best practices. Foundation provides the following key features are: semantic sintaxis, mobile first, customizable.
What are CSS preprocessors? 
R: Usually they are programs that lets generate CSS from the preprocessor own unique syntax.To use a CSS preprocessor, you must install a CSS compiler on your web server; Or use the CSS preprocessor to compile on the development environment, and then upload compiled CSS file to the web server.
Explain how LESS works; advantages & disadvantages.
R: Less (which stands for Leaner Style Sheets) is a backwards-compatible language extension for CSS. This is the official documentation for Less, the language and Less.js, the JavaScript tool that converts your Less styles to CSS styles.
 The JavaScript tool that converts your Less styles to CSS styles. Because Less looks just like CSS, learning it is a breeze.
What is a mixin?
R:Mixins allow document authors to define patterns of property value pairs, which can then be reused in other rulesets. The mixin name is a class selector that identifies the mixin being declared. The @mixin keyword must be followed by the mixin name and a declaration block.
What are the reasons to use preprocessors?
R: Pre-processors have advanced features that can make code in CSS extensible, reusable, and maintainable. Because it enables you to plug-in logic into your CSS code, it will eliminate the need to write different vendor versions – creating reusable, maintainable and extensible code in CSS. 
There are several benefits to using CSS preprocessors, the most useful are:
Multiple Files of Preprocessed CSS Code Later Compiled Into One
Nesting of Style Rules
Extensibility of Classes
Reusability of Variables & Snippets of Style Rules




76.Explain how you would create a simple slider using CSS and HTML with values of 0 for min and 100 for max. No JS.
R:  This can be done by adding an <intup type="range" id"" min="0" max="100">

82. Scenario issue: You are given a URL in which, when accessed, returns only a blank page.
How do you resolve the issue?
R: This happens because the html thinks the link is internal which it isn’t it’s external so you need to tell it this.
Internal links would be <a href="folder/this.html">This Page Is on the same server as me</a> Which when clicked would take you to http://mywebsite.com/folder/this.html External links must be <a href="http://www.ghg.html">This Page is on a different website than me</a> 




       
