# GS-EOP-8
This contains list of resources that were shared during Girlscript Education outreach program 8.

Mentored by : [Ritika Gupta](https://www.linkedin.com/in/gritika1906/)

Platforms used : [jsfiddle](https://jsfiddle.net/) and [codepen.io](https://codepen.io/collection/AQPkmq )

## Day 1 - Grooming session on UI Development

### What is UI development?

**UI** : User Interface , refers to the intermediate between a user and an application. In the Previous times, this intermediate often used to be command line (much
alike CMD) but in the modern times , this intermediate is highly graphical in nature.

**Development**: the process of making something.

**UI Development**: Making an intermediate which helps users to interact and communicate with a web-based or mobile-based application.

**Process Of Making/Development**: Technologies like HTML (Hyper Text Markup Language), CSS (Cascading Style Sheet), Javascript etc. are the part of toolkit to begin making such an interface/intermediate.

**Examples**: the home-page of flipkart webiste/app, the dialog box that appears while installing a software, your desktop and it's accessories, social-media webistes/apps etc.

**Advanced Scope of UI Development**: Responsive Web Designing , refers to compatibility of UI elements view w.r.t different devices like IPad, mobile-phones, laptopscreens, etc.

### Techstack comprising UI development

* HTML (Hyper Text Markup Language)
* CSS (Cascading Style Sheets)
* JS (Javascript)
* RWD (Responsive Web Design)
* SASS (Syntactically awesome Style Sheets) : interpreted or compiled into CSS
* JS Frameworks : AngularJS, VueJS, NuxtJS, NextJS, ExpressJS etc.
* JS Libraries: Loadash, JQuery etc.
Many more are coming soon...

### Difference between UI/UX Designing, UI Development and Front-End Development

UI/UX Designing | UI Development |  Front-End Development
--- | --- | ---
Stands for User Experience and User Interface Designing |Stands for User Interface Development | Stands for Functional and Dynamic Development on UI
Definition: Painting and sketching out the look and feel of UI | Converting the painted & sketched UI into the static HTML/CSS Code. | Converting the static UI code into functional and dynamic code.
IT Industry Designation: Graphic Designer | IT Industry Designation: UI Developer | IT Industry Designation: UI/Front-End developer
This requires knowledge of tools like corel-draw, adobe photoshop, adobe XD, Invision, E-Sketch etc. | This requires knowledge of HTML, CSS, JQuery, Javascript-DOM, Responsive Web Design (media queries or CSS flexbox, Bootstrap) etc. | This requires knowledge of Advanced Javascript, a strong grip on any one of the JS frameworks like AngularJS, VueJS etc.
Relationship: A Graphic Designer sketches and paints out a website layout with all minute elements like buttons, icons, modals, toast messages, links, logos, forms etc. using the above mentioned tools and takes help of tools like Zeplin, Avocode or Invision to upload those files as what is known as style guides | Relationship: A UI developer uses these style guide from the tools to fetch dimensions, color-codes, sizes, margins, spaces, font-family etc. to use these values in the code | Relationship: A Front-End developer uses this static UI code and embeds logics and consumes APIs to make buttons, modals functional and content on the web page dynamic which renders as per user-to-user

### Market Trend and Scope

* Trending UI Tech stack is HTML and SASS , where SASS is a CSS pre-processor which brings to us the features of making functions, mixins, variables, arrays to make CSS code highly re-usable. Developing and maintaining a repository of common elements across website like buttons, links, modals, fonts, forms etc.
* Trending Front-End tech stack is ReactJs and AngularJS to maintain re-usable components across the website and consume APIs and it's data.
* Trending tools on which the style guides are deployed by the graphic designing team are zeplin, avocode, invision etc. which are easily readable and provide copy-paste option for css styles snippet.
* Scope Of UI and Front-End is so bright and wide in near future that newer tech stacks like VueJS and many other handy and highly compact yet functional JS frame-works are being manufactured and launched rapidly. Along with the same, CSS4 is also being supplied with newer attributes and values to minimize the need of JS on UI-front.

## Day 2 - Kickstart to UI Development

### Introduction to HTML

**Building Blocks Of HTML Coding**

Tags and their attributes; attributes and their values.

**Tags**

Tags are keywords of coding vocabulary, which act as the native language to the web browser. Web browser understands these keywords and brings out the desired output on
it's page. Much alike how we understand Hindi, English keywords your teacher uses to assign you a task, and after comprehending them we indulge in actions to complete the
task, with expected output. 

Grammar rules to write these keywords: Tags contain an opening and a closing tag (few exceptional tags do not require a closing tag). Opening Tags are written inside '<' and '>'brackets. Closing tags are written inside '<' and '>' along with a '/'. E.g. ```<html>``` and ```</html>```

**Attributes**

Attributes are entities to add an extra flavour to tags for enhancement of the output
produced by the tags. Eg. your teacher asks you to submit an assignment on Data
Structures, but also adds that you should use different colored sheets for different
chapters like linked list, arrays, algorithms etc. , these colored sheets act as attributes to
the tag of making an assignment.
E.g. attributes are written along-side tagname with a space in between <textarea
disabled>

**Values**

Values are, what type of enhancements do we need to embed to our output. For an instance, teacher has told you to use colored sheets for different chapters but what
colors you will choose to make the assignment forms the part of values to attributes.E.g. values are written after attribute name with an = in between and inside quotes " or '
`<textarea disabled="true">`
  
**Typography Tags**

* `<p></p> `: This is a paragraph tag used to code text type of content for the web browser.
* `<label></label>` : This is a label tag used to code text type of content, especially the descriptions for the form fields, for the web browser.
* `<h1></h1>` to `<h6></h6>` : This is a paragraph tag used to code text type of content, especially the headings and sub headings, for the web browser.
* `<span></span>` : This is a tag used to code text type of content, inline in nature, for the web browser.
* `<i></i>` or `<em></em>` : This is an italics/emphasis tag used to format the syle of content, making it appear italicized in nature. This also forms a part of formatting tags. Both the tags visually appear to have same effect on the browser but for website translating speech programs, the tone of text changes for 'em' tag.
* `<b></b>` and `<strong></strong>` : This is a bold tag used to format the style of content, making it appear bold in nature. This also forms a part of formatting tags. Both the tags visually appear to have same effect on the browser but for website translating speech programs, the tone of text changes for 'strong' tag.
* `<u></u>` : This is an underline tag used to format the style of content, making it appear underlined in nature. This also forms a part of formatting tags.
* `<mark></mark> `: This is a mark tag used to format the style of content, making it appear highlighted in nature. This also forms a part of formatting tags.

**Semantic Tags**

* `<header></header>` : This is a header tag used to wrap structure of header, for any webpage/website.
* `<footer></footer>` : This is a footer tag used to wrap structure of header, for any webpage/website.
* `<section></section>` : This is a section tag used to wrap sections of the webpage/webiste apart from header or footer.
* `<article></article>` : This is an article tag used to wrap textual content of the webpage/website.
* `<aside></aside>` : This is an aside tag used to wrap content aligned to corners of the webpage/website.
* `<main></main>` : This is a main tag used to wrap content of specific and relevant importance for the webpage/website.
* `<thead></thead>` : This is a table head tag used to wrap content of a table headers.
* `<tbody></tbody>` : This is a table body tag used to wrap content of a table body.
* `<figure></figure>` and `<figcaption></figcaption>` : This is a figure tag used to wrap content of image media placed on a webpage/website, figcaption is a sub-tag to wrap caption of the image in it.

**Media Tags**

* `<img></img>` : This is an image tag, used to display image type media on the webpage/website. But this tag will not only work by mentioning it's tag name like other tags mentioned so far, it will require attributes to be guided with more information to perform desired function. The mandatory attribute with this tag name is "src" written as `<img src="path of the image file"></img>` E.g. `<img src="https://redzonekickboxing.com/wpcontent/uploads/2017/04/default-image-620x600.jpg"></img>`
* `<a></a>` : This is the anchor tag used to embed links to external webistes/webpages or to navigate between different pages of same website or to embed an email address to redirect in composing the mail etc. This tag alike 'img' tag too requires a mandatory attribute called 'href' written as `<a href="link to webiste/ link to page in this website/ move to an element on the same page/ mail">link text</a>` E.g. `<a href="#top">link text</a>`, E.g. `<a href="https://www.google.com/">link text</a>`E.g. `<a href="mailto: aashigupta1919@gmail.com">link text</a>`

**Form Related Tags**

* `<form></form>` : This is form tag that wraps all the elements which demands an input or action from the user interacting with the website/webpage.
* `<input>` : This is input tag and contains a mandatory attribute called 'type' to display it's nature and is used to render different types of form inputs like text, password, date, time, color, range, file, list etc. on the webpage/website.
* `<textarea></textarea>` : This is textarea tag, used to get an input of multiple lines of text, from the user on a webpage/website.
* `<select></select>` and `<option></option>` : This select tag allows a user to select from a list of options pre-available, fromt the webpage/website. The `<option></option>` tag is a crucial sub-tag of 'select' as inside this tag all the options are written which are to be made available for the user.
* `<datalist></datalist>` : This datalist tag acts as a text input taken from user and if the text string matches any of the available options, it shows the list of those
options to the user much alike a pre-fetch function. This tag operates both by subtag `<option></option>` and by parent tag `<input>` 

**Tag Attributes**

* **Global Attributes**: 'id', 'class', 'style', 'contenteditable', 'spellcheck', 'lang', 'title' 'data-\*' etc. These attributes are not tag-specific and may be used with any tag for tag enhancement.
    * **id**:This attribute assigns a unique id to an element which can be accessed either for styling purposes or for functional purposes. (** Remember 'id' attribute
value cannot be same for multiple elements and must contain a unique value)
    * **class**: This attribute assigns a value to an element which can be accessed either for styling purposes or for functional purposes. Typically, this attribute also
defines, as to which group of styles this element belongs to.
    * **style**: This attribute contains all the style properties and it's values to provide inline styles to the element.
    * **title**: This attribute is used to show a tooltip kind of information related to the element. Typically used to describe the purpose/content/function of an element in a summarized manner.
    * **contenteditable**: This attribute is used to define if content of tag/element can be edited or not via interface.
    
* **Form Input Attributes**: 'type' attribute has different values like "type='text'","type='password'", "type='file'", "type='email'", "type='date'". All these attributes help in obtaining input from the user and send across the server for manipulation.
    * **type='text'**: This attribute is used to obtain single line text input from user like name of the user, contact number, etc.
    * **type='password'**: This attribute is used to obtain single line hidden input from user like password etc.
    * **type='file'**: This attribute is used to obtain file input from user like uploading a resume file, uploading bill proofs etc.
    * **type='email'**: This attribute is used to obtain email input from user. This attribute automatically validates if the input value is in correct format of email or not.
    * **type='date'**: This attribute is used to obtain date input from user. This attribute automatically provides a calendar feature to the user to choose a date from.

And there is an exhaustive list of attributes for other tags.

### Difference between HTML4 and HTML5

HTML 4 | HTML 5
--- | --- 
Absence of Semantic Tags: only tags like \<div\>\<\/div\> | Semantic Tags like: \<article\>\<\/article\>,\<header\>\<\/header\>, \<footer\>\<\/footer\>,\<nav\>\<\/nav\>, \<figure\>\<\/figure\>, \<main\> \<\/main\> etc
Input types like 'text', 'password'etc. available for all purposes. | Input types like 'email', 'url', 'date' etc. have been introduced for wider usage.
Special form tags absent. | Special form tags like \<datalist\>\<\/datalist\>, \<output\>\<\/output\>, etc. have been introduced
Formatting Tags like : \<font\>\<\/font\>, \<big\>\<\/big\>, \<strike\>\<\/strike\>, \<center\>\<\/center\>, were present.| Formatting Tags like :\<font\>\<\/font\>, \<big\>\<\/big\>, \<strike\>\<\/strike\>, \<center\>\<\/center\>, have been removed (deprecated).
The input tag has limited set of attributes like 'id', 'class', 'style','type', 'name' etc. | The input tag has several highly dynamic attributes like 'pattern', 'autocomplete','min', 'max' etc 
\<ol\>\<\/ol\> tag has no attribute for reverse ordering. | \<ol\>\<\/ol\> tag has an attribute for reverse ordering called 'reversed'.
Limited set of global attributes available. | Special feature global attributes like: "spellcheck" , "contenteditable" etc. have been introduced.

And an exhaustive list of differences exist.
Please refer to the official W3 website to study in detail.

### HTML Code for practise

```javascript
HTML Code Practiced on JSFiddle for Tags and attributes
<html>
<head>
<style>
p{
 color: cyan;
}
</style>
</head>
<body>
<p id="para" class="paragraph" spellcheck="true" contenteditable="true" style="color: pink;">
My name is Ritika Gupta. This is my first web page developnt. I am practising tags and attributes through
this demo.
</p>
<h1>
This is my first heading
</h1>
<h2>
This is my second heading
</h2>
<h3>
This is my third heading
</h3>
<h4>
This is my fourth heading
</h4>
<h5>
This is my fifth heading
</h5>
<h6>
This is my sixth heading
</h6>
<code>This is my first code</code>
<i>This text is italicised</i>
<em>This text is italicised too</em>
<b>This text is bold</b>
<strong>This text is bold too</strong>
<span>This is a span tag</span>
<img src="https://www.litmus.com/wp-content/uploads/2020/04/fallback-strategies-for-interactiveemail.gif" title="this is an image"/>
<a href="https://jsfiddle.net/hstumLbe/3/">Take me to this link</a>
<a href="mailto: abc@gmail.com">Send Email</a>
<a href="#para" title="jumper" contenteditable="false">Take me to the top of page</a>
</body>
</html>
```

### Resources

* [HTML Learning from JavaT Point]( https://www.javatpoint.com/html-tutorial)
* [Codecademy HTML Code-Along Learn Platform]( https://www.codecademy.com/learn/learn-html )(**Personally recommended**)
* [W3Schools HTML Learning]( https://www.w3schools.com/html/)
* [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML) (**Preferred when you have a strong grip on fundamentals**)
* [Tutorials Point HTML]( https://www.tutorialspoint.com/html/index.html)

## Day 3 - Adding Visual styles to UI I

### Introduction to CSS

* CSS may be divided into 3 types: inline CSS, embedded CSS, External CSS.
    * **Inline CSS**: when the styles are coded as an attribute of the element or tag in the HTML file. E.g. `<p style="color: darkred;">`
    * **Embedded CSS**: when the styles are coded as a part of head tag in the HTML file. E.g.```<head> <style>p{color: pink;} </style> </head>```
    * **External CSS**: A designated CSS file is maintained containing only the styles , with an extension .css and is called upon in the HTML file through "link" tag. E.g. ```<link href="styles.css">```
    
* Cascading Style Sheets comprise of several property-value set of code to embed visually appealing styles to HTML coded web pages or websites.

* The Grammar to define property-value set is: "property : value;" the property name followed by a colon further followed by the value and ended by a semi-colon. E.g. ```color : blue;```

* These property-value sets are then supplied to elements of the web page, we wish to style, called selectors in CSS. Grammar for the same is as follows:
```"selector{ property: value; }"```

* A Selector is a piece of code that selects and brings element to be styled, to the CSS table. E.g. ``` p{color: red;}```

* Selectors may be of wide variety, common of which are given here:
    * Element Name E.g. ```p, h1, article, nav, div, input etc.```
    * Element Class E.g.``` .box, .container etc.```
    * Element Id E.g.``` #box, #container etc.```
    * Universal Selector E.g. ```*{}```. A Universal Selector selects all the elements or tags on a web page like ```p, body, footer, header, span, a, img, div, etc.```
    * Element Name followed by attribute-value pair E.g. ```input[type="text"]```
    * Element name/class/id followed by attribute-value prefix. E.g. ```div[class^="box"]```,```form-group[class^="box"]``` ,```#form-group[class^="box"]```
    * Element name/class/id followed by attribute-value suffix. E.g. ```div[class$="wrapper"],frame[class$="wrapper"], #frame[class$="wrapper"]```
    * Element name/class/id followed by attribute-value substring. E.g. ```div[class*="wrapper"], .frame[class*="wrapper"], #frame[class*="wrapper"]```
    * homogenous/heterogenous combination of all the above mentioned selectors. E.g. ```p.child{color: green;}, h2#top{color: cyan;}, div[class*="group"] input[type="text"]``` ```{font-size: 20px; border: 1px solid red;}```
    
* What if overriding styles are written for the same element by differentselectors?: The specificity rule follows for different selectors which sets the priority for them.

    * The standard specificity rule is: inline style > id > class > element name

    * Specificity Rule when same method is style is written multiple times: The greater valued line of code will execute. E.g. on line 4``` p{color: green}``` and on line 10 of same sheet ```p{color: blue}```, paragraph will be of blue color.

    * Specificity when dealing with ```"!important"``` : It tends to pick the selector to which it is applied and place it on the top of hierarchy stack. E.g. ```p{color: red
!important} ```

### CSS Box Model

![CSS Image](Class-3/css-box-model.png)

* Every Element or tag placed on a web page may be imagined of as abox. This box contains an invisible environment around it's edges marking it's features. These features are margins -> borders -> padding-> content

* Property-Value Set related to CSS box-model is 'box-sizing'.

* box-sizing: border-box | content-box

* By Default, the box-sizing property is set to the value content-box which means that padding and borders will not be included in the width and height of an element and will add their values to the width and height of the element , changing it's desired width and height.

* Let's take an example to understand this concept in detail: We have a 'div' tag whose total width should be 300px and height should be 100px, border-width should be 3px and padding should be 20px from all edges.

* box-sizing: content-box will make total width of div = 346px (width of div 300px + padding-left 20px + padding-right 20px + border-width-left 3px + border-width-right 3px) violating the requirement of width to be 300px only.

* box-sizing: content-box will make total height of div = 146px (height of div 100px + padding-top 20px + padding-bottom 20px + border-widthtop 3px + border-width-bottom 3px) violating the requirement of height to be 100px only.

* To solve this problem: we have box-sizing: border-box

* box-sizing: border-box, helps to consume dimensions for padding and border value from mentioned value of width and height of 'div' tag.

* For an example: we have given width = 300px and height = 100px for 'div' padding = 20px and border = 3px, hence values for padding and border are auto adjusted from width and height values.

* box-sizing: border-box, will keep total height of div 100px by adjusting values like height 54px (height of div 100px - padding top 20px - padding bottom 20px - border top 3px - border-bottom 3px)

* box-sizing: border-box, will keep total width of div 300px by adjusting values like width 254px (width of div 300px - padding left 20px - padding right 20px - border right 3px - border left 3px)

### Typogrphy and Formating

* font-family: Segoe UI | Times New Roman | Comic Sans | Helvetica | etc.

* Commonly fallback values are given for such properties to ensure the display does not break on any browser. Fallback values may be given in a single property separated by commas. E.g. ```font-family: helvetica,sansserif.```

* color : any color value (hex, rgb, rgba or name of the color).

* font-size: any numeric value(in px, em, rem etc. units)

* text-decoration: none | underline |line-through | underline | overline etc.

* font-weight: normal | bold | bolder | lighter | number | initial | inherit;

* text-transform: uppercase | lowercase | capitalize | none etc.

* text-indent: number

* word-spacing: number

* letter-spacing: number

* line-height: number

* text-shadow: horizontal-shadow-number vertical-shadow-number

* shadow-smudge-number shadow-color

* text-align: center | right | left | justify etc.

* background-color: color code

* display: block | inline-block | inline | flex | inline-flex

* opacity: number between 0 to 1

* position: fixed | absolute | relative | static | sticky

* margin: margin-top margin-right margin-bottom margin-left (TRBL Trouble rule) [shorthand]

* padding: padding-top padding-right padding-bottom padding-left (TRBL Trouble rule) [shorthand]

* border: border-width border-style border-color [shorthand]

* width: number

* height: number

* min-width: number

* max-width: number

* min-height: number

* max-height: number

* overflow: scroll | hidden | auto | none

* border-radius: number

### CSS FlexBox

* CSS Flexbox is a flexible box model used to design webiste/web-page structure to behave responsively for different devices.

* To develop this kind of a structure, a set of CSS property-value are defined mentioned as follows:

* display: flex (set the display property of the container element to flexible box)

* flex-direction: column | row | column-reverse | row-reverse (set the direction of items inside flexible container to appear in a row or a column)

* flex-wrap: nowrap | wrap | wrap-reverse (when the device size is small it adjusts the flexible container items in the available spaces below the other)

* justify-content: center | flex-start | flex-end | space-around | spacebetween etc. (The justify-content property aligns the flexible container's items when the items do not use all available space on the main-axis (horizontally).)

* align-items: center | flex-end | flex-start | baseline | stretch (The alignitems property specifies the default alignment for items inside the flexible container.)

* align-self: center | flex-end | flex-start | baseline | stretch (The align-self property specifies the alignment for the selected item inside the flexible container. The align-self property overrides the flexible container's alignitems property.)

* flex-flow: flex-direction flex-wrap [shorthand property]

* order: number (Specifies the order of a flexible item relative to the rest of the flex items inside the same container)

###  Difference Between CSS2 and CSS 3

**CSS 2**

* Border enhancement properties weren't introduced.
* This doesn't support border-box property.
* border-image property is unsupported.
* limited set of pseudo-elements existed.
* limited set of pseudo-selectors existed.
* box-shadow property missing.

**CSS 3**

* Border enhancement properties like border-radius came into picture.
* border-box property is supported in this version.
* border-image property has been introduced.
* several new selectors like element attribute suffix, element attribute prefix and element attribute substring were introduced.
* several new pseudo-elements are introduced like ::first-line, ::first-letter,::after, ::before etc.
* several new pseudo-classes are introduced like :first-child, :hover, :active,:focus, :lang, :root, :empty etc.
* box-shadow property introduced, box-shadow: none | h-shadow vshadow blur spread color |inset;

### Resources

* [Difference between CSS2 and CSS3 keypoints]( https://nimapinfotech.com/blog/css3-vs-css2/)
* [CSS Study Link W3Schools]( https://www.w3schools.com/css/)
* [CSS Codecademy Link]( https://www.codecademy.com/learn/learn-css) (**Personally Preferred learning portal**)
* [JavaTPoint CSS Learning](https://www.javatpoint.com/css-tutorial)

## Day 4 - Adding Visuals to UI II

### Advanced CSS Concepts

**CSS variables**

CSS variables are the custom keywords used to store property values. These variables can be called at all the code areas where the desired value needs to be put. This is the most efficient code practice as value stored in the variable can be later on modified or deleted (as per the product requirement) very easily and quickly whereas locating all the places where the value has been written and then modifying/deleting it might be cumbersome and lead to unhandled code errors.

Syntax of declaring and using variables is as follows:

Variable Declaration: "--variable-name: value;" E.g. --grey-shade: grey;

Variable Consumption: "property: var(--variable-name);" E.g. color: var(--grey-shade);

**CSS pseudo-selectors**

These are the set of pre-defined classes in CSS used for special case styling on an element.Few of the highly used pseudo-selectors are as follows:

1. **:link** - This is a pseudo-selector used on anchor tags to define styles which enhances the predefined link behaviour of an anchor tag.
2. **:checked** - This is a pseudo-selector used on input type radio or checkbox, used to style them differently when they are in checked state.
3. **:disabled** - This is used on input types or elements to style them differently when they are disabled state.
4. **:invalid** - This is used on several input types to style them differently when they we input mismatched type of values in them. This pseudo-selector has met form validation needs efficiently.
5. **:hover** - This selector is used to add styles to an element to present it differently when user hovers on the element.
6. **:first-child** - This selector is used to add styles differently, to the first child of an element which acts as parent to it.
7. **:last-child** - This selector is used to add styles differently, to the last child of an element which acts as parent to it.
8. **:nth-child** - This selector is used to add styles differently, to the nth child of an element which acts as parent to it. This nth child could be any number like nth-child(4) the fourth child element, nth-child(odd) all the odd child elements, nth-child(5n) all the child elements appearing at a count of 5 will be styled differently and so on.

***CSS pseudo-elements***

These are the set of pre-defined styles in CSS used for special case styling on an element.Few of the highly used pseudo-elements are as follows:

1. **::first-line** - This selects the first line of typography tags and is uesd to style them differently.
2. **::first-letter** - This is used to add different styles to first letter in a typographic element or input elements.
3. **::after** - This is used to concatenate a string value towards the end of an element. The mandatory property-value pair needed to display output of this is content: "string/empty".
4. **::before** - This is used to concatenate a string value towards the beginning of an element. The mandatory property-value pair needed to display output of this is content:
"string/empty".

***Font-Awesome Icons Library***

Font-awesome icons library is used widely to include icons on a web page or website. It is a repository of icons and provide commonly used icons for free to the web applications. There are other similar icon repositories available online. the Font-awesome repository may be used in the following ways:

1. **CDN link**: developers may include the cdn (content delivery network) link for font-awesome repository in the head section of root html file in this way: `<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/fontawesome.min.css">`
2. **NPM Package**: while developing a website using a JS framework, a node package may be installed in the application and used directly. This method has an advantage over the cdn link that if the server where the icons are placed, runs down, it does not affect our webiste as we have the package locally installed in our app. The package may be installed running this command `"npm i font-awesome"`.
3. **Grammar to use the icons**:
    1. **CSS content-code method**: by using the pseudo-element after/before with the element to which icon needs to be applied, the content attribute value can be substituted with string content code of the icon and including the font-family attribute to be FontAwesome. E.g.
       ``` javascript
       p::after{
       content: '\f01e';
       font-family: FontAwesome;
       }```
    2. **HTML entity code method**: much alike css content code method, the html entity code is written inside the element where icon is needed and element css must contain font-family as FontAwesome. E.g.
      ``` javascript
      <span> '&#wwww' home </span >
      css: span { font-family: FontAwesome;}
      ``` 
    3. **HTML tag and class attribute method**: An i tag with class="fa icon-class" is placed in the html code to display the icon. E.g.
       ``` javascript
       <i class="fa fa-adjust">
       ```
**CSS Transform**

* **transform: rotate(angle)** - This property enables to rotate an element by an angle given, to which it is applied. E.g. `transform: rotate(45deg);`
* **transform: scale(x,y)** - This property enables to zoom-in/zoomout/stretch an element by the value of x and y axis given, to which it is applied. E.g. `transform: scale(1.5,2.5);`
* **transform: translate(x,y)** - This property re-positions the element on x axis and y axis , to which it is applied. E.g. `transform: translate(50px,20px);`
* **transform: none** - This property clears and removes all the transform applied to an element.
* **transform: scaleX(x)** - This property enables to zoom-in/zoomout/stretch an element by the value of x coordinate only, to which it is applied. E.g. `transform: scale(1.5);`
* **transform: scaleY(y)** - This property enables to zoom-in/zoomout/stretch an element by the value of y coordinate only, to which it is applied. E.g. `transform: scale(4.5);`
* **transform: translateY(y)** - This property re-positions the element on it's y coordinate only, to which it is applied. E.g. `transform: translateY(15px);`
* **transform: translateX(x)** - This property re-positions the element on it's x coordinate only, to which it is applied. E.g. `transform: translateX(15px);`
* **transform: rotateX(angle)** - This property enables to rotate an element by an angle given from it's x-axis, to which it is applied. E.g. `transform:rotate(45deg);`
* **transform: rotateY(angle)** - This property enables to rotate an element by an angle given from it's y-axis, to which it is applied. E.g. `transform:rotate(45deg);`

### Resources

* [CSS transform property]( https://www.w3schools.com/cssref/css3_pr_transform.asp)
* [CSS variables]( https://www.w3schools.com/css/css3_variables.asp)
* [Difference between :root pseudo-selector and html{} selector]( https://stackoverflow.com/questions/15899615/whats-the-difference-between-css3s-root-pseudo-class-and-html) 
   
One technical difference between them is that :root - being a pseudo class has a greater specificity than html (a type selector)

## Day 5 - Introduction to CSS preprocessors

### Introduction to SASS

* What is SASS? - SASS is a pre-processor scripting language compiled or interpreted into CSS. It is the most powerful, mature and stable CSS extension language. It eliminates the redundancy in CSS code and allows to create reusable components.
* Difference between SASS and SCSS: The only difference is that a file saved with .sass extension must contain an indented syntax and a file saved with .scss extension may take help of curly braces to define the scope. Hence, the only difference lies in the grammar of writing the code.

    A file with .sass extension:
    ```javascript
    p
     color: green;
     span
       color: red;
       font-family: arial black;
     font-family: Segoe UI;
    ```
    
    A file with .scss extension
    ```javascript
    p
    {
    color: green;
    span
    {
    color: red;
    font-family: arial black;
    }
    font-family: Segoe UI;
    }
    ```
* Fundamental Concepts of SASS are: variables, mixins, functions and arguments,lists and arrays.

### SASS Variables

* **SASS Variables**: These are the store houses for property values much alike CSS variables.
* **Syntax for Variable Declaration**- $variable-name: value stored; E.g. `$primary-color:darkblue;`
* **Syntax for Variable Consumption**- property: $variable-name; E.g. `color: $primarycolor; etc.`
* **Syntax for Variable as function argument**- @function btn($value){@return $value;}
* **Syntax for Variable as argument with default value**- @function btn($value = "primary"){ @return $value; }

### SASS Mixins

* **Mixins**: These are collection of code statements for some common styles under a single roof to be re-used wherever same set of styles are needed in a website/web-page.

* **Syntax of mixins**:

    ```javascript
      @mixin btn-primary{
      background-color: blue;
      color: white;
      border-radius: 3px;
      padding: 12px;
      &:hover{
      background-color: darkblue;
      border: 1px inset blue;
      }
      }
      
      .btn-action{
      @include btn-primary;
      }
      
      .btn-ok{
      @include btn-primary;
      background-color: green;
      }
    ```
    
* **More Dynamic Mixins**:

    ```javascript
      @mixin btn($color, $borderRadius, $bgColor, $padding, $margin, $hoverbg){
      background-color: $bgColor;
      color: $color;
      border-radius: $borderRadius;
      margin: $margin;
      padding: $padding;
      &:hover{
      background-color: $hoverbg;
      }
      }
      
      .btn-cancel{
      @include btn('white', '3px', 'darkblue', '12px', '0px', 'lightblue');
      }
      
      .btn-warning{
      @include btn('goldenrod', '3px', '#202020', '8px', '0px', 'yellow'); }
    ```

A mixin may be called in another mixin with additional or no set of style statements.

### SASS Functions and Lists

* **SASS Functions**: These are code snippets which helps rendering functional,conditional or looped styles to an element.
* **Syntax**: @function function-name(arguments){ function to be performed }
* E.g.
  ```javascript
    @function edges($edgesValue: 'flat'){
    $value: 25px;
    @if $edgesValue == 'semi'{
    $value: 5px;
    @return $value;
    }
    @else if $edgesValue == 'rounded'{
    $value: 50%;
    @return $value;
    }
    @else if $edgesValue == 'flat'{
    $value: 0px;
    @return $value;
    }
    }
    p{
    border-radius: edges('semi');
    border: 1px solid;
    padding: 12px;
    }
    div{
    border: 2px solid;
    border-radius: edges('rounded');
    width: 20px

    height: 20px;
    }
   ```
   
* **SASS Lists**: SASS Lists are key-value pairs stored like an object.

* **Syntax**: `$colors: (black: #000000, white: #ffffff, grey: #efefef, red: #000099);`

* These list key-values may be accessed by inbuilt SASS function `map-get()`. E.g. 
  ```Javascript
     div{
     background-color: map-get($colors, grey);
     }
  ```

* **More functional example**:
  ```javascript
      $palette:( grey: (5: #404040, 10: #606060, 20: #808080, 30: #B0B0B0, 40: #D0D0D0), 
                 blue: (5: #000033, 10: #000066, 20: #000099), 
                 red: (5: #660000, 10: #990000) );
      @function color($colorname, $colorcode){
      $color-map: map-get($palette, $colorname);
      @if ($color-map == null) {
      @error $selectedColor + ' is not part of the color palette';
      }
      @return map-get($color-map, $colorcode);
      }
      p{
      color: color(red,10);
      }
   ```   


