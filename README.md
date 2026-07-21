<!DOCTYPE html>
<html>
    <head>
      <meta charset="UTF-8">
      <title>About Us Page</title>
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
      <style>
 /* internal css */
*{margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial;
}
/* HEADER */
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 30px;
  border-bottom: 1px solid #4C3D19;
  background-color: #354024;
}
.logo {
  font-weight: 800;
  font-size: 28px;
  color:#CFBB99;
}
.left-icons i,
.right-icons i {
  margin: 0 8px;
  cursor: pointer;
}
.fa-bars{
    color: #CFBB99;
}
.fa-magnifying-glass{
    color: #CFBB99;
}
.fa-user{
    color: #CFBB99;
}
.fa-heart{
    color: #CFBB99;
}
.fa-cart-shopping{
    color: #CFBB99;
}
.nav {
  width: 100%;
  display: flex;
  font-size: 18px;
  justify-content: center;
  font-family: 'Courier New', Courier, monospace;
  gap: 210px;
  padding: 15px;
  border-bottom: 1px solid #4C3D19;
}
/* nav bar category text color */
a{
  text-decoration: none;
  color:#4C3D19;
  font-weight: bold;
}
/* displaying big image */
.image-box{
    height: 450px;
    padding: 30px 30px;
    padding-left: 60px;
    padding-right: 60px;
    background-color: white;
    margin-bottom: 10%;
}
 .image{
    position:relative;
    height: 380px;
    border-radius: 20px;
    overflow: hidden;
}
 .image img{
    width: 100%;
    height: 100%;
}
 /* image content design */
.image-text{
    position:absolute;
    top:10%;
    font-size: large;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    max-width: 470px;
    padding-left: 10px;
    margin: 40px;
    background-color: #dadfcd;
}
.image-text h1{
    color:#354024;
}
.content-box{ 
    width:100%;
    background-color: #c2c8b4;
    border-radius: 8px;
    padding: 8px;
    padding-left: 60px;
    padding-right: 60px;
    margin-bottom: 10%;
    } 
.content-heading{
    font-size:x-large;
    color: #354024;
    text-align: center;
    margin-bottom: 25px;
    margin-top:35px;
    }
.content-detail{ 
    font-size:large;
    line-height:1.8;
    margin-bottom: 30px;
    font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    color:#354024; 
}
.table-style{
  border-style:dashed;
    border-color:bisque;
    background-color:#fcf7ef;
    color: #354024;
    font-family:'Times New Roman', Times, serif; font-size: large;
    text-align: center;
}
.table-row-style{
  border-style:ridge;
  border-color: bisque;
  background-color: #fcf7ef;
  text-align: center;
  font-family: 'Times New Roman', Times, serif;
  font-size: large;
}
table {
      width: 85%;
      margin: 20px auto; 
}
.sales-content{
  display: flex;
  margin-bottom: 50px;
}
.footer {
  margin-top: 30px;
  padding: 20px;
  border-top: 1px solid #ccc;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.footer-box {
  font-size: 14px;
}

.social i {
  margin: 0 8px;
  cursor: pointer;
}
      </style>
    </head>
<!-- html part-->
    <body>
    <!-- header icons and logo using div to group them accordingly-->
    <header class="header">
        <div class="left-icons">
            <i class="fa-solid fa-bars"></i>
            <i class="fa-solid fa-magnifying-glass"></i>
        </div>
        <h1 class="logo"> Essentia </h1>
        <div class="right-icons">
            <i class="fa-solid fa-user"></i>
            <i class="fa-solid fa-heart"></i>
            <i class="fa-solid fa-cart-shopping"></i>
        </div>
    </header>

  <!-- navigation bar -->
    <nav class="nav">
      <a href="">Art Supplies</a>
      <a href="">Beauty & Personal care</a>
      <a href="">Fashion</a>
      <a href="../HomeDecorPage/homedecor.html">Home Decor</a>
      <a href="../KitchenwarePage/kitchenware.html">Kitchenwares</a>
    </nav>
    <!-- using inline css to style "Blog" heading -->
    <h1 style="font-family:'Times New Roman', Times, serif;font-size: xx-large;
    background-color:#f9f1e5;color: #354024;
    text-align: center;text-decoration:underline;border-radius:30px; margin-bottom: 3%;">Blog</h1>
    <!-- displaying big tech image -->
    <div class="image-box">
            <div class="image">
                <img src="PicturesUsed/tech3.jpg" alt="bg-image">
               <div class="image-text">
                <h1>Technology</h1>
               </div>
            </div>
    </div>
    <div class="content-box">
                <h3 class="content-heading">Technology</h3>
                <p class="content-detail">Technology is using tools and knowledge in solving our daily problems. In this modern world the definition of Technology
                has slightly changed over time, it is the use of machines,computers,robots,advanced tools to do different tasks.For example: A smartphone helps us to communicate with people,
                use of social media to connect to different people,share ideas. Now we cant imagine our lives without the use of modern technologies. Likewise it has deeply rooted in 
                every field like education,banking,business,healthcare,etc. Technology has helped business to reach people around the world through the use of internet,mobiles,
                laptops,computer,etc. Technology has become really important in this time.This is because technology gave a new and better ways on solving tasks in faster and efficient way.
                </p>

                <table>
                    <h3 style="text-align: center;margin-bottom: 40px;">Positive Impacts and Negative Impacts</h3>
                    <img src="PicturesUsed/effectsOfTech.png" style="width: 100%;height:25%;">
                <tr>
                    <th style="font-weight: bold;" class="table-style">Positive Impact</th>
                    <th style="font-weight: bold;" class="table-style">Negative Imapct</th>
                </tr>
                <tr>
                    <td class="table-row-style">It improved virtual connectivity to every corner of the world.</td>
                    <td class="table-row-style">It has reduced face-to-face interaction among people because of excessive virtual interactions only.</td>
                </tr>
                <tr>
                    <td class="table-row-style">It promotes production of eco-friendly products.</td>
                    <td class="table-row-style">Due to it there will be overuse of natural resources for production</td>
                </tr>
                <tr>
                    <td class="table-row-style">It helps in manufacturing and promoting eco-friendly items.</td>
                    <td class="table-row-style">Use of execcive technologies like machines release many toxic gases.</td>
                </tr>
                <tr>
                    <td class="table-row-style">It makes work easier,increase efficiency and reduce human errors.</td>
                    <td class="table-row-style">Excessive use of technology makes human brain dull and lazy.</td>
                </tr>
                </table>

                <h3 class="content-heading">How technology boosts sustainable product sales?</h3> 
                <div class="sales-content">
                <img src="PicturesUsed/TechBoostingBusiness.webp" style="width: 30%;height:30%;border-radius: 20px;text-align: center;">
                <p class="content-detail" style="padding-left: 50px;padding-top:55px;">Technology boosts sustainable product sales through advertisements which increases awareness and accessibility to people worldwide.Digital platforms such as e-commerce websites and social media allow 
                eco-friendly brands to reach audience world-wide and make constumers aware of the positive environmental impact of their products.</p>
                </div>

                <h3 style="text-align: center;">Conclusion </h3>
                <p class="content-detail"> In conclusion,use of technology has become a major part in human life. As the use of technology increases its positive and negative imopact also increase along with it. It is our responsibility to use technology in balanced manner.
                    If used right technology will help promote and convince people around the world to use eco-friendly products and help main the eco-system of our planet.</p>
                <img src="PicturesUsed/TechInEcoFriendlyEnv.jpeg" style="width: 100%;height:320px;border-radius: 20px;">         
    </div>
    <!-- footer section -->
<footer class="footer">
    <div class="footer-box">
    <h3>Essentia</h3>
    <a href="aboutus.html">About us</p></a>
    <a href="../BlogPage/Blogpage.html">Blog</p></a>
    <a href="">Terms & Conditions</p></a>
    <a href="">Privacy Policies</p></a>
    <a href="../ReferencePage2/reference.html">Research</p></a>
    </div>

  <div class="footer-box">
    <h3>Contact Us</h3>
    <p>Pokhara,New Road-8</p>
    <p>+977 9854760945</p>
    <p>essentia@gmail.com</p>
  </div>

  <div class="footer-box">
    <h3>Payment can be done by</h3>
    <p>Cash</p>
    <p>eSewa</p>
    <p>Khalti</p>
    <p>Other Banks</p>
  </div>

  <div class="footer-box">
    <h3>Verified by</h3>
    <p>Eco Certification Authority</p><br>

    <h3>Join us</h3>
    <div class="social">
    <i class="fa-brands fa-facebook-f"></i>
    <i class="fa-brands fa-instagram"></i>
    <i class="fa-brands fa-youtube"></i>
  </div>
  </div>

  <div class="footer-box">
    <h4>Why our products?</h4>
    <ul>
      <li>100% Eco-friendly</li>
      <li>Biodegradable</li>
      <li>Sustainable material</li>
    </ul>
  </div>
</footer>
    </body>
</html>
