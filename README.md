# Ex.06 Book Front Cover Page Design

## Date:14.10.2025

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

` ` `

<!DOCTYPE html>
<html>
<head>
    <title>Book Cover Layout</title>
</head>
<style>
.book-cover-container {
    position: relative;
    width: 400px;
    margin: 0 auto; 
}
.title {
  position: absolute;
  top: 30%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
  font-size: 28px;
  font-weight: bold;
  text-align: center;
  line-height: 1.3;
}

/_ Subtitle text _/
.subtitle {
position: absolute;
top: 55%;
left: 50%;
transform: translate(-50%, -50%);
color: white;
font-size: 16px;
text-align: center;
}

/_ Bottom text (special edition, name, etc.) _/
.bottom-left {
position: absolute;
bottom: 10%;
left: 5%;
color: white;
font-size: 18px;
font-weight: bold;
}

.bottom-right {
position: absolute;
bottom: 10%;
right: 5%;
color: white;
font-size: 18px;
}

.main-cover {
width: 100%;
height: 200%;
display: block;
}

.photo-box {
position: absolute;
bottom: 5%;
right: 5%;

    width: 100px;
    height: 120px;
    background-color: white;
    padding: 5px;
    box-sizing: content-box;
    border: 1px solid #ccc;

}

.author-photo {
width: 100%;
height: 100%;
object-fit: cover;
display: block;
}
</style>

<body>
    <div class="book-cover-container">
         <div class="title">
    FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT
  </div>

  <div class="subtitle">
    Deep Dive in HTML, CSS & JS Basics<br>
    Top seller of 2025
  </div>

  <div class="bottom-left">SPECIAL EDITION<br>P. Mageshwaran</div>
  <div class="bottom-right">SEC</div>

        <img src="plain background img.jpg" alt="Fundamentals of Web Application Development Book Cover" class="main-cover">

        <div class="photo-box">
            <img src="pic.jpg" alt="Author Photo" class="author-photo">
        </div>
    </div>

</body>
</html>
` ` `

## OUTPUT:

![alt text](<Screenshot (35).png>)

## RESULT:

The program for designing book front cover page using HTML and CSS is completed successfully.
