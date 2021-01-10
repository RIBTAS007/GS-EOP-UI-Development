# Day 4 - Adding Visuals to UI II

Mentored by : [Ritika Gupta](https://www.linkedin.com/in/gritika1906/)

Platforms used : [jsfiddle](https://jsfiddle.net/) and [codepen.io](https://codepen.io/collection/AQPkmq )

## Advanced CSS Concepts

### CSS variables

CSS variables are the custom keywords used to store property values. These variables can be called at all the code areas where the desired value needs to be put. This is the most efficient code practice as value stored in the variable can be later on modified or deleted (as per the product requirement) very easily and quickly whereas locating all the places where the value has been written and then modifying/deleting it might be cumbersome and lead to unhandled code errors.

Syntax of declaring and using variables is as follows:

Variable Declaration: "--variable-name: value;" E.g. --grey-shade: grey;

Variable Consumption: "property: var(--variable-name);" E.g. color: var(--grey-shade);

### CSS pseudo-selectors

These are the set of pre-defined classes in CSS used for special case styling on an element.Few of the highly used pseudo-selectors are as follows:

1. **:link** - This is a pseudo-selector used on anchor tags to define styles which enhances the predefined link behaviour of an anchor tag.
2. **:checked** - This is a pseudo-selector used on input type radio or checkbox, used to style them differently when they are in checked state.
3. **:disabled** - This is used on input types or elements to style them differently when they are disabled state.
4. **:invalid** - This is used on several input types to style them differently when they we input mismatched type of values in them. This pseudo-selector has met form validation needs efficiently.
5. **:hover** - This selector is used to add styles to an element to present it differently when user hovers on the element.
6. **:first-child** - This selector is used to add styles differently, to the first child of an element which acts as parent to it.
7. **:last-child** - This selector is used to add styles differently, to the last child of an element which acts as parent to it.
8. **:nth-child** - This selector is used to add styles differently, to the nth child of an element which acts as parent to it. This nth child could be any number like nth-child(4) the fourth child element, nth-child(odd) all the odd child elements, nth-child(5n) all the child elements appearing at a count of 5 will be styled differently and so on.

### CSS pseudo-elements

These are the set of pre-defined styles in CSS used for special case styling on an element.Few of the highly used pseudo-elements are as follows:

1. **::first-line** - This selects the first line of typography tags and is uesd to style them differently.
2. **::first-letter** - This is used to add different styles to first letter in a typographic element or input elements.
3. **::after** - This is used to concatenate a string value towards the end of an element. The mandatory property-value pair needed to display output of this is content: "string/empty".
4. **::before** - This is used to concatenate a string value towards the beginning of an element. The mandatory property-value pair needed to display output of this is content:
"string/empty".

### Font-Awesome Icons Library

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
### CSS Transform

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
