# PathFinder-Pro
Recursive backtracking is a technique used by PathFinder Pro to create mazes with specific dimensions.

One of the few maze generation methods that produces a perfect maze—that is, a solvable maze without unreachable parts or loops—is recursive backtracking.

An overview of the recursive backtracking algorithm is given below:

Select a maze beginning cell.

If the neighboring cell has never been visited, take a random wall from that cell and remove it to connect the starting cell to it. The current cell changes to the neighboring cell.

Once every neighbor cell has been explored, go back to the last cell with unexplored neighbors and repeat the process.

Once it has backed up all the way to the, the algorithm is finished.
