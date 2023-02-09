# CSC8503-Engine
Submission for CSC8503. Involves a basic physics engine implementation with some AI. Requires CMake to create build folder to run for each machine.

Initial code base supplied from Newcastle University, mostly for handling graohical representation of the physics engine

|Feature|Description|
|State Machines|There are three forms of state machines I have implemented in this project, finite state machine for simple AI agents, behvaiour tree for more advance AI agents, and pushdown automata for the menu systems|
|Pathfinding|In this project exists the pathfinding algorithm A*, this is used by agents in the game to traverse the maze,  by ranmdomly selecting to naviaget to certain points on the map|
|Collsion Detection|Objects in this engine have collision volumes for capsules, spheres, and cubes. Cube collsion detection is done using Axis Aligned Bounding Boxes|


##Controls  
G – turn gravity on or off  
V – turn on spring collision resolution  
Q – select mode  
L – lock to selected object to control  
##Pause Menu  
P – pause game  
Space – un-pause game  
M – enter option menu  
5 – decrease player speed  
6 – increase player speed  
Locked object controls for player  
Arrow Keys – to move selected object  
Shift – Jump  
Middle mouse button – fire rope to point  
R – detach from rope  
2 – Zoom in  
1 – Zoom out  
