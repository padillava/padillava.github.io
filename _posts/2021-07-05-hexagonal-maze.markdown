---
layout: post
title: Hexagonal Maze
date: 2022-06-27 14:40:00 +0300
description: A game with a procedural generated maze.
img: hexagonal-maze.png # Add image post (optional)
tags: [Unreal Engine, C++] # add tag
---

Hexagonal Maze is a demo of a game developed with a few partners. It consists on a race against a ghost to find the exit of the labyrinth. The player starts in the start, while the ghosts starts in the exit. The player must get around traps to try to not die and reach the exit. For that, the player can use a teleport skill to mark a point and return to there anytime they want. The objective of the game is to get as many points as possible by completing each run without being hit by traps.

In the demo, all the labyrinths are created using a procedural generation of rooms. We created a base room and then the game creates a random path between all the room in the labyrinth. After that, it adds all the traps and the start and exit point, being sure that they are far enought apart from each other. And the ghost will try to find the start using always the rule of the right hand. Always going into the rooms on its right until reaching the start point.

In this developement my part of the work was the following:

* Generation of the labyrinths, traps and points of exit and start.
* AI of the ghost.
* Creation of some traps.
* Creation of the teleport.
* Creation of the score system.



{% include video.html id="JV4Wa2UFmgU" %}
