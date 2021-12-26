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
  background-image: url("https://wallpaperaccess.com/full/58334.jpg");
  color: #17421d;
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
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-weight: bold;
  font-size: 60px;
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
  background-image: url("https://s3.envato.com/files/264967564/IMG_8996.jpg");
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
    <title>D Organica Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="C:/Users/Shrruthilaya/Documents/Web technology/productwebsite-1/companywebsite/static/img/dorganica.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">D Organica Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="C:/Users/Shrruthilaya/Desktop/dorganica.png">
          <div class="contenttext">
            A natural take on beauty, at D Organica we believe in organic care for
            the body. A fusion of nature and goodness, we combine every
            particle by hand and bring to you an immersive experience of
            oneness with the earth. Our craftsmen celebrate raw, natural and
            organic beauty in every product they chisel.
            <br></br>
            When enriching oils play with nurturing ingredients, high
            performing anti-oxidants fuse with naturally occurring vitamins,
            purity meets wisdom, and you choose D Organica, a world of gentle,
            natural and ethical love is born. 
            
            <ul>
              <li>Pamper your skin</li>
              <li>As fresh as Petrichor before rain</li>
              <li>Crafted with love and harmony</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2020 D Organica Private Limited, Developed by Shrruthilaya Gangadaran.
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
    <title>D Organica Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">D Organica Private Limited.</div>
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
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Aloe vera gel.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Aloe vera gel</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Charcoal face pack.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Charcoal face pack</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Lip kit.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Lip balm and Lip scrub</div>
                  <div class="itemprice">Price: Rs.400.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Neem comb.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Neem comb</div>
                  <div class="itemprice">Price: Rs.150.00 </div>
              </div>
              <div class="productitem"> 
                    <div class="itemimage">
                    <img src="C:/Users/Shrruthilaya/Desktop/Bamboo brush.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">Bamboo brush</div>
                    <div class="itemprice">Price: Rs.100.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                    <img src="C:/Users/Shrruthilaya/Desktop/Hair oil.jpeg"  alt="product image">
                    </div>
                    <div class="itemname">Hair oil</div>
                    <div class="itemprice">Price: Rs.300.00 </div>
                </div>
                <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Face wash.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Anti acne face wash</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Body butter.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Body butter</div>
                  <div class="itemprice">Price: Rs.350.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Under eye gel.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Under eye gel</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Hibiscus gel.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Hibiscus gel</div>
                  <div class="itemprice">Price: Rs.250.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Beard oil.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Beard oil</div>
                  <div class="itemprice">Price: Rs.300.00 </div>
               </div>
               <div class="productitem"> 
                  <div class="itemimage">
                  <img src="C:/Users/Shrruthilaya/Desktop/Facial glow scrub.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Facial glow scrub</div>
                  <div class="itemprice">Price: Rs.200.00 </div>
                </div>
               
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2020 D Organica Private Limited, Developed by Shrruthilaya Gangadaran.
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
    <title>D Organica Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner">D Organica Private Limited</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/angelinajolie.jpg"  alt="product image">.
                </div>
                <div class="itemname">Abhinaya Jothi</div>
                <div class="itemprice">Marketing manager</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/jkrowling.jpg"  alt="product image">.
                </div>
                <div class="itemname">Elakkiya Jothi</div>
                <div class="itemprice">Operation Manager</div>
            </div>
            <div class="productitem"> 
               <div class="itemimage">
               <img src="C:/Users/Shrruthilaya/Desktop/emmawatson.jpg"  alt="product image">.
               </div>
               <div class="itemname">Shamrudha</div>
               <div class="itemprice">Office Manager</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/billieeilish.jpg"  alt="product image">.
                </div>
                <div class="itemname">Hoshini</div>
                <div class="itemprice">Sales Manager</div>
             </div>
             <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/selenagomez.jpg"  alt="product image">.
                </div>
                <div class="itemname">Donashri</div>
                <div class="itemprice">Product dealer</div>
             </div>
             <div class="productitem"> 
                <div class="itemimage">
                <img src="C:/Users/Shrruthilaya/Desktop/arianagrande.jpg"  alt="product image">.
                </div>
                <div class="itemname">Tanushri</div>
                <div class="itemprice">Marketing manager</div>
             </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2020 D Organica Private Limited, Developed by Shrruthilaya Gangadaran.
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
    <title>Bonanza Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">D Organica Private Limited</div>
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
            75/W D Organica Private Limited, Mylapore, Chennai-600004.
          </div><br>
          <h1>Phone:</h1><br>
          <div class="contenttext">
              Mrs.Abhinaya Jothi(MARKETING MANAGER):8220156869<br><br>
              Mrs.Elakkiya Jothi(OPERATION MANAGER):9865432145<br><br>
              Mrs.Shamrudha(OFFICE MANAGER):6384569585
          </div>
          <h1>E-Mail:</h1><br>
          <div class="contenttext">
              Sales:dorganicaprivatelimited@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2020  D Organica Private Limited, Developed by Shrruthilaya Gangadaran.
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
