<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pallavi Amarlapudi | Portfolio</title>
    <style>
        /* General Styles */
        body {
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            font-family: 'Poppins', sans-serif;
            text-align: center;
            background: linear-gradient(135deg, #1e1e2f, #3a3a5e);
            color: white;
        }

        /* Name Styling */
        .name {
            font-size: 3rem;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;
            background: linear-gradient(90deg, #ff6b6b, #f7b42c);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: fadeIn 2s ease-in-out;
        }

        /* Subtitle */
        .subtitle {
            font-size: 1.5rem;
            margin-top: 10px;
            opacity: 0;
            animation: fadeIn 3s ease-in-out forwards;
        }

        /* Animations */
        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <h1 class="name">Pallavi Amarlapudi</h1>
    <p class="subtitle">Welcome to My Portfolio</p>
</body>
</html>
