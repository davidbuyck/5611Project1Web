# 5611 Project 1 Web Page

David Buyck

## [View the code on Github](https://github.com/davidbuyck/5611Project1Code.git)

### Click on the images to play the YouTube videos!!!

## Part 2

#### Features attempted

- Single Agent Navigation
- 3D Rendering & Camera
- Improved Agent & Scene Rendering
- Incorperate Particle System
- Orientation Smoothing
- User Scenario Editing+
- Realtime User Interaction

[![Part 2](https://img.youtube.com/vi/iGEM7R6mYZI/0.jpg)](https://www.youtube.com/watch?v=iGEM7R6mYZI)

### Single Agent Navigation
A 3D ship is the agent that navigates from space station to space station on its way to Earth. The stars are obsitcles. A* is used to ensure there are no collisions and the path to the Earth is optimal along the graph created by the space stations.

### 3D Rendering and Camera
The ship, space stations, Earth, and stars are all 3D modles. The camera is on a cinnemachine rig that allows the camera to rotate around a focused object. I added the functionality of zooming in and out with a mouse wheel. Lighting is everywhere since you are surrounded by stars. 

### Improved Agent and Scene Rendering
The ship is a space ship model and is not a simple geometric shape. Obsicles are stars and waypoints are space stations. Stars have complex textures and shaders and the space stations is extremely complex.

### Incorperate Particle System
The ships thrusters emit particles when the ship accelerates. The particles change colors from blue (very hot) to white (less hot) throughtout the particle lifetime. 


### Orientation Smoothing
I originally had the ship turn towards each waypoint and have smooth trajectory curves at each space station. This is not how space ships travel from destination t o destination and caused issues with accuracy. To make a more realistic space simulation the ship accelerates from one station, rotates to apply a reverse thrust, then accelerates to a stop at the next station. This allows the simulation to feel more realistic. 

### User Scenario Editiong+
The user can change the agnets starting position by flying the ship through the stars with the WASDQE keys and the space bar to apply thrust. This allows the user to chose a starting posiiton for the ship. Then the user can press R with they are ready to Resume the simulation.

### Realtime User Interaction
Just as stated above, the user can fly the ship with the WASDQE keys and the space bar. So the user could explore and interact with the scenario for as long as they want before resuming the simulation.

## Part 3

[![Part 3](https://img.youtube.com/vi/6wyiY0b3XRw/0.jpg)](https://www.youtube.com/watch?v=6wyiY0b3XRw)

The first interesting scenario is where the birds avoid the trees while flying out of the forrest. The second interesting scenario is where the birds fly up a hill ascending with the hills slope. 

The boid code provided in class was used for the birds flight patterns. The cinnemachine camera was used to focus on the flock and zoom in and out. 



No partners we used. 

I used Wikipedia for the A* pseudocode. The simulations were made int the Unity Engine 2021.3.10f1. The UnityEngine and Cinnemachine libraries were used. 
