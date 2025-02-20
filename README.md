# Maze-Solving-Robot

The tasks attempted for this assignment was having the robot complete the maze and find the exit without going past walls, having the robot return to its original starting position, and mapping coordiantes that are part of the solution.

The algorithm that I used for the robot to solve the maze is a wall following algorithm that is designed to follow the right wall until the exit is found. The algorithm makes the robot move when the way is clear, it will then check right and if there is a wall the robot will turn left. If there is another wall it will keep going left until the robot no longer detects a wall nearby.

The way the robot maps the solution is that at every unqiue square along the path it takes, the robot will note down the coordinates in a list and at the end will display to the user the coordinates visited.

The returning feature is a seperate function that is executed after the robot finishes the maze. It will still follow the right wall algorithm until it reachess the orignal coordiante it started from. If the starting coordiante was different everytime you could use the coordinates from the pathing feature, but the coordiante it will always return to is 130, -900.
