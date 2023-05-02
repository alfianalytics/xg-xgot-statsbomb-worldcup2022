# Building xG and xGOT based on Statsbomb World Cup 2022 Open Data
This repo contains my Notebook that covers steps to build simple
expected goals (xG) model and expected goals-on-target (xGOT) model.

## xG Model
First, I built a simple model with only 2 features that are angle and distance of the shot.
Then, I built the 2nd model with more features that are:
- Shot types of play (penalty, free kick)
- Body part (header, preferable side)
- Is under pressure?
- Shot technique

I also identified which team is the biggest overachiever and underachiever.

## xGOT Model
I built the xGOT model with just simple features that are the distances of the end shot to the center of goal.
I also visualized players to see how their xG and xGOT correlated to each other, made us know
which player has better chances and which player has better shot placing ability.

I wrote an article about the xG model, and soon the xGOT model
- [How to Build Your Own Expected Goals (xG) Model](https://medium.com/@alf.19x/how-to-build-your-own-expected-goals-xg-model-2bd186dccdf7)
