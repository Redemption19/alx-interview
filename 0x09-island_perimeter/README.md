# Island Perimeter

## Description
This function calculates the perimeter of the island described in a grid. The grid represents a map where 1 represents land and 0 represents water. The perimeter of the island is defined by the number of edges between land and water cells.

### Function Signature
```python
def island_perimeter(grid: List[List[int]]) -> int:
    pass
grid: A list of lists of integers representing the island grid.
Each cell is square with a side length of 1.
0 represents water.
1 represents land.
Cells are connected horizontally/vertically, not diagonally.
The grid is rectangular, with its width and height not exceeding 100.
The grid is completely surrounded by water.
There is only one island (or nothing).
The island doesn’t have "lakes" (water inside that isn’t connected to the water surrounding the island).
