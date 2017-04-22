***********************
--- Just Some Notes ---
***********************

-----------------------
----- Bootstrap ------
-----------------------

-> Browsers read CSS from top to bottom.

-> Responsive Design <-
    Bootstrap is responsible to know the size you are using your screen and it will automatically resize your HTML elements. This include mobile and tablet versions so when you use this framework you don't need to create another version of your website.

-> Containers <-
    Bootstrap needs to use a containing element to wrap the content and adjust its grid. 
    There are two container options: 
    1) Responsive fixed width container.
    Ex: <div class="container">...</div>
    2) Full width container, spanning the entire width of your viewport.
    Ex: <div class="container-fluid">...</div>

-> Images <-
    Using the img-responsive it's possible to adjust the image with the screen's width automatically. 

-> Block Elements <-
    When using a Block Element your element will fill your page's 100% width and any elements after it will got to another line below the block.

-> Grid System <-
    Bootstrap has a 12 column grid layout used to facilitate putting elements side by side and specify each width. An image example can be found on /images/bootstrap-grid-example.png
    Ex: <div class="row"> <div class="col-md-x">: md means medium and x is the number representing how many columns wide the element should be.
    Ex2: <div class="row"> <div class="col-xs-x">: xs means extra small.

-> Font Awesome <-
    Bootstrap uses font awesome so that icons can be treated as fonts. These icons are actually stored in .svg files so they are vector graphics. Before <i> elements were used only for italic. Now it can mean that "Here comes an icon!".
    The fa in the class means you are using font awesome and the name after, the icon you would like to use.
    Ex: <i class="fa fa-info-circle"></i>
    For more font awesome icons see http://fontawesome.bootstrapcheatsheets.com/
    Sometimes people still prefer using .svg files. For more info or just food for thought, 
    see http://ianfeather.co.uk/ten-reasons-we-switched-from-an-icon-font-to-svg/

-> Well <-
    This class is used to creat an aspect of depth for elements adding a gray background and a rounded border. It can be used as:
    1)<div class="well well-sm">Small Size Well</div>
    2)<div class="well well-lg">Large Size Well</div>
    3)<div class="well">Normal Size Well</div>