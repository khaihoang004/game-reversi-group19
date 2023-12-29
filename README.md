# Game Reversi
Capstone Project by Group 19 in the course Intro to Artificial Intelligence - IT3160E of SOICT - HUST, semester 2023.1.

For further information on our project, please refer to the report attached to our repository.

## Group members

|       Name       | Student ID|
| ---------------- | --------- |
| Pham Minh Hieu   | 20220062  |
| Nguyen Viet Anh  | 20225434  |
| Nguyen Trong Tam | 20225527  |
| Hoang Trung Khai | 20225502  |
| Trinh Duy Phong  | 20220065  |

## Installation
First, clone this repository to access our work:
```
git clone https://github.com/ahihidongok111/game-reversi-group19.git
```
To install necessary packages, run:
```
pip install -r requirements.txt
```
For running the main program, run the following script:
```
python main.py
```

## Instruction
Our Reversi/Othello program supports multiple heuristics for evaluating board positions, namely **Coin Parity**, **Corners**, **Mobility**, **Stability**, **Everything**, **E-coins**, **E-corner**, **E-mobility** and **E-stability**. You can choose your desired heuristic in the heuristic selection menu in our program.

Furthermore, you can also choose the depth of the opponent (from **1** to **8**). **Please be aware that selecting a high depth (greater than or equal to 7) may lead to the program's unresponsiveness.**

To play a move, use the **left mouse button**. To print the current board state to the terminal, press the **right mouse button**.

If one player does not have a legal move, a _pass_ button will appear on the right-hand side of the screen. Click the _pass_ button to continue the game.
