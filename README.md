# Ex.06 Book Front Cover Page Design
## Date:30.11.2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <head>
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: darkkhaki;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                background-image: url("back.png");
                background-size: cover;
            }
            .insight{
                color: blue;

            }
            .hrstyle{
                width: 100px;
            }
            .author{
                display: inline;
                position: relative;
                color: blue;
                top: 190px;

                font-family: Georgia;
                font-size: medium;
            }
            .booktitle{
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;

            
            }
            .id{
                width: 400px;
                position: relative;
                top: 180px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top: 155px;
                left: 330px;
            }
            .ed{
                color: black;
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 85px;

            }
            .subtitle{
                font-family: 'Tahoma';
                font-size: large;
                position: relative;
                top: 40px;
            }
            .mypic{
                position: relative;
                top: 175px;
                left: 260px;
                width: 165px;
                height: 165px;
                background-size: cover;
            }
        </style>
        <title>Book Cover Page</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: yellow;">
            </div>
            <div class="booktitle">
                <h1>Date Analytics and Visualisation</h1>
            </div>
            <div class="subtitle">
                Concepts Explained With Solved Numericals 
            </div>
            <div class="mypic">
                <img src="My Photo.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>THARUN D</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>

    </body>
</html>
```

## OUTPUT:
![Screenshot (4)](https://github.com/THARUNDT/cover/assets/144871537/392ef6fe-61f9-478a-8705-07ff88842191)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
