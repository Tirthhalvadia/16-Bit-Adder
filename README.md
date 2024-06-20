# 16-Bit-Adder

## Project Description

This project focuses on the design and evaluation of four types of 16-bit adders using Cadence Virtuoso. The adders are assessed through comprehensive functional, corner, and temperature simulations to determine their performance characteristics. Among the evaluated designs, the Carry Bypass Adder (CBA) demonstrated superior efficiency, achieving total addition times of less than 400ps under most conditions. The project also emphasizes the significance of power-supply voltage optimization to enhance performance.

## Introduction

In this project, four different adders were compared based on delay:
1) Ripple carry adder: A ripple carry adder is built by cascading 1-bit full adders, where the carry output of each full adder is connected to the carry input of the next full adder in the sequence.
2) Carry Bypass adder (CBA): The carry bypass adder operates by bypassing carry propagation when all propagate bits are 1, effectively minimizing delay.
3) Carry Lookahead adder (CLA): The carry lookahead adder involves precomputing carry signals independently of the data inputs, enhancing addition speed by reducing carry propagation delays.
4) Carry select adder (CSA). The carry-select adder concurrently generates sum outputs with both possible carry inputs and selects the sum and cout using the 2x1 mux based on the carry-in signal.

## Key Features

•	16-bit binary addition: Each adder is capable of adding two 16-bit binary numbers.

•	Performance Evaluation: Detailed simulations to analyze functional, corner, and temperature performance.

•	Efficiency Highlight: The Carry Bypass Adder (CBA) shows total addition times of less than 400ps.

•	Power-Supply Voltage Optimization: Emphasis on the importance of optimizing power-supply voltage for better performance.

## Simulation and Evaluation
The project involved generating and analyzing various simulations to evaluate the performance of the designed adders:

•	Functional Simulations: To ensure correct functionality of the adder designs.

•	Corner Simulations: To assess the performance under different manufacturing process variations.

•	Temperature Simulations: To evaluate the adder performance across a range of operating temperatures.

## References
•	Cadence Virtuoso Documentation

•	Digital Integrated Circuits: A Design Perspective by Jan M. Rabaey



