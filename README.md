<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Workspace</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: #f5f7fa;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            background: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            text-align: center;
            max-width: 480px;
            width: 90%;
        }
        h1 { font-size: 24px; color: #1a202c; margin-bottom: 12px; }
        p { font-size: 14px; color: #718096; line-height: 1.6; margin-bottom: 24px; }
        .status-badge {
            display: inline-block;
            background-color: #e6fffa;
            color: #234e52;
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 13px;
            font-weight: 500;
            border: 1px solid #b2f5ea;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Personal Site</h1>
        <p>Welcome to my static workspace. All internal services and routes are currently running normally.</p>
        <div class="status-badge">● System Status: Operational</div>
    </div>
</body>
</html>
