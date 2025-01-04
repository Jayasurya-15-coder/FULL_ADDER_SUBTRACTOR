### NAME : B JAYASURYA
### REG NO : 24001758
# EXPERIMENT 3 : Implementation of Full Adder and Full subtractor circuit


# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

# Full Adder

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

# Figure -1 FULL ADDER

# Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# Truthtable

![Screenshot 2024-12-26 104614](https://github.com/user-attachments/assets/2ad79e13-d402-4b4e-b242-76e44db39931)


# Procedure

 Implementing BOOLEAN functions in Verilog HDL (Hardware Description Language) involves
 translating the simplified Boolean expressions into Verilog code to describe the behavior of digital
 circuits. The basic building blocks in Verilog is module. The module represent a combinational
 circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate
 primitives for basic functions. Use University program VWF to verify the functionality of your Verilog
 modules. Create waveform and check outputs against expected results.


# Program1:

![Screenshot 2024-12-26 104837](https://github.com/user-attachments/assets/06e0ece5-ab06-40c0-a983-9101228e2a80)


# RTL Schematic:

![Screenshot 2024-12-26 104941](https://github.com/user-attachments/assets/45f14009-453c-40b3-acce-4634b08c89f3)


# Output Timing Waveform

![image](https://github.com/user-attachments/assets/1f84cc24-90e0-43e7-8148-289a47ff251d)


# Result:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



