# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Peter Kjaer
## Lab Summary
This lab continued to build on identifying maxterm and minterm equations from truth tables and k-maps. The place where I really learned something this lab was the constraints and top files. I learned how the vivado and the board actually work. I learned how the constraints file is helpful so that only the things that are neccessary on the board are used in the program and implementation. I now know how the ports are mapped onto the board. In the top file I continued to learn how variables in the v code can be mapped to switches and leds on the board.

## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file connects the switches, buttons, leds, etc. to the code. It also combines other files that you make (like circuit a and b) to complete the logic. Finally, it pulls from the constraints.xdc file to run it in vivado.
### 2 - Explain the function of the Constraints file.
The constraints file activates different ports, switches, and leds on the board. It tells which port goes to which physical pin. It can also set clock and timing things for the program.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
The selection for maxterm on circuit A was correct. It was easy to see in the k-map and ended up with a very simple equation. For circuit B, I think a maxterm would have also been better, but not by much only reducing the circuit by one gate. Minterm was not a terrible choice, both resulted in fairly complicated circuits.