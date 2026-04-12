<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>Dify Chat with Dog Avatar</title>
  <style>
    #container {
      position: relative;
      width: 100%;
      height: 100vh;
    }

    #dify-chat {
      width: 100%;
      height: 100%;
      border: none;
    }

#avatar {
  position: absolute;
  bottom: 20px;
  right: 20px;
  width: 300px;   /* PC のときの大きさ */
  pointer-events: none;
}

#avatar img {
  width: 100%;
}

/* スマホ（画面幅 600px 以下）のとき */
@media (max-width: 600px) {
  #avatar {
    width: 150px;   /* スマホ用に小さくする */
    bottom: 10px;
    right: 10px;
  }
}
  </style>
</head>
<body>
  <div id="container">
    <iframe
      src="https://udify.app/chat/7Hhb8iWAlQookn0L"
      id="dify-chat"
    ></iframe>

    <div id="avatar">
      <img src="dog.gif" alt="dog avatar">
    </div>
  </div>
</body>
</html>
