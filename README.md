# Ex.06 Book Front Cover Page Design
## Date:27/9/2025
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
v.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #6e2553;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(87, 42, 99);
      border: 2px solid #0a68bb;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(43, 29, 51, 0.567);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #976cc6;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      color: #d08adb;
      text-align: center;
      font-style: italic;
    }

    .image {
      flex: 1;
      background: url('https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.livemint.com%2Fentertainment%2Fsolo-leveling-season-3-likely-set-to-release-in-2027-here-s-what-fans-can-expect-from-the-next-chapter-11757192595714.html&psig=AOvVaw1yv39iMMU1-xo-sWZFGT2z&ust=1759049137521000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCICS5O7G-I8DFQAAAAAdAAAAABAE') center/contain no-repeat;
      margin: 30px 0;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #bdbfcd;
      margin-top: 20px;
    }

    .line {
      height: 2px;
      background: #da92f0;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">Solo Leveling</div>
      <div class="line"></div>
      <div class="subtitle">Arise From The Shadows </div>
    </div>
    <div class="image">
        <img src="https://4kwallpapers.com/images/walls/thumbs_3t/17972.jpg" length="40%" width="100%">
    </div>
    <div class="author">By Chu gong</div>
  </div>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2025-09-27 144526.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
