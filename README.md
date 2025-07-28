<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的網站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            text-align: center;
        }
        .product {
            display: inline-block;
            margin: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 10px;
            width: 250px;
            background-color: white;
        }
        .product img {
            width: 100%;
            border-radius: 8px;
        }
        .product h3 {
            margin: 15px 0 10px;
        }
        .product a {
            display: inline-block;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        .product a:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>歡迎來到我的商店！</h1>
    </header>

    <div class="container">
        <h2>商品展示</h2>
        
        <!-- 商品 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/250x250" alt="商品1">
            <h3>商品名稱 1</h3>
            <p>這是商品描述。</p>
            <a href="https://line.me/R/ti/p/%40yourlineid" target="_blank">聯繫我們（LINE）</a>
            <a href="https://www.messenger.com/t/yourfacebookpage" target="_blank">聯繫我們（Facebook Messenger）</a>
        </div>
        
        <!-- 商品 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/250x250" alt="商品2">
            <h3>商品名稱 2</h3>
            <p>這是商品描述。</p>
            <a href="https://line.me/R/ti/p/%40yourlineid" target="_blank">聯繫我們（LINE）</a>
            <a href="https://www.messenger.com/t/yourfacebookpage" target="_blank">聯繫我們（Facebook Messenger）</a>
        </div>
    </div>
</body>
</html>
