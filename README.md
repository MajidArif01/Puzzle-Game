Initialization:

Two arrays, tiles and goal, represent the current state of the puzzle and the goal state.
The shuffle_tiles function is defined to randomly shuffle the tiles.
Printing Functions:

print_grid prints the current state of the puzzle in a 5x5 grid.
print_path prints the sequence of moves.
Game Logic Functions:

goal_State checks if the current state of the puzzle matches the goal state.
tile_Index finds the index of a specific tile in the puzzle.
legal_Moves shows the legal moves that can be made from the current state.
swap_tiles swaps a chosen tile with the blank tile.
is_solveable checks if the puzzle is solvable.
Main Game Loop:

The script starts with a welcome message and shuffles the tiles until a solvable configuration is achieved.
The initial state of the puzzle is printed using print_grid.
The main game loop runs until the goal state is reached.
It displays legal moves.
Accepts user input for the tile to move, with options to quit or print the move path.
Checks the validity of the move and updates the puzzle state accordingly.
Checks if the goal state is reached after each move.
After winning the game, the sequence of moves is printed using print_path.
