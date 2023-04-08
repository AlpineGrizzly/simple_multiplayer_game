# Simple Multiplayer game using python sockets

Simple multiplayer game that will have a client server pair where multiple users
can log into the hosted server and compete against one another in a shot them up
2d base building game. Concept so far is players will be divided into two groups and will be able to fight one another to earn income that can be used towards
strengthing defenses against opposing groups.

## Dependencies 
| OS   | Dependencies | 
|------|--------------|
|Windows| TBD         | 
|Ubuntu| sudo apt-get install python3-pip python3-dev; sudo pip3 install pygame|

## Usage
python3 destrBros.py.

Problems:
- Doesn't exit properly, not sure why, might be a python issue or a pygame issue but
  calls are being properly called. 

TODO:
Overview of the gameplan for this repository. I will be creating a server that 
a user will have to host in order to have all players/clients connect to it to play.
- [] First and formost, need to plan out how the game is going to work. Need to
probably start on the client and server connection portion first then 
development for the game can follow that knowing we have an operational base 
and connection between the two
