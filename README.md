<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>나만의 웹사이트</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Pretendard', 'Noto Sans KR', sans-serif;
      background: linear-gradient(135deg, #74ABE2, #5563DE);
      color: white;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    header {
      width: 100%;
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      text-align: center;
      padding: 1.5rem 0;
      font-size: 1.8rem;
      font-weight: 700;
      letter-spacing: 1px;
    }
    main {
      flex: 1;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      max-width: 600px;
      padding: 2rem;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    p {
      font-size: 1.1rem;
      line-height: 1.6;
      margin-bottom: 2rem;
    }
    a.button {
      display: inline-block;
      background: white;
      color: #5563DE;
      padding: 0.75rem 1.5rem;
      border-radius: 2rem;
      font-weight: 600;
      text-decoration: none;
      transition: 0.3s;
    }
    a.button:hover {
      background: #e5e5e5;
      transform: scale(1.05);
    }
    footer {
      width: 100%;
      text-align: center;
      padding: 1rem 0;
      font-size: 0.9rem;
      background: rgba(255, 255, 255, 0.1);
    }
  </style>
</head>
<body>
  <header>
    🌟 나만의 웹사이트 🌟
  </header>

  <main>
    <h1>안녕하세요!</h1>
    <p>이곳은 내가 직접 만든 나만의 공간이에요.<br>
    취미, 작품, 생각 등을 자유롭게 담아보세요 ✨</p>

    <a href="#" class="button">더 알아보기</a>
  </main>

  <footer>
    © 2025 My Web Page | Designed by Me
  </footer>
</body>
</html>
