# MyBouncingBox

This is my implementation of the old (I think 90's) Microsoft bouncing box screen saver.

Here, the (0, 0) coordinate (x, y) is at the very top left of your screen.
The box moves diagonally and each time it reaches a border it will change direction depending to it's initial direction and the border it touches.
If the box is moving bottom-right:
-- when it reaches the bottom border it will go top.
-- when it reaches the right border it will go left.
