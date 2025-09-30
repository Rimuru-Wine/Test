<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Do You Wanna Partner</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0d001f;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .container {
      display: flex;
      max-width: 1100px;
      background: #111;
      border-radius: 12px;
      overflow: hidden;
    }

    .left {
      flex: 1;
      padding: 40px;
      background: linear-gradient(120deg, #150024, #240033);
      position: relative;
    }

    .left h1 {
      font-size: 50px;
      margin-bottom: 20px;
      font-weight: bold;
    }

    .left p {
      font-size: 16px;
      line-height: 1.6;
      color: #ddd;
      margin-bottom: 30px;
    }

    .left .handle {
      font-size: 16px;
      color: #bbb;
    }

    .right {
      flex: 1;
      background: url('https://i.ibb.co/9b6VbyD/partner-girls.jpg') center/cover no-repeat;
      position: relative;
    }

    .right .title-overlay {
      position: absolute;
      bottom: 30px;
      left: 30px;
      color: white;
      font-weight: bold;
      text-transform: uppercase;
    }

    .right .title-overlay h2 {
      font-size: 40px;
      margin: 0;
    }

    .right .title-overlay span {
      font-size: 55px;
      color: #ffcc00;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Left Text Section -->
    <div class="left">
      <h3>Entertainment AG</h3>
      <h1>DO YOU WANNA<br>PARTNER</h1>
      <p>
        Best friends Shikha and Anahita turn entrepreneurs with an exciting craft beer brand, Jugaaro, 
        to stand out in the crowded NCR beer market. However, they face gender discrimination every step of the way. 
        To fight for an equal place in this male dominated sector, they decide to invent a fictitious male partner 
        to help smooth their way.
      </p>
      <div class="handle">@Entertainment_AG</div>
    </div>

    <!-- Right Image Section -->
    <div class="right">
      <div class="title-overlay">
        <h2>Do You Wanna</h2>
        <span>Partner</span>
      </div>
    </div>
  </div>
</body>
</html>
