Reverse-Delete Game

# Goal:
The goal of the game is to have the most points at 
the end. Players can recive points by removing 
edges and completing trees,and players can lose 
points by disconnecting components that include cycles.


# Rules:
You receive the amount of points per edge as that 
edge's weight. A player loses points if they remove an edge that 
dissconnects a component from the rest of the board.
Then, they will lose the amount of points as the sum of the disconnected edges in the
component with the fewest nodes (player's choice if both components are equal). 
BUT, if the disconnected component is a tree with 3 or more nodes, they
DO NOT lose any points, and collect all of the edges in that component including the 
deleted edge used to disconnect the tree.
