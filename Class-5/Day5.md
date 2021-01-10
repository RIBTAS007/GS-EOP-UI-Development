# Day 5 - Introduction to CSS preprocessors

Mentored by : [Ritika Gupta](https://www.linkedin.com/in/gritika1906/)

Platforms used : [jsfiddle](https://jsfiddle.net/) and [codepen.io](https://codepen.io/collection/AQPkmq )

## Introduction to SASS

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

## SASS Variables

* **SASS Variables**: These are the store houses for property values much alike CSS variables.
* **Syntax for Variable Declaration**- $variable-name: value stored; E.g. `$primary-color:darkblue;`
* **Syntax for Variable Consumption**- property: $variable-name; E.g. `color: $primarycolor; etc.`
* **Syntax for Variable as function argument**- @function btn($value){@return $value;}
* **Syntax for Variable as argument with default value**- @function btn($value = "primary"){ @return $value; }

## SASS Mixins

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

## SASS Functions and Lists

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

## Resources

* [SASS official website to explore in-depth features of SASS and their usage]( https://sass-lang.com/guide)
* [SASS from W3Schools]( https://www.w3schools.com/sass/)
* [SASS from JavaTPoint]( https://www.javatpoint.com/sass-tutorial)
