# CSS-Interview-Questions

Z-Index
=======
Helps to specifiy positioned element that may over lap with another <br>

auto- order equals to parent<br>
number - order the number specified<br>
initial - default - 0<br>
inherit - Inherits from parent<br>

External Vs Inline CSS or JS
============================
Inline CSS
- Hard to maintain
- Load slower
- No caching benefits

Box Model
=========
Border: Maximum area in which the element will be contained <br>
Padding: Spacing between the border and the element<br>
Margin: Spacing between the border and the neighbouring element<br>

Selectors
=========
<code> div,p</code> - selects all the div elements and the p elements <br>
<code> div p </code> - Descendent Selector - Selects all the p elements anywhere inside the div element <br>
<code> div>p </code> - Child Selector - Selects all the p elements whose immediate parent is div <br>
<code> div+p </code> - Selects all the p elements placed immediately after the div elements <br>
<code> div~p </code> - Selects all p elements anywhere preceeded by div elements <br>
<code> a[href^="https"] </code> - Selects every a element whose href attribute value begins with https <br>
<code> a[href$=".pdf"] </code> - Selects every a element whose href attribute value ends with .pdf <br>
<code> a[href*="css"] </code> - Selects every a element whose href attribute value contains the substring css <br>

Rule set
=======
Selector can be attached to another selector to be identified by ruleset.<br>
It has two part selector and declaration <br>
eg. p { text-indent: 11px; }

Difference between display:none and Visibility:hidden 
=====================================================
<strong>Display: none</strong> <br>
   Will hide the element and will not take any space of the element <br>
<strong>Visibility: hidden</strong> <br>
   Will hide the element, will take the space of the element and will affect the entire layout of the document <br>
   
Difference between inline and block elements
============================================
Block Elements:
- Will leave space before and after the element
- Uses full width available
- eg. div, h1
Inline Elements:
- Will take only the required width
- eg.  span,a

Line break using span
=====================
span style="display:block"

Rounded corners
===============
- Can be given using border radius
- Properties
  1. border-radius
  2. border-bottom-right-radius
  3. border-bottom-left-radius
  4. border-top-right-radius
  5. border-top-left-radius
  
New backgrounds in css3
=======================
- background-clip
- background-origin
- background-size

New Texts in css3
=================
- word-wrap
- word-break
- text-overflow

Opacity in css3
===============
- Used to hide or show an element
- value 0 to hide
- value 1 to show

pseudo-class
============
- Keyword added to the selector (pattern that mach against elements in tree)
- specifies a <strong> special state </strong> of the selected element
- Apply style to the element - not only in relation to the content of the document tree but also external factors like history (: visited), status of content (:checked) or position of the mouse (:hover)
- Can chain many pseudoclass together
```
button : hover {
  color : blue
}

p:first-child{
color:blue
}

p i:first-child{
color:blue
}

p:first-child i{
color:blue
}

selector : pseudo-class {
  property : value
}
```
- eg :link, :visited, :active ,:focus , :nth-child() , :last-child, :only-child

psudo-elements
==============

- keyword added to selector (pattern that mach against elements in tree)
- Style a <strong> specific part </strong> of the selected elements
```
p::first-line{
 color:blue
}
selector :: pseudo-element {
  property : value
}
```
 - Content related - ::after, ::before
 - Text related - ::first-letter, ::first-line


