<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hướng Dẫn Viên Ảo</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      margin: 0;
      padding: 0;
      background-image: url(bg/ảnh\ cún.jpg)
      background-size: cover;
      background-position: center;
      font-family: sans-serif;
    }
    .guide-container {
      display: flex;
      align-items: center;
      padding: 20px;
      background: rgba(255, 255, 255, 0.8);
      border-radius: 12px;
      max-width: 600px;
      margin: 30px auto;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    .avatar {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      margin-right: 20px;
    }

    .chat-box {
      flex: 1;
      max-height: 300px;
      overflow-y: auto;
      background: #fff;
      padding: 15px;
      border-radius: 10px;
    }

    #user-input {
      display: block;
      margin: 20px auto 10px;
      width: 80%;
      padding: 10px;
      font-size: 16px;
      border-radius: 6px;
      border: 1px solid #ccc;
    }

    button {
      display: block;
      margin: 0 auto;
      padding: 10px 20px;
      font-size: 16px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="guide-container">
    <img src="guide-avatar.png" alt="Hướng dẫn viên Linh" class="avatar">
    <div class="chat-box">
      <p id="chat-output">Xin chào! Mình là Linh – hướng dẫn viên của bạn!</p>
    </div>
  </div>

  <input type="text" id="user-input" placeholder="Bạn muốn hỏi gì?" />
  <button onclick="sendMessage()">Gửi</button>

  <script src="script.js"></script>
</body>
</html>
