---
title: "Coin Collection Game (Python)"
excerpt: "<img src='/assets/img/projects/coin.png'>"
collection: portfolio
date: 2016-11-16
---

![Screen shot](/assets/img/projects/coin.png)

This is a simple game of Python.

The game is played on a grid whose cells contain a character and coins of various values (5, 10, 20, 50, 100, and 200).
The grid height and width are equal, with an odd number of columns / rows. The character is initially placed on the
central cell, and all the other cells contain a coin with a random value.

The two players play in turn to move the king of the map. The current player chooses a direction to move king to one
cell(horizontally, vertically, or diagonally), provided that the destination is in the grid and contains a coin.
The coin is taken by the player as the result of the move. If the king has no possible move, the game ends and the winner
is the player whose coins sum to the greatest amount.


## Requirements

* Python 3.5.2 ( > 3.0)
* Pyqt 4

## Run

```
$python main.py
```
## Options

#### Game Mode

* Single-player   Mode : To play with computer. The computer's action is optimized by an AI algorithm ([Minimax Algorithm](https://en.wikipedia.org/wiki/Minimax))
* Double-player Mode : Two humain players play in turn.

#### Map Initialization

* Random initialization
* Load map from csv file

## Source code

Find out more by [visiting the project on GitHub](https://github.com/Tong-ZHAO/Coin_Collection_Game).
