# Ex.06 Book Front Cover Page Design
# Date:03/10/2025
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
book.html

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover - Fundamentals of Web Application Development</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: linear-gradient(180deg, #8358af, #d24178, #ffe066);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: url("web image 1245.jpg") no-repeat center center / cover;
      /* ✅ Fixed typo: 'no-repat' → 'no-repeat' and proper background-size syntax */
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.4);
      border-radius: 12px;
      border: 4px solid #fff;
      position: relative;
      padding: 30px 25px;
      color: white;
      text-align: center;
      backdrop-filter: brightness(0.9);
    }

    .book-header {
      font-size: 16px;
      letter-spacing: 2px;
      text-transform: uppercase;
      border-bottom: 2px solid white;
      display: inline-block;
      padding-bottom: 5px;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.4);
    }

    h1 {
      font-size: 24px;
      margin-top: 40px;
      font-weight: bold;
      line-height: 1.4;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
    }

    .subtitle {
      font-size: 14px;
      margin-top: 10px;
      font-style: italic;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.4);
    }

    .tagline {
      font-size: 12px;
      margin-top: 5px;
      color: #fffae6;
    }

    .author-section {
      position: absolute;
      bottom: 80px;
      left: 0;
      width: 100%;
    }

    .photo {
      width: 90px;
      height: 90px;
      border: 3px solid #fff;
      border-radius: 10px;
      object-fit: cover;
      margin-top: 10px;
      box-shadow: 2px 2px 8px rgba(0,0,0,0.5);
    }

    .special {
      font-size: 14px;
      color: #fff;
      font-weight: bold;
      margin-top: 15px;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.4);
    }

    .author {
      margin-top: 5px;
      font-weight: bold;
      font-size: 15px;
      color: #fffbd8;
    }

    .footer {
  position: absolute;
  bottom: 15px;        /* keeps it at the bottom */
  width: 100%;         /* full width to center properly */
  text-align: center;  /* centers SEC horizontally */
  font-weight: bold;
  letter-spacing: 2px;
  text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
  font-size: 18px;
}

  </style>
</head>
<body>

  <div class="book-cover">
    <div class="book-header">SEC INSIGHTS</div>
    <h1>FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT</h1>
    <div class="subtitle">Deep Dive into HTML, CSS & JS</div>
    <div class="tagline">Top Seller of 2025</div>

    <div class="author-section">
      <img src="Screenshots/me.jpg" alt="Author Photo" class="photo">
      <div class="special">SPECIAL EDITION</div>
      <div class="author">MAHA LAKSHMI M (25015887)</div>
    </div>

<<div class="footer">SEC</div>
  </div> <!-- book-cover -->

</body>
</html>
```
# OUTPUT:
![output](<Screenshot (16).png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
