# Ex.06 Book Front Cover Page Design
## Date:12.04.2024

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
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>

       .bookpage{
           width: 400px;
           height: 600px;
           color:rgb(5, 3, 3);
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           background-image: url(./background.jpeg);
           background-size: cover;
       }
           

       .insight{
           color: rgb(245, 183, 135);

       }

       
       .hrstyle{
           width:100px;
       }
       .author{
       
           display: inline;
           position: relative;
           color: rgb(35, 247, 7);
           top:190px;
           
           font-family:'Times New Roman', Times, serif;
           font-size: medium;
       }
       .booktitle{
           font-family: Verdana, Geneva, Tahoma, sans-serif;
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
       .ed{
           color: rgb(204, 37, 129);
           font-size: medium;
           font-family: Verdana;
           position:relative;
           top:85px;

       }
       .subtitle{
           color:rgb(244, 8, 8);
           font-family:Verdana;
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
               <h2>Blockchain And it's Technologies</h2></div>
           <div class="subtitle">
            Polishing Minds Of Gen Z
           </div>
           <div class="mypic">
               <img src="Screenshot_2022-01-22-17-02-46-63.jpg" width="125" height="150" alt="">
           </div>
           <div class="id">
               <hr style="color: rgb(246, 245, 249);">
           </div>
           <div class="author">
              <p><b>Charitha Kamireddy(212221040068)</b></p>
           </div>
           <div class="ed">
               <b>Second Edition</b>
           </div>
       </div>
   </body>
</html>
```


## OUTPUT:
![19e23cd9-fd6e-4871-baa6-2045fc31751e](https://github.com/swethasurendar/cover/assets/133625914/132e2954-6023-4e5f-b72d-a704a058e001)
![image](https://github.com/swethasurendar/cover/assets/133625914/bf3e5233-64f1-4415-a909-f6ca5fc4f27f)




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
