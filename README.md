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

## Lab Questions

Summary: In this lab, we learned how to design combinational logic circuits using Verilog. We practiced writing minterms (SOP) and maxterms (POS) given a truth table, then implemented those equations in Verilog modules. We also learned more about the top-level module and how it's used to instantiate submodules and connect them to the physical hardware (switches/led's).

### 1 - Explain the role of the Top Level file.

The top level file instantiates all other sub-modules. In the context of this lab, the top level file connects the circuits to eachother and the switches/led's.

### 2 - Explain the function of the Constraints file.

The Constraints file is the physical implementation for the target hardware. For this assignment, we used Diligent's default mapping for the Basys3 board.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?

The Minterm and Maxterm were correct for each circuit, as they produced the desired results (matched the truth table) and were minimized as much as they could be. We ensured that they were minimized by using groups that were as large as possible (4 values). 
	
