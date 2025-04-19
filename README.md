KWAZAM CHESS
============

DESCRIPTION
-----------
Kwazam Chess is a custom two-player strategy game built in Java using the Swing framework. 
It introduces unique pieces like RAM, SAU, TOR, XOR, and BIZ, each with special movement rules. 
The game follows the MVC design pattern and features an interactive GUI, move tracking, 
and automatic piece transformation.

FEATURES
--------
- 8x5 chess-style board with custom pieces
- Game ends when the Sau (king-like) piece is captured
- Tor ↔ Xor pieces auto-transform every 4 moves
- RAM pieces reverse direction after reaching the board end
- Animated GUI with flipping board view
- Move history panel
- Save and load game support
- Sound effects for actions
- Player name input dialog with themed background

HOW TO RUN
----------
1. Make sure you have Java 8 or above installed
2. Compile all files:
   javac controller/*.java model/*.java view/*.java KwazamChessMain.java
3. Run the main class:
   java KwazamChessMain
4. Ensure required resources (images, sounds) are in the correct folders:
   - /chessImages/ (e.g., redBIZ.png, blueSAU.png)
   - /audio/ (e.g., move.wav, capture.wav, game over.wav)

PROJECT STRUCTURE
-----------------
- KwazamChessMain.java         : Main launcher
- model/                       : Game logic (pieces, board, game state)
- view/                        : GUI components and panels
- controller/                  : MVC controller to handle user interaction
- util/                        : Sound utility (not included in current upload)

REQUIREMENTS
------------
- Java 8 or above
- mainpagebackground.png
- Piece image files (e.g., redRAM.png, blueXOR.png)
- Audio files for game actions

CREDITS
-------
Developed by Aleesya, Seow Rou, Kuanyang, and Zeti
