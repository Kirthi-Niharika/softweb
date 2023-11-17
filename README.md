# Ex.07 Software Product Company Website
## Date : 31/10/2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
### index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>II TECHI</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }
        .logo img{
            height: 100px;
            width: 130px;
        }
        header {
        overflow: hidden;
        background-color: rgb(177, 177, 177);
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;

        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: rgb(8, 47, 87);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
            color: black;
            font-size: xx-large;
            font: 2rem 'AmstelvarAlpha', sans-serif;
            font-style: oblique 23deg;
    
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background: rgba(103, 103, 108, 0.5);
            background-image: url(gif1.gif);
            height: 1000px;        
            overflow: hidden;
            line-height: 60px;
            
        }

        h3,h4{
            text-align: left;
            color: aliceblue;
            font: 2rem 'AmstelvarAlpha', sans-serif;
            font-style: oblique 23deg;
            font-style: italic;
            background-color: rgb(31, 31, 44);
        }

        .im1 img{
            padding: 20px;
            height: 200px;
            width: 300px;
            position:absolute;
            top: 580px;
        }

        .im2 img{
            padding: 20px;
            height: 200px;
            width: 300px;
            position:absolute;
            top: 580px;
            left: 400px;
        }

        .im3  img{
            padding: 20px;
            height: 200px;
            width: 300px;
            position:absolute;
            top: 580px;
            left: 780px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <a><img src="iitechi.png" alt="logo" border="2"></a>
        </div>
        <a class="cname">II TECHI</a>
        <div class="header-right">
            <a class="active" href="index.html">Home</a>
            <a href="product.html">Product</a>
            <a href="people.html">People</a>
            <a href="contact.html">Contact</a>
          </div>
    </header>
    <section id="content">
        <h3 >"Empowering Innovation, Transforming Tomorrow."</h1>
        <h4> Welcome to IITECHI, where cutting-edge solutions meet limitless possibilities. <br>We are a dynamic software tech company dedicated to empowering businesses through innovative software solutions.<br><br></h2>
        <div style="width: 100%; display: table;">
        <div style="display: table-row; height: 500px;">
            <div style="width: 50%; display: table-cell; background: black;">
                <div class="im1">
                    <img src="im1.png" alt="image1">
                </div>
                <div class="im2">
                    <img src="im2.png" alt="image2">
                </div>
                <div class="im3">
                    <img src="im3.png" alt="image3">
                </div>
            </div>

        </div>
    </div>
        
    </section>
</body>
</html>
```

### product.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Explore</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color:rgb(177, 177, 177);
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: rgb(8, 47, 87);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: white;
            height: 1500px;        
            overflow: hidden;
            line-height: 30px;
        }
        
        .prod1 img{
            padding: 10px;
            height: 250px;
            width: 200px;
            position:absolute;
            top: 280px;
        }

        .prod2 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 280px;
            left: 970px;
        }

        .prod3 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 280px;
            left: 400px;
        }

        .prod4 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 740px;
        }

        .prod5 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 740px;
            left: 450px;
        }

        .prod6 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 740px;
            left: 900px;
        }

        .prod7 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 1140px;
        }

        .prod8 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 1140px;
            left: 970px;
        }

        .prod9 img{
            padding: 10px;
            height: 200px;
            width: 200px;
            position:absolute;
            top: 1140px;
            left: 450px;
        }


        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="iitechi.png" alt="logo" border="2"></a>
        <a class ="cname"><h1>IITECHI</h1></a>
        <div class="header-right">
            <a href="index.html">Home</a>
            <a class="active" href="product.html">Product</a>
            <a href="people.html">People</a>
            <a href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        
        <div class="prod1">
            <img src="norton.png" alt="prod3">
        </div>
        <div class="prod2">
            <img src="canva.png" alt="prod2">
        </div>
        <div class="prod3">
            <img src="opera.png" alt="prod1">
        </div>
        <div class="prod4">
            <img src="wix.png" alt="prod4">
        </div>
        <div class="prod5">
            <img src="word.png" alt="prod5">
        </div>
        <div class="prod6">
            <img src="vscode.jpg" alt="prod6">
        </div>
        <div class="prod7">
            <img src="adobe.jpg" alt="prod7">
        </div>
        <div class="prod8">
            <img src="sql.jpg" alt="prod8">
        </div>
        <div class="prod9">
            <img src="music.jpg" alt="prod9">
        </div>
    </section>
</body>
</html>
```

### people.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>II TECHI</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 130px;
        }
        header {
        overflow: hidden;
        background-color: rgb(177, 177, 177);
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
        background-color: rgb(8, 47, 87);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: white;
            overflow: hidden;
            line-height:normal;
        }
        .person {
            text-align: center;
        }

        p{
            font-size: 20px;
        }
        .person img {
            display:grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            margin: 0 auto;
            height: 340px;
            padding-top: 40px;
        }

        .person p.name {
            font-weight: bold;
            margin-top: 10px;
            color:black;
        }

        .person p.desig {
            font-weight: bold;
            margin-top: 10px;
            color:rgb(47, 20, 220);
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:rgb(0, 30, 128)  ;
        }
        
        footer{
            font-size: 20px;
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="iitechi.png" alt="logo" border="2"></a>
        <a class ="cname"><h1>II TECHI</h1></a>
        <div class="header-right">
            <a href="index.html">Home</a>
            <a href="product.html">Product</a>
            <a class="active" href="people.html">People</a>
            <a href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>OUR REPRESENTATIVES</h3>
        </div>
        <div class="image">
            <div class="person">
                <img src="sid.png" alt="Sid">
                <p class="name">Sid W</p>
                <p class="desig">MANAGING DIRECTOR</p>
            </div>
            <div class="person">
                <img src="sarah.png" alt="Sarah">
                <p class="name">Sarah US</p>
                <p class="desig">CEO</p>
            </div>
            <div class="person">
                <img src="Aeri.png" alt="Aeri">
                <p class="name">Aeri G</p>
                <p class="desig">GENERAL MANAGER</p>
            </div>
            <div class="person">
                <img src="lia.png" alt="Lia">
                <p class="name">Lia J</p>
                <p class="desig">MARKETING HEAD</p>
            </div>
            <div class="person">
                <img src="zach.png" alt="Zach">
                <p class="name">Zach K</p>
                <p class="desig">HR MANAGER</p>
            </div>
            <div class="person">
                <img src="min.png" alt="Mina">
                <p class="name">Mina O</p>
                <p class="desig">REGIONAL MANAGER</p>
            </div>
        </div>
    </section>
</body>
</html>
```

### contact.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>II TECHI</title>
    <style>
        *{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        }

        .logo img{
            height: 100px;
            width: 100px;
        }
        header {
        overflow: hidden;
        background-color: rgb(177, 177, 177);
        padding: 20px 10px;
        }

        header a {
        float: left;
        color: black;
        text-align: center;
        padding: 12px;
        text-decoration: none;
        font-size: 18px; 
        line-height: 25px;
        border-radius: 4px;
        }

        header a.logo {
        font-size: 25px;
        font-weight: bold;
        }

        header a:hover {
        background-color: #ddd;
        color: black;
        }

        header a.active {
            background-color: rgb(8, 47, 87);
        color: white;
        }

        .header-right {
        float: right;
        padding-top: 30px;
        }

        .cname{
            padding-top: 20px;
        }

        @media screen and (max-width: 500px) {
            header a {
                float: none;
                display: block;
                text-align: left;
            }
        }

        #content{
            background-color: white;
            overflow: hidden;
            line-height:normal;
        }
        
        .contact-container {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 50px;
        }

        .contact-image {
            flex: 1;
            text-align: center;
        }

        .contact-image img {
            max-width: 100%;
            height: auto;
        }

        .contact-details {
            flex: 1;
            padding: 50px;
            font-size: 25px;
        }

        .title{
            text-align: center;
            font-size: 30px;
            color:rgb(6, 0, 128);
        }

    </style>
</head>
<body>
    <header>
        <a class="logo"><img src="iitechi.png" alt="logo" border="2"></a>
        <a class ="cname"><h1>IITECHI</h1></a>
        <div class="header-right">
            <a href="index.html">Home</a>
            <a href="product.html">Product</a>
            <a href="people.html">People</a>
            <a class="active" href="contact.html">Contact</a>
          </div>
    </header>

    <section id="content">
        <div class="title">
            <h3>CONTACT US</h3>
        </div>
        <div class="contact-container">
            
            <div class="contact-image">
                <img src="company.png">
            </div>
            <div class="contact-details">
                <p><strong>Email:</strong> iitechi326@gmail.com</p>
                <p><strong>Phone:</strong> +144 4353 9233</p>
                <p><strong>Address:</strong> 19, ABC Street, Porur, Chennai</p>
            </div>
        </div>
    </section>

</body>
</html>
```
## OUTPUT:
![image](https://github.com/Kirthi-Niharika/softweb/assets/114135005/0ee5b798-e203-496c-9bb9-2152c94b7872)
![image](https://github.com/Kirthi-Niharika/softweb/assets/114135005/bf3f592e-a02d-4a8d-b6a6-de523411f9e3)
![image](https://github.com/Kirthi-Niharika/softweb/assets/114135005/d6399d20-ca6a-41fa-9fcc-26130feb128c)
![image](https://github.com/Kirthi-Niharika/softweb/assets/114135005/59c996d7-7aed-4c33-b150-039c705d4117)
![image](https://github.com/Kirthi-Niharika/softweb/assets/114135005/27c7e243-a546-4490-b0b0-8979412d1fe2)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
