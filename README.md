<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy 2nd Monthsary ❤️</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      color: #333;
      text-align: center;
    }

    .container {
      max-width: 800px;
      margin: auto;
      padding: 40px 20px;
      background: rgba(255, 255, 255, 0.9);
      border-radius: 20px;
      margin-top: 50px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
    }

    h1 {
      color: #e75480;
      font-size: 3em;
    }

    h2 {
      color: #ff6f91;
    }

    p {
      font-size: 1.1em;
      line-height: 1.6;
    }

    .heart {
      font-size: 60px;
      animation: beat 1.5s infinite;
    }

    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    .photos {
      margin-top: 30px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
    }

    .photos img {
      width: 100%;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #777;
    }

    button {
      margin-top: 20px;
      padding: 12px 25px;
      font-size: 1em;
      border: none;
      border-radius: 25px;
      background: #ff6f91;
      color: white;
      cursor: pointer;
    }

    button:hover {
      background: #e75480;
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="heart">❤️</div>

    <h1>Happy 2nd Monthsary!</h1>

    <h2>To My Nonchalant 💕</h2>

    <p>
      Happy <strong>2 months</strong> with you, my Nonchalant.
      Even when you act calm and unbothered, you mean so much to me.
      These 2 months have been full of smiles, comfort, and special moments.
    </p>

    <p>
      Thank you for being you simple, real, and always special in your own way.
      I’m grateful for every day we’ve spent together and excited for the many months ahead ❤️
    </p>

    <button onclick="showMessage()">Click Me 💖</button>

    <p id="hiddenMessage" style="display:none; margin-top:20px;">
      I choose you today, tomorrow, and every month after 💗
    </p>

    <div class="photos">
      <!-- Replace these with your own photos -->
      <img src="https://via.placeholder.com/300x300?text=Us+1" alt="Photo 1">
      <img src="https://via.placeholder.com/300x300?text=Us+2" alt="Photo 2">
      <img src="https://via.placeholder.com/300x300?text=Us+3" alt="Photo 3">
    </div>

    <footer>
      Made with ❤️ for Nonchalant
    </footer>
  </div>

  <script>
    function showMessage() {
      document.getElementById("hiddenMessage").style.display = "block";
    }
  </script>

</body>
</html>
