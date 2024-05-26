# solar-power-area-optimizer

You can write your solution(s) in Python.


We have a map of an area where two square solar power plants are planned to be built. The map is given as a rectangular matrix A of boolean values. A[R][C] is true if a place in the R-th row and C-th column can be covered by a solar power plant and false if it is not possible.

Each solar power plant must be built in a square shape. Note that a single cell is sufficient for a valid solar power plant. Solar power plants cannot share any cell and should be of the same size.

What is the area of each of the two biggest solar power plants that can be built?

Write a function:

def solution(A)

that, given a matrix A consisting of N rows and M columns, returns the area of the largest possible solar power plants that can be built in a square shape. If no two square solar power plants can be built, the function should return 0.


Examples:

1. Given the 4 x 4 map shown in the figure below, the function should return 4. Cells on
which the solar power plant can be built are coloured white and cells that are
unavailable are coloured black. Two solar power plants are hatched. The area of each
power plant is equal to 4, as they each occupy four cells.

A[0][0] = `False` A[0][1] = `True` A[0][2] = `False` A[0][3] = `True`
A[1][0] = `True` A[1][1] = `True` A[1][2] = `True` A[1][3] = `False`
A[2][0] = `True` A[2][1] = `True` A[2][2] = `True` A[2][3] = `True`
A[3][0] = `False` A[3][1] = `True` A[3][2] = `True` A[3][3] = `True`

2. Given the 6 x 4 map shown in the figure below, the function should return 9.

A[0][0] = `True`   A[0][1] = `True`   A[0][2] = `True`   A[0][3] = `True`
A[1][0] = `True`   A[1][1] = `True`   A[1][2] = `True`   A[1][3] = `True`
A[2][0] = `True`   A[2][1] = `True`   A[2][2] = `True`   A[2][3] = `True`
A[3][0] = `True`   A[3][1] = `True`   A[3][2] = `True`   A[3][3] = `True`
A[4][0] = `True`   A[4][1] = `True`   A[4][2] = `True`   A[4][3] = `True`
A[5][0] = `True`   A[5][1] = `True`   A[5][2] = `True`   A[5][3] = `True`

3. Given the 3 x 5 map shown in the figure below, the function should return 0. It is impossible to build two solar power plants.

A[0][0] = `False`  A[0][1] = `False`  A[0][2] = `False`  A[0][3] = `False`  A[0][4] = `False`
A[1][0] = `False`  A[1][1] = `False`  A[1][2] = `True`   A[1][3] = `False`  A[1][4] = `False`
A[2][0] = `False`  A[2][1] = `False`  A[2][2] = `False`  A[2][3] = `False`  A[2][4] = `False`

Write an efficient algorithm for the following assumptions: ・N and M are integers within the range[1...700].


## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/solar-power-area-optimizer.git
cd solar-power-area-optimizer
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
