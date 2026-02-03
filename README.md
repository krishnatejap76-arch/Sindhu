

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Kutti ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            background: #fff0f3; /* Soft pinkish white */
            font-family: 'Arial', sans-serif;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Continuous Floating Background */
        .bg-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
            pointer-events: none;
        }

        .float-icon {
            position: absolute;
            bottom: -50px;
            opacity: 0.6;
            animation: moveUp 5s linear infinite;
        }

        @keyframes moveUp {
            to {
                transform: translateY(-110vh) rotate(360deg);
            }
        }

        /* Main Card */
        .card {
            background: rgba(255, 255, 255, 0.95);
            padding: 40px;
            border-radius: 25px;
            box-shadow: 0 20px 50px rgba(255, 77, 109, 0.3);
            text-align: center;
            border: 5px solid #ff4d6d;
            z-index: 10;
            width: 320px;
            position: relative;
        }

        h1 {
            color: #ff4d6d;
            font-size: 1.8rem;
            margin-bottom: 40px;
            line-height: 1.4;
        }

        .buttons {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 100px;
        }

        button {
            padding: 15px 30px;
