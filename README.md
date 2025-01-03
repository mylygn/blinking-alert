<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blinking Alert</title>
    <style>
        @keyframes blinker {
            50% {
                opacity: 0;
            }
        }
        .blinking {
            font-size: 24px;
            color: red;
            animation: blinker 1s linear infinite;
            text-align: center;
            margin-top: 20%;
        }
    </style>
</head>
<body>
    <div class="blinking">Important Alert! Take Action!</div>
</body>
</html>
