# Ex.05 Book Front Cover Page Design
## Date:18/12/25

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
<html>
<head>
    <title>Book Cover</title>

    <style>
        body {
            background-color: #ecf5fa;
            font-family: Arial, sans-serif;
        }

        .cover {
            position: relative;
            width: 350px;
            height: 550px;
            margin: 40px auto;
            padding: 15px;
            box-shadow: 0 0 10px gray;
            background-image: url("c58d078a-856c-4aed-9ff9-0bf536e245f2.jpg");
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: white;
}


        .cover img {
            width: 100%;
            height: 220px;
        }

        .title {
            color:rgb(223, 251, 251);
            font-size: 24px;
            font-weight: bold;
            margin-top: 15px;
            text-align: center;
        }

        .subtitle {
            color:rgb(126, 225, 225);
            font-size: 16px;
            color: rgb(165, 156, 156);
            text-align: center;
            margin-top: 10px;
        }

        .synopsis {
            color:rgb(206, 241, 241);
            font-size: 15px;
            margin-top: 80px;
            text-align: left;
        }

        .author {
            color:rgb(249, 252, 252);
            position: absolute;
            bottom: 15px;
            right: 15px;
            font-size: 16px;
            font-weight: bold;
        }
    </style>
</head>

<body>

<div class="cover">
    <div id="image">
        <img src="image.png" alt="Book Image">
    </div>


    <div class="title">FUNDAMENTALS OF WEB DEVELOPMENT</div>
    <div class="subtitle">Concepts and Basics</div>


    <div class="synopsis">
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>Web Design</li>
        <li>Layout</li>
        <li>Styling</li>
        <li>Basics</li>
    </ul>
<div>
    <div class="author">R CHITHRA</div>
</div>

</body>
</body>
</html>
```

## OUTPUT:
![alt text](image.png)
![alt text](book.jpg)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
