<!DOCTYPE html>
<html lang="ja">

<head>
    <meta charset="UTF-8">
    <title>自己紹介</title>
    <link rel="stylesheet" href="style.css">

    <style>
        details {
            width: 600px;
            margin: 80px 20px;
        }

        summary {
            display: inline-block;
            padding: 15px 20px;
            background-color: #f3f2ef;
            border-radius: 8px;
            font-weight: bold;
            cursor: pointer;
            list-style: none;
        }

        summary:hover {
            background-color: #e5e5e5;
        }

        .news-item {
            padding: 20px 0;
            border-bottom: 1px solid #ccc;
        }
    </style>

</head>

<body>

    <h1>自己紹介ページ</h1>

    <p>こんにちは！大学生です。</p>

    <h2>趣味</h2>
    <p>ゲームやプログラミングが好きです。</p>

    <h2>お知らせ</h2>

    <details>

        <summary>さらに表示 ＋</summary>

        <div class="news-item">
            <p>2026/08/18</p>
            <p>AIについてのニュース</p>
        </div>

        <div class="news-item">
            <p>2026/08/17</p>
            <p>大学からのお知らせ</p>
        </div>

        <div class="news-item">
            <p>2026/08/13</p>
            <p>イベントについて</p>
        </div>

    </details>

</body>

</html>
