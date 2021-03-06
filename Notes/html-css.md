***********************
--- Just Some Notes ---
***********************

-----------------------
----- HTML + CSS ------
-----------------------

-> Browsers read CSS from top to bottom.

-> Padding vs Margin <-
    padding - controls the amount of space between the element and its border (On the inside).
    margin - controls the amount of space between an element's border and surrounding elements (On the outside).

-> Clockwise Notation <-
    Instead of specifying an element's padding-top, padding-right, 
    padding-bottom, and padding-left properties, 
    you can specify them all in one line.
    Ex: padding: 10px 20px 10px 20px;

-> Override CSS in the Same Element <-
    The second declaration will always take precedence over the first. 
    Because class2 is declared second, it overrides the attributes of class1.
    Ex: class="class1 class2"

    Override works in the following hierarchy: class < id < inline style < !important.
    So, in the following example the text will be white.
    Ex: <h2 id="orange-text" class="red-text blue-text" style="color: white">
            CatPhotoApp</h2>
    BUT...
    If in the CSS class red-text is like: .red-text {color: red !important;}, then the text will be red.
    Why override? For when a framework/Css library is being used and 
    you want to modify an element anyway.

-> Abbreviated Hex Code <- 
    The short form has only three digits: one digit for red, one digit for green, and one digit for blue.
    Ex: Red as #F00, Fuchsia as #F0F, Green	as #0F0 and Cyan as #0FF
