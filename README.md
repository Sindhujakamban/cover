# Ex.06 Book Front Cover Page Design
## Date: 12-12-24

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
    <title>Book cover </title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image:url("https://png.pngtree.com/thumb_back/fh260/background/20210917/pngtree-blue-bubble-effect-background-with-golden-stripes-book-cover-page-poster-image_902262.png");
            background-size: cover;
        }
          
        
        .insight{
            color:whitesmoke;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
            position: relative;
            color:white;
            top:170px;
            font-size: medium;
            font-family: 'Times New Roman', Times, serif;
            text-align: left;
          
        }
        .booktitle{
            color:whitesmoke;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:whitesmoke;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:azure;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:whitesmoke;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                LIFE
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1 style="font-family: cursive; color:wheat;">POWER OF YOUR SUBCONSCIOUS MIND</h1></div>
            <div class="subtitle" style="text-align: center;color: beige;">
                 Unlock your master
            </div>
            <div class="subtitle" style="color: rgb(193, 172, 133);text-align: center;">
                 Top seller of 2024
            </div>

            <div class="mypic">
                <img src="myphoto.jpg"width="120" height="120" >
            </div>
             <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>SINDHUJA K</b></p>
            </div>
            <div class="pub">
              
            </div>
            <div class="ed">
                <b></b>
            </div>
        </div>
        </body>
        

</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-12-12 105203.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
