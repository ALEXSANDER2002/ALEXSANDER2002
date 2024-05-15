<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bio GitHub e Jogo da Cobrinha</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        #user-content-toc {
            text-align: center;
        }
        canvas {
            background-color: #000;
            display: block;
            margin: 20px auto;
        }
        p, h1, h3 {
            text-align: center;
        }
        .skills, .tools {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
        }
    </style>
</head>
<body>
    <!-- título -->
    <div id="user-content-toc">
        <ul align="center">
            <summary><h1 style="display: inline-block">Hello, World!</h1></summary>
        </ul>
    </div>
    
    <!-- Presentation -->
    <p>
        Oi 👋🏻, Eu me chamo ALEX! Sou graduando em Engenharia da Computação.

        - 👾 Atualmente estou no 3° período, cursando pela UNIFESSPA.
    </p>

    <!-- Dropdown -->
    <details>
        <summary>🧑🏻‍💻 Sobre mim</summary>

        <p>- 💬 Possuo 19 anos, sou natural de Rondon do Pará, mas atualmente resido em Marabá onde curso Sistemas de Informação pela UNIFESSPA (Universidade Federal do Sul e Sudeste do Pará). Tenho contato com diversas linguagens de programação, dentre elas: Java, JavaScript, Python, Swift, C.</p>
        <p>- 🎮 Sou um amante de futebol, animes, filmes e jogos. Admirador das diversas tecnologias existentes, procurando sempre me manter atualizado sobre as diversas criações que surgem diariamente. \o/</p>
    </details>

    <!-- Links -->
    <p align="center">
        <a href="https://www.linkedin.com/in/igor-santos-b70b35271">
            <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
        </a>
        <a href="https://www.instagram.com/igorsxntos?igsh=MW4xNWJkdGduNzBsbQ==">
            <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
        </a>
        <a href="mailto:igorsantosigor272@gmail.com">
            <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
        </a>
        <a href="https://t.me/igorsxntos">
            <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
        </a>
    </p>

    <!-- GithubStats -->
    <h2 align="center">🎯 Estatísticas</h2>
    <div align="center">
        <img height="200" src="https://github-readme-stats.vercel.app/api?username=correasouza&theme=tokyonight&hide_border=false&include_all_commits=false&count_private=false&show_icons=true&line_height=29&locale=pt-br&rank_icon=github" alt="GitHub Stats">
        <img height="200" src="https://github-readme-stats.vercel.app/api/top-langs/?username=correasouza&theme=tokyonight&hide_border=false&include_all_commits=false&count_private=false&layout=donut" alt="Top Languages">
    </div>

    <!-- GIF -->
    <p align="center">
        <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYW1jOG90dWNwMGcwYjNta2NvNG02aTZmaTM0cG93ZHF5eDY5a3FzbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/SO8sDJQB8LXBS/giphy.gif" alt="Imagem">
    </p>

    <!-- Skills -->
    <h2 align="center">🔥 Skills</h2>
    <div class="skills">
        <div>
            <h3>Programming Languages</h3>
            <img alt="Java" height="28" width="90" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
            <img alt="Js" height="28" width="90" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
            <img alt="Python" height="28" width="90" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
            <img alt="Swift" height="28" width="90" src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white">
            <img alt="C" height="28" width="50" src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
        </div>
        
        <div>
            <h3>Tools & Frameworks</h3>
            <img alt="Node.js" height="28" width="90" src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
            <img alt="React Native" height="28" width="90" src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
            <img alt="Git" height="28" width="90" src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">
            <img alt="Colab" height="28" width="90" src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252">
            <img alt="IntelliJ IDEA" height="28" width="90" src="https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white">
            <img alt="Xcode" height="28" width="90" src="https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white">
        </div>
    </div>

    <!-- Jogo da Cobrinha -->
    <h2 align="center">🐍 Jogo da Cobrinha</h2>
    <canvas id="snakeGame" width="400" height="400"></canvas>
    <script>
        const canvas = document.getElementById('snakeGame');
        const ctx = canvas.getContext('2d');
        const box = 20;
        const canvasSize = 400;
        const snake = [];
        let food = {};
        let score = 0;
        let direction;

        snake[0] = {
            x: 9 * box,
            y: 10 * box
        };

        function createFood() {
            food = {
                x: Math.floor(Math.random() * 19 + 1) * box,
                y: Math.floor(Math.random() * 19 + 3) * box
            };
        }

        function draw() {
            ctx.clearRect(0, 0, canvasSize, canvasSize);

            for (let i = 0; i < snake.length; i++) {
                ctx.fillStyle = (i === 0) ? "green" : "white";
                ctx.fillRect(snake[i].x, snake[i].y, box, box);
                ctx.strokeStyle = "red";
                ctx.strokeRect(snake[i].x, snake[i].y, box, box);
            }

            ctx.fillStyle = "red";
            ctx.fillRect(food.x, food.y, box, box);

            let snakeX = snake[0].x;
            let snakeY = snake[0].y;

            if (direction === "LEFT") snakeX -= box;
            if (direction === "UP") snakeY -= box;
            if (direction === "RIGHT") snakeX += box;
            if (direction === "DOWN") snakeY += box;

            if (snakeX === food.x && snakeY === food.y) {
                score++;
                createFood();
            } else {
                snake.pop();
            }

            const newHead = {
                x: snakeX,
                y: snakeY
            };

            if (snakeX < 0 || snakeX >= canvasSize || snakeY < 0 || snakeY >= canvasSize || collision(newHead, snake)) {
                clearInterval(game);
            }

            snake.unshift(newHead);
        }

        function collision(head, array) {
            for (let i = 0; i < array.length; i++) {
                if (head.x === array[i].x && head.y === array[i].y) {
                    return true;
                }
            }
            return false;
        }

        function directionHandler(event) {
            if (event.keyCode === 37 && direction !== "RIGHT") {
                direction = "LEFT";
            } else if (event.keyCode === 38 && direction !== "DOWN") {
                direction = "UP";
            } else if (event.keyCode === 39 && direction !== "LEFT") {
                direction = "RIGHT";
            } else if (event.keyCode === 40 && direction !== "UP") {
                direction = "DOWN";
            }
        }

        document.addEventListener("keydown", directionHandler);

        createFood();
        const game = setInterval(draw, 100);
    </script>
</body>
</html>
