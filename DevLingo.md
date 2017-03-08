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
>>     2.4.1 Link to other fonts
>>
>>     2.4.2 Font-size
>>
>>     2.4.3 PX
>>
>>     2.4.4 EM
>>
>>     2.4.5 % - Percentages
>>
>>     2.4.6 line-height
>>
>>     2.4.7 Word-spacing
>>
>>     2.4.8 Font-weight
>>
>>     2.4.9 Font-style
>>
>>     2.4.10 Text-transform
>>
>>     2.4.11 Text-align

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

>         <ol>
>           <li>Russia</li>
>           <li>United States</li>
>           <li>Canada</li>
>         </ol>

        ouput:

          1. Russia
          2. Untited States
          3. Canada

        1.2.2.2 <ul></ul> Un-Ordered lists is to make un-ordered lists within html

        example:

>         <ul>
>           <li>Russia</li>
>           <li>United States</li>
>           <li>Canada</li>
>         </ul>

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

>     .class_name or html_element(called the selector) {
>        property(ex color): value(Blue); This line in called a declaration.
>     }

  2.2 linking CSS and HTML together

    HTML and CSS can be linked using the <link/> tag or element inside of the head
    element in your HTML code.
    The struckture of the link element would typically look as follows.

>   `<link rel="stylesheet" href="style.css" type="text/css">`

    As jou can see the href target is set to "style.css", this tells the browswer
    that the CSS file is in the same directory as the HTML file.

    When linking a CSS file in a different directory it would typically look as
    follow.(No example added yet)

  2.3 Colors

    It is important to remember that not all browswers and versions of browsers
    support hsl, hsla and rgba and it is therefore neccesary to include other
    color options above the color used for the newest browsers.

    example:

>     .main {
>       color: rgb(23, 88, 9); (Browser will use this(top) color when un-supported)
>       color: rgba(23, 88, 9, 0.9); (If supported will use this lower one by default)
>     }

    Foreground color refers to the actual color of an element, styled with the
    color property.
    Background color refers to the color behind an element, styled with the background-color property.

    2.3.1 rgb(Red, Green, Blue)

>     h1 {
>       color: rgb(123, 88, 9);
>     }

      2.3.1.1 rgba(Red, Green, Blue, Opacity)

>       h1 {
>         color: rgba(123, 88, 9, 0.5);
>       }

    2.3.2 hsl(Hue, Saturation, and Lightness)

>     h1 {
>       color: hsl(182, 20%, 50%);
>     }

      2.3.2.1 hsla(Hue, Saturation, and Lightness, Opacity)

>       h1 {
>         color: hsla(239, 45%, 22%, 0.4);
>       }

    2.3.3 hexadecimal color codes

>     h1 {
>       color: #09AA34;
>     }
>
>     h1 {
>       color: #FFFFFF;
>       color: #FFF; (This is the same color as above)
>     }
>
>     h2 {
>       color: #AA33BB;
>       color: #A3B; (This is the same color as above)
>     }

  2.4 Fonts

    To change the typeface of text on your web page, you can use the font-family
    property.

>     h1 {
>       font-family: Garamond;
>     }

    When setting typefaces on a web page, keep the following points in mind:

    The font specified in a stylesheet must be installed on a user's computer
    in order for that font to display when a user visit the web page.

    The default typeface for all HTML elements is Times New Roman.

    It's a good practice to limit the number of typefaces used on a web page
    to 2 or 3.

    When the name of a typeface consists of more than one word, it must be
    enclosed in double quotes (otherwise it will not be recognized), like so:

>     h1 {
>       font-family: "Courier New";
>     }

    Most computers have a small set of typefaces pre-installed. This small set includes serif fonts and sans-serif fonts, like Times New Roman and Arial, respectively.

    When the stylesheet specifies a font not installed on a user's computer, the pre-installed fonts can be used as fallback fonts for users.

    To use fallback fonts, the following syntax is required:

>     h1 {
>       font-family: Garamond, Times, serif;
>     }

    The Browser will try each font from left to right until it finds the a font
    that is installed on the users device.

    2.4.1 Link to other fonts

      you can link to a specific Google Font in your HTML code and use it immediately in your stylesheet. Because the HTML file links directly to the Google Font, a user's browser can display the typeface you specify. This avoids having to determine whether or not that font is installed on a user's computer.

      To use a Google Font, you can use a <link> element, just like you did for a CSS stylesheet:

>       <head>
>         <link href="https://fonts.googleapis.com/css?family=Raleway"
>         type="text/css" rel="stylesheet">
>       </head

      In the example above, the href attribute is set to the following URL, which was retrieved from Google Fonts:
      The URL in the example above also specifies the Raleway typeface from Google Fonts.

    2.4.2 Font-size

      To change the size of text on your web page, you can use the font-size property.

>       p {
>         font-size: 18px;
>       }

    2.4.3 PX

      px - Represents the unit of pixels. The display of a computer monitor can
      be measured in pixels. A pixel is a small point on the display. How small?
      Most computer monitors have a resolution of 72 pixels per inch, so a pixel
      represents about 1/72nd of an inch. Pixels are sometimes also referred to
      as points. Pixels are used to set the exact size of an element, in this c
      ase, text.

>       p {
>         font-size: 18px;
>       }

    2.4.4 EM

      ems - Pronounced just as it looks, "em." An em is equal to the width of
      the letter "m". Ems are a relative unit of measurement. They change the
      size of text relative to the parent element's size of text.

>       p {
>         font-size: 1.3em;
>       }

    2.4.5 % - Percentages

      % - Percentages are also a relative unit of measurement. The default size
      of text in web browsers is 16 pixels, or 16px. When percentages are used,
      they set the size of text relative to this default size. For example,
      setting the font size to 200% would be equivalent to setting it to 32px.

>       p {
>         font-size: 150%;
>       }

    2.4.6 line-height

      Text on a web page must also be easy to read. When text is styled to appear
      larger, the vertical spacing between lines of text can decrease, creating
      text that is difficult to read, particularly in paragraphs.

      To avoid this problem, you can modify the spacing between lines of text
      with the line-height property.

      When the line height is increased, the spacing between lines of text increases, which can make text easier to read.

>       p {
>         line-height: 1.5em;
>       }

      When the line-height property of an element is modified, the leading is
      increased, resulting in an increase of the vertical spacing between lines
      of text.
      This means that when you increase the line-hight you can use larger font
      without changing the spacing between lines.

    2.4.7 Word-spacing

      Word-spacing works in the same way as line_hight so does letter-spacing
      and all other related property's.
      The default amount of space between words is usually 0.25em.
      It's not common to increase the spacing between words, but it may help
      enhance the readability of bolded or enlarged text. Note, again, that the
      preferred unit is ems.

    2.4.8 Font-weight

      In CSS, the font-weight property turns bold on or off.

>       p {
>         font-weight: bold;(normal numbers can be used ex: 100, 200, 300)
>       }

      Notice the 100 in the URL below. This specifies that you'd like to use a
      font weight of 100 when linking to the Roboto font. It's possible to
      specify a different font weight, or even multiple within the same URL.

>       <link href="https://fonts.googleapis.com/css?family=Roboto:100" rel="stylesheet">

    2.4.9 Font-style

      font-style is used to set the font style between italic, normal and oblique

    2.4.10 Text-transform

      Is used to tranform any text within your html to the following modes:

        capitalize
        full- width
        lowercase
        uppercase
        inherit(this will inheret from the parent element)

    2.4.11 Text-align

      The text-align property can be set to one of the following three values:

        1. left - aligns text to the left hand side of the browser.
        2. center - centers text.
        3. right - aligns text to the right hand side of the browser.
