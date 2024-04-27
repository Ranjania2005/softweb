# Ex.07 Software Product Company Website
## Date:28.04.2024

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
home.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Home</title>
    <style>
        *{
            margin:0;
            padding:0
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,h1,ul{
            display:inline;
        }
        ul{
            margin-left:45%;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:plum;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
      
        .box {
            display:inline-block;
            border-style:dotted ;
            border-radius: 10px;
            border-color: pink;
            width: 400px;
            min-height: 300px;
            font-size: 20px;
            background-color:pink;
        
        }
        .heading1{
            color:black;
            text-align: center;
            padding-top: 20px;
        }
        .heading2{
            color:black;
            text-align: justify;
            font-size: 30px;
            margin-left: 30px;
        }
        .edge{
            padding-left: 900px;
        }
        .box{
            text-align: center;
        }
 p{
            color:black;
            text-align: center;
        }
    
        .bottomdiv{
 background-color:yellow;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 30px;

        }
        table{
            margin-left: 40px;
        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body background="bg.png">
    <div class="header">
        <nav id="nav">
            <h1>
                WIPRO TECHNOLOGIES
            </h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
        </nav>
    </div>
    <div class="searchbar">
    <input placeholder="search">
    </div>
        <div><pre class="heading2"><i><b>
            "wipro provides information technology,consultant
            and business process services .It is one of the
            leading big tech companies"
            <b></i></pre></div>
                   <div class="edge">
                       <div class="box">
                       <h1 class="heading1">LOGIN HERE</h1>
                       <br>
                       <br>
                       <form>
                           <table cellpadding="15px" cellspacing="15px">
                               <tr>
                                   <td>
                                      <p> Username:</p>
                                   </td>
                                   <td>
                                       <input type="email" name="name" placeholder="Enter a Email">
                                   </td>
                               </tr>
                               <tr>
                                   <td>
                                       <p> Password:</p>
                                   </td>
                                   <td>
                                       <input type="password" name="pwd" placeholder="Enter a Password">
                                   </td>
                               </tr>
                               <tr>
                                   <td colspan="2">
                                       <input type="submit" value="LOGIN" style="background-color: yellow; color:black;">
                                   </td>
                                </tr>
                            </table>
                            
                        </form>
                        </div>
                    </div>
                <div class="bottomdiv">
                    <p>Designed and Developed by Ranjani A (212223230170)</p>
                </div>
            </body>
            <html>
            
           
```
product.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Products</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
 input{
            width: 18%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:purple;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:yellow;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color:plum;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:black;
        }
      p{
            color:black;
            text-align: center;
        }
   b{
            width: 300px;
            height: 200px;
        }
    h1{
            color:black;
            text-align: center;
        }
        .bottomdiv{
 background-color:yellow;
            color:black;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 140px;

        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body background="bg.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">WIPRO TECHNOLOGIES</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">PRODUCTS</h1>
        <br>
        <div class="product">
            <div class="box">
               <b><img src="cyber.jpg" ></b>
                <h1>CYBER SECURITY</h1>
<p>Wipro’s Cybersecurity Platforms increase the speed of change while reducing the 
    costs using advanced automation and other digital technologies.
   </p>
               </div>
               <div class="box">
                   <img src="infra.png">
                   <h1>CLOUD AND INFRA SECURITY</h1>
                   <p>Fortify defenses both on cloud and data center against the most advanced cyber threats.
                    Make your journey secure-by-design to deliver better business outcome by using defence-in-depth and zero-trust architectures.</p>
               </div>
               <div class="box">
                   <img src="applcation.jpg">
                   <h1>APPLICATION SECURITY</h1>
                   <p>As cloud becomes the ubiquitous and predominant technology platform for transforming
                    business, it drastically increases the enterprise attack surface making applications vulnerable to cyber-attacks. </p>
               </div>
           </div
       </div>
       <div class="bottomdiv">
           <b>Designed and Developed by Ranjani A (212223230170)</b>
       </div>
   </body>
   </html>
   
```
person.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Employees</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
        }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
        a{
            color:black;
text-decoration: none;
        }
        a:hover{
            color:plum;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color:black;
        }
        .bottomdiv{
            background-color:yellow;
            color:purple;
            text-align: center;
            position:relative;
            display:block;
            margin-top: 155px;

        }
        img{
            border-radius: 50%;
            width: 200px;
            display: inline;
            padding:3px;
            
        }
        .person{
            margin:100px;
            text-align: center;
        }
        b,p{
            color:black;
            text-align: center;
        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
      
</style>
</head>
<body background="bg.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">WIPRO TECHNOLOGIES</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">EMPLOYEES</h1>
        <table class="person">
            <tr>
                <td>
                    <img src="meee.jpeg" class="MyPic">
                </td>
                <td>
                    <img src="shinchan.png" class="Vijay">
                </td>
                <td>
                   <img src="kazama.png" class="Adharva">
                </td>
                <td>
                    <img src="nene.png" class="Sivakarthikeyan">
                </td>
                <td>
                    <img src="masao.png" class="nazriya">
                </td>
                <td>
                    <img src="bo.png"class="samantha"
                </td>
            </tr>
            <tr>
                <td>
                    <b>Ranjani</b>
                    <p>CEO</p>
                </td>
                <td>
                    <b>Shinchan Nohara</b>
                    <p>CEO,Co-Founder</p>
                </td>
                <td>
                    <b>Tooru Kazama</b>
                    <p>CTO,Co-Founder</p>
                </td>
                <td>
                    <b>Nene Sakurada</b>
                    <p>CEODirector</p>
                </td>
                <td>
                    <b>Masao Sato</b>
                    <p>Asst.Director</p>
                </td>
                <td>
                    <b>Bo Suzuki</b>
                    <p>Dy.Director</p>
                </td>
     
            </tr>
        </table>
    </div>
    <div class="bottomdiv">
<p>Designed and Developed by Ranjani A (212223230170)</p>
    </div>
</body>
</html>


```
contactus.html
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DD_Contactus</title>
    <style>
        *{
            margin:0;
            padding:0;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        #nav{
            background-color:yellow;
            color:black;
            padding: 15px;
    
        }
        li,.heading1,ul{
            display:inline;
        }
        ul{
            margin-left:45%
        }
        li{
            color:black;
  }
        li:hover{
            color:white;
            cursor:pointer;
        }
        input{
            width: 60%;
            padding: 15px;
        }
            .searchbar{
            padding:50px;
            text-align: center;
        }
        .box{
            border-color:black;
            border-width:2px;
            border-style:solid;
            display: inline-block;
            width: 414px;
        }
        .product{

            text-align: center;
        }
        .box{
            background-color:yellow;
            cursor:pointer;
        }
        a{
            color:black;
            text-decoration: none;
        }
        a:hover{
color:black;
            cursor:pointer;
        }
        .heading2{
            padding-top: 100px;
            padding-bottom: 10px;
            text-align: center;
            color: black;
        }
        .table1{
            color:blue;
            font-size: large;
        }
        .contactus{
            margin-left:400px;
        }
        .heading3{
            padding-top: 30px;
            padding-bottom: 10px;
            text-align: center;
            color: purple;
        }
        .table2{
            color:black;
            font-size: large;
            background-color:yellow;
            border-radius: 5px;
            border-style:dotted;
            border-color: black;

        }
        .queries{
            margin-left:570px;
        }
        .bottomdiv{
            background-color:yellow;
            color:black;
            text-align: center;
            position:relative;
display:block;
            margin-top: 15px;

        }
        body{
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body background="bg.png">
    <div class="header">
        <nav id="nav">
            <h1 class="heading1">WIPRO TECHNOLOGIES</h1>
                <ul>
                    <li class="li1"> 
                        <a href="home1.html" target="_blank">Home  |</a>
                    </li>
                    <li class="li2"> 
                        <a href="product.html" target="_blank">Products  |</a>
                    </li>
                    <li class="li4"> 
                        <a href="person.html" target="_blank">Employees  |</a>
                    </li>
                    <li class="li5"> 
                        <a href="contactus.html" target="_blank">Contact Us</a>
                    </li>
                </ul>
            </nav>
        </div>
        <h1 class="heading2">CONTACT US</h1>
        <div class="contactus">
            <table cellpadding="15px" cellspacing="15px" class="table1">
                <tr>
                    <td>
                        ADDRESS :
                    </td>
                    <td>
                        No. 602 , Medavakkam Road, Ecr Link Road, Shollinganallur-600119,Chennai - 600 017.

</td>
                </tr>
                <tr>
                    <td>
                        LANDMARK :
                    </td>
                    <td>
                        shollinganallur chennai.
                    </td>
                </tr>
                <tr>
                    <td>
                        Email :
                    </td>
                    <td>
                        wiprotech@gmail.com
                    </td>
                </tr>
                <tr>
                    <td>
                        PHONE :
                    </td>
                    <td>
                        9345446158
                    </td>
                </tr>
            </table>
        </div>
        <div>
            <h3 class="heading3">QUERIES</h3>
            <div class="queries">
                <table cellpadding="15px" cellspacing="15px" class="table2">
                    <tr>
                        <td>
                            NAME :
                        </td>
                        <td>
                            <input type="name" placeholder="Enter your name"> 
                        </td>
                    </tr>
                    <tr>
                        <td>
                            EMAIL :
                        </td>
                        <td>
                            <input type="email" placeholder="Enter your E-mail">
                        </td>
                    </tr>
                    <tr>
                        <td>
                            MESSAGE :
                        </td>
                        <td>
                            <input type="text" placeholder="Enter your text">
                        </td>
                    </tr>
                    <tr>
                        <td colspan="2">
                            <input type="submit" style="background-color: white; color: purple;">
                        </td>
                    </tr>
            </table>
        </div>
        <div class="bottomdiv">
            <p>Designed and Developed by Ranjani A (212223230170)</p>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-4.png)
![alt text](image-6.png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.