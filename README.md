# Product_Landing_Page

# Nike Collections Landing Page

Welcome to Nike Collections, a simple and stylish product landing page showcasing limited edition Nike products. This project is built with HTML and CSS.

## Preview

![Nike Collections Landing Page](http://127.0.0.1:5501/Index.html)

## Features

- Responsive design for a seamless experience on various devices.
- Explore limited edition Nike products.
- Easy navigation with a clean and intuitive interface.

**Project Structure**

--> index.html: 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Keval's Collections</title>
    <link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.1.0/fonts/remixicon.css"
    rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@500;700&display=swap" rel="stylesheet">
</head>
<body>
    <div id="main">
        <div id="nav">
            <div id="nav-prt1">
                <img src="images/nike img2.png" alt="">
                <h4>Home</h4>
                <h4>Men</h4>
                <h4>Women</h4>
                <h4>Collections</h4>
                <h4>Contact</h4>
            </div>
            <div id="nav-prt2">
                <i class="ri-search-line"></i>
                <i class="ri-shopping-cart-2-line"></i>
                <i class="ri-menu-line"></i>
            </div>
        </div>
        <div id="content">
            <div id="left">
                <h5>Explore The Limited Edition</h5>
                <h1>Nike limited Edition</h1>
                <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore neque dolorem maxime, similique error est reiciendis, explicabo porro minus voluptate eius velit alias culpa repudiandae nisi sapiente nulla harum totam beatae voluptatum aspernatur non id illo. Animi qui amet consequatur. ipsum dolor sit amet, consectetur adipisicing elit. Dicta molestiae quas assumenda voluptatum minima, quisquam sunt placeat voluptatem, in nulla ab, porro libero modi natus suscipit temporibus delectus id tenetur!</P>
                <button><b>Shop Now</b></button>
            </div>
            <div id="right">
                <div class="elem">
                    <img src="https://cdn.weartesters.com/wp-content/uploads/2018/10/nike-lebron-soldier-12-team-colorways-.jpg" alt="">
                    <h4>LeBron Soldier 12(Team)</h4>
                    <h5>Men's Basketball shoes</h5>
                </div>
                <div class="elem">
                    <img src="https://i.ebayimg.com/images/g/epMAAOSwGsleZBd5/s-l400.jpg" alt="">
                    <h4>Jordan Black cat</h4>
                    <h5>Men's shoes</h5>
                </div>
                <div class="elem">
                    <img src="https://th.bing.com/th/id/OIP.EOuid_KcZSXAqmNYYexkLQHaHa?rs=1&pid=ImgDetMain" alt="">
                    <h4>Air Jordan 13 Retro </h4>
                    <h5>Men's Basketball shoes</h5>
                </div>
                <div class="elem">
                    <img src="https://www.febbuy.com/uploads/Nike_Air_Jordan_Shoes/Air_Jordan_I_1_Shoes/Air_Jordan_I_Mid/Air_Jordan_1_Mid_Black_Dark_Concord_white_554724051_P5.jpg" alt="">
                    <h4>Air Jordan 1 Mid Black Dark</h4>
                    <h5>Men's shoes</h5>
                </div>
                <div class="elem">
                    <img src="https://media.endclothing.com/media/catalog/product/1/2/12-04-2016_nike_dunk-retro-qs_white-universityred_1_bm.jpg" alt="">
                    <h4>Nike Dunk Retro</h4>
                    <h5>Men's shoes</h5>
                </div>
            </div>
        </div>
    </div>
</body>
</html>


--> style.css: CSS styles for the page.

*{
    margin : 0;
    padding: 0;
    box-sizing: border-box;
}
html,body{
    height: 100%;
    width: 100%;
}

#main{
    height: 100%;
    width: 100%;
    background-color: lightgrey;
    position: relative;
    
}


#nav{
    height: 120px;
    padding: 20px 50px;
    width: 100%;
    display: flex;
    justify-content: space-between;
    font-family:  sans-serif;
    font-family: gilroy;
}

#nav img{
    height: 30px;
    margin-right: 120px;
    margin-left: 40px;

}

#nav-prt1{
    display: flex;
    justify-content: center;

}

#nav-prt1 h4{
    margin-right: 50px;
    font-size: 18px;
    text-transform: uppercase;
    font-weight: 600;
}

#nav-prt2 i{
    margin-right: 40px;
    font-size: 20px;
    font-weight: 24px;
}
#content {
    width: 100%;
    height: calc(100% - 110px);
    position: relative;
    display: flex;
}
#left {
    height: 100%;
    width: 35%;
    padding: 20px 60px;
    justify-content: center;
    margin-left: 30px;
    margin-top: 70px;
    position: relative;
}
#left h1{
    font-size: 50px;
    text-transform: uppercase;
    margin-bottom: 30px;
    font-family: 'Ubuntu', sans-serif;
}
#left p{
    font-size: 15px;
    margin-bottom: 50px;
    justify-content: center;
}
#left h5{
    color: rgb(93, 91, 91);
    margin-bottom: 20px;
}
#left button{
    padding: 20px 40px;
    margin-bottom: 10px;
    background-color: black;
    color: rgb(246, 249, 249);
    border-radius: 0px 70px 70px;
    text-align: center;
    box-shadow: 5px 5px 5px 0px rgba(0,0,0,0.4);
}
#right {
    height: 100%;
    width: 70%;
    margin-left: 20px;
    position: relative;
    padding: 50px;
    white-space: nowrap;
    overflow-x: auto;
}
#right::-webkit-scrollbar{
    display: none;
}
.elem{
    height: 480px;
    width: 300px;
    background: #fff;
    position: relative;
    object-fit: cover;
    border-radius: 10px;
    box-shadow: 0px 5px 10px 0px rgba(0,0,0,0.3);
    display: inline-block;
    margin-right: 30px;
}
.elem img{
    height: 60%;
    width: 100%;
    padding: 0px 10px 0px 10px;
    position: absolute;
    object-fit: cover;
    top: 10%;
}
.elem h4{
    position: absolute;
    bottom: 0;
    right: 0;
    background: lightgray;
    padding: 15px 30px;
    border-radius: 10px;
    border-top-right-radius: 0;
}
.elem h5{
    position: absolute;
    bottom: 9%;
    right: 0;
    background: black;
    padding: 10px 20px;
    color: #fff;
    border-radius: 10px;
    border-bottom-right-radius: 0;
}

images/: Directory containing images used in the project.

images/nike img2.png
https://cdn.weartesters.com/wp-content/uploads/2018/10/nike-lebron-soldier-12-team-colorways-.jpg
https://i.ebayimg.com/images/g/epMAAOSwGsleZBd5/s-l400.jpg
https://th.bing.com/th/id/OIP.EOuid_KcZSXAqmNYYexkLQHaHa?rs=1&pid=ImgDetMain
https://www.febbuy.com/uploads/Nike_Air_Jordan_Shoes/Air_Jordan_I_1_Shoes/Air_Jordan_I_Mid/Air_Jordan_1_Mid_Black_Dark_Concord_white_554724051_P5.jpg
https://media.endclothing.com/media/catalog/product/1/2/12-04-2016_nike_dunk-retro-qs_white-universityred_1_bm.jpg
