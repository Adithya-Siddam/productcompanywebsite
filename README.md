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
## Home.html:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tally Solutions Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Tally Solutions Ltd.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/produts.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Who are we</h1>
          <img src="./img/building1.png" alt="Building1" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make future 
            product users efficient, empowered and happier, so they can focus on what
            matters most for their learning skills. We design and sell our
             products to focus on what is required? to make our products understandable to you,
              and not the other way around.We are a technology & innovation company. 
              Delivering business software for Small and Medium Businesses is our passion.
              What sets a company apart is as much in its DNA as its achievements. 
            <br />
            <br/>
            Our new products like tally prime, etc and many other books
             takes this to a new level, making your programming life to make it
            simple and hassle free, the products we create are easier to use.
            You can now learn tally easily without any hassle.
            There is greater flexibility as you can use these products inspite of your busy schedule
            way of working. And the transformed look and feel will only make you
            love the books even more.
            <ul>
              <li>to learn tally  easily</li>
              <li>Insightful ,accoustamable, conceptual reasoning</li>
              <li>All the products are written by top most authors.</li>
            </ul>
            <h2>OUR MOTTO:</h2>
            <b>"To Make Everyone Who Touches Tally Happier"</b>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Tally Solutions Ltd, Developed by Adithya Chowdary.
      </div>
    </div>
  </body>
</html>
~~~
### Products.html:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tally Solutions Ltd</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">Tally Solutions Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact US.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/book1.jpg" alt="product image">
                  </div>
                  <div class="itemname">Tally gold</div>
                  <div class="itemprice">Price: Rs.4000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/book2.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Tally silver</div>
                  <div class="itemprice">Price: Rs.4000.00 </div>
              </div>
              <div class="productitem">
                <div class="itemimage">
                  <img src="/static/img/book3.png" alt="product image">
                </div>
                <div class="itemname">Tally prime Gold</div>
                <div class="itemprice">Price: Rs.4000.00</div>
              </div>
              <div class="productitem">
                <div class="itemimage">
                  <img src="/static/img/book4.png" alt="product image">
                  </div>
                  <div class="itemname">Tally prime silver</div>
                  <div class="itemprice">Price: Rs.4000.00</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
              <img src="/static/img/book5.jpg" alt="product image">
              </div>
              <div class="itemname">Tally Auditors Edition</div>
              <div class="itemprice">Price: Rs.4000.00</div>
      </div>
      <div class="productitem">
        <div class="itemimage">
          <img src="/static/img/book6.png" alt="product image">
          </div>
          <div class="itemname">Tally Shoper9 gold Edition</div>
          <div class="itemprice">Price: Rs.4000.00</div>
  </div>
  <div class="productitem">
    <div class="itemimage">
      <img src="/static/img/book7.png" alt="product image">
      </div>
      <div class="itemname">Tally shoper9 silver Edition</div>
      <div class="itemprice">Price: Rs.4000.00</div>
</div>
<div class="productitem">
  <div class="itemimage">
    <img src="/static/img/book8.jpg" alt="product image">
    </div>
    <div class="itemname">Tally Rentals</div>
    <div class="itemprice">Price: Rs.4000.00</div>
</div>
<div class="productitem">
  <div class="itemimage">
    <img src="/static/img/book9.png" alt="product image">
    </div>
    <div class="itemname">Tally silver Edition 5.4</div>
    <div class="itemprice">Price: Rs.4000.00</div>
</div>
<div class="productitem">
  <div class="itemimage">
    <img src="/static/img/book10.jpg" alt="product image">
    </div>
    <div class="itemname">Tally Edition 6.3</div>
    <div class="itemprice">Price: Rs.4000.00</div>
</div>
<div class="productitem">
  <div class="itemimage">
    <img src="/static/img/book11.jpg" alt="product image">
    </div>
    <div class="itemname">Tally Edition 7.2</div>
    <div class="itemprice">Price: Rs.4000.0</div>
</div>
<div class="productitem">
  <div class="itemimage">
    <img src="/static/img/book12.jpg" alt="product image">
    </div>
    <div class="itemname">Simple Tally 8.1</div>
    <div class="itemprice">Price: Rs.4000.00</div>
</div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Tally Solutions Ltd, Developed by Adithya Chowdary.
      </div>
    </div>
  </body>
</html>
~~~
### People.html:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tally Solutions Ltd</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">Tally Solutions Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact Us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="peoplecontent">    
          <h1>Our beloved management</h1>
          <div class="peopleitems">
              <div class="peopleitem"> 
                  <div class="itemimage">
                  <img src="/static/img/author2.jpg" alt="people image">
                  </div>
                  <div class="itemname">Shyam Sundar Goenka</div>
                  <div class="itemprice">LATE Chairperson of Tally solutions </div>
              </div>
              <br/>
              <div class="peopleitem"> 
                  <div class="itemimage">
                  <img src="/static/img/author5.jpg"  alt="people image">
                  </div>
                  <div class="itemname">Sheela Goenka</div>
                  <div class="itemprice">Current chairperson of Tally solutions</div>
              </div>
              <br/>
              <div class="peopleitem">
                <div class="itemimage">
                  <img src="/static/img/author1.jpg" alt="people image">
                </div>
                <div class="itemname">Bharat Goenka</div>
                <div class="itemprice">CEO of Tally solutions</div>
              </div>
              <br/>
              <div class="peopleitem">
                <div class="itemimage">
                  <img src="/static/img/author3.jpg" alt="people image">
                  </div>
                  <div class="itemname">Tejas Goenka</div>
                  <div class="itemprice">Managing director of Tally solutions</div>
          </div>
          <br/>
          <div class="peopleitem">
            <div class="itemimage">
              <img src="/static/img/author4.jpg" alt="people image">
              </div>
              <div class="itemname">Ganesh.S</div>
              <div class="itemprice">Chief Financial officer</div>
      </div>
      
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Tally Solutions Ltd, Developed by Adithya Chowdary.
      </div>
    </div>
  </body>
</html>
~~~
### Contact US.html:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Tally Solutions Ltd</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">Tally Solutions Ltd.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/Contact US.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Contact Info</h1>
          <h3>
            Tally Solutions Ltd.
            <br/>
            Mailing: tallysols@gmail.com
            <br/>
            Phone: 1800 309 8859.
             <h2>Address:</h2>
            </h3>
            <h3>
            AMR Tech Park II,
            <br/>
            No.23 & 24,
            <br/>
            Hongasandra,
            <br/>
            Hosur Main Road,
            <br/> 
            Bangalore,
            <br/> 
            560 068,
            <br/> 
            India,
          </h3>
      <div class="footer">
        Copyright &#169; 2021 Tally Solutions Ltd, Developed by Adithya Chowdary.
      </div>
    </div>
  </body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](./images/homepage.png)
![output](./images/homepage2.png)
![output](./images/homepage3.png)
![output](./images/homepage4.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
