# Introduction

Hey everyone, I've built a chess AI based on Minimax algorithm (Negamax implementation) & Alpha-beta pruning optimization. Minimax tries to find most optimal move for a player,
assuming that our opponent also plays optimally. Its a backtracking based algorithm, its tries all possible moves for given depth and then backtracks and makes a decision 
which is based on some heuristic evaluation of the leaf nodes.

For the smartness of our engine, we are using initial moves from a book of past openings done by many Grandmasters.

Also, Stockfish, famous chess engine is implemented and can be tested versus our engine.

### Technology used
Python&Flask

### Libraries
python-chess, sys


## Installation

To get this project up and running you should start by having Python and pip installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
pip install virtualenv
```

Clone or download this repo, cd into the folder and create your virtual environment

```
python -m venv venv
```

That will create a new folder `venv` in your project directory. Next activate the environment

Mac OS / Linux:
```
source venv/bin/activate
```

Windows:
```
venv\Scripts\activate
```

Install the project dependencies with

```
pip install -r requirements.txt
```

Run local server

```
flask run
```

## Demo

![Screenshot (537)](https://user-images.githubusercontent.com/85017668/148134812-6d7ebaa7-2cbe-4179-8cc5-c2249da16f75.png)
Stockfish checkmates
![Screenshot (538)](https://user-images.githubusercontent.com/85017668/148134849-7c52df1c-54a7-4e53-95ca-4a895fa201af.png)

