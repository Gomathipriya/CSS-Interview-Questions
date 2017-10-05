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

<code> div,p</code> - selects all the div elements and the p elements <br>
<code> div p </code> - Descendent Selector - Selects all the p elements anywhere inside the div element <br>
<code> div>p </code> - Child Selector - Selects all the p elements whose immediate parent is div <br>
<code> div+p </code> - Selects all the p elements placed immediately after the div elements <br>
<code> div~p </code> - Selects all p elements anywhere preceeded by div elements <br>
<code> a[href^="https"] </code> - Selects every a element whose href attribute value begins with https <br>
<code> a[href$=".pdf"] </code> - Selects every a element whose href attribute value ends with .pdf <br>
<code> a[href*="css"] </code> - Selects every a element whose href attribute value contains the substring css <br>




