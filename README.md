# ai-air-hotel-service
본 저장소는 AI 기술이 항공·호텔 서비스 산업에 적용되는 사례를 HTML, CSS, JavaScript를 활용하여 구현한 웹 콘텐츠입니다.
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AI 기반 항공·호텔 서비스</title>

  <style>
    body {
      font-family: 'Apple SD Gothic Neo', sans-serif;
      margin: 0;
      background-color: #f5f7fa;
      color: #333;
    }
    header {
      background-color: #1e3a8a;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .cards {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      width: 100%;
      max-width: 400px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    button {
      margin-top: 10px;
      padding: 10px;
      border: none;
      background-color: #2563eb;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #1e40af;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #e5e7eb;
      font-size: 14px;
    }
  </style>
</head>

<body>

<header>
  <h1>AI 기반 항공·호텔 서비스</h1>
  <p>AI 기술로 변화하는 서비스 산업의 미래</p>
</header>

<section>
  <h2>왜 AI가 중요한가?</h2>
  <p>
    AI는 고객 데이터를 분석하여 맞춤형 서비스를 제공하고,
    서비스 품질과 운영 효율성을 동시에 향상시킵니다.
  </p>
</section>

<section class="cards">
  <div class="card">
    <h3>✈️ 항공 서비스</h3>
    <p>AI 챗봇, 자동 체크인, 맞춤형 좌석 추천</p>
  </div>

  <div class="card">
    <h3>🏨 호텔 서비스</h3>
    <p>AI 컨시어지, 고객 선호 분석, 스마트 객실</p>
  </div>
</section>

<footer>
  <p>제작자: 조아현</p>
  <p>GitHub Pages 웹 콘텐츠 과제</p>
</footer>

</body>
</html>
