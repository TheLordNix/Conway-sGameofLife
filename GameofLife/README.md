# Conway-sGameofLife

A simulation of Conway's Game of Life, This is a zero-player game, meaning the evolution is determined by its initial state, with no further input. It's played on a grid of cells, each of which can be either alive (1) or dead (0). The state of each cell in the next generation depends on its 8 neighbors, following the classic rules of:
Underpopulation: A live cell with fewer than 2 live neighbors dies.

Survival: A live cell with 2 or 3 live neighbors lives on.

Overpopulation: A live cell with more than 3 live neighbors dies.

Reproduction: A dead cell with exactly 3 live neighbors becomes a live cell.

## Conquest the 1v1 mode with slightly adjusted rules:
Underpopulation: A live cell (P1 or P2) with <2 neighbors dies (turns to 0).

Survival: A live cell (P1 or P2) with 2 or 3 neighbors of the same player stays alive.

Overpopulation: A live cell with >3 total neighbors dies (regardless of ownership).

Conquest (Reproduction): A dead cell with exactly 3 live neighbors becomes alive:

If 2+ of the neighbors are from Player 1, the cell becomes 1.

If 2+ are from Player 2, it becomes 2.

If it's a tie (e.g. 1 from each), the cell stays dead (or resolves based on your implementation — some variants give priority or keep it dead).

