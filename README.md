# Ex.06 Book Front Cover Page Design
## Date:05/10/2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(255, 0, 13);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(WEB_06_spam2.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(221, 0, 255);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(255, 238, 0);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 20px;
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
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgb(0, 255, 60);
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
        .mypic{
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
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(0, 166, 255);">
            </div>
            <div class="booktitle">
                <h1>CODE GATEWAY FOR BEGINNERS</h1></div>
            <div class="subtitle">
                Development of bots into pro in coding is here
            </div>
            <div class="mypic">
                <img src="ME.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(255, 0, 217);">
            </div>
            <div class="author">
               <p><b>BY SHAKTHI KUMAR</b></p>
            </div>
            <div class="pub">
                OPEN >>>
            </div>
            <div class="ed">
                <b>Special Edition</b>
            </div>
        </div>
    </bodY>
</html>
```

## OUTPUT:
![Screenshot (251)](https://github.com/Shakthikumar22009242/cover/assets/120207509/26585bce-fdcb-4d8a-a825-3a4f23918766)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
