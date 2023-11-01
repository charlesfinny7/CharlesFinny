# CharlesFinny
<!DOCTYPE html> <html
lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title> CONTENT | E-COMMERCE WEBSITE BY EDYODA </title>
<link href="https://fonts.googleapis.com/css?family=Lato&display=swap" rel="stylesheet">
<!-- favicon -->
<link rel="icon" href="https://yt3.ggpht.com/a/AGF-l78km1YyNXmF0r3-
0CycCA0HLA_i6zYn_8NZEg=s900-c-k-c0xffffffff-no-rj-mo" type="image/gif" sizes="16x16">
<link rel="stylesheet" href="css/content.css">
</head>
<body>
<div id="mainContainer">
<h1> clothing for men and women </h1>
<div id="containerClothing">
<!-- JS rendered code -->
</div>
<h1> accessories for men and women </h1>
<div id="containerAccessories">
<!-- JS rendered code -->
</div>
</div>
#Header
  <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title> HEADER | E-COMMERCE WEBSITE </title>
<!-- favicon -->
<link rel="icon" href="https://yt3.ggpht.com/a/AGF-l78km1YyNXmF0r3-
0CycCA0HLA_i6zYn_8NZEg=s900-c-k-c0xffffffff-no-rj-mo" type="image/gif" sizes="16x16">
<!-- EXTERNAL LINKS -->
<link rel="stylesheet" href="css/header.css">
<script src="https://kit.fontawesome.com/4a3b1f73a2.js"></script>
<link href="https://fonts.googleapis.com/css?family=Lato&display=swap" rel="stylesheet">
</head>
<body>
<header>
<section>
<!-- MAIN CONTAINER -->
<div id="container">
<!-- SHOP NAME -->
<div id="shopName"><a href="index.html"> <b>SHOPPING</b>DAMAKA</a></div>
<!-- COLLCETIONS ON WEBSITE -->
<div id="collection">
<div id="clothing"><a href="clothing.html"> CLOTHING </a></div>
<div id="accessories"><a href="accessories.html"> ACCESSORIES </a></div>
</div>
<!-- SEARCH SECTION -->
<div id="search">
<i class="fas fa-search search"></i>
<input type="text" id="input" name="searchBox" placeholder="Search for Clothing and
Accessories">
</div>
<!-- USER SECTION (CART AND USER ICON) -->
<div id="user">
<a href="cart.html"> <i class="fas fa-shopping-cart addedToCart"><div id="badge"> 0
</div></i></a>
<a href="#"> <i class="fas fa-user-circle userIcon"></i> </a>
</div>
</div>
</section>
</header>
</body>
</body>
<html>
#CODE FOR SLIDE
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title> SLIDER | E-COMMERCE WEBSITE </title>
<!-- favicon -->
<link rel="icon" href="https://yt3.ggpht.com/a/AGF-l78km1YyNXmF0r3-
0CycCA0HLA_i6zYn_8NZEg=s900-c-k-c0xffffffff-no-rj-mo" type="image/gif" sizes="16x16">
<!-- EXTERNAL LINKS -->
<script src="http://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-
CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
</html>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.css">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-
carousel/1.9.0/slicktheme.min.css">

<style>
body
{
margin: 0;
}
#containerSlider
{
margin: auto;

width: 90%; text-
align: center;

padding-top: 100px;
box-sizing: border-box;
}
#containerSlider img
{
width: 100%;

height: 140%; text-
align: center; align-
content: center;

}
@media(max-width: 732px)
{
#containerSlider img

{
height: 12em;
}
}
@media(max-width: 500px)
{
#containerSlider img
{
height: 10em;
}
}
</style>
</head>
<body>
<section>
<div id="containerSlider">
<div id="slidingImage"> <img src="img/img1.png" alt="image1"> </div>
<div id="slidingImage"> <img src="img/img2.png" alt="image2"> </div>
<div id="slidingImage"> <img src="img/img3.png" alt="image3"> </div>
<div id="slidingImage"> <img src="img/img4.png" alt="image4"> </div>
</div>
</section>
</body>
<!-- <script src=“https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.js”></script> -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.9.0/slick.min.js"></script>
<script>
$(document).ready(function()
{
$('#containerSlider').slick({
dots: true, infinite: true,
slidesToShow: 1,
slidesToScroll: 1,
autoplay: true,
autoplaySpeed: 2000,
});
});
</script>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
#CODE TO ADD ITEMS TO CART
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title> Cart | E-COMMERCE WEBSITE BY EDYODA </title>
<link rel="stylesheet" href="css/cart.css">
<!-- favicon -->
<link rel="icon" href="https://yt3.ggpht.com/a/AGF-l78km1YyNXmF0r3-
0CycCA0HLA_i6zYn_8NZEg=s900-c-k-c0xffffffff-no-rj-mo" type="image/gif" sizes="16x16">
<!-- header links -->
<script src="https://kit.fontawesome.com/4a3b1f73a2.js"></script>
<link href="https://fonts.googleapis.com/css?family=Lato&display=swap" rel="stylesheet">
</head>
<body>
<!-- HEADER -->
<div id="1"></div>
<script>
load("header.html");
function load(url)
{
req = new XMLHttpRequest();
req.open("GET", url, false);
req.send(null);
document.getElementById(1).innerHTML = req.responseText;
}
</script>
<!-- CART CONTAINER -->
<div id="cartMainContainer">
<h1> Checkout </h1>
<h3 id="totalItem"> Total Items: 0 </h3>
<div id="cartContainer">
<!-- JS rendered code -->
</div>
</div>
</body>
<!-- FOOTER -->
<div id="4"></div>
<script>
load("footer.html");
function load(url)
{
req = new XMLHttpRequest();
req.open("GET", url, false);
req.send(null);
document.getElementById(4).innerHTML = req.responseText; }
</script>
<script src="/cart.js"></script>
</html>
#CODE FOR SUCCESSFUL ORDER
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title> ORDER PLACED | E-COMMERCE WEBSITE BY EDYODA </title>
<!-- favicon -->
<link rel="icon" href="https://yt3.ggpht.com/a/AGF-l78km1YyNXmF0r3-
0CycCA0HLA_i6zYn_8NZEg=s900-c-k-c0xffffffff-no-rj-mo" type="image/gif" sizes="16x16">
<!-- fontawesome -->
<script src="https://kit.fontawesome.com/4a3b1f73a2.js"></script>
<link href="https://fonts.googleapis.com/css?family=Lato&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/orderPlaced.css">
</head>
<body>
<!-- HEADER -->
<div id="1"></div>
<script>
load("header.html");
function load(url)
{
req = new XMLHttpRequest();
req.open("GET", url, false);
req.send(null);
document.getElementById(1).innerHTML = req.responseText;
}
</script>
<!-- OREDER PLACED -->
<div id="orderContainer">
<div id="check"><i class="fas fa-check-circle"></i></div>
<div id="aboutCheck">
<h1> Order Placed Successfully! </h1>
<p> We've sent you an email with the Order details. </p>
</div>
</div>
<!-- FOOTER -->
<div id="4"></div>
<script>
load("footer.html");
function load(url)
{
req = new XMLHttpRequest();
req.open("GET", url, false);
req.send(null);
document.getElementById(4).innerHTML = req.responseText;
}
</script>
</body>
<script src="/orderPlaced.js"></script>
</html>
