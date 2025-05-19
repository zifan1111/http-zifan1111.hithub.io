<!DOCTYPE html>
<html>
<head>
    <title>HTML Review: April</title> <!-- The Title of the Tab / Window -->
    <style>
        /* CSS Comment Style:  Within the style tab, we are creating classes for styles */
        .center {text-align: center;} /* <center> center-align */
        
        .italics {font-style:italic;} /* <i> italics*/
        
        .colorful { /* Similar to the Style we made in W3D1 */
            background-color:darkgoldenrod; 
            font-family:Arial, Helvetica, sans-serif;
            font-weight:bold;
            color:crimson;
            padding: 15px;}

        .divStyle {
            background-color:cornsilk;
            color:darkgreen;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            padding: 5px;
        }

        .spanStyle {
            background-color: darkgreen;
            color: cornsilk;
            font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            padding: 10px;
        }

        .tab { /* Make a tab-space spacing for our nav bar */
            display: inline-block;
            margin-left: 40px; 
        } 

        h2 { /* This will affect all <h2> tags. Notice that there is no period before the class name */
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }

        
    </style>
</head>
<body> <!-- Semantic Tag (Doesn't do anything, just easier to distinguish parts of the page) -->

<div class = "center">
    <a href="directory.html">Lesson Directory</a>
    <span class="tab"></span>|<span class="tab"></span>
    <a href="about.html">About</a>
    <span class="tab"></span>|<span class="tab"></span>
    <a href="http://www.youtube.com" target=_blank>YouTube</a>
</div>

    <h2 class="center">Heading Tags</h2>  <!-- We called the class attribute to center-align the <h2> header -->
    <p>Heading Tags range from h1 to h6.</p>
    <h1>&#60;h1> Heading 1</h1> <!-- &#60; is the escape character for "<" so we can print the html tag without it turning into actual html -->
    <h2>&#60;h2> Heading 2</h2>
    <h3>&#60;h3> Heading 3</h3>
    <h4>&#60;h4> Heading 4</h4>
    <h5>&#60;h5> Heading 5</h5>
    <h6>&#60;h6> Heading 6</h6>
    <hr> <!-- Horizontal Bar -->

    <h2 class="center">Inserting Images: Size Not Explicitly Set</h2>
    &#60;img src = "<i>url</i>"><br><br>
    <img src="https://assets.surlatable.com/m/15a89c2d9c6c1345/72_dpi_webp-REC-283110_Pizza.jpg"><br><hr>

    <h2 class="center">Inserting Images: Size Explicitly Set (400 x 400)</h2>
    &#60;img src = "<i>url</i>" width = 400 height = 400><br><br>
    <img src="https://assets.surlatable.com/m/15a89c2d9c6c1345/72_dpi_webp-REC-283110_Pizza.jpg" width=400 height=400><br><hr>

    <h2 class="center">Inserting Links</h2>
    <a href = "http://www.google.com" target = _self>Google Link (Opens in this Tab)</a><br><br> <!-- target=_self : open the link in THIS browser space (tab) - DEFAULT action when not stated -->
    <a href = "http://www.google.com" target = _blank>Google Link (Opens in a New Tab)</a><br><hr> <!-- target=_blank : open the link in a BLANK browser space (new tab / new window) -->

    <h2 class="center">Playing with the &#60;style> Tag</h2><br>

    <p>Please look at the page source code so you can see how the &#60;style> tag works within the &#60;head> tag, and using the <span class="italics">class</span> attribute.</p> 

    <p class = "colorful"> Fancy Styles! </p><br><hr>

    <h2 class="center">&#60;div> & &#60;span> Elements</h2>
    
    <div class="divStyle">
        <p>The &#60;div> element is a <b>BLOCK ELEMENT</b>. This means that it affects text as a whole to whatever is inside. &#60;div> can also hold numerous other semantic block elements, such as &#60;p>.</p>
        <p>However, there is an equivalent <b>INLINE ELEMENT</b> that is similar to the &#60;div> tag. This is the <span class = "spanStyle">&#60;span> tag</span>.</p>
    </div>

</body>
</html>
