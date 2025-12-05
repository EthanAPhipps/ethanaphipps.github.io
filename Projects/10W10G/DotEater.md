---
layout: page
title: 10 Weeks 10 Games - Dot Eater
---
This was my second, much more ambitious attempt, making a procedurally generated maze, but otherwise similar to a standard Pac-Man game. This one took the longest by far and extended into the following week, something I took into consideration in the rest of the projects.

It randomly generates a symmetrical maze and place the power-ups randomly within it, enemies would spawn in that had to be avoided.

Compared to the Snake game I added button controls but re-used some assets, such as the title screen and grid squares, basic as they were, to allow me to spend more time on the game itself. Likewise the arrows that I made got re-used a lot in the future games.

In hindsight however I have a few grievances with the way I wrote it which I'd reconsider if I had to do it again:
- There was only one RNG seed, such that enemy spawn locations would change depending on the enemy AI random decisions, which also then changed the seed for the next level. I'd instead designate spawn positions ahead at level generation time and run any in-game RNG on a different seed.
- There would too often be "peninsulas" formed in the generation, including in the screenshot below in the bottom corners, that are very easy to get trapped in. I'd refine how the maze generation is done to avoid having points that are only accessible through one route.

Though that being said, I did enjoy the challenge in making this and doing it early gave me the confidence to do the rest, as well as establish what I could and couldn't re-use.

![](/assets/img/10W10G/dot_0.png)
*Screenshot of the game*

![](/assets/img/10W10G/dot_1.png)
*Screenshot of the game with a different level layout*

Previous: [Snake]({% link Projects/10W10G/Snake.md %})

Next: [Shmup]({% link Projects/10W10G/Shmup.md %})