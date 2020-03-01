# bryan-villafuerte-js-frameworks-ma-1-level-2

Simple Image Slider

How to use:
1. Load the necessary jQuery library in the document.

<!doctype html>
<html>
    <head>
        <!-- Place your kit's code here -->
        <script src="node_modules/jquery/dist/jquery.min.js"></script>
        <script src="js/image-slider.js" crossorigin="anonymous"></script>
    </head>
    <body>
        <!-- Add the markup in here -->
    </body>
</html>


2. Write the markup for the image slider as written in the example below. Remember to add the appropriate class and id attributes.

<div id="slider">
    <a href="#" class="control_next"><i class="fas fa-chevron-circle-right"></i></a>
    <a href="#" class="control_prev"><i class="fas fa-chevron-circle-left"></i></a>
    <ul>
        <li id="image01"></li>
        <li id="image02"></li>
        <li id="image03"></li>
        <li id="image04"></li>
    </ul>  
</div>
    
<div class="slider_option">
    <input type="checkbox" id="checkbox">
    <label for="checkbox">Autoplay Slider</label>
</div>

3. Apply the stylesheet as well to your markup.

<!doctype html>
<html>
    <head>
        <!-- Place your kit's code here -->
        <script src="node_modules/jquery/dist/jquery.min.js"></script>
        <script src="js/image-slider.js" crossorigin="anonymous"></script>
        <!-- Add the CSS file from the CSS folder -->
        <link rel="stylesheet" href="css/styles.css">
    </head>
    <body>
        <!-- Add the markup in here -->
    </body>
</html>