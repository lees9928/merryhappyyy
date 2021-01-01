# merryhappyyy

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hello 2021</title>

  
    <meta property="og:title" content="happy merry new year">
    <meta property="og:description" content="연하장이 도착했습니다"> 


    <link rel="preconnect" href="https://fonts.gstatic.com"> 
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@500&display=swap" rel="stylesheet">
    <script src="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/xmas/snow.js"></script>
    
    <style>
        * {
            font-family: 'Noto+Sans+KR:wght@500&display'
        }
    
        body {
            background-color="#f8d586";
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
    
            width: 390px;
            height: 640px;
    
            background-image:<iframe title="'backup'에서 업로드한 동영상" width="640" height="360" src="https://play-tv.kakao.com/embed/player/cliplink/415400496?service=player_share&autoplay=1" allowfullscreen frameborder="0" scrolling="no" allow="autoplay"></iframe>
            background-size: cover;
            background-position: center;
    
            margin: 80px auto 0px auto;
    
            border-radius: 100px;
            border: 5px solid white;
    
            box-shadow: 0px 10px 10px 2px white;
        }
    
        .messegebox {
            background-color: ivory;
    
            width: 500px;
    
            margin: auto;
    
            color: black;
    
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
            첫 연하장이라 이런 저런 시도를 해봤어요. 어떤가요? <br />
            좋은 하루 좋은 한 해 보내세요. <br />
            늘 고맙습니다. 건강하세요!  <br />
             <br />
            <p class="from">2021.12.31 서영 씀</p>
        </div>

    </div>

</body>

</html>
