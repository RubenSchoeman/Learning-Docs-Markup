# General Development *Lingo*

## **Content**

#### Definitions

#### 1. HTML *Lingo*

>  1.1. `<form></form>` Tag
>
>  1.2. `<body></body>` Tag
>
>>     1.2.1. <h1></h1> to <h6></>
>>
>>     1.2.2  Lists
>>
>>>         1.2.2.1 <ol></ol> Ordered lists
>>>
>>>         1.2.2.2 <ul></ul> Un-oredered list
>>
>>     1.2.3 <a></a> Anchors
>>
>>>         1.2.3.1 <a href=""></a>
>>>
>>>         1.2.3.2 <a href="" target=""></a>
>
>  1.3. `<div></div>` Tag
>
>  1.4. `<head></head>` Tag
>
>      1.4.1 List of elements used in the <head></head> element*
>


#### 2. CSS *Lingo*

>   2.1 Basic structure of CSS
>
>   2.2 linking CSS and HTML together
>
>   2.3 Colors
>
>>     2.3.1 rgb(Red, Green, Blue)
>>
>>>       2.3.1.1 rgba(Red, Green, Blue, Opacity)
>>
>>     2.3.2 hsl(Hue, Saturation, and Lightness)
>>
>>>       2.3.2.1 hsla(Hue, Saturation, and Lightness, Opacity)
>>
>>     2.3.3 hexadecimal color codes
>
>   2.4 Fonts
>
#### 3. JavaScript *Lingo*

#### 4. HTML Video Tutorials

#### 5. CSS Video Tutorials

#### 6. JavaScript Video Tutorials

### 1. HTML *Lingo*


#### Definitions

| Index | Name | Definition |
|:-----:|:----:|:----------:|
| | CSS background-color  | Background color refers to the color behind an element, styled with the background-color property.  |
| 1.0.1 | Boilerplate | The term "boilerplate code" is used to describe the basic HTML code required to begin creating a web |
| 1.0.1.1 |  Boilerplate | ```<!DOCTYPE html> <html> <head> <title></title> </head> <body></body> </html>``` |
| 1.0.2. | Elements | HTML element (or simply, element) - HTML code that lives inside of angle brackets. Angle Brackets is simply the less than and greater than brackets <></> |
| | CSS Foreground color | Foreground color refers to the actual color of an element, styled with the color property  |
| | HSLA | Hue, Saturation, and Lightness and Opacity (Not supported by some browswers) {color: hsla(123, 88, 9, 0.6);} |
| | HSL | Hue, Saturation, and Lightness (Not supported by some browswers) {color: hsl(123, 88, 9);} |
| | RGBA  | Red, Green, Blue, Opacity (Not supported by some browswers){color: rgb(123, 88, 9, 0.5);} |
| | RGB  | Red, Green, Blue {color: rgb(123, 88, 9);} |



  1.1. `<form></form>` Tag

    The HTML <form></form> tag is used for creating a form for user input. A form
    can contain textfields, checkboxes, radio-buttons and more. Forms are used to
    pass user-data to a specified URL.
    Any input form the client side will be submitted through the <form></form> tag.

  1.2. `<body></body>` Tag

    Before we can add content that a browser will display, we have to add a body
    to the HTML file.
    Once the file has a body, many different types of content can be added within
    the body, like text, images, buttons, and much more.

    1.2.1
      <h></h> elements can be placed in the <body></body> elements and range
      from h1 to h6

    1.2.2 List

        1.2.2.1 <ol></ol> Ordered lists is to make ordered lists within html

        example:

          <ol>
            <li>Russia</li>
            <li>United States</li>
            <li>Canada</li>
          </ol>

        ouput:

          1. Russia
          2. Untited States
          3. Canada

        1.2.2.2 <ul></ul> Un-Ordered lists is to make un-ordered lists within html

        example:

          <ul>
            <li>Russia</li>
            <li>United States</li>
            <li>Canada</li>
          </ul>

        output:

          * Russia
          * United States
          * Canada

    1.2.3 <a></a> Anchors

        1.2.3.1 <a href=""></a>

          Is used to create a link to other domains.

        1.2.3.2 <a href="" target=""></a>

          Is used to create a new tab when opening a link.


  1.3. `<div></div>` Tag

  1.4. `<head></head>` Tag

    The <head></head> element will contain information about the page that isn't
    displayed directly on the actual web page.
    This include <title></title> elements which is used to dispay information in
    the browser tab at the top.

  #####  1.4.1. *List of elements used in the `<head></head>` element*
  > ##### `<title></title>`
  > ##### `<style></style>`
  > ##### `<range></range>`
  > ##### `<nextid></nextid>`
  > ##### `<meta></meta>`
  > ##### `<link></link>`
  > ##### `<isindex></isindex>`
  > ##### `<base></base>`

### 2. CSS *Lingo*

  2.1 Basic structure of CSS

    CSS structure can be used in many ways.
    the basic structure being the following.

    ```css
    .class_name or html_element(called the selector) {
      property(ex color): value(Blue); This line in called a declaration.
    }
    ```

  2.2 linking CSS and HTML together

    HTML and CSS can be linked using the <link/> tag or element inside of the head
    element in your HTML code.
    The struckture of the link element would typically look as follows.

    ```html
    <link rel="stylesheet" href="style.css" type="text/css">
    ```

    As jou can see the href target is set to "style.css", this tells the browswer
    that the CSS file is in the same directory as the HTML file.

    When linking a CSS file in a different directory it would typically look as
    follow.(No example added yet)

  2.3 Colors

    It is important to remember that not all browswers and versions of browsers
    support hsl, hsla and rgba and it is therefore neccesary to include other
    color options above the color used for the newest browsers.

    example:

      ```css
      .main {
        color: rgb(23, 88, 9); (Browser will use this(top) color when un-supported)
        color: rgba(23, 88, 9, 0.9); (If supported will use this lower one by default)
      }
      ```

    Foreground color refers to the actual color of an element, styled with the
    color property.
    Background color refers to the color behind an element, styled with the background-color property.

    2.3.1 rgb(Red, Green, Blue)

      ```css
      h1 {
        color: rgb(123, 88, 9);
      }
      ```

      2.3.1.1 rgba(Red, Green, Blue, Opacity)

      ```css
      h1 {
        color: rgba(123, 88, 9, 0.5);
      }
      ```

    2.3.2 hsl(Hue, Saturation, and Lightness)

      ```css
      h1 {
        color: hsl(182, 20%, 50%);
      }
      ```

      2.3.2.1 hsla(Hue, Saturation, and Lightness, Opacity)

      ```css
      h1 {
        color: hsla(239, 45%, 22%, 0.4);
      }
      ```

    2.3.3 hexadecimal color codes

      ```css
      h1 {
        color: #09AA34;
      }

      h1 {
        color: #FFFFFF;
        color: #FFF; (This is the same color as above)
      }

      h2 {
        color: #AA33BB;
        color: #A3B; (This is the same color as above)
      }
      ```

  2.4 Fonts

    To change the typeface of text on your web page, you can use the font-family
    property.

      ```css
      h1 {
        font-family: Garamond;
      }
      ```

      When setting typefaces on a web page, keep the following points in mind:

      The font specified in a stylesheet must be installed on a user's computer
      in order for that font to display when a user visit the web page.

      The default typeface for all HTML elements is Times New Roman.

      It's a good practice to limit the number of typefaces used on a web page
      to 2 or 3.
