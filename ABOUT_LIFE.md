# About Life
Life is a cellular automation created by the English mathematician John Conway. As a cellular automation, 
Life has the following elements:
* A two-dimensional grid of cells, where each cell in the grid has an attribute called a state
* A set of states that a cell can be in
* A transition function that maps a cell's state and the states of its neighbours to a new state

For Life in particular:
* A cell can be in one of two states: dead or live
* The transition function consists of the following rules:
    * If a cell is live and has 2 or 3 live neighbours, the cell's next state is live
    * If a cell is dead but has 3 live neighbours, the cell's next state is live
    * All other cells have a next state of dead
    
Note that for Life, a cell's neighbours are defined using the 
[Moore neighbourhood](https://en.wikipedia.org/wiki/Moore_neighborhood) definition.

The game is played by setting an initial state, and then repeatedly applying the rules of the game 
to generate successive states.

Life is interesting for several reasons:
* Emergence: repeated application of simple rules to a simple initial state can result in very 
complex and intricate future states
* Undecidability: no algorithm can take two states and determine if application of the rules
to one of the states will yield the other state
* Turing completeness: the game can theoretically simulate any Turing machine
* Self-similarity: the game can be implemented in itself 
(see [Life in Life](https://www.youtube.com/watch?v=xP5-iIeKXE8))
