# BoardGameFramework
A framework for 2-player board games written in C++.
<br><br>
Uses the Model-View-Control pattern to organize code.
<br><br>
Two games are already implemented using the pattern as examples: <b>Othello</b> (also known as Reversi), and <b>Tic-Tac-Toe</b>. The games are seletable through a text menu.
<br><br>
The UI is all text-based through the console. These are the list of valid commands:

<b>NOTE:</b> "x" and "y" are variables and must be integers for the move to be accepted.

<ul>
  <li>move (x, y) -- Places a game piece at the specified coordinate.</li>
  <li>undo x -- Undo the game board x amount of turns.</li>
  <li>showValue -- Shows the total value of pieces on the board.</li>
  <li>showHistory -- Shows the history of moves made in the current game (most recent move first).</li>
  <li>quit -- Quit the game.</li>
</ul>