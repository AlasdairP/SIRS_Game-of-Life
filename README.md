# SIRS_Game-of-Life
Spring 2022, part of Modelling and Visualisation in Physics

Two parts:

1. Game of Life

All cells are updated in parallel at each time step.





2. SIRS

On each update step, a cell is chosen at random.

Cells become infected (S -> I) with probability p1 if a neighbouring cell is infected.
Cells recover (I -> R) with probability p2
Cells become susceptible again (immunity wears off) (R -> S) with probability p3.
