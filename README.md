TREASURE HUNT

This code defines a text-based treasure hunt game in C. Here are the key highlights and functionality:

Overview:

Grid Size: The game is played on a 5x5 grid.

Player Movement: Controlled by W, A, S, D keys for moving up, left, down, and right, respectively.

Game Objective: Collect all treasures while avoiding traps, staying within a time limit (60 seconds), and managing moves and health.

Dynamic Elements:

Treasures (T): +10 points for each treasure collected.
Traps (X): -1 health when stepped on.

Power-ups (+): +3 moves when picked up.


Game Over: The game ends when the player:

1. Collects all treasures.


2. Runs out of health or moves.
3. Time runs out.

Features:

 Dynamic Traps: Traps move to new random locations after every player move.


 Leaderboard: Maintains up to 10 high scores with players' names and scores.


 Timer: Ends the game if the player exceeds the 60-second limit.

 Player Feedback: Provides real-time updates on score, health, moves, treasures collected, and remaining time.


 Error Handling: Invalid moves (outside grid boundaries or unsupported commands) are gracefully handled.
