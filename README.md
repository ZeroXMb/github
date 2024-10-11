<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" href="style.css">
    <script type="text/javascript" src="script.js" defer></script>
    <title>Git hub</title>
    <style>
        img {
            float: right;
            width: 200px;
            margin-left: 20px;
        }
    </style>
</head>
<body>
    <img src="https://upload.wikimedia.org/wikipedia/commons/c/c2/GitHub_Invertocat_Logo.svg" alt="GitHub Logo">
    <h1>Команди Git hub</h1>
    <p>Основні команди</p>
    <ul>
        <li>git init — ініціалізує новий Git репозиторій.</li>
        <li>git clone &lt;url&gt; — клонування існуючого репозиторію.</li>
        <li>git status — показує статус змін у репозиторії.</li>
        <li>git add &lt;файл&gt; — додає файл до індексу.</li>
        <li>git add . — додає всі зміни в поточній директорії.</li>
        <li>git commit -m "повідомлення" — фіксує зміни з повідомленням.</li>
        <li>git log — показує історію комітів.</li>
        <li>git diff — показує різницю між змінами.</li>
    </ul>
    <br>
    <p>Робота з гілками</p>
    <ul>
        <li>git branch — показує всі гілки.</li>
        <li>git branch &lt;назва-гілки&gt; — створює нову гілку.</li>
        <li>git checkout &lt;назва-гілки&gt; — переключається на вказану гілку.</li>
        <li>git checkout -b &lt;назва-гілки&gt; — створює нову гілку і переходить на неї.</li>
        <li>git merge &lt;назва-гілки&gt; — об'єднує вказану гілку в поточну.</li>
        <li>git branch -d &lt;назва-гілки&gt; — видаляє вказану гілку.</li>
        <li>git branch -D &lt;назва-гілки&gt; — примусово видаляє гілку.</li>
    </ul>
    <br>
    <p>Робота з віддаленими репозиторіями</p>
    <ul>
        <li>git remote -v — показує список віддалених репозиторіїв.</li>
        <li>git remote add &lt;назва&gt; &lt;url&gt; — додає новий віддалений репозиторій.</li>
        <li>git remote remove &lt;назва&gt; — видаляє віддалений репозиторій.</li>
        <li>git fetch &lt;назва&gt; — отримує зміни з віддаленого репозиторію.</li>
        <li>git pull &lt;назва&gt; &lt;гілка&gt; — отримує і об'єднує зміни з віддаленого репозиторію.</li>
        <li>git push &lt;назва&gt; &lt;гілка&gt; — відправляє зміни до віддаленого репозиторію.</li>
    </ul>
    <br>
    <p>Робота з тегами</p>
    <ul>
        <li>git tag — показує список тегів.</li>
        <li>git tag &lt;назва-тега&gt; — створює тег для останнього коміту.</li>
        <li>git tag -a &lt;назва-тега&gt; -m "повідомлення" — створює анотаційний тег.</li>
        <li>git push origin &lt;назва-тега&gt; — відправляє тег до віддаленого репозиторію.</li>
    </ul>
</body>
</html>
