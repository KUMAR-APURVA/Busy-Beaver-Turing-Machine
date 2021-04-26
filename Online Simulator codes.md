## We have simulated 2 states 2 symbols and 3 state 2 symbols Busy Beaver Turing Machine using online simulator https://turingmachine.io/
Just go to the above mentioned site, clear the code on the right side and copy the below mentioned code and then click on load machine.

### For 2 states 2 symbols Busy Beaver Turing Machine
```
# A 2-state 2-symbol busy beaver
blank: '0'
start state: q1
table:
  q1:
    0: {write: 1, R: q2}
    1: {L: q2}
  q2:
    0: {write: 1, L: q1}
    1: {R : H}
  H:
  ```
  
  ### For 3 states 2 symbols Busy Beaver Turing Machine 
  ```
  # A 3-state 2-symbol busy beaver
blank: '0'
start state: q1
table:
  q1:
    0: {write: 1, R: q2}
    1: {R : H}
  q2:
    0: {write: 0, R: q3}
    1: {write: 1, R: q2}
  q3:
    0: {write: 1, L: q3}
    1: {write: 1, L: q1}
  H:
  ```
