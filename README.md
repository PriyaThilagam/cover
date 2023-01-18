# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:

Clone the Github repository and create a Django admin interface.

### Step 2:

Write HTML and CSS code for designing bac cover page and execute them.

## Code:

```
cover.html

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:hsl(24, 78%, 52%);
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back.jpg);
            background-size: cover;
        }
            

        .insight{
            color: yellow;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(248, 222, 244);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Garamond', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            color:burlywood;
        
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
            color: rgb(255, 80, 80);
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
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(80, 224, 217);">
            </div>
            <div class="booktitle">
                <h1><b>Fundamentals of Web Block Chain</b></h1></div>
            <div class="subtitle">
                
            </div>
            <div class="mypic">
                <img src="/static/images/pic.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(44, 15, 97);">
            </div>
            <div class="author">
               <p><b>Priyanka S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>

```

## Output:

![Output](./output.png)

## HTML Validator

![HTML Validator](./validate.png)

## Result:

The program for designing book cover page using HTML and CSS is executed successfully.
