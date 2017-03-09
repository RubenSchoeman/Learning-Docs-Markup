# General Development *Lingo*

## **Content**

#### Definitions

#### 1. HTML *Lingo*

#### Element Img

#### Definitions

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
>  1.5 Labels
>
>>     1.5.1 ID Label
>>
>>     1.5.2 Classes Label
>>
>>>     1.5.2.1 Targeting specific Classes with same name
>>>
>>>     1.5.2.2 Elements with more than one class
>
>  1.6 Multiple selectors

#### 2. CSS *Lingo*

>   2.1 Basic structure of CSS
>
>   2.2 linking CSS and HTML together
>
>   2.3 Colors property
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
>>     2.4.2 Font-size property
>>
>>     2.4.3 PX
>>
>>     2.4.4 EM
>>
>>     2.4.5 % - Percentages
>>
>>     2.4.6 line-height property
>>
>>     2.4.7 Word-spacing property
>>
>>     2.4.8 Font-weight property
>>
>>     2.4.9 Font-style property
>>
>>     2.4.10 Text-transform property
>>
>>     2.4.11 Text-align property
>
>   2.5 Min and Max widths and hights property
>
>   2.6 Overflow property
>
>   2.7 Border-style property
>>
>>    2.7.1 Border-width property
>>
>>    2.7.2 Border-color property
>>
>>    2.7.3 Border-radius property
>
>   2.8 Shorthand Styling
>
>   2.9 Padding property
>
>   2.10 Margin property
>
>   2.11 User Agent Stylesheets
>
>   2.12 Display property
>
>   2.13 Visibility property.
>
>   2.14 Box model


#### 3. JavaScript *Lingo*

#### 4. HTML Video Tutorials

#### 5. CSS Video Tutorials

#### 6. JavaScript Video Tutorials

### 1. HTML *Lingo*

#### Element Img

  ![Element structure](htmlcss1-diagram__htmlanatomy.svg)

#### Definitions

| Index | Name | Definition |
|:-----:|:----:|:----------:|
| | Block-level elements  | elements that use an entire line of space in a web page and disrupt the natural flow of text. Most of the common HTML elements are block-level elements (headings, paragraphs, divs, and more).  |
| 1.0.1 | Boilerplate | The term "boilerplate code" is used to describe the basic HTML code required to begin creating a web |
| 1.0.1.1 |  Boilerplate | ```<!DOCTYPE html> <html> <head> <title></title> </head> <body></body> </html>``` |
| | Box model  | The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.  |
| | CSS background-color  | Background color refers to the color behind an element, styled with the background-color property.  |
| | Default Stylesheets  | User Agent Stylesheets or Browser Stylesheets |
| 1.0.2. | Elements | HTML element (or simply, element) - HTML code that lives inside of angle brackets. Angle Brackets is simply the less than and greater than brackets <></> |
| | CSS Foreground color | Foreground color refers to the actual color of an element, styled with the color property  |
| | HSLA | Hue, Saturation, and Lightness and Opacity (Not supported by some browswers) {color: hsla(123, 88, 9, 0.6);} |
| | HSL | Hue, Saturation, and Lightness (Not supported by some browswers) {color: hsl(123, 88, 9);} |
| | Inline elements  | Elements that display inline with text, without disrupting the flow of the text (like links)  |
| | RGBA  | Red, Green, Blue, Opacity (Not supported by some browswers){color: rgb(123, 88, 9, 0.5);} |
| | RGB  | Red, Green, Blue {color: rgb(123, 88, 9);} |
| | User Agent  | Is a technical term for the browser  |



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

    HTML offers an element that is the backbone of code organization: the div,
    represented by <div> in HTML.

    You can think of the div as a box, or container, that groups elements that
    belong together.

      1. Keep HTML code easy to read.
      2. Group elements that belong together.

>       <div>
>         <h1>Alice In Wonderland</h1>
>         <p> ... </p>
>       </div>



  1.4. `<head></head>` Tag

    The <head></head> element will contain information about the page that isn't
    displayed directly on the actual web page.
    This include <title></title> elements which is used to dispay information in
    the browser tab at the top.

    1.4.1. *List of elements used in the `<head></head>` element*
>   ##### `<title></title>`
>   ##### `<style></style>`
>   ##### `<range></range>`
>   ##### `<nextid></nextid>`
>   ##### `<meta></meta>`
>   ##### `<link></link>`
>   ##### `<isindex></isindex>`
>   ##### `<base></base>`

  1.5 Labels

    1.5.1 ID Label

      With the proper labels, we can style individual HTML elements! Specifically,
      we can label HTML elements with a unique identifier, or ID. We can then
      style that specific element in the stylesheet.

      IDs are intended to label unique elements in an HTML file. No two HTML
      elements should ever share the same ID.
      To label an element with an ID, we can use the id attribute on an HTML element.

>       <h1 id="botswana">Botswana</h1>

      To style a specific element labeled with an ID, you can use an ID selector
      in the stylesheet.
      The ID would be called in CSS in the following manner using a hash character
      also known as the octothorpe character: #.

>       #botswana {
>         color: Blue;
>       }

    1.5.2 Classes Label

      For multiple elements that should share the same styling, classes can be
      used to label them.

      To label an element with a class, we can use the class attribute on an HTML
      element.

>       <h1 class="science">Scientist Discovers Important Cure</h1>

      To style elements of the same class, you can use a class selector in the
      stylesheet.
      Class selectors begin with a period (.) and are immediately followed by
      the name of the class.

>
>       .science {
>         text-transform: uppercase;
>       }

      1.5.2.1 Targeting specific Classes with same name

        The class selector targets all elements of a particular class.
        It's possible, however, for multiple elements on a web page to share a
        specific styling, but for one of those elements to differ slightly.

        You can see that the first example targets all classes named breaking
        and the second example only targets paragraphs with the class breaking.
        We will call this the element.class selector syntax

>         .breaking {
>           font-family: Georgia, Times, serif;
>         }
>
>         p.breaking {
>          line-height: 1.3em;
>         }

      1.5.2.2 Elements with more than one class

        It's also possible to label HTML elements with more than one class.When
        those same elements must also be differentiatedlabeling with an additional
        class is helpful.

        HTML elements can be labeled with many classes, but whenever possible,
        it's best to limit an element to four classes at most.

>         <h1 class="book domestic">The Way of the Deep</h1>
>
>         <h1 class="book foreign">A Night in the Sky</h1>

>         .book {
>           font-family: Georgia, serif;
>         }
>
>         .domestic {
>           font-color: #0902CC;
>         }
>
>         .foreign {
>           font-color: #B097DD;
>         }

  1.6 Multiple selectors

    CSS does not limit you to selectors that target a single element or class.
    Using a multiple class selector is an efficient way of styling multiple HTML
    elements.

>     h1, p {
>       font-family: Garamond, serif;
>     }
>
>     .first, .last {
>       font-size: 20px;
>      }






### 2. CSS *Lingo*

  2.1 Basic structure of CSS

    CSS structure can be used in many ways.
    the basic structure being the following.

  ![Structure](htmlcss1-diagram__cssdeclaration.svg)

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

    Most computers have a small set of typefaces pre-installed. This small set
    includes serif fonts and sans-serif fonts, like Times New Roman and Arial,
    respectively.

    When the stylesheet specifies a font not installed on a user's computer, the pre-installed fonts can be used as fallback fonts for users.

    To use fallback fonts, the following syntax is required:

>     h1 {
>       font-family: Garamond, Times, serif;
>     }

    The Browser will try each font from left to right until it finds the a font
    that is installed on the users device.

    2.4.1 Link to other fonts

      you can link to a specific Google Font in your HTML code and use it
      immediately in your stylesheet. Because the HTML file links directly to the
      Google Font, a user's browser can display the typeface you specify. This
      avoids having to determine whether or not that font is installed on a user's
      computer.

      To use a Google Font, you can use a <link> element, just like you did for
      a CSS stylesheet:

>       <head>
>         <link href="https://fonts.googleapis.com/css?family=Raleway"
>         type="text/css" rel="stylesheet">
>       </head

      In the example above, the href attribute is set to the following URL, which
      was retrieved from Google Fonts:
      The URL in the example above also specifies the Raleway typeface from Google
      Fonts.

    2.4.2 Font-size property

      To change the size of text on your web page, you can use the font-size
      property.

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

    2.4.6 line-height property

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

  ![Leading](htmlcss1-diagram__leading.svg)

    2.4.7 Word-spacing property

      Word-spacing works in the same way as line_hight so does letter-spacing
      and all other related property's.
      The default amount of space between words is usually 0.25em.
      It's not common to increase the spacing between words, but it may help
      enhance the readability of bolded or enlarged text. Note, again, that the
      preferred unit is ems.

    2.4.8 Font-weight property

      In CSS, the font-weight property turns bold on or off.

>       p {
>         font-weight: bold;(normal numbers can be used ex: 100, 200, 300)
>       }

      Notice the 100 in the URL below. This specifies that you'd like to use a
      font weight of 100 when linking to the Roboto font. It's possible to
      specify a different font weight, or even multiple within the same URL.

>       <link href="https://fonts.googleapis.com/css?family=Roboto:100" rel="stylesheet">

    2.4.9 Font-style property

      font-style is used to set the font style between italic, normal and oblique

    2.4.10 Text-transform property

      Is used to tranform any text within your html to the following modes:

        capitalize
        full- width
        lowercase
        uppercase
        inherit(this will inheret from the parent element)

    2.4.11 Text-align property

      The text-align property can be set to one of the following three values:

        1. left - aligns text to the left hand side of the browser.
        2. center - centers text.
        3. right - aligns text to the right hand side of the browser.

  2.5 Min and Max widths and hights property

    Because a web page can be viewed through displays of differing screen size,
    the content on the web page can suffer from those changes in size. To avoid
    this problem, CSS offers two properties that can limit how narrow or how
    wide an element's box can be sized to.
    You can also limit the minimum and maximum height of an element.

      1. min-width - this property ensures a minimum width for an element's box.
      2. max-width - this property ensures a maximum width for an element's box.
      3. min-height - this property ensures a minimum height for an element's box.
      4. max-height - this property ensures a maximum height for an element's box.


>     p {
>       min-width: 300px;
>       max-width: 600px;
>       min-height: 150px;
>       max-height: 300px;
>     }

  2.6 Overflow property

    When the value of the max-height property is set too low, the contents will
    spill outside of the box. How can we ensure that this doesn't happen?

    The overflow property controls what happens to content when it spills, or overflows, outside of its box. It can be set to one of the following values:

      1. hidden - when set to this value, any content that overflows be hidden
         from view.
      2. scroll - when set to this value, a scrollbar will be added to the
         element's box so that the rest of the content can be viewed by scrolling.

>     p {
>       min-width: 300px;
>       max-width: 600px;
>       min-height: 150px;
>       max-height: 300px;
>       overflow: scroll;
>     }

  2.7 Border-style property

    It's not possible to view a box's border if the border's style has not been set. A border's style can be set with the border-style property. This property can take on one of the following values:

      1. solid - border is a solid line.
      2. dashed - border is a series of lines or dashes.
      3. dotted - border is a series of square dots.
      4. double - border is two solid black lines.
      5. groove - border is a groove (or carving).
      6. inset - border appears to cut into the screen.
      7. outset - border appears to pop out of the screen.
      8. ridge - border appears as a picture frame.
      9. hidden or none - no border.

>     p {
>       border-style: dashed;
>     }

    2.7.1 Border-width property

      You can control the thickness, or width, of borders with the border-width
      property. The value of border-width is given in pixels.

      It's also possible to also set the border-width property to one of the
      following named thicknesses:

        1. thin
        2. medium
        3. thick

>       p {
>         border-style: dashed;
>         border-width: 2px;
>       }

      the border-width property allows you to specify the width for each side of
      the border.

      The values in the example below refer to the border width in clockwise
      order (top: 3 pixels, right: 1 pixel, bottom: 2 pixels, left: 1 pixel).

>       p {
>         border-style: dashed;
>         border-width: 3px 1px 2px 1px;
>       }

      If you'd like to be even more specific about the width of different sides
      of the border, you can use the following properties:

      border-top-width
      border-right-width
      border-bottom-width
      border-left-width

      2.7.2 Border-color property

        The color of a border can also be customized with the border-color property.
        The border-color property accepts colors in various formats:
        Named colors, RGB(a) colors, and hex colors. It's common to use hex colors
        for borders, but you'll likely also come across RGB(a) colors as well.

>       p {
>         border-style: dashed;
>         border-width: 3px 1px 2px 1px;
>         border-color: #12AAF9;
>       }

      2.7.3 Border-radius property

        Thanks to CSS, a border doesn't have to be square.
        The corners of an element's border box can be modified with the border-radius property.

        The code in the example below will set all four corners of the border to
        a radius of 5 pixels (i.e. the same curvature that a circle with radius
        5 pixels would have).

>       p {
>         border: 3px solid rgb(22, 77, 100);
>         border-radius: 5px;
>       }

        You can create a border that is a perfect circle by setting the radius
        equal to the height of the box, or to 100%.

>       p {
>         border: 3px solid rgb(22, 77, 100);
>         border-radius: 100%;
>       }

  2.8 Shorthand Styling

    The shorthand way of setting border style, width, and color can be achieved
    with the border property.

    Note that the border property includes all of the properties that we previously
    styled individually: width, style, and color.

    It's considered best practice to follow the width-style-color order when using
    the border property.

>       p {
>         border-style: dashed;
>         border-width: 3px 1px 2px 1px;
>         border-color: #12AAF9;
>       }

>       p {
>         border: 3px solid rgb(22, 77, 100);
>       }

  2.9 Padding property

    The space between the contents of a box and the borders of a box is known as
    padding. In CSS, you can modify this space with the padding property.

    The code in the example will put 10 pixels of space between the content of
    the paragraph (the text) and the box borders, on all four sides.

    The padding property is particularly useful at making text easier to read when
    the text has a border around it.

    When padding is set for a box (as in the example above) it will be added to
    the width and height of a box, increasing the dimensions of the box.

>       p {
>         border: 3px solid #A2D3F4;
>         padding: 10px;
>       }

    padding can also be used for each corner seperately.

>       p {
>         border: 3px solid #A2D3F4;
>         padding: 10px 5px 9px 2px;/*Top, Right, Bottom, Left*/
>       }

    When you're certain that the top and bottom values for padding will equal
    each other, and that the left and right values for padding will also equal
    each other, you can use the following shortcut:

>       p {
>         border: 3px solid #A2D3F4;
>         padding: 10px 2px;
>       }

    If you want to be even more specific about the amount of padding on each side
    of a box's content, you can use the following properties:

      1. padding-top
      2. padding-right
      3. padding-bottom
      4. padding-left

  2.10 Margin property

    The margin refers to the space directly outside of the box. You can adjust
    this spacing with the margin property.

    The code in the example below will place 20 pixels of space on the outside of
    the paragraph's box, on all four sides. This means that other HTML elements
    on the page cannot come within 20 pixels of the paragraph.

>     p {
>       border: 3px solid #A2D3F4;
>       margin: 20px;
>     }

    Like all the other properties margin can also has a shorthand option to control
    each side seperately.
    The same shortcuts apply in all aspects.

      1. margin-top
      2. margin-right
      3. margin-bottom
      4. margin-left


>       p {
>         margin: 20px 10px 20px 10px;
>       }
>
>       p {
>         margin: 20px 10px;/*This is the same as the example above*/
>       }

    The margin property also lets you center content, if you follow certain
    requirements.

    In order to center an element, a width must be set for that element.
    Otherwise, the width of the div will be automatically set to the full width
    of its containing element, like the <body>, for example. It's not possible,
    therefore, to center an element that takes up the full width of the page.

  2.11 User Agent Stylesheets

    All major web browsers have a default stylesheet they use in the absence of an external stylesheet. These default stylesheets are known as user agent stylesheets. In this case, the term "user agent" is a technical term for the browser.

    User agent stylesheets often have default CSS rules that set default values for padding and margin. This affects how the browser displays HTML elements, which can make it difficult for a developer to design or style a web page.

    Many developers choose to reset these default values so that they can truly work with a clean slate.

>     p {
>       padding: 0;
>       margin: 0;
>     }

  2.12 Display property

    In CSS, you can change the default behavior of elements with the display
    property.

    Modifying the display property of an element can help achieve a desired layout
    for a web page. The display property can take on one of four values:

      1. inline - causes block-level elements (like a div) to behave like an inline
         element (like a link).

      2. block - causes inline elements (like a link) to behave like a block element
         (like a div).

      3. inline-block - causes block-level elements to behave like an inline element,
         but retain the features of a block-level element.

      4. none - removes an element from view. The rest of the web page will act as if
         the element does not exist.

  2.13 Visibility property.

    Elements can be hidden from view with the visibility property.

    The visibility property can be set to one of the following values:

      1. hidden - hides an element.
      2. visible - displays an element.

>     <ul>
>       <li>Explore</li>
>       <li>Connect</li>
>       <li class="future">Donate</li>
>     <ul>
>
>     .future {
>       visibility: hidden;
>     }

    Keep in mind, however, that users can still view the contents of the list item
    (e.g., Donate) by viewing the source code in their browser. Furthermore, the
    web page will only hide the contents of the element. It will still leave an
    empty space where the element is intended to display.

    Note: What's the difference between display: none and visibility: hidden? An
    element with display: none will be completely removed from the web page. An
    element with visibility: hidden, however, will not be visible on the web page,
    but the space reserved for it will.

  2.14 Box model

    The box model has an awkward limitation regarding box dimensions.
    This limitation is best illustrated with an example.

>     h1 {
>       border: 1px solid black;
>       height: 200px;
>       width: 300px;
>       padding: 10px;
>     }

    In the example above, a heading element's box has solid, black, 1 pixel thick borders. The height of the box is 200 pixels, while the width of the box is 300 pixels. A padding of 10 pixels has also been set on all four sides of the box's content.

    Unfortunately, under the current box model, the border thickness and the padding will affect the dimensions of the box.

    The 10 pixels of padding increases the height of the box to 220 pixels the width to 320 pixels. Next, the 1 pixel thick border increases the height to 221 pixels and the width to 321 pixels.

  ![Box Model](htmlcss1-diagram__contentbox.svg)
