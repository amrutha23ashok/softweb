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
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Zafran Beauty Collage</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Zafran Beauty Collage</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/logo.jpeg" alt="Building" />
          <div class="contenttext">
            At Zafran Beauty Collage,we believe in making the best.
            oral care, skin care, sun care, hair care, decorative cosmetics,
            body care and perfumes.Our main motto is to 
            produce good products with best quality at an affordable price. 
            <br />
            Our company mainly focus on giving the best product for the customers.
            We have collabed with one of the top companies like Lakme,
            Mamaearth and Dazller.We are proud to start our company in India. We 
            assure you for the brand and quality. 
            <ul>
              <li>Comfy</li>
              <li>Affordable</li>
              <li>Customer satisfaction matters the most</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; Zafran Beauty Collage, Developed by Abrin Nisha.
      </div>
    </div>
  </body>
</html>

PRODUCTS.HTML:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Zafran Beauty Collage</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpeg type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Zafran Beauty Collage</div>
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
                  <img src="/static/img/cetaphil.webp" alt="product image">
                  </div>
                  <div class="itemname">Cetaphil</div>
                  <div class="itemprice">Price: Rs.2500 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/coco.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Parachute Body lotion</div>
                  <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/cream.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Nivea</div>
                  <div class="itemprice">Price: Rs.2,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/dazller.webp"  alt="product image">
                  </div>
                  <div class="itemname">Dazller</div>
                  <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/kajal.webp"  alt="product image">
                  </div>
                  <div class="itemname">Maybelline Newyork</div>
                  <div class="itemprice">Price: Rs.7000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/lipbalm.webp"  alt="product image">
                  </div>
                  <div class="itemname">Arrah</div>
                  <div class="itemprice">Price: Rs.3,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/mamaearth.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Mamaearth</div>
                  <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/nivea.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Nivea</div>
                  <div class="itemprice">Price: Rs.3,500.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/nykaa.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Nykaa</div>
                  <div class="itemprice">Price: Rs.5,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/olay.png"  alt="product image">
                  </div>
                  <div class="itemname">Olay</div>
                  <div class="itemprice">Price: Rs.7,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/ponds.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Ponds</div>
                  <div class="itemprice">Price: Rs.8,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/spinz.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Spinz</div>
                  <div class="itemprice">Price: Rs.2,800.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; Zafran Beauty Collage, Developed by Abrin Nisha.
      </div>
    </div>
  </body>
</html>

PEOPLE.HTML:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Zafran Beauty Collage</title>
    <link rel="stylesheet" href="./css/layout.css">
    <link rel="icon" href="./img/banner1.jpg" type="image/x-icon"/>
  </head>

  <body>
    <div class="container">
      <div class="banner">Zafran Beauty Collage</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/products/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">   
          <h1>CEO of the Brand</h1>
          <div class="productitems">
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/ceo keerthi.jpg" alt="product image">
                  </div>
                  <div class="itemname">Keerthi shetty</div>
                  <div class="itemprice">President & CEO of Lakme</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/nazi.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Nazriya</div>
                  <div class="itemprice">Founder & CEO of Mamaearth</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/priya.jpg" alt="product image">
                  </div>
                  <div class="itemname">Priya Bhavanisankar</div>
                  <div class="itemprice">CEO of Ponds</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/kalyani.jpg" alt="product image">
                  </div>
                  <div class="itemname">Kalyani</div>
                  <div class="itemprice">Ambassador of Lakme</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/img3.jpg" alt="product image">
                  </div>
                  <div class="itemname">Alia Bhatt</div>
                  <div class="itemprice">Ambassador of Mamaearth</div>
              </div>
              <div class="productitem">
                  <div class="itemimage">
                  <img src="/static/img/img4.jpg" alt="product image">
                  </div>
                  <div class="itemname">Kajal Aharwal</div>
                  <div class="itemprice">Ambassador of Ponds</div>
              </div>

          </div>
          </div>       
      </div>
      <div class="footer">
        Copyright &#169; Zafran Beauty Collage, Developed by Abrin Nisha
      </div>
    </div>
  </body>
</html>

CONTACT.HTML:

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Zafran Beauty Collage</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Zafran Beauty Collage</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contacts.html">Contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
       
          <div class="contenttext">
           Mail us at  Zafrananddesign@gmail.com
           <br>
           Contact us at 9635874125
           <br>
           Our main office is at 5th car street,TamilNadu,India.
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; Zafran Beauty Collage, Developed by Abrin Nisha.
      </div>
    </div>
  </body>
</html>




## OUTPUT:
HOME PAGE:
![image](https://github.com/amrutha23ashok/softweb/assets/120772913/2c721329-b371-40c1-b4ff-2b26f614facf)

PRODUCTS PAGE:
![image](https://github.com/amrutha23ashok/softweb/assets/120772913/2897084f-e360-47ce-9749-8d51f351549f)


PEOPLE PAGE:
![image](https://github.com/amrutha23ashok/softweb/assets/120772913/90823e8c-6897-474b-97cd-f058a572ca92)

CONTACT PAGE:
![image](https://github.com/amrutha23ashok/softweb/assets/120772913/7203206d-6045-4280-a35f-98d881637777)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
