# Introduction

Hey everyone, this is the backend for the ChessAI project (https://github.com/BranimirKoprivnjak/ChessAI).
It offers some extra funcionalities such as implementation of Stockfish and for the overall smartness of our engine,
initial moves from the book of past openings done by many Grandmasters.

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

