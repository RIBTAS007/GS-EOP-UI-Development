# Day 2 - Kickstart to UI Development

Mentored by : [Ritika Gupta](https://www.linkedin.com/in/gritika1906/)

Platforms used : [jsfiddle](https://jsfiddle.net/) and [codepen.io](https://codepen.io/collection/AQPkmq )

## Introduction to HTML

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

## Difference between HTML4 and HTML5

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

## HTML Code for practise

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

## Resources

* [HTML Learning from JavaT Point]( https://www.javatpoint.com/html-tutorial)
* [Codecademy HTML Code-Along Learn Platform]( https://www.codecademy.com/learn/learn-html )(**Personally recommended**)
* [W3Schools HTML Learning]( https://www.w3schools.com/html/)
* [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML) (**Preferred when you have a strong grip on fundamentals**)
* [Tutorials Point HTML]( https://www.tutorialspoint.com/html/index.html)
