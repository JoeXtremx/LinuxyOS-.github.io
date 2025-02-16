<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LinuxyOS - The Future of Open Source</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
            text-align: center;
            position: relative;
            overflow-y: auto;
            min-height: 100vh;
        }
        header {
            padding: 20px;
            font-size: 2rem;
            font-weight: bold;
            background: linear-gradient(90deg, #ff8c00, #ff2e63);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: fadeIn 2s ease-in-out;
        }
        .container {
            padding: 50px 20px;
            max-width: 900px;
            margin: auto;
            animation: slideUp 1.5s ease-in-out;
        }
        .btn {
            background: #444;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            color: #aaa;
            font-size: 1.2rem;
            display: inline-block;
            margin-top: 20px;
            cursor: not-allowed;
            opacity: 0.6;
            animation: pulse 2s infinite ease-in-out;
            transition: none;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes pulse {
            0% { opacity: 0.6; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.05); }
            100% { opacity: 0.6; transform: scale(1); }
        }
        .glowing {
            position: fixed;
            width: 100vw;
            height: 100vh;
            top: 0;
            left: 0;
            pointer-events: none;
            background: radial-gradient(circle, rgba(255, 46, 99, 0.2) 10%, transparent 80%) center;
            animation: glowMove 5s infinite alternate ease-in-out;
        }
        @keyframes glowMove {
            from { transform: translateY(-10%) translateX(-10%); }
            to { transform: translateY(10%) translateX(10%); }
        }
    </style>
</head>
<body>
    <div class="glowing"></div>
    <header>LinuxyOS - The Future of Gamers'OS</header>
    <div class="container">
        <h2>Experience Speed, Security, and Flexibility</h2>
        <p>LinuxyOS is a next-generation open-source operating system built for speed, security, and customization. Designed for developers, gamers, and everyday users.</p>
        
        <h2>Overview</h2>
        <p>LinuxyOS is a powerful and lightweight operating system that combines modern features with open-source flexibility. It is optimized for performance, security, and ease of use.</p>
        
        <h2>Key Features</h2>
        <ul>
            <li>Lightning-fast performance</li>
            <li>Advanced security features</li>
            <li>Highly customizable interface</li>
            <li>Wide range of software compatibility</li>
            <li>Minimal system resource usage</li>
        </ul>
        
        <h2>Minimum Requirements</h2>
        <ul>
            <li>Processor: Dual-core 1.5 GHz</li>
            <li>RAM: 2GB</li>
            <li>Storage: 10GB available space</li>
            <li>Graphics: Integrated GPU</li>
        </ul>
        
        <h2>Recommended Requirements</h2>
        <ul>
            <li>Processor: Quad-core 2.5 GHz or higher</li>
            <li>RAM: 8GB</li>
            <li>Storage: 15GB available space</li>
            <li>Graphics: Dedicated GPU with OpenGL support</li>
        </ul>
        
        <a href="#" class="btn">Coming Soon</a>
        
      <p>Credits to Shark-dev (aka ahmed shafik) & JoeXtremx (aka Joe)
    </div>
</body>
</html>
