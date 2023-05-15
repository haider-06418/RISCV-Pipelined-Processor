# 5 Stage RISC-V Pipelined Processor 
## About
A 5-stage pipelined processor capable of executing any one array sorting algorithm using RISC-V instruction set. 
## Description
### Part 1:
Chose a suitable sorting algorithm. Converted its pseudocode to assembly using RISC-V instruction set and tested its working on the assembly code simulator. Then, modified the existing lab 11 single-cycle processor architecture to run the sorting algorithm code on it. Tested and verified that it did the sorting correctly.
### Part 2:
Modified this processor to make it a pipelined one (5 stages). Tested and ran each instruction separately to verify that the pipelined processor version could at least execute one instruction correctly in isolation. Tested different types of instructions. Test cases mattered!
### Part 3:
Introduced circuitry to detect hazards (data, control, and structural if needed) and tried to handle them in hardware i.e., by forwarding, stalling, and flushing the pipeline. If this was done correctly, then the array sorting code should have been able to function in its entirety.
### Part 4:
Compared the performance of running the array sorting program on Single Cycle Processor with RISC-V Processor in terms of execution time.
## Attribution
Course Project for EE 371L/CS 330L/CE 321L Computer Architecture, Spring 2023 offering at Habib University. 
