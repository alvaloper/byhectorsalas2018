/**
*** least.
*** Author: Kamil Czujowski, Sergej Müller
*** Version: 1.1
*** Made in ♥ - Copyright (c) 2013 Hamburg, Germany - All rights reserved.
*** https://twitter.com/kamilczujowski, http://wpcoder.de
**/

least.js is a Random & Responsive HTML 5, CSS3 Gallery with LazyLoad

Demo: http://kamilczujowski.github.io/least/

##### How to install: #####

1. Download least.js (http://kamilczujowski.github.io/least/least.zip) or view the Code on GitHub (https://github.com/kamilczujowski/least).

2. Insert the following code before end of </head>-tag.

<!-- least.js CSS-file -->
<link href="css/least.min.css" rel="stylesheet" />
<!-- jQuery libary -->
<script src="http://code.jquery.com/jquery-latest.js" defer="defer"></script>
<!-- least.js JS-file -->
<script src="js/least.min.js" defer="defer"></script>
<!-- Lazyload JS-file -->
<script src="js/jquery.lazyload.js" defer="defer"></script>

3. Insert the following code right after the <body>-tag.

<section>
    <ul id="gallery">
        <li id="fullPreview"></li>

        <li>
            <a href="img/full/full_1.jpg"></a>
            <img data-original="img/thumb/thumb_1.jpg" src="img/effects/white.gif" width="240" height="150" alt="Ocean" />

            <div class="overLayer"></div>
            <div class="infoLayer">
                <ul>
                    <li>
                        <h2>
                            Ocean
                        </h2>
                    </li>
                    <li>
                        <p>
                            View Picture
                        </p>
                    </li>
                </ul>
            </div>

            <div class="projectInfo">
                <strong>
                    Monday, 14th April 2093:
                </strong> sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
            </div>
        </li>
    </ul>
</section>

##### done #####
