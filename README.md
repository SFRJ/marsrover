You’re part a Mars exploration program. A remotely controlled rover was sent to the surface of the planet.
Develop software that translates the commands sent from earth to instructions that are understood by the rover.

- You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is facing.
- The rover receives a character array of commands.
- Implement commands that move the rover forward/backward (f,b).
- Implement commands that turn the rover left/right (l,r).


Some example acceptance criterias but you can create your own
Given the rover landed at (0,0,N)
When the rover receives command (F)
Then the rover sends feedback back to earth (0,1,N)

Given the rover landed at (0,0,N)
When the rover receives command (FFF)
Then the rover sends feedback back to earth (0,3,N)

Given the rover landed at (0,0,N)
When the rover receives command (R)
Then the rover sends feedback back to earth (0,0,E)

Given the rover landed at (0,0,N)
When the rover receives command (RFF)
Then the rover sends feedback back to earth (2,0,E)





