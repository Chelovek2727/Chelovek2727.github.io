# Chelovek2727.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel='stylesheet' href='style.css'>
    <title>Турагенція</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
</head>
<body>

    <div class='header'>
        <div class="nav">
        
            <a class="nav-item" href="#">Головна</a>
            <a class="nav-item" href="#">Новини</a>
            <a class="nav-item" href="#">Про нас</a>
            <a class="nav-item" href="#">Контакти</a>
        </div>

        <div class="main">
            <div class="title">А ви вже мріяли про відпочінок у Карпатах?</div>
            <div class="subtitle">Мы допоможемо здійснити вашу мрію!</div>
            <div class="forma">
                <form action="" method="">
                    <input type="text" class="input" placeholder="Введіть ваш номер телефону">
                </form>
            </div>
            <div class="button">
                <a href="" class="btn">Замовити зворотній дзвінок!</a>
            </div>
        </div>

     


    </div>

</body>
</html>

body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
}

.header {
    background-image: url(bg1.jpg);
    background-size: cover;
    height: 100vh;
}

.nav-item {
    color: #fff;
    text-decoration: none;
    margin-right: 80px;
    font-size: 38px;
}

.nav-item:last-child{
    margin-right: 0;
}

.nav-item:hover{
    color: #bc1717;
}

.nav{
    display: flex;
    justify-content: center;
    padding-top: 34px;
   

}

.title{
    color: #fff;
    font-size: 80px;
    width: 1114px;
    text-align: center;
    margin-right: auto;
    margin-left: auto;
    margin-top: 146px;
}
.subtitle{
    color: #fff;
    font-size: 48px;
    font-weight: 900;
    text-align: center;
    margin-right: auto;
    margin-left: auto;
    width: 514px;
    line-height: 44px;
    margin-top: 50px;
}
.input{
    width: 447px;
    height: 64px;
    font-size: 24px;
    outline: none;
    border: 4px solid #8D8D8D;
    border-radius: 20px;
    padding-left: 15px;
}
.forma{
    text-align: center;
    margin-top: 20px;
}
.btn{
    background-color: #5B89CE;
    padding: 15px 18px;
    color: #fff;
    text-decoration: none;
    font-size: 24px;
    font-weight: 700;
    border: 2px solid #476443;
    border-radius: 25px;

}
.btn:hover{
    background-color: #3b0aeb;
}
.button{
    text-align: center;
    margin-top: 20px;

}

