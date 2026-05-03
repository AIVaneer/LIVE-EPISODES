# LIVE-EPISODES
Education/ Interactive 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LIVE-EPISODES // PCVR</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: radial-gradient(circle at center, #1a0033, #000000);
            color: #00ff9d;
            font-family: 'Courier New', monospace;
            text-align: center;
            overflow: hidden;
        }
        .neon {
            text-shadow: 0 0 10px #00ff9d,
                        0 0 20px #00ff9d,
                        0 0 40px #ff00ff;
        }
        .container {
            max-width: 800px;
            margin: 100px auto;
            padding: 40px;
        }
        h1 {
            font-size: 3.5em;
            margin-bottom: 10px;
            letter-spacing: 4px;
        }
        p {
            font-size: 1.3em;
            opacity: 0.9;
        }
        .btn {
            display: inline-block;
            margin: 30px 15px;
            padding: 15px 40px;
            background: transparent;
            color: #00ff9d;
            border: 2px solid #00ff9d;
            font-size: 1.2em;
            text-decoration: none;
            transition: all 0.3s;
        }
        .btn:hover {
            background: #00ff9d;
            color: #000;
            box-shadow: 0 0 30px #00ff9d;
        }
        .scanline {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(transparent, rgba(0, 255, 157, 0.05), transparent);
            animation: scan 4s linear infinite;
            pointer-events: none;
        }
        @keyframes scan {
            0% { transform: translateY(-100%); }
            100% { transform: translateY(100%); }
        }
    </style>
</head>
<body>
    <div class="scanline"></div>
    <div class="container">
        <h1 class="neon">LIVE-EPISODES</h1>
        <p>PCVR EDTECH // INTERACTIVE BROADCAST</p>
        <p style="margin: 40px 0; font-size: 1.1em;">
            Real-time coding missions.<br>
            Drop in. Fix the code. Level up.
        </p>
        
        <a href="#" class="btn">START EPISODE 01</a>
        <a href="https://github.com/AIVaneer/PCVR-EdTech" class="btn">MAIN PCVR HUB</a>
        
        <p style="margin-top: 80px; font-size: 0.9em; opacity: 0.7;">
            Always for good, never for bad.<br>
            Built by AIVaneer • 2026
        </p>
    </div>
</body>
</html>
