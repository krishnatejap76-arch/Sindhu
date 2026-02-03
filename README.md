
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
