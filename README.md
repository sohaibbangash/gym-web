HTML CODE

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Club</title>
    <link rel="stylesheet" href="index.css">
</head>

<body>

    <header id="header">
        <div class="left"> <img src="img/images-removebg-preview.png"></div>
        <div class="mid">
            <div class="navbar">
                <ul>
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#" class="active">About Us</a></li>
                    <li><a href="#" class="active">Fitness Calculator</a></li>
                    <li><a href="#" class="active">Contact Us</a></li>
                </ul>
            </div>
        </div>
        <div class="right"><button class="btn">Join Now</button><button class="btn">Email Us</button></div>
    </header>

</body>
<div class=" container">
    <h1> Join Now  </h1>
    <form action="noaction.sql"></form>
    <div class="from-group">

        <div> <input type="text" name="" placeholder="Enter your Name"></div>
        <div> <input type="text" name="" placeholder="Enter your Age"></div>
        <div> <input type="text" name="" placeholder="Enter Email"></div>
        <div> <input type="text" name="" placeholder="Enter phone number"></div>
    <button class="btn">Submit</button>
</div>
</div>
</html>







CSS CODE


body{
    color: white;
    margin: 0px;
    padding: 0px;
    background: url(img/bg.webp) ;
background-repeat: no-repeat;


}

.left img{
    top: 0%;
    width: 110px;
}

.left{
    display: inline-block;
    position: absolute;
    left: 34px ;
    top: 2px;
}

.navbar{
    display: inline-block;
}
.navbar li {
    display: inline-block;
}
.navbar li a{
    text-decoration: none;
    padding: 34px 24px;
    color: white;
}
.navbar li a:hover, .navbar li a.actvie{

    text-decoration: underline;
    color:gray; 
}

.mid{

    display: block;
    width: 40%;
    margin: 20px auto;
}

.right{
    display: inline-block;
    position: absolute;
    right :34px ;
    top: 34px;
}

.btn{
    margin: 0px 9px;
    background-color:black;
    color: white;
    padding: 4px 14px;
    border: solid 2px black;
    border-radius: 10px;
    font-size: 13px;
    cursor: pointer;
}

.btn:hover{
    background-color: gray
}

.container{
    
    border: 2px solid rgb(255, 255, 255);
    margin: 90px 120px;
    padding: 75px;
    width: 33%;
    border-radius: 20px;
}

.container h1{
    text-align: center;
    color: rgb(255, 208, 0);
}

.from-group input{

    text-align: center;
    display: block;
    width: 80% ;
    margin: 10px auto ;
    padding: 6px ;
    border: 2px solid black;
   font-size: 13px;

}

.container button{
    display: block;
    width: 60%;
    margin: auto;
}

