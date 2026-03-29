# hover-box-demo
index.html

فكرة الكود:
إن فيه box في منتصف الصفحة، ولما المستخدم يعمل hover عليه بيحصل rotate بشكل smooth باستخدام

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="stile.Css">
</head>
<body>
    <div class="box"><h1>Hover Me</h1></div>
</body>
</html>


<!-- <stile> -->

  
body{
    margin: 0;
    padding: 0;
    background: #0e2136;
    height: 100vh;
    display: flex;
    justify-content:center;
    align-items: center;
}

.box{
    background-color: #50749e; 
    height: 200px;
    aspect-ratio: 1/1;
    border-radius: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: 0.5s;
}

.box:hover{
    transform: rotate(10deg) scale(1.05);
    background-color: #00aaff;
}
