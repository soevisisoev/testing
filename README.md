<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

        #header {
            background-color: grey;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 0 20px;
        }

        #header h1 {
            margin: 0;
            text-align: center;
        }

        #header h1 span:first-child {
            color: rgb(133, 204, 27);
        }

        #header h1 span:last-child {
            color: cornflowerblue;
        }

        #loginn {
            border-radius: 10px;
            border: solid;
            padding: 5px;
            background-color: cornflowerblue;
            border-color: cornflowerblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            transition: background-color 0.5s, border-color 0.5s;
            text-decoration: none; /* Убираем подчеркивание */
        }

        #loginn:hover {
            background-color: rgb(133, 204, 27);
            border-color: rgb(133, 204, 27);
        }

        #menu {
            background-color: #f4f4f4;
            padding: 10px 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        #menu ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            gap: 20px; /* Расстояние между пунктами меню */
        }

        #menu ul li a {
            text-decoration: none;
            color: #333;
            font-size: 16px;
            transition: color 0.3s;
        }

        #menu ul li a:hover {
            color: cornflowerblue;
        }
    </style>
</head>
<body>
    <div id="header">
        <h1>
            <span>Skill</span><span>Head</span>
        </h1>
        <a href="login.html" id="link">
            <div id="loginn">Войти</div>
        </a>
    </div>

    <div id="menu">
        <nav>
            <ul>
                <li><a href="#">Курсы CSS</a></li>
                <li><a href="#">Курсы JS</a></li>
                <li><a href="#">Курсы HTML</a></li>
                <li><a href="#">Курсы PHP</a></li>
            </ul>
        </nav>
    </div>
</body>
</html>
