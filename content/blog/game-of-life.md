---
title: "Game of Life"
date: 2018-03-03T12:50:41+13:00
---
My first encounter with Conway's Life was much less low-brow than this.[^1]

Games like chess have simple rules that enable complicated gameplay. ["Conway's Life"](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) shows how even without any players, a very simple game, with rules even simpler than chess, can support surprising and interesting dynamics.

In Conway's Life, the gameboard is a grid of squares which are either "living" or "empty". Simple rules say for each square, based on its eight neighbour squares, whether it will be alive in the next turn. There is a just right goldilocks zone between loneliness and overcrowding. Living squares with 2-3 neighbours survive, and empty squares with three neighbours fill with new life. Those with more or fewer neighbours die or remain empty.

Changes occur only by mechanically following those simple rules, clearing-out squares which are too lonely or too crowded, and filling-in squares where the number of neighbours is in the "just right" goldilocks zone for reproduction. The only human input is at the initial design of the gameboard -- whether it is sparsely or densely filled, and in what pattern.

The very simple rules of Life can support surprisingly complicated behaviour. There are shapes which, by

![glider animation](img/glider.gif)

Some patterns of squares repeatedly send out gliders.

![breeder animation](img/breeder_animation.gif)


## ADOM

[^1]: My first encounter with Conway's Life was within another game. "Ancient Domains of Mystery" or ADOM is a dungeon-crawling game. Among other challenging and amusing complexities, players can manage bushes of herbs which offer beneficial effects, and grow according to the rules of Conway's Life. Check [here](http://www.adomgb.info/adomgb-0-13.html#0.13.6) for way too much information on herbs in ADOM.


