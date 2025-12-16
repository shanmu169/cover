# Ex.05 Book Cover Page Design
## Date:15-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html
<html>
    <head>
        <title>BOOK COVER DESIGN</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">
            <br>
            <br>
            <h2><b>ABOUT THE BOOK </b></h2>
            <hr>
            <br>
            <p class="content"><font size="3">This book <span class="highlight"> "Computer Graphics"</span> explores the core concepts of computer graphics and explains how images, animations, and 3D scenes are created using mathematical and programming techniques, blending theory with practical implementation through OpenGL, a powerful graphics API widely used in real-time rendering. It shows how basic shapes are generated, how objects are transformed in space, how light and shading create realism, and how viewing and projection techniques help form complete scenes. By connecting geometric principles with hands-on OpenGL examples, the book helps readers understand everything from simple 2D drawings to complex 3D models, animated motion, textured surfaces, and interactive graphics applications, all forming a solid foundation for further study in visualization, game development, virtual reality, and modern graphics programming.</font></p>
        
            <div class="quotes">
                <br>
                <br>
                <p><font size="3"><i>"Computer graphics transforms mathematics into visuals, turning imagination into images and bringing digital worlds to life through code." </i></font></p>

            </div>
            <div class="item">
                <img src="img.png.jpg">
                <div class="author">
                    <h3>K.Shanmuga priya(25004352)</h3>
                    <p class="words">K.Shanmuga priya is a student in saveetha engineering college studying 1st year CSE department and writer of this book</p>
                </div>
            </div>
            <div class="footer">
               
                <p class="PUBLISHERS">SEC PUBLISHERS</p>
                <p class="print">PRINTED IN INDIA</p>
                
                <p class="price">price:Rs.500</p>
                
            </div>
        </div>
        
    </body>
</html>

style.css
.container
{
 background-image: url('img 44.jpg');
 height:800px;
 width:800px;
 margin: 30px;
 padding:20px;
 border-radius: 10px;
 border:3px solid;
}
hr{
    border:1px solid;
    color: black;
}
.highlight
{
background-color: chocolate;
}
.content
{
    padding: 15px;
}
.quotes
{
margin-top: 20px;
margin-left: 10px;
padding: 10px;
padding-left: 11px;
border-left: 5px solid rgb(0, 0, 75);
display: flex;
background-color: bisque;
}
.item
{
display: flex; 
margin-top: 20px;
background-color: rgb(173, 247, 186);
padding: 10px;
}
.item img
{
    width:95px;
    height:95px;
}
.words
{
    padding-left: 20px;
    
}
.author h3
{
    color: blueviolet;
    padding-left: 20px;   
}
.footer
{
    margin-top: 150px;
    display: flex;
    background-color: indianred;
    color:white;
    padding:5px;
    justify-content: space-between;
    border-radius: 5px;
    text-align: left;
}


.PUBLISHERS
{
    color: rgb(223, 175, 20);
    text-align: left;
}
.print
{
    
}

.price
{
    color: rgb(223, 175, 20);
}
```

## OUTPUT:
![alt text](<Screenshot (38).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
