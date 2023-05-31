<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <style>
        main {width:100%; height: 200px; }
        a { text-decoration:none; }
        img { max-width: 100%;}
        .logo {
            width: 200px;
            margin-top:10px
        }
        .onlynav {
            display: flex;
            list-style: none;
        }
        .onlynav li { margin-left: 20px; }
        .onlynav a:hover { color: brown; }
        .headerAndnav {
            display:flex;
            justify-content:space-between;
        }
        .header-wrap { padding: 0 5%; }
        .webcontent {
            text-align: center;
            margin-top:10%;
        }
        .mybackground {
            background-size: cover;
            background-position: center top;
            background-repeat: no-repeat;
        }
        main {
            background-image: url(sea.jpg),linear-gradient(to top right, red, yellow 30%, green);
            background-blend-mode: hard-light;
            height: 250px;
            margin-bottom: 10px;
        }
        main .page-title {
            text-align: center;
         color: blue;
         font-size: 3rem;
        }
        footer {
            text-align: center;
            background: lightgreen;
            padding: 3px 0;
        }
        footer p {
            color: blue;
            font-size: 1rem;
        }
        .grid {
            display: grid;
            gap: 20px;
            grid-template-columns: repeat(5, minmax(250px, 1fr));
            margin-top: 10px;
            margin-bottom: 30px;
        }
        .author, .booktitle {text-align: center;}

    </style>
</head>
<body>
    <main id="home" class="mybackground">
        <header class="headerAndnav header-wrap">
            <img class="logo" src="sseremove.png" alt="王者歸來logo">
            <nav>
                <u1 class="onlynav">
                    <li><a href="news.html">最新消息</a></li>
                    <li><a href="query.html">查詢</a></li>
                    <li><a href="mail.html">聯絡</a></li>
                </u1>
            </nav>
        </header>
        <div class="wrapper">
            <h1 class="page-title">洪錦魁最新著作</h1>
        </div>
    </main>
    <div class="wrapper grid">
        <div class="mybook">
            <img src="book/dm1920.jpg" alt="">
            <p class="booktitle">Python網路爬蟲</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2032.jpg" alt="">
            <p class="booktitle">最完整跨平台網頁設計</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2039.jpg" alt="">
            <p class="booktitle">Python最強入門邁向頂尖高手之路</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2101.jpg" alt="">
            <p class="booktitle">演算法最強彩色圖鑑+Python程式實作</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2118.jpg" alt="">
            <p class="booktitle">Excel函數庫</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2125.jpg" alt="">
            <p class="booktitle">機器學習基礎數學</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2132.jpg" alt="">
            <p class="booktitle">機器學習基礎微積分</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2137.jpg" alt="">
            <p class="booktitle">Excel VBA上冊</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2138.jpg" alt="">
            <p class="booktitle">Excel VBA下冊</p>
         <p class="author">作者：洪錦魁</p>
        </div>
        <div class="mybook">
            <img src="book/dm2142.jpg" alt="">
            <p class="booktitle">Power BI最強入門</p>
         <p class="author">作者：洪錦魁</p>
        </div>
    </div>
    <footer>
        <div class="footer-wrapper">
            <p>&reg 版權所有 &reg</p>
        </div>
    </footer>
</body>
</html>
