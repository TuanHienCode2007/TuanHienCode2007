<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="./assets/img/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="./assets/css/base.css">
    <link rel="stylesheet" href="./assets/css/style.css">
    <link rel="stylesheet" href="./assets/css/reponsive.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;500;600;700&display=swap" rel="stylesheet">
    <title>N.Điệp's Birthday</title>
</head>
<body>
    <div class="app">
        <div class="wishes">
            <h1 class="title">H A P P Y B I R T H D A Y</h1>
            <div class="about">
                <div class="introduce">
                    <h2>Hello, I'm T.Hiền
                        <br>
                        hôm nay là sinh nhật tuổi 15 của mình, nên mình cũng muốn làm web này như là món quà tặng chính bản thân mình, 
                        và cũng là cách để mình ôn lại những kiến thức đã học được trong thời gian qua. 
                    </h2>
                </div>
                <div class="gallery">
                    <div class="gallery-item">
                        <img src="./assets/img/giphy.gif" alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="tome">
            <div class="tome-content">
                <h1 class="tome-heading">
                    Gửi lời chúc đến mình nhé 😘😘
                    <span class="note">Sẽ gửi trực tiếp đến mình luônn</span>
                </h1>
                <span>Tên bạn: </span>
                <input type="text" class="your-name" placeholder="Chưa nhập tên đã biết đáng iu rùi :3" required>
                <span>Chúc gì vậy nè?</span>
                <textarea class="des" name="" id="" cols="30" rows="5" placeholder="Viết gì đó đi 🥺" required></textarea>
                <button class="submit">Gửi</button>
            </div>
        </div>
        <div class="modal modal-thanks">
            <h2 class="thank-you">Cảm ơn bạn rất nhiều 😘😘</h2>
            <p>Lời chúc đã được gửi đến mình</p>
            <div class="btn-wrap">
                <button class="btn">Hehe, không có gì nha</button>
                <button class="btn">Ờ =))</button>
            </div>
        </div>
        <div class="modal-error modal">
            <h2 class="thank-you">Chưa chúc gì mà đã gửi rồi à 🥺🥺</h2>
            <div class="btn-wrap">
                <button class="btn">Kệ mày =))</button>
                <button class="btn">Ờ thì chúc 😒😒</button>
            </div>
        </div>
        <div class="modal-errorName modal">
            <h2 class="thank-you">Chưa ghi tên kìa 😒😒</h2>
            <div class="btn-wrap">
                <button class="btn">Quên =))</button>
                <button class="btn">Ẩn danh k đc à 😒😒</button>
            </div>
        </div>
        <div class="layout"></div>
    </div>
    <div class="begin">
        <h2>Cảm ơn bạn đã dành chút thời gian để vào đâyy 😘😘</h2>
        <button class="start">Let's Party 🤩🕺</button>
    </div>
    <audio id="mainAudio" src="./song.mp3"></audio>
    <script src="./main.js"></script>
</body>
</html>
