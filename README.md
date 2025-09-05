# Sudoku note

Here's an aid to solve Sudoku puzzles. It keeps track of where there are conflicts while you still do the thinking, the whole point of spending time with puzzles.

Start in Setup mode and enter your puzzle.  Use the tab key to move between cells. Use shift-tab to move backwards. Press Done and you will be in Solve mode. The initial values will be in green.

All other cells have numbers 1–9 in them. A cell with a red border has at least one number that is in conflict with another cell that has a single number.

Remove numbers from a cell that cause conflict. The remaining numbers are those that can be in that cell.

For example, if a cell has the single value 5, then no other cell in the same row, the same column or the same square, may have value 5. Click on 5 in all the cells in the same row, column and square. Those cells will now have the numbers 1–4 and 6–9 as options. Keep going until there are no more conflicts. Eventually, cells will have a single value and reduce the options for adjacent cells.

There is a bomb symbol on the top. Press it and all red numbers are removed.

There is also a bomb symbol in a cell when it has a decided number. Press it and every number (red) that the cell is in conflict with gets eliminated.

The notebook is saved in your browser, so if you come back here, your last puzzle will be restored. 