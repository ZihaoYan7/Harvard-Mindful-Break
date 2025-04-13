<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A comfort place where you can rest your heart</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #ffe4e1, #ffd7e7); /* 粉红色渐变 */
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
        }
        .container {
            text-align: center;
            max-width: 600px;
            padding: 20px;
            border-radius: 10px;
            background: rgba(255, 255, 255, 0.8);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 2.5rem;
            color: #4a90e2;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            color: #333;
            line-height: 1.6;
            margin-bottom: 30px;
        }
        .background-image {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url("https://images.unsplash.com/photo-1507525428034-b623305aa183?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80");
            background-size: cover;
            background-position: center;
            opacity: 0.6;
            z-index: -1;
        }
        .button {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            font-size: 1.2rem;
            color: #fff;
            background-color: #4a90e2;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #3b78c3;
        }
    </style>
</head>
<body>
    <div class="background-image"></div>
    <div class="container">
        <h1>Harvard Mindful break 🧘</h1>
        <p>Here, you can relax and enjoy a moment of tranquility. Hopefully, this space will bring you warmth and comfort.</p >
        <button class="button" onclick="redirect('https://www.youtube.com/embed/inpok4MKVLM?autoplay=1&mute=1')">5-minute meditation video</button>
        <button class="button" onclick="redirect('https://www.youtube.com/watch?v=cEqZthCaMpo')">1-minute meditation video</button>
    </div>

    <script>
        // 定义一个函数来跳转到指定的网页
        function redirect(url) {
            window.location.href = url;
        }
    </script>
</body>
</html>
