# Ex.06 Book Front Cover Page Design
## Date:24.05.2025

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
    <title>Army's Universe - Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f3f3f3;
        }

        .book-cover {
            width: 400px;
            height: 600px;
            margin: 50px auto;
            background: linear-gradient(135deg, #a64ca6, #e0b3ff);
            color: white;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            position: relative;
            padding: 30px 20px;
        }

        .title {
            font-size: 36px;
            font-weight: bold;
            text-align: center;
            margin-top: 60px;
        }

        .tagline {
            font-size: 18px;
            font-style: italic;
            text-align: center;
            margin: 20px 0;
            color: #ffe6ff;
        }

        .content {
            font-size: 16px;
            text-align: justify;
            margin: 40px 20px;
            color: #f5e6ff;
        }

        .author {
            position: absolute;
            bottom: 30px;
            right: 30px;
            font-size: 20px;
            font-weight: bold;
            color: #fff3f3;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="title">Army's Universe</div>
        <div class="tagline">"Seven voices, one ARMY, infinite love."</div>
        <div class="content">
            Dive into the world where music heals, love unites, and BTS and ARMY share an unbreakable bond. This book celebrates the magic of seven artists and the global fandom that stands by them.
        </div>
        <div class="author">By Janani</div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (50).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
