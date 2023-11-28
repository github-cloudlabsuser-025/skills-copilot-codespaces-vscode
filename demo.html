<!DOCTYPE html>
<html>
<head>
    <title>Snake Game</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #333;
            margin: 0;
            padding: 0;
            color: #fff;
            font-family: Arial, sans-serif;
        }
        #game {
            border: 1px solid #fff;
        }
        #score {
            position: absolute;
            top: 10px;
            left: 10px;
        }
    </style>
</head>
<body>
    <div id="score">Score: 0</div>
    <canvas id="game" width="512" height="512"></canvas>
    <script>
        let canvas = document.getElementById('game');
        let context = canvas.getContext('2d');
        let scoreElement = document.getElementById('score');

        let box = 32;
        let score = 0;
        let snake = [];
        snake[0] = { x: 8 * box, y: 8 * box };
        let direction = "right";
        let food = {
            x: Math.floor(Math.random() * 15 + 1) * box,
            y: Math.floor(Math.random() * 15 + 1) * box
        }

        function createBG() {
            context.fillStyle = "#4caf50";
            context.fillRect(0, 0, 16 * box, 16 * box);
        }

        function createSnake() {
            for (i = 0; i < snake.length; i++) {
                context.fillStyle = i == 0 ? "darkgreen" : "green";
                context.fillRect(snake[i].x, snake[i].y, box, box);
            }
        }

        function drawFood() {
            context.fillStyle = "red";
            context.fillRect(food.x, food.y, box, box);
        }
        function update(event) {
            if (event.keyCode == 37 && direction != 'right') direction = 'left';
            if (event.keyCode == 38 && direction != 'down') direction = 'up';
            if (event.keyCode == 39 && direction != 'left') direction = 'right';
            if (event.keyCode == 40 && direction != 'up') direction = 'down';
        }
       

        document.addEventListener('keydown', update);

        // Rest of your code...

        function startGame() {
            if (snake[0].x > 15 * box && direction == "right") snake[0].x = 0;
            if (snake[0].x < 0 && direction == 'left') snake[0].x = 16 * box;
            if (snake[0].y > 15 * box && direction == "down") snake[0].y = 0;
            if (snake[0].y < 0 && direction == 'up') snake[0].y = 16 * box;

            for (i = 1; i < snake.length; i++) {
                if (snake[0].x == snake[i].x && snake[0].y == snake[i].y) {
                    clearInterval(game);
                    alert('Game Over :(');
                }
            }

            createBG();
            createSnake();
            drawFood();

            let snakeX = snake[0].x;
            let snakeY = snake[0].y;

            if (direction == "right") snakeX += box;
            if (direction == "left") snakeX -= box;
            if (direction == "up") snakeY -= box;
            if (direction == "down") snakeY += box;
            // Rest of your code...

            if (snakeX != food.x || snakeY != food.y) {
                snake.pop();
            } else {
                food.x = Math.floor(Math.random() * 15 + 1) * box;
                food.y = Math.floor(Math.random() * 15 + 1) * box;
                score++;
                scoreElement.innerText = 'Score: ' + score;
            }
            let newHead = {
                x: snakeX,
                y: snakeY
            }

            snake.unshift(newHead);

            // Rest of your code...
        }

        let game = setInterval(startGame, 100);
    </script>
</body>
</html>
