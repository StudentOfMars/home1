<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./home.css">
</head>
  <style>
      *{
    margin: 0px;
}

.container{
    max-width: 1600px;
}

.nav{
    margin: 0px 0px 80px 0px;
    display: flex;
    justify-content: space-around;
    box-shadow: 6px 6px 15px 1px gray;
    padding: 30px;
}

a{
    text-decoration: none;
    font-size: 30px;
    color: gray;
    position: relative;
}

a:hover{
    color: orangered;
    border-bottom: 3px solid orangered;
    padding-bottom: 20px;
}

.nav_menu{
    display: flex;
    align-items: center;
    gap: 60px;
}

.nav button{
    background-color: white;
    border-radius: 15px;
    border: 3px solid orangered ;
    color: orangered;
    padding: 0px 20px;
    font-size: 20px;
    width: 200px;
    height: 50px;
    position: relative;
    top: 10px;
}

.nav button:hover{
    background-color: orangered;
    color: white;
}

.nav_block{
    display: flex;
    justify-content: space-around;
}

.nav_box{
    display: flex;
    justify-content: space-around;
    gap: 30px;
}

.nav_text1{
    display: flex;
    align-items: center;
    font-size: 35px;
    color: darkblue;
}

.nav_text2{
    display: flex;
    align-items: center;
    font-size: 30px;
    color: orangered;
    width: 300px;
}

input{
    border-radius: 20px;
    border: none;
    outline: none;
    background-color: black;
    padding: 20px;
    width: 300px;
}

.nav_box button{
    width: 120px;
    border-radius: 15px;
    background-color: darkblue;
    color: white;
    padding: 20px;
    font-size: 20px;
    outline: none;
    border: none;
}

.main_block{
    display: flex;
    justify-content: space-around;
    margin: 90px auto;
    width: 1400px;
    flex-wrap: wrap;
}

h3, h4, h5{
    text-align: center;
}

h4{
    margin-bottom: 20px;
}

h3{
    color: gray;
    margin-bottom: 40px;
    position: relative;
}

h5{
    color: rgb(78, 78, 78);
}

.main_box{
    width: 300px;
    border-radius: 20px;
    box-shadow: 0px 0px 20px 1px rgb(168, 168, 168);
    padding: 20px 10px;
    margin: 10px;
    height: 300px;
}

.main_box img{
    position: relative;
    left: 80px;
}

.footer_block{
    display: flex;
    justify-content: space-around;
    box-shadow: -6px 0px 25px 1px gray;
    padding: 20px;
}

.footer_block a{
    display: flex;
    align-items: center;
    color: black;
    text-decoration:underline;
}

.footer_block a:hover{
    border: none;
    color: black;
    padding: 0px;
}

h2{
    display: flex;
    align-items: center;
    color: rgb(54, 54, 54);
}  
  </style>
<body>
    <section class="container">
        <header>
            <div class="nav">
                <img src="./img/image 2.png" alt="">
                <div class="nav_menu">
                    <a href=""><img src="./img/image 4.png" alt="">Home</a>
                    <a href=""><img src="./img/image 5.png" alt="">Learning</a>
                    <a href=""><img src="./img/image 6.png" alt="">Shop</a>
                </div>
                <button>Post yaratish</button>
                <img src="./img/image 7.png" alt="">
            </div>
            <div class="nav_block">
                <div class="nav_box">
                    <img src="./img/image 8.png" alt="">
                    <h1 class="nav_text1">Magazin</h1>
                </div>
                <div class="nav_box">
                    <input type="text" name="" id="" placeholder="search....">
                    <button>click</button>
                </div>
                <div class="nav_box">
                    <img src="./img/image 9.png" alt="">
                    <h1 class="nav_text2">Haridlar tarixi</h1>
                </div>
            </div>
        </header>
        <main>
            <div class="main_block">
                <div class="main_box">
                    <img style="position: relative; left: 60px;" src="./img/image 10.png" width="200" height="150" alt="">
                    <h4>Mars rug</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 100 coin</h3>
                    <h5>24 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 22.png" width="150" alt="">
                    <h4>Keyboard sticker</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 49 coin</h3>
                    <h5>11 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 23.png" width="150" alt="">
                    <h4>Smart watch</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 899 coin</h3>
                    <h5>4 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 24.png" width="150" height="150" alt="">
                    <h4>Wireless keyboard</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 350 coin</h3>
                    <h5>0 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 25.png" width="150" alt="">
                    <h4>Mouse</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 359 coin</h3>
                    <h5>24 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img style="position: relative; left: 40px;" src="./img/image 26.png" width="220" height="150" alt="">
                    <h4>AirPods</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 499 coin</h3>
                    <h5>11 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 27.png" width="150" alt="">
                    <h4>Powerbank</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 899 coin</h3>
                    <h5>5 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 28.png" width="150" height="150" alt="">
                    <h4>USB flash drive</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 299 coin</h3>
                    <h5>21 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 29.png" width="150" alt="">
                    <h4>Smartphone</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 3699 coin</h3>
                    <h5>2 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 30.png" width="150" alt="">
                    <h4>Playstation 5</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 7449 coin</h3>
                    <h5>Ushbu tovarga oldindan buyurtma berish mumkin</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 31.png" width="150" alt="">
                    <h4>Yandex Station</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 1999 coin</h3>
                    <h5>4 dona mavjud</h5>
                </div>
                <div class="main_box">
                    <img src="./img/image 32.png" width="150" alt="">
                    <h4>Planshet Samsung</h4>
                    <h3><img style="position: relative; left: -5px;" src="./img/Coin 2.png" alt=""> 4999 coin</h3>
                    <h5>24 dona mavjud</h5>
                </div>
            </div>
        </main>
        <footer>
            <div class="footer_block">
                <h2>MARS IT School 2022</h2>
                <img src="./img/image 2.png" alt="">
                <a href="https://space.marsit.uz/space-shop">Политика конфидециальности</a>
            </div>
        </footer>
    </section>
</body>
</html>
