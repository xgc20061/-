<!DOCTYPE html>  
<html lang="zh-CN">  
<head>  
    <meta charset="UTF-8">  
    <title>世界美食之旅</title>  
    <style>  
        body {  
            font-family: 'Microsoft YaHei', Arial, sans-serif;  
            background-color: #FFF4E0;  
            color: #333;  
            line-height: 1.6;  
        }  
        .container {  
            max-width: 1000px;  
            margin: 0 auto;  
            padding: 20px;  
            background-color: #FFFFFF;  
            box-shadow: 0 0 10px rgba(0,0,0,0.1);  
        }  
        .header {  
            background-color: #FF6B6B;  
            color: white;  
            text-align: center;  
            padding: 20px;  
        }  
        .nav {  
            background-color: #4ECDC4;  
            padding: 10px;  
            text-align: center;  
        }  
        .nav a {  
            color: white;  
            margin: 0 15px;  
            text-decoration: none;  
        }  
        .content {  
            display: flex;  
            margin-top: 20px;  
        }  
        .sidebar {  
            width: 250px;  
            background-color: #F7FFF7;  
            padding: 15px;  
        }  
        .main-content {  
            flex-grow: 1;  
            padding: 0 20px;  
        }  
        img {  
            max-width: 100%;  
            height: auto;  
        }  
    </style>  
</head>  
<body>  
    <div class="container">  
        <div class="header">  
            <h1>🌍 世界美食之旅 🍽️</h1>  
        </div>  
        
        <div class="nav">  
            <a href="#chinese">中国美食</a>  
            <a href="#italian">意大利美食</a>  
            <a href="#japanese">日本料理</a>  
            <a href="#mexican">墨西哥菜系</a>  
        </div>  

        <div class="content">  
            <div class="sidebar">  
                <h3>推荐链接</h3>  
                <ul>  
                    <li><a href="https://www.epicurious.com" target="_blank">Epicurious美食网</a></li>  
                    <li><a href="https://www.bbcgoodfood.com" target="_blank">BBC美食频道</a></li>  
                    <li><a href="#video">美食视频集锦</a></li>  
                </ul>  
            </div>  

            <div class="main-content">  
                <section id="chinese">  
                    <h2>🥢 中国美食</h2>  
                    <img src="chinese_cuisine.jpg" alt="中国美食">  
                    <p>中国美食博大精深，八大菜系各具特色。从川菜的麻辣到粤菜的清淡，展现了丰富的烹饪智慧。</p>  
                    <a href="#top">返回顶部</a>  
                </section>  

                <section id="italian">  
                    <h2>🍝 意大利美食</h2>  
                    <img src="italian_cuisine.jpg" alt="意大利美食">  
                    <p>披萨、意大利面、提拉米苏，意大利美食以其新鲜食材和精细烹饪技艺闻名世界。</p>  
                    <a href="#top">返回顶部</a>  
                </section>  

                <section id="video">  
                    <h2>🎥 美食视频</h2>  
                    <video width="100%" controls>  
                        <source src="world_cuisine.mp4" type="video/mp4">  
                        您的浏览器不支持视频播放  
                    </video>  
                </section>  
            </div>  
        </div>  
    </div>  
</body>  
</html>
