<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Flower Bouquet</title>

<style>
body{
    margin:0;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    background:linear-gradient(#e8f7ff,#fff5f9);
    overflow:hidden;
    font-family:sans-serif;
}

.bouquet{
    position:relative;
    width:320px;
    height:500px;
}

.stem{
    position:absolute;
    bottom:110px;
    width:5px;
    height:170px;
    background:#3b8d4b;
    transform-origin:bottom;
}

.flower{
    position:absolute;
}

.center{
    position:absolute;
    width:22px;
    height:22px;
    background:#ffd54f;
    border-radius:50%;
    left:19px;
    top:19px;
    z-index:2;
}

.petal{
    position:absolute;
    width:30px;
    height:30px;
    background:#ff7aa2;
    border-radius:50%;
}

.p1{left:15px;top:0;}
.p2{left:38px;top:15px;}
.p3{left:15px;top:38px;}
.p4{left:0;top:15px;}
.p5{left:32px;top:32px;}
.p6{left:0;top:32px;}

.wrap{
    position:absolute;
    bottom:0;
    left:70px;
    width:180px;
    height:150px;
    background:#c9b6ff;
    clip-path:polygon(50% 100%,0 0,100% 0);
    opacity:.9;
}

.ribbon{
    position:absolute;
    bottom:95px;
    left:145px;
    width:30px;
    height:30px;
    background:#ff5c8a;
    transform:rotate(45deg);
}

.ribbon::before,
.ribbon::after{
    content:"";
    position:absolute;
    width:25px;
    height:15px;
    border:4px solid #ff5c8a;
    border-radius:50%;
}

.ribbon::before{
    left:-22px;
    top:0;
}

.ribbon::after{
    right:-22px;
    top:0;
}

.message{
    position:absolute;
    bottom:-35px;
    width:100%;
    text-align:center;
    color:#444;
    font-size:22px;
    font-weight:bold;
}
</style>
</head>

<body>

<div class="bouquet">

<div class="stem" style="left:90px;transform:rotate(-18deg);"></div>
<div class="flower" style="left:55px;top:70px;">
<div class="petal p1"></div>
<div class="petal p2"></div>
<div class="petal p3"></div>
<div class="petal p4"></div>
<div class="petal p5"></div>
<div class="petal p6"></div>
<div class="center"></div>
</div>

<div class="stem" style="left:150px;"></div>
<div class="flower" style="left:115px;top:30px;">
<div class="petal p1" style="background:#ff5ea8"></div>
<div class="petal p2" style="background:#ff5ea8"></div>
<div class="petal p3" style="background:#ff5ea8"></div>
<div class="petal p4" style="background:#ff5ea8"></div>
<div class="petal p5" style="background:#ff5ea8"></div>
<div class="petal p6" style="background:#ff5ea8"></div>
<div class="center"></div>
</div>

<div class="stem" style="left:210px;transform:rotate(18deg);"></div>
<div class="flower" style="left:175px;top:80px;">
<div class="petal p1" style="background:#b86cff"></div>
<div class="petal p2" style="background:#b86cff"></div>
<div class="petal p3" style="background:#b86cff"></div>
<div class="petal p4" style="background:#b86cff"></div>
<div class="petal p5" style="background:#b86cff"></div>
<div class="petal p6" style="background:#b86cff"></div>
<div class="center"></div>
</div>

<div class="wrap"></div>
<div class="ribbon"></div>

<div class="message">
Made with ❤️
</div>

</div>

</body>
</html>
