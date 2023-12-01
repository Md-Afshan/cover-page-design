# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a Django Admin Project.

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
Insert the images in their appropriate place.

### Step 8:
Publish the website in the localHost.
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
           color:cyan;
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           background-image: url(./background.jpg);
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
           color: pink;
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
       .pub{
           font-size: medium;
           position: relative;
           top:155px;
           left:330px;
       }
       .ed{
           color: pink;
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
               <hr style="color: cyan;">
           </div>
           <div class="booktitle">
               <h1>Fundamentals of Web Application Development</h1></div>
           <div class="subtitle">
               HTML and CSS Combined with Django Architecture
           </div>
           <div class="mypic">
               <img src="./myphoto.jpg" width="130" height="145" alt="">
           </div>
           <div class="id">
               <hr style="color: orange;">
           </div>
           <div class="author">
              <p><b>MUHAMMAD AFSHAN A</b></p>
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
![Alt text](bookcover.png)

## Result:
The program for designing book front cover page using HTML and CSS is completed successfully.
