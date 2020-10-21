# Boids
## Boids implementation using WebGL, THREE.js and dat.gui
### The code was developed with WebStorm IDE and tested on Google Chrome, no other browser was tested.

The code on this repository is a answer to a practical exercise of Graphical Computation course of Universidade Federal de Minas Gerais


DEMO: https://matvargas.github.io/flocking/


# Features

- The world starts with "creatureNum" creatures, the current default value is 150
- This value can be altered by a slider on the menu
- Each creature is spawn as a three-dimensional polyhedron with random dimensions and colors
- Each creature has it own speed vector and the direction is randomized
- Boids avoid the box walls, the center cone and other boids
- Interaction between boids are calculated by enforcing align, cohesion and separation properties inside a loop that compares each creature on the current instance
- The red ball is the boid's leader, it has bigger values of align and cohesion
- The starting behavior of creatures is undefined, once the red ball starts to move through the scenario, it "collects" other boids to its own gravity
- Align and separate properties of boids are also customizable through the menu
- The camera can walk through the scenario by using mouse commands:
-- Zoom in: Scroll down
-- Zoom out: Scroll up
-- Move right: click + move mouse right
-- Move left: click + move mouse left
-- Move down: click + move mouse down
-- Move up: click + move mouse up
- A light spot is defined in the upper left corner of the box
- The world implements fog once the user zoom out

# Running code
In order to local run the project, one must open the index.html on the browser. 
Once file hierarchy has been obeyed, it should work fine.

