###Mars Rover Kata

Develop an API that moves a rover around a grid.

    Given an initial starting point (0,0,N) of a rover
    Given 0,0 are X,Y coordinate on a grid of (10,10)
    Given N is the direction it is facing (i.e. N,S,E,W)
    Given L allow the rover to rotate left
    Given R allow the rover to move right
    Given the grid may have obstacles

    When the rover receives a command RMMLM
    Then it returns the finishing point after the move (e.g. 2:2:N)

    When the rover reaches the end of the grid
    Then the rover wraps around

    When the rover meets an obstacle
    Then the rover moves up to the last possible points
    And reports the obstacle (e.g. O:2:2:N)