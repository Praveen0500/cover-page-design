# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

## Step 1:

Create a new Django project and app.
## Step 2:

Create a static file directory and mention the changes in settings.
## Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.
## Step 4:

Write down the code for book cover using HTML and CSS.
## Step 5:

Add images and other contents using CSS record a screenshot of it.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('https://th.bing.com/th/id/R.671f161d141466cdcf83db28cb0f3a9c?rik=chK%2bVFNfy9d5yQ&riu=http%3a%2f%2fwww.textronic.com%2fblog%2fwp-content%2fuploads%2f2017%2f10%2fJARVIS.png&ehk=ZeD47puFibIuEgnTFLJ0EvR0pvMX2F4jcL4rRn2y4EU%3d&risl=1&pid=ImgRaw&r=0');
            background-size: cover;
        }
        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:lightblue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
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
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
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
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="/static/images/hacker.jpg" height="130" width="145">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>NAVEEN M</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## Output:

![LAB06 1](https://github.com/Praveen0500/cover-page-design/assets/120218611/0fcf1d69-f82c-4c86-8f83-63fe8ce50c56)
![lab06 2](https://github.com/Praveen0500/cover-page-design/assets/120218611/eb5bd2f1-8253-4c8c-8af5-e384bc5a0fdb)


## Result:
Successfully designed a website to display the cover page of the book Responsive Web Design with HTML5 and CSS
