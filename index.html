<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ビンゴ - 抽選画面 
    </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@700&family=M+PLUS+Rounded+1c:wght@800&family=Kosugi+Maru&display=swap" rel="stylesheet">
    <style>
        *, *::before, *::after{box-sizing:border-box;margin:0;padding:0}
        :root{
            --color-bg-dark-purple:#3a1c6a;--color-bg-light-purple:#5c3b8c;
            --color-pop-pink:#ff69b4;--color-pop-blue:#00ffff;
            --color-pop-yellow:#ffee00;--color-pop-green:#00ff7f;
            --color-text-white:#fff;--color-text-dark:#333;
            --shadow-text:3px 3px 0 #ffee00,6px 6px 0 rgba(0,0,0,.4);
            --shadow-text-number:6px 6px 0 #ff69b4,9px 9px 0 rgba(0,0,0,.5);
            --shadow-element:4px 4px 0 #00ffff,7px 7px 0 rgba(0,0,0,.3);
            --shadow-button:0 0 10px #ff69b4,0 0 20px #00ff7f;
            --font-japanese:'Kosugi Maru','M PLUS Rounded 1c',sans-serif;
            --font-numbers:'Chakra Petch',sans-serif
        }
        body{
            font-family:var(--font-japanese);display:flex;flex-direction:column;
            justify-content:center;align-items:center;min-height:100vh;
            background:linear-gradient(135deg,var(--color-bg-dark-purple),var(--color-bg-light-purple));
            background-size:250% 250%;animation:gradient-shift 12s ease infinite alternate;
            color:var(--color-text-white);overflow:hidden;position:relative;
            text-shadow:1px 1px 2px rgba(0,0,0,.3)
        }
        @keyframes gradient-shift{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
        .background-shapes{
            position:absolute;top:0;left:0;width:100%;height:100%;overflow:hidden;
            z-index:0;pointer-events:none
        }
        .shape{opacity:.5;animation:move-and-scale-shape 20s infinite linear;will-change:transform,opacity}
        .shape.circle{background-color:var(--color-pop-yellow);border-radius:50%}
        .shape.square{background-color:var(--color-pop-green);transform:rotate(45deg)}
        .shape.triangle{width:0;height:0;border-left:75px solid transparent;border-right:75px solid transparent;border-bottom:120px solid var(--color-pop-pink)}
        /* 図形スタイル */
        .shape.hexagon{
            background-color: var(--color-pop-blue);
            width: 120px; height: 69px;
            position: relative;
        }
        .shape.hexagon::before,
        .shape.hexagon::after {
            content: "";
            position: absolute;
            width: 0; height: 0;
            border-left: 60px solid transparent;
            border-right: 60px solid transparent;
        }
        .shape.hexagon::before {
            bottom: 100%;
            border-bottom: 34.5px solid var(--color-pop-blue);
        }
        .shape.hexagon::after {
            top: 100%;
            border-top: 34.5px solid var(--color-pop-blue);
        }
        .shape.star {
            background-color: var(--color-pop-pink);
            width: 0; height: 0;
            border-right: 75px solid transparent;
            border-left: 75px solid transparent;
            border-bottom: 52.5px solid var(--color-pop-pink);
            position: relative;
            transform: rotate(35deg);
        }
        .shape.star::before {
            content: "";
            width: 0; height: 0;
            border-right: 75px solid transparent;
            border-left: 75px solid transparent;
            border-top: 52.5px solid var(--color-pop-pink);
            position: absolute;
            top: 22.5px;
            left: -75px;
        }
        .shape.diamond {
            background-color: var(--color-pop-yellow);
            width: 120px; height: 120px;
            transform: rotate(45deg);
        }
        .shape.oval {
            background-color: var(--color-pop-green);
            width: 150px; height: 90px;
            border-radius: 50%;
        }
        .shape.plus {
            background-color: var(--color-pop-blue);
            width: 120px; height: 120px;
            position: relative;
        }
        .shape.plus::before,
        .shape.plus::after {
            content: "";
            background-color: var(--color-pop-blue);
            position: absolute;
        }
        .shape.plus::before { /* Horizontal bar */
            width: 100%;
            height: 30%;
            top: 35%;
            left: 0;
        }
        .shape.plus::after { /* Vertical bar */
            width: 30%;
            height: 100%;
            top: 0;
            left: 35%;
        }

        /* 図形の初期サイズと位置、アニメーション時間 */
        .shape:nth-child(1){top:10%;left:15%;width:150px;height:150px;animation-duration:22s}
        .shape:nth-child(2){top:60%;left:80%;width:180px;height:180px;animation-duration:25s}
        .shape:nth-child(3){top:30%;left:5%;width:225px;height:90px;animation-duration:28s}
        .shape:nth-child(4){top:85%;left:40%;width:135px;height:135px;animation-duration:20s}
        .shape:nth-child(5){top:5%;left:70%;animation-duration:23s}
        /* 新しい図形の位置とアニメーション時間 */
        .shape:nth-child(6){top:20%;left:40%;animation-duration:26s}
        .shape:nth-child(7){top:70%;left:10%;animation-duration:21s}
        .shape:nth-child(8){top:45%;left:90%;animation-duration:24s}
        .shape:nth-child(9){top:80%;left:60%;animation-duration:27s}
        .shape:nth-child(10){top:15%;left:55%;animation-duration:19s}

        /* アニメーション中のscale値を調整 */
        @keyframes move-and-scale-shape{
            0%{transform:translate(0,0) scale(1.5) rotate(0deg);opacity:.5}
            25%{transform:translate(30vw,22.5vh) scale(2.1) rotate(90deg);opacity:.6}
            50%{transform:translate(60vw,-7.5vh) scale(1.8) rotate(180deg);opacity:.4}
            75%{transform:translate(15vw,-30vh) scale(2.25) rotate(270deg);opacity:.7}
            100%{transform:translate(0,0) scale(1.5) rotate(360deg);opacity:.5}
        }
        .bingo-container{
            display:flex;flex-direction:column;align-items:center;gap:25px;width:95%;max-width:1100px;
            height:90vh;justify-content:space-between;padding:25px 0;box-sizing:border-box;
            transition:opacity .5s ease-out;z-index:1;background-color:rgba(0,0,0,.4);
            border-radius:20px;backdrop-filter:blur(6px);border:4px solid var(--color-pop-pink);
            box-shadow:0 0 15px var(--color-pop-blue),0 0 30px var(--color-pop-green)
        }
        .bingo-container.hidden{opacity:0;pointer-events:none}
        .current-number-section{
            background-color:var(--color-pop-blue);border-radius:30px;padding:30px 50px;
            box-shadow:var(--shadow-element);text-align:center;width:85%;max-width:600px;
            border:6px solid var(--color-pop-yellow);flex-shrink:0;position:relative;overflow:hidden
        }
        .current-number-label{
            font-family:var(--font-japanese);font-size:3.5em;margin-bottom:15px;
            color:var(--color-text-white);text-shadow:var(--shadow-text);
            animation:text-float-vibrant 1.8s infinite ease-in-out
        }
        @keyframes text-float-vibrant{
            0%{transform:translateY(0);text-shadow:var(--shadow-text)}
            50%{transform:translateY(-5px);text-shadow:5px 5px 0 #00ff7f,8px 8px 0 rgba(0,0,0,.5)}
            100%{transform:translateY(0);text-shadow:var(--shadow-text)}
        }
        .current-number{
            font-family:var(--font-numbers);font-size:14em;font-weight:700;
            color:var(--color-text-white);line-height:1;
            text-shadow:var(--shadow-text-number);
            animation:number-pulse-vibrant .8s infinite alternate;
            will-change:transform,text-shadow
        }
        @keyframes number-pulse-vibrant{
            0%{transform:scale(1);text-shadow:var(--shadow-text-number)}
            50%{transform:scale(1.03);text-shadow:8px 8px 0 #ffee00,12px 12px 0 rgba(0,0,0,.6)}
            100%{transform:scale(1);text-shadow:var(--shadow-text-number)}
        }
        .drawn-numbers-section{
            background-color:var(--color-pop-green);border-radius:25px;
            padding:50px; /* 図形たち */
            width:98%; /* 図形の */
            max-width: 900px; /* 大きさ */
            flex-grow:1;display:flex;flex-direction:column;box-shadow:var(--shadow-element);
            border:6px solid var(--color-pop-pink);min-height:0;
            overflow-y: auto; /* スクロールを許可 */
        }
        .drawn-numbers-label{
            font-family:var(--font-japanese);font-size:3.2em; 
            margin-bottom:25px; 
            text-align:center;color:var(--color-text-white);text-shadow:var(--shadow-text)
        }
        .drawn-numbers-list{
            display:flex;flex-wrap:wrap;
            gap:22px; 
            justify-content:center;
            flex-grow:1;align-content:flex-start;padding-bottom:10px;
        }
        .drawn-number-item{
            background-color:var(--color-pop-yellow);color:var(--color-text-dark);
            border-radius:50%;
            width:90px; 
            height:90px; 
            display:flex;justify-content:center;
            align-items:center;font-family:var(--font-numbers);
            font-size:3.8em; 
            font-weight:700;
            flex-shrink:0;
            border:4px solid var(--color-pop-blue);
            box-shadow:0 0 10px var(--color-pop-blue),0 0 20px var(--color-pop-pink);
            transition:transform .1s ease-out;opacity:0;transform:scale(.5)
        }
        @keyframes item-appear{from{transform:scale(.5) rotate(-30deg);opacity:0}to{transform:scale(1) rotate(0deg);opacity:1}}
        .drawn-number-item:hover{transform:scale(1.05);z-index:2}
        .game-over-display{
            position:fixed;top:0;left:0;width:100vw;height:100vh;
            background:linear-gradient(135deg,var(--color-bg-dark-purple),var(--color-bg-light-purple));
            background-size:200% 200%;animation:gradient-shift 15s ease infinite alternate;
            color:var(--color-pop-pink);display:flex;justify-content:center;align-items:center;
            font-family:var(--font-japanese);font-size:25vw;font-weight:800;
            text-shadow:var(--shadow-text-number);opacity:0;transition:opacity .8s ease-in;
            pointer-events:none;z-index:100;letter-spacing:5px
        }
        .game-over-display.active{opacity:1}
        .check-page-link{
            position:fixed;bottom:25px;left:50%;transform:translateX(-50%);
            padding:15px 30px;background:linear-gradient(45deg,var(--color-pop-yellow),var(--color-pop-blue));
            color:var(--color-text-dark);border-radius:12px;text-decoration:none;
            font-size:1.8em;font-weight:bold;box-shadow:var(--shadow-button);
            transition:all .3s ease;z-index:50;border:3px solid var(--color-pop-pink);
            animation:button-float-vibrant 1.5s infinite alternate;
            text-shadow:1px 1px 2px rgba(0,0,0,.3);will-change:transform,box-shadow
        }
        @keyframes button-float-vibrant{
            0%{transform:translateX(-50%) translateY(0);box-shadow:var(--shadow-button)}
            50%{transform:translateX(-50%) translateY(-5px) scale(1.02);box-shadow:0 0 15px #00ffff,0 0 30px #ffee00}
            100%{transform:translateX(-50%) translateY(0);box-shadow:var(--shadow-button)}
        }
        .check-page-link:hover{
            background:linear-gradient(45deg,var(--color-pop-blue),var(--color-pop-yellow));
            box-shadow:0 0 15px var(--color-pop-blue),0 0 30px var(--color-pop-yellow);
            transform:translateX(-50%) translateY(-3px) scale(1.03);border-color:var(--color-pop-blue)
        }
        @media (max-width:768px){
            .current-number-label{font-size:2.5em}.current-number{font-size:10em}
            .drawn-numbers-label{font-size:2.5em} /* 調整 */
            .drawn-numbers-section{
                padding:40px; /* 調整 */
                width:98%;
                max-width: 700px; /* 調整 */
            }
            .drawn-number-item{
                width:75px; /* 調整 */
                height:75px; /* 調整 */
                font-size:3.2em; /* 調整 */
                gap:18px; /* 調整 */
            }
            .check-page-link{font-size:1.5em;padding:12px 25px}
            /* レスポンシブでも背景図形を調整 */
            .shape:nth-child(1){width:120px;height:120px;}
            .shape:nth-child(2){width:150px;height:150px;}
            .shape:nth-child(3){width:180px;height:75px;}
            .shape:nth-child(4){width:105px;height:105px;}
            .shape:nth-child(5){border-left:52.5px solid transparent;border-right:52.5px solid transparent;border-bottom:82.5px solid var(--color-pop-pink);}
            .shape:nth-child(6){width:90px;height:52.5px;}
            .shape:nth-child(7){border-right:52.5px solid transparent;border-left:52.5px solid transparent;border-bottom:37.5px solid var(--color-pop-pink);top:15px;left:-52.5px;}
            .shape:nth-child(8){width:90px;height:90px;}
            .shape:nth-child(9){width:120px;height:72px;}
            .shape:nth-child(10){width:90px;height:90px;}
        }
        @media (max-width:480px){
            .current-number-section{padding:20px 30px}
            .current-number-label{font-size:2em}.current-number{font-size:8em}
            .drawn-numbers-section{
                padding:30px; /* 調整 */
                width:100%;
                max-width: unset; /* モバイルではmax-widthを解除して画面幅いっぱいにする */
            }
            .drawn-number-item{
                width:60px; /* 調整 */
                height:60px; /* 調整 */
                font-size:2.4em; /* 調整 */
                gap:15px; /* 調整 */
            }
            .check-page-link{font-size:1.2em;padding:10px 20px}
            .bingo-container{gap:15px}
            /* レスポンシブでも背景図形を調整 */
            .shape:nth-child(1){width:90px;height:90px;}
            .shape:nth-child(2){width:120px;height:120px;}
            .shape:nth-child(3){width:135px;height:60px;}
            .shape:nth-child(4){width:75px;height:75px;}
            .shape:nth-child(5){border-left:37.5px solid transparent;border-right:37.5px solid transparent;border-bottom:60px solid var(--color-pop-pink);}
            .shape:nth-child(6){width:60px;height:34.5px;}
            .shape:nth-child(7){border-right:37.5px solid transparent;border-left:37.5px solid transparent;border-bottom:26.25px solid var(--color-pop-pink);top:11.25px;left:-37.5px;}
            .shape:nth-child(8){width:60px;height:60px;}
            .shape:nth-child(9){width:90px;height:54px;}
            .shape:nth-child(10){width:60px;height:60px;}
        }
    </style>
</head>
<body>
    <div class="background-shapes">
        <div class="shape circle"></div>
        <div class="shape square"></div>
        <div class="shape triangle"></div>
        <div class="shape circle"></div>
        <div class="shape square"></div>
        <div class="shape hexagon"></div>
        <div class="shape star"></div>
        <div class="shape diamond"></div>
        <div class="shape oval"></div>
        <div class="shape plus"></div>
    </div>
    <div class="bingo-container" id="bingoContainer">
        <div class="current-number-section">
            <div class="current-number-label">今回の数字</div>
            <div class="current-number" id="currentNumber">--</div>
        </div>
        <div class="drawn-numbers-section">
            <div class="drawn-numbers-label">これまでの抽選数字</div>
            <div class="drawn-numbers-list" id="drawnNumbersList"></div>
        </div>
    </div>
    <div class="game-over-display" id="gameOverDisplay">FIN!</div>
    <a href="check.html" class="check-page-link">当選数字を確認する</a>
    <script>
        const currentNumberDisplay=document.getElementById('currentNumber'),
              drawnNumbersList=document.getElementById('drawnNumbersList'),
              bingoContainer=document.getElementById('bingoContainer'),
              gameOverDisplay=document.getElementById('gameOverDisplay');
        const MAX_NUMBER=75;
        let availableNumbers=[],drawnNumbers=[];

        function initializeGame(){
            availableNumbers=Array.from({length:MAX_NUMBER},(_,i)=>i+1);
            drawnNumbers=[];
            currentNumberDisplay.textContent='--';
            drawnNumbersList.innerHTML='';
            localStorage.removeItem('bingoDrawnNumbers');
            localStorage.removeItem('bingoLastUpdated');
            bingoContainer.classList.remove('hidden');
            gameOverDisplay.classList.remove('active')
        }
        document.addEventListener('DOMContentLoaded',initializeGame);

        function drawNumber(){
            if(availableNumbers.length===0){alert('全ての数字が抽選されました！ゲーム終了！');showGameOver();return}
            const randomIndex=Math.floor(Math.random()*availableNumbers.length);
            const drawn=availableNumbers.splice(randomIndex,1)[0];
            drawnNumbers.push(drawn);
            currentNumberDisplay.textContent=drawn;
            localStorage.setItem('bingoDrawnNumbers',JSON.stringify(drawnNumbers));
            localStorage.setItem('bingoLastUpdated',Date.now());
            renderDrawnNumbers();
            if(availableNumbers.length===0)showGameOver()
        }
        function renderDrawnNumbers(){
            drawnNumbersList.innerHTML='';
            drawnNumbers.slice().reverse().forEach((num,idx)=>{
                const item=document.createElement('div');
                item.className='drawn-number-item';
                item.textContent=num;
                item.style.animation=`item-appear .3s ease-out forwards`;
                item.style.animationDelay=`${idx*.02}s`;
                drawnNumbersList.appendChild(item)
            })
        }
        function showGameOver(){
            bingoContainer.classList.add('hidden');
            gameOverDisplay.classList.add('active')
        }
        document.addEventListener('keydown',e=>{
            if(e.code==='Space')drawNumber();
            else if(e.shiftKey&&e.code==='KeyR')
                if(confirm('Shift + Rでゲームがリセットする'))location.reload()
        });
    </script>
</body>
</html>
