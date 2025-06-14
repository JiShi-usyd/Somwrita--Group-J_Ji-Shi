# Interaction Instructions
My interaction method is to use the keyboard to interact: use the W, A, S, and D keys to control Pac-Man to move up, down, left, and right. And make Pac-Man walk along the maze path and then "eat" all four ghosts. When all ghosts are eaten, a message "Mission Success!" will pop up.
# Details
The key point is that ghosts disappear after being "eaten", and Pac-Man can move, but can only walk on the path.
## Technical Implementation
The maze consists of a series of path segments, and Pac-Man's movement is restricted to these paths. Coordinate checks are required to ensure that Pac-Man stays on a valid path.
A simple distance-based check is performed between Pac-Man and the ghost, and the ghost disappears when it is within a certain range of Pac-Man.