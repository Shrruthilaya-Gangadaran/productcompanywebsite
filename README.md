# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### Layout :
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(26, 29, 29);
  color: whitesmoke;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-weight: bold;
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: whitesmoke;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  margin-right: 10px;
  color: #0d0f0f;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-image: url("https://t4.ftcdn.net/jpg/04/09/70/87/360_F_409708782_HxuxOH8f7xSmj5p4ygbAbuJE74vGGj2N.jpg");
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  font-style: italic;
  font-family: sans-serif;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: left;
  font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
  font-style: italic;
  font-family: sans-serif;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  font-family: cursive;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}

~~~

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FrivLee Clipzee</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FrivLee Clipzee</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="C:/Users/Shrruthilaya/Desktop/flcplogo.jpeg">
          <div class="contenttext">
            Internet gaming can be a safe and enjoyable online activity if your educate yourself and
            practice the basic principles of good computer security. Many computer security principles
            are the same as those you may have practiced in other computer applications.
            <br></br>
            Altogether, playing online games help players develop complex problem-solving skills,
            leadership skills, and the ability to deal better with unexpected consequences. They also
            enhance a player's skills of observation, intuitive abilities, and hone their alertness and
            concentration.
            
            <ul>
              <li>Refresh your mind</li>
              <li>Endless Entertainment</li>
              <li>Safe International gaming</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 FrivLee Clipzee, Developed by Shrruthilaya Gangadaran.
      </div>
    </div>
  </body>
</html>

~~~

### Product Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FrivLee Clipzee</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FrivLee Clipzee</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Best Games For Kids:</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/hauntthehouse.jpg" alt="product image">
                  </div>
                  <div class="itemname">Haunt the house</div>
                  <div class="itemprice">Price: Rs.190.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/vampireskills.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Vampire skills</div>
                  <div class="itemprice">Price: Rs.210.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/rachel.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Rachel's cake</div>
                  <div class="itemprice">Price: Rs.190.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/fbwglt.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Fire boy and Water girl-Light temple</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
              </div>
              <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Shrruthilaya/Desktop/fbwgit.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Fire boy and Water girl-Ice temple</div>
                    <div class="itemprice">Price: Rs.150.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                    <img src="C:/Users/Shrruthilaya/Desktop/fbwgct.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Fire boy and Water girl-Crystal temple</div>
                    <div class="itemprice">Price: Rs.150.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/deathchase.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Death chase</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/coco.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Coco monkey</div>
                  <div class="itemprice">Price: Rs.190.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/btg.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Break the glass</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/rhrz.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Robo hero-Red zone</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/rhgz.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Robo hero-Green zone</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/rhbz.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Robo hero-Blue zone</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
                </div>
               
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 FrivLee Clipzee, Developed by Shrruthilaya Gangadaran.
      </div>
    </div>
  </body>
</html>

~~~

### People Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FrivLee Clipzee</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner">FrivLee Clipzee</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Foundation team:</h1><br><br>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/img6.jpg"  alt="product image">.
                </div>
                <div class="itemname">Shrruthilaya Gangadaran</div>
                <div class="itemprice">Founder</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/img5.jpg"  alt="product image">.
                </div>
                <div class="itemname">Lizaa</div>
                <div class="itemprice">CEO</div>
            </div>
            <div class="productitem"> 
               <div class="itemimage">
               <img src="C:/Users/Shrruthilaya/Desktop/img4.jpg"  alt="product image">.
               </div>
               <div class="itemname">Ishwarya</div>
               <div class="itemprice">CFO</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/img3.jpg"  alt="product image">.
                </div>
                <div class="itemname">Hoshini</div>
                <div class="itemprice">CTO</div>
             </div>
             <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/img2.jpg"  alt="product image">.
                </div>
                <div class="itemname">Donashri</div>
                <div class="itemprice">Team lead of Software development</div>
             </div>
             <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/img1.jpg"  alt="product image">.
                </div>
                <div class="itemname">Tanushri</div>
                <div class="itemprice">Head of Creative department</div>
             </div>
          </div>
        </div>        
      </div>
      <div class="footer">
      Copyright &#169; 2021 FrivLee Clipzee, Developed by Shrruthilaya Gangadaran.
      </div>
     </div>
   </body>
  </html>
~~~

### Contact Us Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>FrivLee Clipzee</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">FrivLee Clipzee</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext">
            75/W FrivLee Clipzee, Chicago, US.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Ms.Hoshini(CTO):<br><br>
              Ms.Donashri(Team lead of Software development):9865432145<br><br>
              Ms.Tanushri(Head of Creative department):6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Games:frivleeclipzee@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021  FrivLee Clipzee, Developed by Shrruthilaya Gangadaran.
      </div>
    </div>
  </body>
</html>
~~~


## OUTPUT:

### Home Page:

![output](Homepage.png)

### Product Page:

![output1](Productpage.png)

### People Page:

![output2](Peoplepage.png)

### Contact Us Page:

![output3](Contactuspage.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
