# KeyMod
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        :root {
            --primary: #00d2ff;
            --secondary: #3a7bd5;
            --bg: #0f0f12;
            --card-bg: #1a1a20;
            --text: #e0e0e0;
            --accent: #ff0055;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        .header h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: -1px;
            color: white;
        }

        .header p {
            font-size: 1.2rem;
            opacity: 0.9;
            color: white;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 2px;
            border: 1px solid #333;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
            border-color: var(--primary);
        }

        .card h3 {
            color: var(--primary);
            margin-top: 0;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .plugin-tag {
            display: inline-block;
            background: #2a2a35;
            padding: 4px 10px;
            border-radius: 6px;
            font-size: 0.8rem;
            margin: 4px;
            border: 1px solid #444;
        }

        .feature-list {
            list-style: none;
            padding: 0;
        }

        .feature-list li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }

        .feature-list li::before {
            content: "▹";
            position: absolute;
            left: 0;
            color: var(--primary);
        }

        .footer {
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
            border-top: 1px solid #333;
            margin-top: 40px;
        }

        .highlight {
            color: var(--accent);
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <h1>KeyMod Beta v0.1</h1>
        <p>The Ultimate RocketGoal Enhancement Suite</p>
    </div>

    <div class="grid">
        <div class="card">
            <h3>🌐 Mod Purpose</h3>
            <p>A full-spectrum enhancement tool built for visibility, streamer safety, and next-gen performance tracking.</p>
            <ul class="feature-list">
                <li>Live Gameplay Visibility</li>
                <li>Streamer-Safe Overlays</li>
                <li>Performance Optimizer</li>
            </ul>
        </div>

        <div class="card">
            <h3>🔧 Core Runtime</h3>
            <ul class="feature-list">
                <li><strong>F2 / Backtick:</strong> Draggable UI Menu</li>
                <li><strong>Live HUD:</strong> Real-time MMR & Scoreboard</li>
                <li><strong>Shot Analysis:</strong> Post-match insights</li>
                <li><strong>Toast System:</strong> Full-width notifications</li>
            </ul>
        </div>
    </div>

    <h2 style="text-align:center; color: var(--primary);">🧩 Included Plugins</h2>
    <div class="grid">
        <div class="card">
            <h3>Stats & Training</h3>
            <div class="plugin-tag">Win Predictor</div>
            <div class="plugin-tag">Shot Analysis</div>
            <div class="plugin-tag">Playstyle Classifier</div>
            <div class="plugin-tag">Peak Ghost</div>
            <div class="plugin-tag">Rank Tracking</div>
        </div>

        <div class="card">
            <h3>Visual & Themes</h3>
            <div class="plugin-tag">Animated Backgrounds</div>
            <div class="plugin-tag">Visual FX (LUTs)</div>
            <div class="plugin-tag">Themes (GTA/KCorp)</div>
            <div class="plugin-tag">macOS Loading Screen</div>
        </div>

        <div class="card">
            <h3>Utility & Streamer</h3>
            <div class="plugin-tag">Auto Queue</div>
            <div class="plugin-tag">Streamer Tools</div>
            <div class="plugin-tag">16K Clip Recorder</div>
            <div class="plugin-tag">Optimizer</div>
        </div>
    </div>

    <div class="card" style="text-align: center;">
        <h3>🎨 UI & Customization</h3>
        <p>Featuring <span class="highlight">BakkesMod style</span> plus overrides for <strong>Vitality, NRG, and KCorp</strong>. Uses clean CSS gradients for maximum performance with zero remote image lag.</p>
    </div>

    <div class="footer">
        <p>Mod Architecture by <strong>@keydopz</strong> | Design inspired by RocketGoal Streamer UI</p>
    </div>
</div>

</body>
</html>
