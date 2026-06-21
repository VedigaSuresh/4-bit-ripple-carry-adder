# 4-Bit Ripple Carry Adder Project Report

## Introduction

A Ripple Carry Adder (RCA) is a digital circuit used to perform binary addition. It consists of multiple Full Adders connected in series. The carry output from one Full Adder becomes the carry input of the next stage.

## Objective

* To design a 4-Bit Ripple Carry Adder.
* To understand binary addition.
* To study carry propagation.
* To implement the circuit using Verilog HDL.

## Theory

A 4-Bit Ripple Carry Adder uses four Full Adders to add two 4-bit binary numbers.

Inputs:

* A[3:0]
* B[3:0]
* Cin

Outputs:

* Sum[3:0]
* Cout

The carry generated in each stage ripples to the next stage, hence the name Ripple Carry Adder.

## Block Diagram

FA0 → FA1 → FA2 → FA3

Where:

* FA = Full Adder

## Working

Each Full Adder performs:

Sum = A ⊕ B ⊕ Cin

Carry = AB + BCin + ACin

The carry output of one stage is connected to the carry input of the next stage.

## Advantages

* Simple design
* Easy implementation
* Low hardware complexity

## Disadvantages

* High propagation delay
* Carry must pass through all stages

## Applications

* Arithmetic Logic Units (ALUs)
* Digital processors
* Embedded systems
* Calculators

## Conclusion

The 4-Bit Ripple Carry Adder was successfully studied and implemented. The circuit demonstrates binary addition using cascaded Full Adders and highlights the effect of carry propagation delay in digital systems.

## References

1. Digital Design – M. Morris Mano
2. Digital Fundamentals – Thomas L. Floyd
3. Verilog HDL Documentation
