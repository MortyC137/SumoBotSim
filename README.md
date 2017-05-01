# SumoBotSim
This repo is a simulator written in python for the purpose of simulating robot sumo battles. You can see examples of this sort of hobby on [youtube](https://www.youtube.com/watch?v=orVAhhQAJ_c).

## Development Plan
Currently I am learning pyglet and pybox2d in an effort to understand where it is appropriate to abstract various elements of the simulator. Currently I have identified that at least the following concepts will be distinct:
* The core simulator
  * Dynamics models for the robots
  * Sensing models for the robots
* Rendering the simulation
  * A debug visualizaiton mode to show when certain sensors are active, and thier area of coverage
  * A "realistic" top down visulation. Not photo realistic, but at least avoiding any non-visible concepts as would be common in debug mode
* A high level "black box" interface to control the robots and retreive sensing data from the robots
