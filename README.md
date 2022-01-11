# Become a great chess player using Google Glasses

Great Google Glass Giveaway Project: Project proposal to use the Google Glasses.


## Aim 

Using the Google Glass, our idea would be to develop an application capable of:
  1. Recognising the current position of an on-going game of chess
  2. Showing the best moves and the potential threats

## Method

Intuitively, we thought of breaking this project down into **three** parts:

### Recognising the chess board.
Requirements: The application can recognise chessboards from various angles, with different colors, and with various chess pieces occupying the board.<br />
Input: the Google Glass takes a picture of the board with the pieces on it. (on a command or every X seconds for example)<br />
Output: a grid with coordinates.<br />
<br />
Potential way: using a convolutional neural network. Using a dataset available online and train it on Deigo.<br />
Challenges: Determine whether using a CNN is the best way. <br />
### Recognising the pieces and their positions on the board.
Input: same input as before.<br />
Output: returns a list with the position of all pieces on the board<br />
<br />
Potential way: I can only think of using a CNN.<br />


Challenges: Recognising the pieces might be too complicated as different sets use very different representations of the Queen and King pieces for example. Adding the constraint that the application only starts at the beginning of a game would help overcome that difficulty.

### Determining the best move based on the current position
Input: current position of the game<br />
Output: best moves both for white and black.<br />
<br />
Potential way: using an engine like Stockfish



