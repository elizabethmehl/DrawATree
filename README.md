This Python script creates a tree shape using Turtle graphics. The tree is drawn recursively, with branches branching out at various angles.

Usage
Copy the provided Python code into a file.
Run the script using Python.
A window will display the drawn tree.
Description
The script uses the Turtle module to draw the tree shape. It sets the background color to black, pen size to 2, and the turtle color to green. The turtle's shape is set to 'turtle', and it's positioned facing upwards.

The tree function recursively draws the tree shape. It takes a parameter i representing the length of the current branch. If i is less than 10, the function returns, terminating the branch. Otherwise, it draws the branch, circles at its end, changes color to brown for subsequent branches, and recursively calls itself twice to draw smaller branches at different angles.

Customization
Adjust the starting length of the tree by modifying the argument passed to the tree function.
Experiment with different colors by changing the arguments of the color function calls.
Modify the angles of the branches by adjusting the values passed to left and right functions.
