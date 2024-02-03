# 
![Intro](https://github.com/Karthik-6362/Standard-Cell-Design-Workshop/assets/137412032/5963e65a-9f38-4938-bd7c-c66a6c003969)

# AIM :- 
Workshop Objective
§ Understand SCL design flow
§ ASIC Flow - Role of Std cell library
§ Importance of Different files associated with ASIC Flow


Workshop Flow:
![flow](https://github.com/Karthik-6362/Standard-Cell-Design-Workshop/assets/137412032/77d88ee4-a0d9-4377-acf0-f0b36e4ba687)


# Day 1 

## AIM :- 
- Design a simple symmetrical schematic for Inverter/NOT (INV1X1), NOR (NOR2X1) and  NAND (NAND2X1).
- 


### Introduction to VLSI Design Flow

What is VLSI Design Flow?
* Methodology to design an IC such that it delivers the required functionality or beha

Methodology to design an IC such that it delivers the required functionality or behavior. What decides VLSI Design Flow?
* The VLSI design flows depends on the type of integrated circuits:
* Scope of application
* Design Style

### Different VLSI Design Flow – based on Scope of Application :-
- Application Specific Integrated Circuits (ASIC's)
- General Purpose Integrated Circuits
![asic and gpic diff](https://github.com/Karthik-6362/Standard-Cell-Design-Workshop/assets/137412032/5a8aeb4f-1413-43c5-bb6d-0ebab89f04b3)

### Different types of design styles :- 
- Full custom :- The design starts from the transistors and has huge space for PPA improvements but requires lot of efforts.
- Standard based cell design :- The existing standard cells(simple cells such as AND, NAND, flipflop etc. that are optimally designed and modeled in a library, fixed height) will be used to design.
- FPGA based design :- The hardware is fixed with the i/o ports and the design logic will be programmed onto the board.
- Gate array based design :- Transistors predefined on wafer, interconnect design specific.

### Figures of Merit (FoMs) :- 
- Power: sum of static and dynamic power consumed by an IC.
- Performance: maximum frequency of clock at which an IC will work.
- Area: area of the die for an IC.
- Other FOMs:
- - Testability
- -  Reliability
- -  Schedule







Schematic Design
Design
Simulation
Analysis
Functional Simulation
Synthesis
