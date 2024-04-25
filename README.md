# Ex.06 Book Front Cover Page Design
## Date:25-04-2024

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
<meta charset="UTF-8" name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    .bookpage {
        width: 400px;
        height: 600px;
        color: white;
        margin-left: auto;
        margin-right: auto;
        padding: 20px;

        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-color: rgb(42, 165, 63);
        background-size: cover;
    }

    .insight {
        color: pink;
        text-align: left;
    }

    .hrstyle {
        width: 100px;

    }

    .author {
        display: inline;
        position: relative;
        color: white;
        top: 200px;
        text-align: left;
        font-family: Georgia;
        font-size: medium;
    }

    .booktitle {
        font-family: 'Courier New', Courier, monospace;
        font-size: medium;
        text-align: center;
        position: relative;
        top: 30px;
        color: rgb(253, 253, 250);

    }

    .id {
        width: 400px;
        position: relative;
        top: 200px;
    }

    .pub {
        font-size: medium;
        position: relative;
        text-align: left;
        top: 170px;
        left: 330px;

    }

    .ed {
        color: rgb(166, 43, 61);
        font-size: medium;
        font-family: Verdana;
        position: relative;
        text-align: left;
        top: 95px;
    }

    .subtitle {
        font-family: Tahoma;
        font-size: large;
        position: relative;
        text-align: left;
        top: 40px;
        color: rgb(143, 44, 44);
    }

    .mypic {
        position: relative;
        top: 135px;
        left: 260px;
        width: 100px;
        height: 100px;
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
            <h1>FRONTEND DEVELOPMENT </h1>
        </div>
        <div class="subtitle">
            <b>complete guide to become a frontend developer</b>
        </div>
        <div class="mypic">
            <img src="23014240 Gowshik IT .png" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: lightgreen;">
        </div>
        <div class="author">
            <p><b> GOWSHIK S</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Extended edition</b>
        </div>
</body>

</html>
```

## OUTPUT:
![Screenshot 2024-04-25 191127](https://github.com/gowshik145/cover/assets/155086127/cc07efae-af1d-462e-81be-f15c17f7d1d8)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
