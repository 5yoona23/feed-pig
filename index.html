<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>돼지 밥 먹이기 🐷</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: "Arial", "Malgun Gothic", sans-serif;
      background: #fff4e8;
      color: #5b3a35;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow-x: hidden;
    }

    .game {
      width: min(92vw, 700px);
      min-height: 650px;
      padding: 35px 25px;
      text-align: center;
      background: #fffaf5;
      border: 5px solid #f5c7bd;
      border-radius: 35px;
      box-shadow: 0 15px 40px rgba(180, 105, 90, 0.15);
      position: relative;
      overflow: hidden;
    }

    h1 {
      margin: 0 0 10px;
      font-size: clamp(34px, 8vw, 55px);
      color: #d86f78;
    }

    .guide {
      font-size: clamp(19px, 4vw, 25px);
      margin: 0 0 25px;
      color: #76534d;
      font-weight: bold;
    }

    .pig-area {
      height: 300px;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .pig {
      font-size: 175px;
      line-height: 1;
      position: relative;
      transition: transform 0.3s ease;
      user-select: none;
      z-index: 2;
    }

    .pig.happy {
      animation: happyPig 0.6s ease-in-out 3;
    }

    @keyframes happyPig {
      0%, 100% { transform: scale(1) rotate(0); }
      25% { transform: scale(1.12) rotate(-5deg); }
      75% { transform: scale(1.12) rotate(5deg); }
    }

    .heart {
      position: absolute;
      font-size: 45px;
      opacity: 0;
      pointer-events: none;
    }

    .heart.show {
      animation: floatHeart 1.2s ease-out forwards;
    }

    .heart1 { left: 25%; top: 25%; }
    .heart2 { right: 25%; top: 20%; animation-delay: .15s; }
    .heart3 { left: 35%; top: 5%; animation-delay: .3s; }

    @keyframes floatHeart {
      0% {
        opacity: 0;
        transform: translateY(30px) scale(.5);
      }
      30% {
        opacity: 1;
      }
      100% {
        opacity: 0;
        transform: translateY(-100px) scale(1.2);
      }
    }

    .food {
      position: absolute;
      bottom: 25px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 75px;
      transition: all .4s ease;
      z-index: 3;
      cursor: pointer;
    }

    .food.eaten {
      animation: eatFood .5s ease forwards;
    }

    @keyframes eatFood {
      0% { transform: translateX(-50%) scale(1); }
      50% { transform: translateX(-50%) scale(1.3) rotate(10deg); }
      100% {
        transform: translateX(-50%) translateY(-100px) scale(0);
        opacity: 0;
      }
    }

    .message {
      min-height: 50px;
      font-size: clamp(21px, 4vw, 28px);
      font-weight: bold;
      color: #c75d68;
      margin-bottom: 20px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    button {
      border: 0;
      border-radius: 18px;
      padding: 17px 30px;
      font-size: clamp(19px, 4vw, 23px);
      font-weight: bold;
      cursor: pointer;
      font-family: inherit;
      transition: transform .15s, box-shadow .15s;
    }

    button:hover {
      transform: translateY(-3px);
    }

    button:active {
      transform: translateY(1px);
    }

    .feed-button {
      background: #f28b91;
      color: white;
      box-shadow: 0 6px 0 #d86f78;
    }

    .reset-button {
      background: #f9ddd5;
      color: #8b5a52;
      box-shadow: 0 6px 0 #e8bdb3;
    }

    .counter {
      margin-top: 22px;
      font-size: 18px;
      color: #96716a;
    }

    .sparkle {
      position: absolute;
      font-size: 30px;
      animation: sparkle 2s infinite ease-in-out;
      opacity: .6;
    }

    .s1 { top: 100px; left: 8%; }
    .s2 { top: 180px; right: 8%; animation-delay: .7s; }
    .s3 { bottom: 100px; left: 10%; animation-delay: 1.2s; }
    .s4 { bottom: 70px; right: 12%; animation-delay: 1.7s; }

    @keyframes sparkle {
      0%, 100% { transform: scale(.8) rotate(0); opacity: .4; }
      50% { transform: scale(1.2) rotate(20deg); opacity: 1; }
    }

    @media (max-width: 500px) {
      .game {
        min-height: 620px;
        padding: 28px 18px;
      }

      .pig-area {
        height: 270px;
      }

      .pig {
        font-size: 140px;
      }

      .food {
        font-size: 65px;
      }
    }
  </style>
</head>

<body>
  <main class="game">
    <span class="sparkle s1">✨</span>
    <span class="sparkle s2">🌸</span>
    <span class="sparkle s3">✨</span>
    <span class="sparkle s4">🌷</span>

    <h1>🐷 돼지 밥 먹이기</h1>
    <p class="guide">돼지에게 맛있는 밥을 주세요!</p>

    <section class="pig-area">
      <div class="pig" id="pig">🐷</div>

      <div class="heart heart1">💗</div>
      <div class="heart heart2">💕</div>
      <div class="heart heart3">💖</div>

      <div class="food" id="food">🥣</div>
    </section>

    <div class="message" id="message">
      배가 꼬르륵... 밥 주세요! 🥺
    </div>

    <div class="buttons">
      <button class="feed-button" id="feedButton">
        🥣 밥 먹이기
      </button>

      <button class="reset-button" id="resetButton">
        🔄 다시 고르기
      </button>
    </div>

    <div class="counter" id="counter">
      먹인 밥: 0그릇
    </div>
  </main>

  <script>
    const pig = document.getElementById("pig");
    const food = document.getElementById("food");
    const message = document.getElementById("message");
    const feedButton = document.getElementById("feedButton");
    const resetButton = document.getElementById("resetButton");
    const counter = document.getElementById("counter");
    const hearts = document.querySelectorAll(".heart");

    let feedCount = 0;
    let isEating = false;

    const happyMessages = [
      "냠냠! 정말 맛있어요! 😋",
      "우와! 배가 든든해졌어요! 💕",
      "밥 최고! 돼지가 행복해요! 🐷💖",
      "냠냠냠! 더 맛있는 것 같아요! 😍",
      "고마워요! 기분이 아주 좋아요! 🌸"
    ];

    feedButton.addEventListener("click", () => {
      if (isEating) return;

      isEating = true;
      feedButton.disabled = true;

      // 밥이 사라지는 애니메이션
      food.classList.add("eaten");

      setTimeout(() => {
        feedCount++;
        counter.textContent = `먹인 밥: ${feedCount}그릇`;

        // 돼지가 행복해지는 모습
        pig.classList.add("happy");
        message.textContent =
          happyMessages[Math.floor(Math.random() * happyMessages.length)];

        // 하트가 나타남
        hearts.forEach(heart => {
          heart.classList.remove("show");
          void heart.offsetWidth;
          heart.classList.add("show");
        });
      }, 300);

      setTimeout(() => {
        pig.classList.remove("happy");
      }, 2000);

      setTimeout(() => {
        food.classList.remove("eaten");
        isEating = false;
        feedButton.disabled = false;
      }, 1600);
    });

    // 처음 상태로 돌아가기
    resetButton.addEventListener("click", () => {
      feedCount = 0;
      isEating = false;

      food.classList.remove("eaten");
      pig.classList.remove("happy");

      message.textContent = "배가 꼬르륵... 밥 주세요! 🥺";
      counter.textContent = "먹인 밥: 0그릇";

      hearts.forEach(heart => {
        heart.classList.remove("show");
      });

      feedButton.disabled = false;
    });
  </script>
</body>
</html>
