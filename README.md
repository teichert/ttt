# Introduction: Tic-Tac-Toe (ttt)

Welcome to our tic-tac-toe project. **ttt** is a command-line
tic-tac-toe game that supports multiple players (>=2), custom board
sizes, custom player symbols, and a custom number of target symbols in
a row.  It is also designed to allow automatic play of entire games
from the command-line for testing purposes.  We would eventually like
to include the possibility of computer-controlled opponents.

The purpose of the project is to give our intro to software
engineering class an opportunity to practice git commands and
collaborate on a small project.


## Using ttt: intended functionality

Sample run:

starting the program:

   ./ttt --cols 3 --rows 3 --players xo --n2win 3

sample input/output:
```
  1 2 3
a  | |
  -----
b  | |
  -----
c  | |
x's turn: a3

  1 2 3
a  | |x
  -----
b  | |
  -----
c  | |
o's turn: b3

  1 2 3
a  | |x
  -----
b  | |o
  -----
c  | |
x's turn: b2

  1 2 3
a  | |x
  -----
b  |x|o
  -----
c  | |
o's turn: c3

  1 2 3
a  | |x
  -----
b  |x|o
  -----
c x| |o
the winner is x
```
