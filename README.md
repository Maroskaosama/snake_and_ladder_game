📘 User Manual: Snake and Ladder Game
🎮 Overview
This Snake and Ladder game offers an enhanced digital experience with multiple game modes, dynamic visuals, and a user-friendly interface. Built in Python, the game includes interactive features such as difficulty settings, random in-game messages, and custom rules to provide a fun and fair gameplay environment.

✨ Key Features
📋 Drop-down Menu for easy mode selection

👥 Game Modes:
Player vs Player (PvP)
Player vs Computer (PvC)

🧠 Difficulty Levels for PvC:
Easy
Hard (smart AI behavior)

🎨 Visual Background for a more immersive experience
📊 Progress Bar to track player movement
🐍🪜 Random Sticker Messages (emojis/motivation) when encountering snakes or ladders
🎲 Advanced Dice Rules:
A player rolls again after getting a 6
If a player rolls three 6s in a row, their turn is forfeited

🔁 Replayability:

Exit the game at any time
Restart a new game or replay the current one

🕹️ How to Play
Choose a Game Mode from the main menu.
Enter your name(s) when prompted. (Only letters are allowed; numbers are invalid.)
Position each player's piece on the starting square (Tile 0).
Roll the dice to determine who goes first (the highest roller starts).
On your turn:
Roll the dice and move forward accordingly.
If you land on a ladder base, climb up.
If you land on a snake head, slide down.
Dice Rules:
Rolling a 6 lets you play again.
Rolling three 6s ends your turn.
If a player lands on a tile already occupied by another player, the latter is sent back to the starting square.
The winner is the first player to reach exactly Tile 100.
If a dice roll moves you beyond 100, your piece stays in place.

❗ Input Validation
If a player enters a number or invalid name, an error message will be shown and the player will be prompted again.
The system ensures players can only roll the dice when it’s their turn, and enforces rules related to rolling sixes.

⚙️ System Usage
To start the game, run the main() function in your Python environment.
At any point, use the menu to:
❌ Exit the game
🔁 Replay the current round
🆕 Start a new game

