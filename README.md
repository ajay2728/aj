<!DOCTYPE html>
<html>
  <head>
    <title>Number guessing game</title>
    <meta charset="utf-8">
    <script async src = "found.js"></script>
    <style>
      html {
        font-family: sans-serif;
      }
      body {
        width: 50%;
        max-width: 800px;
        min-width: 480px;
        margin: 0 auto;
      }
      .lastResult {
        color: white;
        padding: 3px;
      }
    </style>
  </head>

  <body>
      <h1>Number guessing game</h1>

      <p>We have selected a random number between 1 and 100. See if you can guess it in 10 turns or less. We'll tell you if your guess was too high or too low.</p>

<div class="form">
  <label for="guessField">Enter a guess: </label><input type="text" id="guessField" class="guessField">
  <button type = "button" onclick = "checkGuess()" class = "guessSubmit">check Guess</button>
</div>

<div class="resultParas">
  <p class="guesses"></p>
  <p class="lastResult"></p>
  <p class="lowOrHi"></p>
</div>
</body>
</html>
