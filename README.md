# Tic-Tak-Toe-Game
Tic Toe Game using HTML and CSS for view of the game and Java Script for the perform operation in the game
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tic-Tac-Toe Game by Jyotish Jamra</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="msg-container hide">
      <p id="msg">Winner</p>
      <button id="new-btn">New Game</button>
    </div>
    <main>
      <h1>Tic Tac Toe by Jyotish</h1>
	  <p> <b>Player X   v/s  Player 0 </b></p> 
      <div class="container">
        <div class="game">
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
          <button class="box"></button>
        </div>
      </div>
      <button id="reset-btn">Reset Game</button>
    </main>
    <script src="app.js"></script>
  </body>
</html>
