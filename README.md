# Ex.06 Book Front Cover Page Design
## Date:04-04-2024

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
    <title>Book Cover</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        background-color:white;
      }
  
      .book-cover {
        width: 500px;
        height: 700px;
        background-color:brown;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        margin: 50px auto;
        position: relative;
      }
      
      .book-cover .insight {
        position: absolute;
        top: 20px;
        left: 20px;
        font-size: 24px;
        font-weight: bold;
        color: azure;
      }
      .book-cover .line1
      {
        position: absolute;
        top: 40px;
        left: 10px;
        width: 80px;
      }
      .book-cover .title1 {
        position: absolute;
        top: 80px;
        left: 50px;
        font-size: 40px;
        font-weight: bold;
        color: red;
      }
      .book-cover .title2 {
        position: absolute;
        top: 130px;
        left: 30px;
        font-size: 40px;
        font-weight: bold;
        color:  grey;
      }
  
     
      .book-cover .subtitle2 {
        position: absolute;
        top: 500px;
        left: 20px;
        font-size: 16px;
        font-weight: bold;
        color: cyan;
      }
     
      .book-cover .line2
      {
        position: absolute;
        top: 480px;
        left: 20px;
        width: 160px;
      }
      .book-cover .line3
      {
        position: absolute;
        bottom:38px;
        left: 20px;
        width: 115px;
      }
  
  
      .book-cover .author {
        position: absolute;
        bottom: 25px;
        left: 20px;
        font-size: 18px;
        color: orange;
      }
  
      .book-cover .end {
        position: absolute;
        bottom: 5px;
        right: 50px;
        font-size: 18px;
        color:violet;
      }
      .book-cover .mypic
      {
        position: relative;
        top:550px;
        left: 370px;
        width : 8px;
        height: 8px;
        background-size:fit;
      }
  
  
      .book-cover .image {
        object-fit: cover;
        position: absolute;
        top:  220;
        left: 100;
      }
    </style>
  </head>
  
  <body>
    <div class="book-cover">
      <img src="./background.png" alt="Book Cover Image" class="image">
      <div class="insight">CODING</div>
      <div class="line1"><hr style="color:blanchedalmond"></div>
      <div class="title1">ZERO TO CODERS:</div>
      <div class="title2">THE COMPLETE REFRENCE</div>
      <div class="line2"><hr style="color:blanchedalmond"></div>
      <div class="subtitle2">WITH PYTHON AND C PROGRAM BASICS</div>
      <div class="line3"><hr style="color:blanchedalmond"></div>
      <div class="mypic"><img src="abhi.jpg"width="120" height="120" ></div>
      <div class="image"><img src="python logo.jpeg"width="250" height="265" ></div>
      <div class="end">CLASSMATE</div>
  
      <div class="author">K.ABHINESWAR REDDY</div>
  
    </div>
  </body>
  
  </html>
```

## OUTPUT:
![alt text](<BOOK COVER.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
