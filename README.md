# Ex.07 Software Product Company Website
## Date:

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
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    HOMEPAGE
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Software Development Company </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner 
            {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(black,black),url(background.png);
                background-size: cover;
                background-position: center;
            }
            .navbar 
            {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo 
            {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span 
            {
                color: white;
            }
            form 
            {
                width: 300px;
                height: 40px;
                display: flex;
                background: black;
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input 
            {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder 
            {
                color: white;
            }
            form button 
            {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li 
            {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a 
            {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover 
            {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content 
            {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 
            {
                color: white;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p 
            {
                color: white;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login 
            {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .login:hover 
            {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup 
            {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover 
            {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: white;
                transition: 0.5s;
                cursor: pointer;
            }
            footer 
            {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">I<span>nfiniti</span>T<span>ech</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/person.html"> Person </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> Software Development Company </h2>
                <br>
                <p> Welcome to InfinitiTech, your gateway to cutting-edge software solutions and innovative web development applications! </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by AMIRTHAVARSHINI V (212223040014) </center>
    </footer>
</body>
</html>
PERSON
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> person page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner 
            {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar 
            {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-person 
            {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo 
            {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span 
            {
                color: white;
            }
            form 
            {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input 
            {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder 
            {
                color: white;
            }
            form button 
            {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li 
            {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a 
            {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover 
            {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image 
            {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table 
            {
                border: 0;
                color: white;
                position: relative;
                left: 150px;
            }
            .image table img 
            {
                height: 140px;
                width: 140px;
                border: 2px solid white;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td 
            {
                color: #6fa1f8;
            }
            footer 
            {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">I<span>nfiniti</span>T<span>ech</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/person.html" class="bg-person"> person </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="30"> 
                <tr align="center">
                    <td> <img src="sundhar.jpg"> </td>
                    <td> <img src="steve.jpg"> </td>
                    <td> <img src="swetha.jpg"> </td>
                    <td> <img src="markzub.jpg"> </td>
                    <td> <img src="musk.jpg"> </td>
                </tr>
                <tr align="center">
                    <th> Viswanathan </th>
                    <th> Dhanalakshmi </th>
                    <th> Amirtha  </th>
                    <th> Shruthi </th>
                    <th> Venu Prasad  </th>
                </tr>
                <tr align="center">
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> CEO </td>
                    <td> Director </td>
                    <td> Co-ordinator </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by AMIRTHAVARSHINI V (212223040014) </center>
    </footer>
</body>
</html>
PRODUCTS
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Product Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner 
            {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar 
            {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-product 
            {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo 
            {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span 
            {
                color: white;
            }
            form 
            {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input 
            {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder 
            {
                color: white;
            }
            form button 
            {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li 
            {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a 
            {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover 
            {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .container 
            {
                background: transparent;
                padding: 10px 5%;
                padding-bottom: 100px;
            }
            .container .box-container 
            {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }
            .container .box-container .box 
            {
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 20px;
                background: transparent;
                border: 1px solid white;
                padding: 30px 30px;
            }
            .container .box-container .box img 
            {
                height: 70px;
                border-radius: 20px;
            }
            .container .box-container .box h2 
            {
                color: #6fa1f8;
                font-size: large;
                padding: 10px 0;
            }
            .container .box-container .box p 
            {
                color: white;
                font-size: small;
                line-height: 1.5;
            }
            footer 
            {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">I<span>nfiniti</span>T<span>ech</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html" class="bg-product"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/person.html"> person </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <h2> CodeForge Pro </h2>
                </div>
                <div class="box">                   
                    <h2> SiteGenie Builder </h2>                   
                </div>
                <div class="box">                    
                    <h2> DevSync Hub Pro </h2>                    
                </div>
                <div class="box">                  
                    <h2> WebOptiMate Suite </h2>                   
                </div>
                <div class="box">                   
                    <h2> CodeLeap Toolkit </h2>                    
                </div>
                <div class="box">                    
                    <h2> SiteGuard Pro Shield  </h2>                   
                </div>
                <div class="box">                    
                    <h2> WebFlow Pro Studio </h2>                    
                </div>
                <div class="box">                  
                    <h2> DevInspect Test Kit </h2>                   
                </div>
                <div class="box">                   
                    <h2> SiteSphere CMS </h2>                   
                </div>
                <div class="box">                   
                    <h2> CodeBoost Accelerator </h2>                
                </div>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by AMIRTHAVARSHINI V (212223040014) </center>
    </footer>
</body>
</html>
CONTACT US
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Us Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner 
            {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgba(0,0,0,0.75),rgba(0,0,0,0.75)),url(background.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar
            {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-contact 
            {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo 
            {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span 
            {
                color: white;
            }
            .navbar form 
            {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            .navbar form input 
            {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } 
            ::placeholder 
            {
                color: white;
            }
            .navbar form button 
            {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li 
            {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a 
            {
                text-decoration: none;
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover 
            {
                border: 1px;
                padding: 10px;
                color: white;
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box 
            {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 
            {
                height: 370px;
                width: 400px;
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 
            {
                height: 370px;
                width: 400px;
                border: 3px solid #6fa1f8;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form 
            {
                display: flex;
                color: white;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input 
            {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea 
            {
                background: transparent;
                color: white;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button 
            {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: white;
                border-radius: 30px;
                background: #6fa1f8;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 
            {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p 
            {
                color: white;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span 
            {
                color: #6fa1f8;
                font-size: 20px;
            }
            footer 
            {
                background-color: #6fa1f8;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">I<span>nfiniti</span>T<span>ech</span></h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/home.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/person.html"> person </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name :">
                        <br>
                        <input type="email" placeholder="Your Email :">
                        <br>
                        <textarea rows="4" cols="40" >Your Message :</textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address :</span> plot no 75 vasanthapuri phase 11,poonamalle,chennai</p>
                <p> <span>Email :</span> amirthaviswanathan536@gmail.com</p>
                <p> <span>Phone :</span>  9025378096 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by AMIRTHAVARSHINI V(212223040014) </center>
    </footer>
</body>
</html>
</body>
</html>

```

## OUTPUT:

![329769223-36f754e1-27a3-451c-a1a2-8d561c91a1ae](https://github.com/amirthaviswanathan05/softweb/assets/149035397/52c0130d-1a75-411c-972f-7d80c36be354)

![web eXP07](https://github.com/amirthaviswanathan05/softweb/assets/149035397/0cea3eb3-90de-48af-b966-27d033ee9de1)

![329769258-346cb4c0-ace9-41b3-8c1d-fd660d3053e1](https://github.com/amirthaviswanathan05/softweb/assets/149035397/0bb47771-da7c-48ba-9848-855ac53848db)

![WEB exp 7](https://github.com/amirthaviswanathan05/softweb/assets/149035397/cb4429ba-4fd2-41d1-9ffe-ed4a4c83f019)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
