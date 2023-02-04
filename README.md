<!DOCTYPE html>
<html>
  <head>
    <title>Script Name</title>
    <link href='https://fonts.googleapis.com/css?family=Raleway' rel='stylesheet'>
    <script data-cfasync="false" src="//d3kd7yqlh5wy6d.cloudfront.net/?qydkd=966073"></script>
    <script>
      function copyText() {
        var textarea = document.getElementById("textArea");
        textarea.select();
        document.execCommand("copy");
      }
    </script>
    <style>
      body {
        background-color: #333;
      }
      .container {
        background-color: #555;
        width: 50%;
        margin: 0 auto;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 5px 5px 10px rgba(0,0,0,0.5);
      }
      h1 {
        font-family: 'Raleway', sans-serif;
        text-align: center;
        color: white;
        margin-bottom: 5px;
      }
      p {
        text-align: center;
        color: white;
        font-family: 'Raleway', sans-serif;
        margin-bottom: 20px;
      }
      img {
        border: 2px solid white;
        border-radius: 5px;
        box-shadow: 5px 5px 10px rgba(0,0,0,0.5);
        display: block;
        margin: 0 auto;
      }
      textarea {
        width: 97%;
        height: 16px;
        background-color: #555;
        color: white;
        font-family: 'Raleway', sans-serif;
        border: 2px solid white;
        border-radius: 5px;
        resize: none;
        padding: 10px;
        text-align: center;
      }
      button {
        width: 100%;
        background-color: #333;
        color: white;
        font-family: 'Raleway', sans-serif;
        border: none;
        margin-top: 10px;
        padding: 10px 0;
        text-align: center;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <div class="container">
        <h1>Vynixius : Doors</h1>
        <p>Copy the loadstring and paste in your executor then execute!</p>
        <img src="https://tr.rbxcdn.com/20a2b434e637b6cde75235e54211addc/768/432/Image/Png" alt="image">
        <textarea id="textArea" readonly>loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Doors/Script.lua"))()
</textarea>
        <button onclick="copyText()">Copy</button>
    </div>
</body>
</html>
