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
<html>
<head>
    <title>CYBERSECURITY</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(mypic3.png);
            background-size: cover;
        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            
            top:280px;
            
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
            top:280px;
            
        }
        .pub{
            
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
        }
        .ed{
            
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
        
        }
        .subtitle{
            
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                SCOFT
            </div>
            
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>DEVELOPMENT OF CYBERSECURITY</h1></div>
            <div class="subtitle">
                 FUTURE OF TECHNOLOGY
            </div>
            <div class="subtitle">
                 Top seller of 2024
            </div>

            <div class="id">
                <hr style="color:rgb(248, 246, 246)">
            </div>
            <div class="author">
               <p><b>GUHANANDAN V(212221220014)</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:
![image](https://github.com/Guhanandan/cover/assets/100425381/93d80d9a-f62d-429d-9b96-20da03a7045d)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
