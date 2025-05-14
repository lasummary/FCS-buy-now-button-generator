<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 1. APP 名称 (也用作网页标题) -->
    <title>Custom Buy It Now  Button - enhance your checkout experience</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f6f8;
            color: #333;
        }
        .container {
            width: 90%;
            max-width: 960px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
            margin-bottom: 20px;
        }
        .logo {
            max-width: 150px; /* 根据你的logo调整大小 */
            height: auto;
            margin-bottom: 15px;
        }
        h1 {
            color: #2c3e50;
            margin-bottom: 10px;
        }
        h2 {
            color: #34495e;
            margin-top: 30px;
            margin-bottom: 15px;
            border-bottom: 2px solid #3498db;
            padding-bottom: 5px;
            display: inline-block;
        }
        p {
            margin-bottom: 15px;
            color: #555;
        }
        .app-description {
            font-size: 1.1em;
        }
        .screenshots {
            display: flex; /* 使用flex布局让图片并排 */
            flex-wrap: wrap; /* 如果屏幕不够宽，图片会换行 */
            gap: 20px; /* 图片之间的间距 */
            justify-content: center; /* 图片居中对齐 */
            margin-top: 20px;
        }
        .screenshots img {
            max-width: 100%; /* 图片最大宽度为其容器宽度 */
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-shadow: 2px 2px 8px rgba(0,0,0,0.05);
            /* 为flex item设置一个基础宽度，可以调整 */
            flex-basis: calc(50% - 10px); /* 两张图时，每张占大约一半宽度，减去gap的一半 */
            max-width: 400px; /* 单张图片的最大宽度，避免在大屏幕上过大 */
        }
        .cta-button { /* Call to Action Button */
            display: inline-block;
            background-color: #2ecc71; /* 绿色 */
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }
        .cta-button:hover {
            background-color: #27ae60;
        }
        footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid #eee;
            font-size: 0.9em;
            color: #777;
        }

        /* 响应式调整：小屏幕上图片堆叠 */
        @media (max-width: 768px) {
            .screenshots img {
                flex-basis: 100%; /* 小屏幕上图片占满一行 */
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <!-- 2. 你的网站LOGO图片URL -->
            <img src="images/applogo.png" alt="Custom Buy It Now  Button Logo" class="logo">

            <!-- 3. APP 名称 -->
            <h1>Custom Buy It Now  Button</h1>
            <p>Replace the default dynamic checkout buttons with a single, clear "Buy it now" button.</p>
        </header>

        <main>
            <section id="description">
                <h2>About this APP</h2>
                <!-- 4. APP 描述 (可以分成几段) -->
                <p class="app-description">
                   This app solves the problem of crowded product pages and potentially confusing multiple payment options by providing a single, clear "Buy it now" button. It allows merchants to effectively replace the default dynamic checkout buttons and the "More payment options" link. Instead of presenting multiple express checkout options upfront, customers are directed straight from the product page to a unified checkout experience when clicking your dedicated button. 
                </p>
                <!-- 你可以根据需要添加更多段落 -->
            </section>

            <section id="features">
                <h2>Key features</h2>
                <ul>
                    <li>Add a Dedicated "Buy It Now" Button</li>
                    <li>Simplify Payment Options</li>
                    <li>Customize Button Appearance</li>
                    <!-- 根据需要添加更多特性 -->
                </ul>
            </section>

            <section id="screenshots-gallery">
                <h2>Button Appearance</h2>
                <div class="screenshots">
                    <!-- 5. APP 示例图片 1 -->
                    <img src="images/before.png" alt="before app installed">

                    <!-- 6. APP 示例图片 2 -->
                    <img src="images/after.png" alt="after app installed">
                </div>
            </section>

        </main>

        <footer>
            <p>© 2025 FCStools All rights reserved.</p>
            <p>
                <a href="【你的隐私政策页面链接】">隐私政策</a> |
                <a href="【你的服务条款页面链接】">服务条款</a> |
                <a href="【你的联系方式或支持页面链接】">联系我们</a>
            </p>
        </footer>
    </div>
</body>
</html>
