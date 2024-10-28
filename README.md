<! DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
    content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>IT services</title>
    <style>
        * {
            margin: 0;
            padding: 0;
           box-sizing: border-box;
        }  
       
        body{
           font-family: 'Montserrat', sans-serif;
           font-weight: 200;
           color: var(--tg-text-color);
           background: var(--tg-theme-bg-color);
       }
    
        #main
       {
           width: 100%;
           padding: 20px;
           text-aligh: center;
       }
    
       h1 {
           margin-top: 50px;
           margin-bottom: 10px;
       }
    
       img {
           width: 400px;
           margin-top: 60px;
           margin-left: 50px;
           margin-right: 50 px;
           border radius: 20px;
           margin: 0 auto;
       }
    
        p {
            width: 350px;
            margin: 0 auto;
        }

        button {
            border: 0;
            border-radius: 5px;
            margin-top: 60px;
            margin-left: 100px;
            margin-right: 100px;
            height: 40px;
            width: 100px;
            font-size: 20px;
            font-weight: 500;
            cursor: pointer;
            text-aligh: center;
            transition: all 500ms ease;
            volor: var(--tg-theme-button-text-color);
            background: var(--tg-theme-button-text-color);
        }

        button:hover {
            background: var(--tg-theme-secondary-bg-color);
        }

        #form {
            display: none;
            text-aligh: center;
        }

        input {
            width: 90%;
            outline: none;
            margin: 10x 5%;
            padding: 15px 10px;
            font-size: 14px;
            border: 2px solid silver;
            border-radius: 5px;
        }

        input:focus {
            border-color: #db5d5d;
        }
    </style>   
</head>
<body>
    <div id="main">
        <h2>Интернет-магазин IT услуг</h2>
        <img src="https://img.freepik.com/free-psd/3d-nft-icon-developer-male-illustration_629802-6.jpg?size=338&ext=jpg&ga=GA1.1.1297763733.1728259200&semt=ais_hybrid">
        <button id="buy">Купить</button>
    </div>
    <form id="form">
        <input type="text" placeholder="Имя" id="user_name">
        <input type="text" placeholder="Gmail" id="user_gmail">
        <input type="text" placeholder="Телефон" id="user_phone">
        <button id="order">Оформить</button>
    </form>
    <script>src="https://telegram.org/js/telegram-web-app.js"</script>
    <scipt>

    </script
</body>
</html>
