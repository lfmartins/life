In this notebook, we answer [a "Riddler Classic" question posed](https://fivethirtyeight.com/features/can-you-solve-the-chess-mystery/) in The Riddler section of  [FiveThirtyEight](https://fivethirtyeight.com)

The question concerns John Conway's Game of Life, originally made popular by a [Mathematical Games column](https://web.stanford.edu/class/sts145/Library/life.pdf) by Martin Gardner.

The problem, as proposed in The Riddler, is:

>Now suppose we were to replace the infinite grid with a finite grid that has periodic boundary conditions, so that cells in the first row are neighbors with cells in the last row, and cells in the first column are neighbors with cells in the last column. If there are three rows and N columns, what is the smallest value of N that can support an oscillator?

The solution found is that the smallest $n$ is 4, for which there are 4 osillators.

As an added result, we also consider the cases $n=5$, $n=6$ and $n=7$. There are no oscillators for $n=5$ or $n=6$, but there are oscillators for $n=7$.

