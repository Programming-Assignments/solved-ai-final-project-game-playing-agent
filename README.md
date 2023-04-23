Download Link: https://assignmentchef.com/product/solved-ai-final-project-game-playing-agent
<br>
<strong>                  </strong>The objective of this assignment is for you to design a game-playing agent. (a) The game to be played is a variant of checker on an 8×8 square board. The rules are:

<ul>

 <li>Each player has 9 pieces initially, arranged as in image (a) to the right.</li>

 <li><strong><em>Black</em></strong> moves first.</li>

 <li>The valid moves (see image (b) to the right) are:

  <ul>

   <li>Move one piece to an adjacent unoccupied square.</li>

   <li>Have one piece hop over another piece of either player to an unoccupied square. Multiple hops by one piece can be taken within one move as long as all the hops are valid and form a sequence. However, each move can only contain at most 99 hops.</li>

  </ul></li>

 <li>When hopping over an opponent’s piece, the opponent’s piece is considered “captured” and removed from the board.</li>

 <li>The overall objective is to move as many of a player’s pieces as possible to the shaded squares in the opposite side (the target region).</li>

 <li>A player’s move is skipped if he/she makes an invalid move or has no piece remaining on the board. The other player will continue to play.</li>

 <li>The game ends when

  <ul>

   <li>Either player has all his/her pieces on the board in the target region, or n A maximum of 200 moves per player has been played.</li>

  </ul></li>

 <li>At the end, the score of a player is the number of pieces placed in the target region. The player with the higher score wins the game.</li>

</ul>

In the tournament, each pair of players will play two games, with each player being <strong><em>Black</em></strong> once. The “tournament points” are awarded as: two points for the winner, zero point for the loser, and one point each if the game ends with a draw. The overall ranking is based on the total tournament points of the players. The tie-breakers, in case multiple players have the same tournament points, are

<ul>

 <li>Number of games actually won.</li>

 <li>Total score differential (a player’s total scores minus the opponents’ total scores).</li>

</ul>