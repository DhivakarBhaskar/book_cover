# Ex.06 Book Front Cover Page Design
# Date:6/10/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
    <head>
        <link rel="stylesheet" href="book.css">
    </head>
    <body>
<div class="box">
    <pre id="b1">
      THE
     COWARD  HERO
</pre>
<h2 id="b2"> A tale of courage</h2>
<h3 id="b3">Special Edition </h3>
<h5 id="b4">A reluctant man must overcome his deepest fears to become an unexpected hero who shows true courage in the face of danger.</h5>
<img id="i" src="C:\Users\Dhivakar\OneDrive\Pictures\Screenshots\Screenshot 2025-10-03 214243.png" alt="Book Cover">
<h4 id="b5">By Dhivakar</h4>
</div>
    </body>
</html>

.box
{
    height:85%;
    width:35%;
    border:2px solid black;
    margin:auto;
    margin-top:50px;
    border-radius: 8px;
    box-shadow:5px 5px 5px 5px grey;
   position:relative;
   background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80');
   background-repeat: no-repeat;
    background-size: cover;
    letter-spacing: 0.2em;
}
#b1
{
    text-align:center;
    font-family: 'Times New Roman', 'Times, serif';
    font-size:45px;
    color:white;
    position:absolute;
    font-weight:bold;
}
#b2
{
    font-style:italic;
    text-align:center;
    top:200px;
    position: absolute;
    color:white;
    width:100%;
    font-size: 30px;
}
#b3
{
    text-align:center;
    position:absolute;
    color:white;
    width:100%;
    font-size:25px;
    font-weight:bold;
    font-family:Times, serif;
    top:540px;
}
#b4
{
    text-align:center;
    position:absolute;
    color:white;
    width:100%;
    font-size:20px;
    font-family: Arial, Helvetica, sans-serif;
    top:320px;
    letter-spacing: 0.1em;
}
#b5
{
    text-align:center;
    position:absolute;
    color:white;
    width:100%;
    font-size:20px;
    font-weight:bold;
    font-family: Times New Roman;
    bottom:30px;
    letter-spacing: 0.4em;
}
#i
{
    width:100px;
    height:100px;
    position:absolute;
    top:450px;
    left:220px;
    border-radius: 5px;
}
```
# OUTPUT:
![alt text](<Screenshot 2025-10-05 125958.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
