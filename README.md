# Ex.07 Restaurant Website
## Date:13.12.2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
web.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web app</title>
    <link rel="stylesheet" href="web.css">
</head>
<body>
    <div align="center" id="template">

        <img src="bghme.png" alt="" id="bg">
        <a href="subway.html" id="tag" >About us</a>
        <a href="onlineorder.html" id="order">  Online order </a>
        <a href="contact.html" id="contact">Contact information</a>

    </div>
    <h1>SUBWAY Restaurant</h1>
    <footer align="center" id="copywrite">
        Designed and devloped by Harisudhan &copy 2024
    </footer>
</body>
</html>
```
```
web.css

*{
    margin: 0px;
    padding: 0px;
}

#template
{
    align-items: center;
    width: 100%;
    object-fit: cover;
    /* height: 800px; */
}
#tag
{
    position: absolute;
    top:40px;
    left: 280px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    color: orange;
    text-transform: capitalize;
    font-size: 40px;
    
}
#order
{
    position: absolute;
    top:50px;
    left: 540px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px;
}
#contact
{
    position: absolute;
    top:50px;
    left: 800px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px; 
}
```
```
subway.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SUBWAY</title>
    <style>
        pre{
            padding: 15px;
            font-size: large;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            
        }
       #order
        {
                display: inline;
                margin-left: 10px;
                color: rgb(27, 29, 30);
                align-items: center;
                font-size: 50px;
        }
        #h1
        {
            text-align: center;
            font-style: oblique;
            margin-top: 10px;
            padding: 25px;
            position: relative;
            top: 50px;
            left: 0px;
            background-color: rgb(250, 252, 251);
        }
        body
        {
            background-color: rgba(238, 207, 212,0.3);
        }
        .About{
            font-size: 25px;
             font-style: italic;
        }
    </style>
</head>
<body >
    
    <h1 id="h1">Subway Restaurant
    </h1>
    <pre>
        
<center>
<b>Welcome to subway foods</b>
</center>
<center>
<p class="About">subway is a farm to fork Indian chain of quick service (QSR) & family restaurants serving fresh and hygienic veg & non-veg fast food,<br> options to customers. Started in 2013, fine-tuned the operations in the areas of products, delivery, restaurant layout, franchisee model,<br>advertising & marketing strategy etc., within 6 months, hence being able to bring consistency across all franchises.<br></p>

<b><a href="onlineorder.html" id="order" target="_blank"> Order Now</a></b>
</center>
</pre>

</body>
</html>
```
```
onlineorder.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>order now</title>
    <style>
        body{
            background-color: rgba(249, 249, 248, 0.733);
        }
        #body
        {
            border: 5px solid black;
           color: black;
           background-color:rgb(241, 240, 236);
            border-radius: 25px;
            height: 800px;
        }
         img
        {
                margin-top: 100px;
                height: 200px;
                width: auto;
                margin-left: 25px;

        } 
        #fish
        {
            height: 200px;
            width: 300px;
        }
        .dish
        {
           margin-left: 240px;
        }
        #dish1
        {
            margin-left: 280px;
        }
        #dish2
        {
            margin-left: 150px;
        }
        p{
            margin-top: 75px;
            margin-left: 250px;
            font-size: 25px;
        }
        
            </style>
</head>
<body>
    <div id="body">
    <h1 align="center" style="text-decoration: underline wavy blueviolet;">Order for best and quality foods from our subway restaurant!</h1>
    <div class="menu">
        <img src="biriyani.jpeg" alt="biriyani">
        
        <img src="chicken.jpg" alt="grill">
        <img id ="fish" src="fishfry-3.jpg" alt="">
        <img src="noodles.jpg" alt="noodles">
        <img src="parotta.jpg" alt="parotta">
        <img src="dish.jpg">
        <img src="dishh.jpg"
        <p > - </p>
    </div>
    </div>
</body>
</html>
```
```
administration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administraion</title>
    <style>
        body
        {
            background-color:rgb(252, 253, 253);
        }
        #container
        {
            background-color: rgb(255, 254, 254);
            display: flex;
            height: 1000px;
            width: auto;
            justify-content: space-evenly;
            border-radius: 5px;
        }
        #main
        {
            border: 1px solid black;
        }
        .box
        {
            position: relative;
            display: inline-block;
            top: 150px;
            height: 200px;
            width: 200px;
            border: 2px solid black;
            background-color: pink;
            border-radius: 50%;
        }
        #head
        {
            text-align: center;
            font-size: 40px;
            font-family: 'Times New Roman', Times, serif;
            font-weight: 700;
            background-size:cover ;
        }
        #name
        {
            justify-content: space-evenly;
        }
        #n1
        {
            position: absolute;
            bottom: 170px;
            left: 100px;
            font-weight: 600;
            font-size: large;
            font-style: inherit;
        }
        #n2
        {
            position: absolute;
            bottom: 170px;
            left: 330px;
            font-weight: 600;
            font-size: large;
            font-style: inherit;
        }
        #n3
        {
            position: absolute;
            bottom: 170px;
            left: 570px;
            font-weight: 600;
            font-size: large;
            font-style: inherit;
        }
        #n4
        {
            position: absolute;
            bottom: 170px;
            left: 800px;
            font-weight: 600;
            font-size: large;
            font-style: inherit;
        }
        #n5
        {
            position: absolute;
            bottom: 170px;
            left: 1020px;
            font-weight: 700;
            font-size: large;
            font-style: inherit;
        }
    </style>
    
</head>
<body>
    <div align="center" id="head">PROFESSIONAL CHEFS</div>
    <div id="container">

            <div ><img src="chef 1.webp" alt="" class="box"></div>
            <div ><img src="chef 2.jpeg" alt="" class="box"></div>
            <div ><img src="chef 3.png" alt="" class="box"></div>
            <div ><img src="chef 4.avif" alt="" class="box"></div>
            <div ><img src="chef 5.avif" class="box"></div>

    </div>
    <p id="n1">STAN RIO</p>
        <p id="n2">KAMARAJ</p>
        <p id="n3">NANCY</p>
        <p id="n4">STEFFY</p>  
        <p id="n5">JOHN WIKS</p>
</body>
</html>
```
```
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">  
    <style>
      *{
        font-family: Arial, Helvetica, sans-serif;
      }
        #contact
        {
            
          background-image: url(bg\ for\ last\ page.jpg);
          background-size: cover;
            display: flex;
            font-size: 30px;
            gap: 10px;
            background-color:	rgba(250, 235, 215,0.2);
            border: 1px inset black;
            height: 800px;
        }
        #contact>div{
            width: 30%;
            /* border: 5px solid pink; */
            padding: 50px;
        }
        #div1
        {
            position: absolute;
            top:40px;
            right: 100px;
            border:1px inset whitesmoke;
            background-color: whitesmoke;
            border-radius: 50px;
        }
        input{
            font-size: 25px;
            margin-left: 30px;
        }
        #textarea
        {
          margin-left: 25px;
          padding: 20px;
          border: #FFFFFF;
          padding: 10px;
          border-radius: 10px;
          font-size: 20px;
        }

        #submit
        {
          background-color: #FF5200;
          border-radius: 10px;
          color: whitesmoke;
        }
        #label2
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;

        }
        #label1
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;
        }
        #info
        {
          padding: 2opx;
        }
        .h3
        {
            position: relative;
            left: 450px;
        }

    </style>
    <script>
            function f1()
            {
                document.getElementById("label3").innerHTML="Informations are saved";
            }
    </script>
    
</head>
<body>
    <div id="contact">
           <div id="info">
            <br><br><br><br>
              <b class="h3" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif ; font-size: 50px;"> Subway Restaurant</b>
              <br>
              <br>

              <br>
              <p class="h3">Email:support@subway.in</p>          
              
            <h3 class="h3" >Address</h3>
            <p class="h3">John Doe
                1234 Maple Street
                Apt. 56B
                Springfield, IL 62701
                USA </p>
            <p class="h3"></p>
              <br>
              <h3 align="center" class="h3"> Thank you for Visiting ....</h3>
    </div>
    </div>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (90).png>)
![alt text](<Screenshot (91).png>)
![alt text](<Screenshot (92).png>)
![alt text](<Screenshot (93).png>)
![alt text](<Screenshot (94).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
