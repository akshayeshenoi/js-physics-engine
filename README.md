# Box Jump

Box jump is a simple game that demonstrates the basics of game development, particularly the 2d physics engine.

<img src="https://raw.githubusercontent.com/akshayeshenoi/js-physics-engine/master/gameplay.png" width=350>

## Basic concepts

The game runs entirely in any browser that supports the `<canvas>` element and is written in Vanilla JavaScript.  

The foundational concepts are:
- Infinite Game Loop
- Game state
- Physics
- Window paint


The game attempts to render a new state every time the browser paints the window. This is done using the `window.requestAnimationFrame()` API.  

Every cycle loops through two stages: **updating the state** (using the physics), and **painting the state**. 
