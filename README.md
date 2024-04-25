# Ex.06 Book Front Cover Page Design
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .img{
        background-image: url(book.jpg); 
        background-repeat: no-repeat;
        margin-left: 10%;
        margin-right: 10%;
        background-position: center;         
        width: 80;
        height:100vh;
        opacity: 0.6;
    }
    .head{
        position: absolute; 
        top: 12%; 
        left: 50%; 
        transform: translate(-50%, -50%); 
        font-family: Arial, sans-serif; 
        font-size: 22px; 
        text-align: center;
    }
    .title{
        position: absolute; 
        top: 30%; 
        left: 50%; 
        transform: translate(-20%, -40%); 
        font-family: Arial, sans-serif; 
        font-size: 50px; 
        text-align:right;
    }
    .base{
        position: absolute; 
        top:90%;
        left: 50%; 
        transform: translate(-50%, -50%); 
        font-family: Arial, sans-serif; 
        font-size: 20px; 
        text-align:center;    
    }
    .author{
        position: absolute;
        top: 58%;
        left: 58%;
        border-radius:50%;
    }
    
</style>
<body>
    <div class="bookpage">
        <div class="img"></div>
    <div class="head">
    <h3>POSTERMYWALL<br>PUBLISHING</h3>
    </div>
    <div class="title">
    <h1>THE <br> NEW<br> WORLD<br></h1>
    </div>
    <div class="base">
    <h3>"IT ALL STARTED WITH A SIMPLE FLU"</h3>
    <h4>A book by Julius Kaesar</h4>
    </div>
    <div class="author">
        <img src="21500136.jpeg" width="130">
    </div>
    </div>
    
</body>
</html>
```
## OUTPUT:
![Screenshot 2024-04-25 213454](https://github.com/pradeepasri26/cover/assets/131433142/fd5fccde-d696-44e7-bc19-b011afc2cbb3)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
