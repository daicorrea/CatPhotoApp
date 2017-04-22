***********************
--- Just Some Notes ---
***********************

-----------------------
----- JQuery ------
-----------------------

-> Document Ready <-
    Function that starts running after the page is loaded. If it's not used and the code runs before the page is ready, it can cause bugs. 
    Ex: $(document).ready(function() {});

-> .addClass() <-
    Adds classes to elements.

-> .removeClass() <-
    Removes classes to elements.

-> .css <-
    Changes the css of an element.
    Ex: ("#id").css("color", "red");

-> .prop() <-
    Changes a propertie of an element.
    Ex: $("button").prop("disabled", true);

-> .html() <-
    Makes possible to add HTML tags and text within an element.

-> .text() <-
    Changes only the text, doesn't add tags.

-> .remove() <- 
    Removes element from the page.
    Ex: $("#id").remove();

-> Moving Objects <-
    Ex: $("#id").appendTo("#some-container");
    Moves the object id to some-container.

-> .clone() <-
    Copies elements from one place to another.
    Ex: $("#id").clone().appendTo("#right-container");

-> Function Chaining <-
    Sticking two jQuery functions together.

-> .parent() <-
    Allows you to access an element's parent.
    Ex: $("#id").parent().css("background-color", "red");

-> .children() <-
    Allows you to access an element's children.
    Ex: $("#id").children().css("color", "red");

-> Target a Specific Child <-
    Using target:nth-child(n) where n is the position, you can target the nth children of the element.
    Ex: $(".id:nth-child(3)").addClass("animated bounce");
    It will bounce the 3rd child of the element id.

