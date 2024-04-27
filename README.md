# Ex.06 Book Front Cover Page Design
## Date:17-04-2024

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
    

    <title>Book Cover Design</title>
    <style> 
        .wrapper {
    
                height:100vh;
                display: flex;
                justify-content: center;
                align-items: center;
                background-image: url(12.jpeg);
                background-repeat: no-repeat;
                background-size: cover;
                margin: 0%;
            }
            
            .bookpage{
                width: 400px;
                height:750px;
                color: black;
                padding: 30px;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    
                background-image:url(13.jpeg)  ;
                background-size: cover;
                background-position: center;
            }
                
            
            .insight{
                color:rgb(253, 253, 150);
                letter-spacing: 1px;
                font-size: 10PX;
                text-align: center  ;
            
            }
    
        
            
            
            .hrstyle{
                width: 400px;
                
            }

            .booktitle{
                color:rgb(253, 253, 150);
                font-family: 'Courier', monospace;
                font-size:40px;
                text-align: center;
                letter-spacing: 10px;
                line-height: 30px;
                
    
    
            
            }

            .title{
                color:rgb(253, 253, 150);
                font-family: 'Courier', monospace;
                font-size:20px;
                text-align: center;
                letter-spacing: 10px;
                line-height: 30px;
                padding-top: 30px;
                
    
    
            
            }
            .id {
                width: 400px;
                position: relative;
                
            }
            .ed{
                color: rgb(28, 120, 120);
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 190px;
            
            }
            .subtitle{
                color:rgb(253, 253, 150);
                font-family:sans-serif;
                font-size: 30px;
                position: relative;
                top: 15px;
                text-align: center;
                line-height: 20PX;
            }
            .subtitle2{
                font-family: Arial, Helvetica, sans-serif;
                font-size: small;
                position: relative;
                text-align: center;
                line-height: 10PX;
               
                
            }
    
    </style>
</head>
    <body style="margin: 0%;">
        <div class="wrapper">
            <div class="bookpage">
                <div class="insight">
                    
                    <b>ECONOMIST,BOOK OF THE YEAR</b>
                </div>
                <div  style="position:var();" class="hrstyle">
                    <hr style="color:blanchedalmond">
                </div>
                <div class="booktitle">
                    <H3><B >THE</B></H3>
                    <h1><b>HUMAN</b></h1>
                    <H1><B>COSMOS</B></H1>
    
                </div>
                <div class="subtitle">
                     <H3><b> A SECRET HISTORY</b></H3>
                     <H3><b>OF STARS</b></H3>
                <div class="subtitle2" style="padding-top: 70px;">
                    <h5>"Marchant's vast and fascinating story packs in plenty </h5>
                    <h5>of human detail..... inspiring and persuasive"</h5>
                    <h4><b>GUARDIAN</b></h4>
                     
                
                </div>     
                </div> 
                <div class="title">
                    <h1><b>Jo Marchant </b></h1>
                    
                </div>
                <div class="subtitle2" style="padding-bottom: 90px;">
                    <h3 style="color:rgb(253, 253, 150) ;">The New York Times Bestselling Author of Cure</h3>
                </div>
                <div class="id">
                    <hr style="color:rgb(208, 205, 255)">
                </div>
            </div>
        </div>
    </body>
</body>
</html>
```

## OUTPUT:
![Screenshot 2024-04-27 114250](https://github.com/MohanramGunasekar/cover/assets/139841812/b10e6c68-5bb0-4747-9b36-4b341ef1d51c)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
