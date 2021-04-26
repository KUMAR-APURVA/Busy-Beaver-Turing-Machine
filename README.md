# Busy-Beaver-Turing-Machine
Busy Beaver Problem aims at finding the best turing machine which produces maximum number of 1's on a infinite length tape cell initially filled with all 0's 
and which finally halts. 

It consists of  symbols (m) and states (n).

Two functions are defined for a Busy Beaver Problem :-
     
     1. Σ(n,m): the largest number of 1's(or non 0's in case of symbols >2) printable by an n-state machine before halting, 
     
     2. S(n,m): the largest number of steps taken by an n-state machine before halting.

In our code we have considered 2 symbols (0 and 1) and 5 different states (1, 2, 3, 4, 5) and
we are computing  Σ(n,m) and S(n,m) for the best turing machines for each state.



