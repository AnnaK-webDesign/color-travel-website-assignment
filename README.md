# color-travel-website-assignment
<!DOCTYPE html>
<html>
<head>
    <style>
        /* style to set body of page */
        body {
            width: 100%;
            margin: auto;
        }
        .gallery {
            width: 100%;
            display: flex;
            flex-flow: row wrap;
        }
        .box {
            flex-basis: 20%;
            width: 100%;
            padding: 10px;
            margin: 8px;
            box-shadow: 1px 1px 1px 1px green;
        }
        .text {
            text-align: center;
            margin-top: 5px;
        }
        .image:hover {
            border: 3px solid green;
        }
        /* media query used here */
        @media only screen and (max-width: 300px) {
            .box {
                flex-basis: 100%;
            }
        }
        @media only screen and (max-width:500px) {
            .box {
                flex-basis: 40%;
            }
        }
    </style>
</head>
<body>
    <div class="gallery">
        <div class="box">
            <div class="image">
                <a target="_blank" href=
"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeek.pngLinks to an external site.">
                    <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeek.pngLinks to an external site."
                         width="300"
                         height="300">
                </a>
            </div>
            <div class="text">
                Geeks Classes Image
            </div>
        </div>
        <div class="box">
            <div class="image">
                <a target="_blank" href=
"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeeks-22.pngLinks to an external site.">
                    <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeeks-22.pngLinks to an external site."
                         width="300"
                         height="300">
                </a>
            </div>
            <div class="text">
                GeekforGeeks Image
            </div>
        </div>
        <div class="box">
            <div class="image">
                <a target="_blank"
                   href=
"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeeks-10.pngLinks to an external site.">
                    <img src=
"https://media.geeksforgeeks.org/wp-content/uploads/geeksforgeeks-10.pngLinks to an external site."
                         width="300"
                         height="300">
                </a>
            </div>
            <div class="text">
                Geeks Image
            </div>
        </div>
    </div>
</body>
</html>
