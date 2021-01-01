# merryhappyyy
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adieu 2020</title>

    <meta property="og:image" content=" 미리보기이미지">
<meta property="og:title" content="happy merry new year">
<meta property="og:description" content="신영..코딩 해보다..."> 


    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Stylish&display=swap" rel="stylesheet">

    <script src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/snow.js"></script>
    
    <style>
        * {
            font-family: 'Stylish', sans-serif;
        }
    
        body {
            background-color: #ffffff;
        }
    
        .envelope {
                    width: 1920px;
            height: 1080px;
    
            background-image: url(file:///Users/iseoyoung/Desktop/mail/mail.001.png);
            background-size: cover;
            background-position: center;
    
            margin: 0px auto 0px auto;

            cursor: pointer;
        }
    
        .envelope-msg {
            color: white;
            text-align: center;
        }
    
        .letter-close {
            display: block;
        }
    
        .letter-open {
            display: none;
        }
    
        .rtan {
            background-color: white;
    
            width: 780px;
            height: 1280px;
    
            background-image: url(file:///Users/iseoyoung/Desktop/연하장1.gif);
            background-size: cover;
            background-position: center;
    
            margin: 100px auto 0px auto;
    
            border-radius: 100px;
            border: 5px solid white;
    
            box-shadow: 0px 0px 10px 2px white;
        }
    
        .messegebox {
            background-color: ivory;
    
            width: 400px;
    
            margin: auto;
    
            color: brown;
    
            padding: 30px;
    
            font-size: 20px;
    
            line-height: 30px;
    
            box-shadow: 0px 0px 10px 2px white;
        }
    
        h1 {
            color: white;
            text-align: center;
    
            margin-top: 30px;
            margin-bottom: 30px;
        }
    
        .from {
            text-align: right;
    
            margin-bottom: 0px;
        }
    
        @media screen and (max-width: 760px) {
            .messegebox {
                width: 300px;
                padding: 20px;
            }
    
            .rtan {
                width: 150px;
                height: 150px;
                margin: 70px auto 0px auto;
            }
    
            h1 {
                font-size: 28px;
            }
    
            .envelope {
                margin: 150px auto 0px auto;
            }
        }
    </style>

    <script>
        function open_letter() {
            document.getElementsByClassName("letter-close")[0].style.display = 'none'
document.getElementsByClassName("letter-open")[0].style.display = 'block'
        }

        function go_rtan() {
        alert('dear you,')
    window.location.href='file:///Users/iseoyoung/Desktop/연하장1.gif'
        }
    </script>

</head>

<body>
    <div class="letter-close">
        function open_letter() {
        <div class="envelope" onclick="open_letter()"></div>
        <h2 class="envelope-msg">Open!</h2>
    </div>

    <div class="letter-open">
        <div class="rtan" onclick="go_rtan()"></div>
        <h1> happy merry new 2021 </h1>
        <div class="messegebox">
            dear you. <br />
            happy new year! <br />
            좋은 하루 좋은 한 해 보내. <br />
            늘 고맙습니다. 건강하세요!  <br />
            연말에 다 같이 못 봐서 아쉽다 <br />
            <p class="from">2021.12.31 서영 씀</p>
        </div>

    </div>

</body>

</html>
