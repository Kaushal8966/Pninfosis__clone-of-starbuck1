# HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starbuks Coffee Company</title>
    <link rel="stylesheet" href="CSS/starbuks.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>

<body>
    <nav>
        <div class="logo">
            <img src="https://th.bing.com/th?id=OIP.UpAn6Il2uWxs8RrU9n5AEwHaG-&w=257&h=242&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2"
                alt="">
        </div>
        <div class="leftmenu">
            <a href="">MENU</a>
            <a href="">REWARDS</a>
            <a href="">GIFT CARDS</a>
        </div>
        <div class="rightmenu">
            <a href="">Find a store</a>
            <button class="button1">sign in</button>
            <button class="button2">join now</button>
        </div>
    </nav>
    <div class="container">
        <div class="image1">
            <img src="image/image 1.webp" alt="">
        </div>
        <div class="image2">
            <h2>Your treat awaits</h2>
            <p>Fall in love with Starbucks® Rewards member perks, like a free drink with qualifying purchase during your
                first week. Valid for one-time use.*</p>
            <button>join now</button>
        </div>
    </div>
    <div class="container1">
        <div class="image3">
            <h2>Find your fall</h2>
            <p>Embrace fall in full flavor with a Pumpkin Spice Latte, Apple Crisp Oatmilk Macchiato or Chai Latte.</p>
            <button>order now</button>
        </div>
        <div class="image4">
            <img src="image/image2.webp" alt="">
        </div>
    </div>
    <div class="container2">
        <div class="image5">
            <img src="image/image3.webp" alt="">
        </div>
        <div class="image6">
            <h2>Pecan perfection</h2>
            <p>Say hello to the nutty new nondairy Pecan Crunch Oatmilk Latte, your comforting companion for a crisp
                fall day.</p>
            <button>order now</button>
        </div>
    </div>
    <div class="container3">
        <div class="image7">
            <h2>Apple of autumn’s eye</h2>
            <p>The only thing better than the return of the irresistible Baked Apple Croissant is that it’s here to
                stay.</p>
            <button>order now</button>
        </div>
        <div class="image8">
            <img src="image/image4.webp" alt="">
        </div>
    </div>
    <div class="container4">
        <div class="image9">
            <img src="image/image5.jpg" alt="">
        </div>
        <div class="image10">
            <h2>Because PSL is baaack</h2>
            <p>Share the love of pumpkin spice with a Starbucks eGift..</p>
            <button>Send an eGift</button>
        </div>
    </div>
    <div class="paragraph">
        <p>*Valid only for new Starbucks Rewards members for 7 days from sign up. Offer good at participating stores for
            a handcrafted menu-sized beverage with eligible purchase ($8 max value). Taxes not included. Excludes
            alcohol, Starbucks Card and Starbucks Card reloads. Limit one per member. Cannot be combined with other
            offers or discounts. Product availability varies by store. Excludes delivery services. Sign up from
            9/23/2024 - 11/6/2024 to be eligible.</p>
    </div>
    <footer>
        <div class="footer-content1">
        <div class="footer-content">
            <h3>
                About Us
            </h3>
            <a href="">Our Company</a>
            <a href="">Our Coffee</a>
            <a href="">Storie and News</a>
            <a href="">Starbucks Archieve</a>
            <a href="">Investor Relations</a>
            <a href="">Customer Service</a>
            <a href="">Contact Us</a>
        </div>
        <div class="footer-content">
            <h3>Careers</h3>
            <a href="">Culture and values</a>
            <a href="">Inclusion,Diversty and Equity</a>
            <a href="">College Achievement plan</a>
            <a href="">Alumini Comunity</a>
            <a href="">U.S. Careers</a>
            <a href="">International Careers</a>

        </div>
        <div class="footer-content">
            <h3>Social Impact</h3>
            <a href="">People</a>
            <a href="">planet</a>
            <a href="">Environmental and Social Impact reporting</a>
        </div>
        <div class="footer-content">
            <h3>For business partner</h3>
            <a href="">Landlord Support Creers</a>
            <a href="">Suppliers</a>
            <a href="">Corporate Gift Crd sales</a>
            <a href="">Office and Food Service Coffee</a>
        </div>
        <div class="footer-content">
            <h3>Order and pickUp</h3>
            <a href="">Order on the app</a>
            <a href="">Order on the web</a>
            <a href="">delievery</a>
            <a href="">order and pickup option</a>
            <a href="">Explore and final coffee for Home</a>
        </div>
    </div><hr>
        <div class="icon">
            <a href=""><i class='bx bxl-spotify'></i></a>
            <a href=""><i class='bx bxl-facebook-circle'></i></a>
            <a href=""><i class='bx bxl-pinterest'></i></a>
            <a href=""><i class='bx bxl-instagram'></i></a>
            <a href=""><i class='bx bxl-youtube'></i></a>
            <a href=""><i class='bx bxl-twitter'></i></a>

        </div>
       <div class="data">
        <ul>
            <li><a href="">Privacy Notice</a></li>
            <li><a href="">Consumer Health Privacy Notice</a></li>
            <li><a href="">Terms of use</a></li>
            <li><a href="">Do Not Share My Personal information</a></li>
            <li><a href="">CA Supply Chain Act</a></li>
            <li><a href="">Accesbility</a></li>
            <li><a href="">Cookie Preference</a></li>
        </ul>
        <p>© 2024 Starbucks Coffee Company. All rights reserved.</p>
       </div> 
    </footer>

</body>

</html>

#CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

nav {
    width: 100%;
    height: 99px;
    background-color: white;
    display: flex;
    justify-content: space-between;
    text-align: center;
    box-shadow: 4px 4px 4px black;

}

nav .logo {
    display: flex;
    justify-content: space-between;
    margin: 25px 43px;
}

nav .logo img {
    width: 51px;
    height: 51px;

}

.leftmenu {
    padding: 36px 0px;
    margin-right: 369px;
}

.leftmenu a {
    padding: 0px 6px;
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 15px;
    text-decoration: none;
    color: black;

    font-weight: 700;
}

.rightmenu {
    padding: 36px 104px;
}

.rightmenu a {
    padding: 0px 51px;
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 15px;
    text-decoration: none;
    color: black;
    font-weight: 700;
}

.button1 {
    width: 80px;
    height: 37px;
    text-align: center;
    border-radius: 25px;
    margin-right: 8px;
    font-weight: 700;
    font-size: 14px;
    border: medium;
    border: 1px solid black;
    background: white;
}

.button1:hover {
    background: rgba(128, 128, 128, 0.801);
}

.button2 {
    width: 80px;
    height: 37px;
    text-align: center;
    border-radius: 25px;
    font-size: 14px;
    color: white;
    background-color: black;
    border: medium;
    font-weight: 700;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* margin: 0px 22px; */
    margin-bottom: 34px;
}

.container .image1 img {
    width: 100%;
    height: 100%;
}

.container .image1 {
    width: 672px;
    height: 392px;
}

.container .image2 {
    width: 672px;
    height: 392px;
    background: #006241;
    text-align: center;
}

.container .image2 h2 {
    color: white;
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    margin-top: 117px;
    margin-bottom: 17px;
    font-size: 25px;
}

.container .image2 p {
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 19px;
    color: white;
    line-height: 30px;
    padding: 0px 105px
}

.container .image2 button {
    width: 110px;
    height: 40px;
    border-radius: 25px;
    border: medium;
    color: white;
    background: #006241;
    font-size: 19px;
    border: 1px solid white;
    margin-top: 25px;
}

.container1 {
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* margin: 0px 22px; */
    margin-bottom: 34px;
}

.container1 .image3 {
    width: 672px;
    height: 582px;
    background: #9e2240;
    text-align: center;
}

.container1 .image3 h2 {
    color: white;
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    margin-top: 117px;
    margin-bottom: 17px;
    font-size: 59px;
}

.container1 .image3 p {
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 25px;
    color: white;
    line-height: 30px;
    padding: 0px 105px
}

.container1 .image3 button {
    width: 110px;
    height: 40px;
    border-radius: 25px;
    border: medium;
    color: white;
    background: #9e2240;
    font-size: 19px;
    border: 1px solid white;
    margin-top: 25px;
}

.container1 .image4 img {
    width: 100%;
    height: 100%;
}

.container1 .image4 {
    width: 672px;
    height: 582px;
}

.container2 {
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* margin: 0px 22px; */
    margin-bottom: 34px;
}

.container2 .image5 img {
    width: 100%;
    height: 100%;
}

.container2 .image5 {
    width: 672px;
    height: 582px;
}

.container2 .image6 {
    width: 672px;
    height: 582px;
    background: #9e2240;
    text-align: center;
}

.container2 .image6 h2 {
    color: white;
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    margin-top: 117px;
    margin-bottom: 17px;
    font-size: 59px;
}

.container2 .image6 p {
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 25px;
    color: white;
    line-height: 30px;
    padding: 0px 105px
}

.container2 .image6 button {
    width: 110px;
    height: 40px;
    border-radius: 25px;
    border: medium;
    color: white;
    background: #9e2240;
    font-size: 19px;
    border: 1px solid white;
    margin-top: 25px;
}

.container3 {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 34px;
    /* margin: 0px 22px; */

}

.container3 .image7 {
    width: 672px;
    height: 582px;
    background: #d2d655;
    text-align: center;
}

.container3 .image7 h2 {
    color: rgba(0, 0, 0, 0.788);
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    margin-top: 117px;
    margin-bottom: 17px;
    font-size: 45px;
    padding: 0px 152px;
}

.container3 .image7 p {
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 25px;
    color: rgba(0, 0, 0, 0.767);
    line-height: 30px;
    padding: 0px 105px
}

.container3 .image7 button {
    width: 110px;
    height: 40px;
    border-radius: 25px;
    border: medium;
    color: black;
    background: #d2d655;
    font-size: 19px;
    border: 1px solid black;
    margin-top: 25px;
}

.container3 .image8 img {
    width: 100%;
    height: 100%;
}

.container3 .image8 {
    width: 672px;
    height: 582px;
}

.container4 {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 34px;
    /* margin: 0px 22px; */
}

.container4 .image9 img {
    width: 100%;
    height: 100%;
}

.container4 .image9 {
    width: 672px;
    height: 582px;
}

.container4 .image10 {
    width: 672px;
    height: 582px;
    background: #ffbe9e;
    text-align: center;
}

.container4 .image10 h2 {
    color: rgba(0, 0, 0, 0.788);
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    margin-top: 140px;
    margin-bottom: 17px;
    font-size: 45px;
    padding: 0px 152px;
}

.container4 .image10 p {
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 25px;
    color: rgba(0, 0, 0, 0.767);
    line-height: 30px;
    padding: 0px 105px
}

.container4 .image10 button {
    width: 180px;
    height: 40px;
    border-radius: 25px;
    border: medium;
    color: black;
    background: #ffbe9e;
    font-size: 19px;
    border: 1px solid black;
    margin-top: 25px;
}

.paragraph p {
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 16px;
    text-align: center;
    padding: 20px 319px;
    line-height: 32px;
}

footer {
    width: 95%;
    height: 850px;
    margin-top: 50px;
    margin: 0px 40px;
    background-color: white;
   box-shadow:  3px 0px 5px gray;
   
}
.footer-content1{
    display: flex;
    justify-content: center;
}
.footer-content1 hr{
    color: rgba(128, 128, 128, 0.63);
}

.footer-content {
    display: block;

}

.footer-content h3 {
    margin-bottom: 30px;
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    padding: 0px 30px;
    margin-top: 37px;
}

.footer-content a {
    text-decoration: none;
    display: block;
    padding: 0px 30px;
    margin-bottom: 30px;
    font-family: SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif;
    font-size: 15px;
    transition: all.40s ease;
    color: rgba(0, 0, 0, 0.616);
}

.footer-content a:hover {
    color: black;
    transform: translateY(-3px) translateX(5px);
}
.icon{
font-size: 45px;
margin-top: 27px;
color: black;
margin-left: 30px;
}
.icon a i{
    color: #212121;
}
.data{
    margin-top: 30px;
    margin-left: 30px;
}
.data ul li{
    display: block;
    padding: 7px 0px;
}
.data li a{
  
    font-family:SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif ;
    text-decoration: none;
    color: #212121;
}
.data li a:hover{
    text-decoration: underline;
}
.data p{
    margin-top: 20px;
    font-family:SoDoSans, Helvetica Neue, Helvetica, Arial, sans-serif ;
    color: rgba(0, 0, 0, 0.596);
    font-size: 15px;
}
