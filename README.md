# Grid Multiple Challenge
Brute force generation of possible solutions to the vertical=horizontal product of NxN grid.

- To execute code, create a logs.txt file in the directory of the main.py.
- The programme appends all possible solutions (along with the respective products formed) to the logs.txt.
- The format for the data is: [Grid] [Horizontal Products] [Vertical Products]
- The grid is displayed as a Python 'list' in such a way that the first 'n'-entries constitute the first row and the next 'n'-entries form the second row and so on.
- Consequently, alternate values, i.e. [0, n, 2n...], form the first column and [1, n+1, 2n+1...] form the second column and so on (taking the first value, the top-left value in grid arrangement, as 0th index and bottom-right value in grid arrangement as the (n^2-1)th index)
