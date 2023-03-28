# minigames

## Game Menu
ChatGPT
Prompt:
- Use flutter to develop a game. First page is a menu of a list of game. First game in the menu is tic tac toe for 2 players.

## Tictactoe
ChatGPT
Prompt:
- you are a flutter developer. write a tic tac toe game in a page for 2 players. check for a winner or a draw. add a float button to restart the game

## Tictactoe in 4x4 grid for 3 players
GPT3.5 turbo
Prompts:
- You are a flutter developer. Write a 4x4 tic tac toe game for 3 players
- Add a function to check for winner or draw from board
- win condition change. 3 tiles linked win.
- write unit tests for _checkForWinnerOrDraw[^1]

## Shikaku
GPT3.5 turbo
Prompts:
- you are a flutter developer, write a game of Shikaku[^2]
- write a line of code to log selectcell
- use logging framework
- create a variable, which is a list of color
- cell color is linked with list grid[^2][^3]
- create a function, check if the selected area is valid on conditions. condition 1, only one positive integer in variable numbers. condition 2, area match the integer[^4]
- dart math return abs value
- add a reset float button to fill grid with 0
- create a function to check all value in grid is larger than 0. show a win game dialog[^2][^4]

## Flappy Bird (WIP)
Prompt:
- create a flappy bird game in flutter. focus on the background scrolling. background scroll from right to left slowly, and then repeat.
Image download from https://weeklyhow.com/flappy-bird-unity-tutorial/

[^1]: The unit test ignore the 3 tiles link rule.
[^2]: reference to -1 in array
[^3]: need to fix binding logic
[^4]: refactored
