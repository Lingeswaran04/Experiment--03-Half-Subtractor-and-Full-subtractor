# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by:lingeswaran k
RegisterNumber:22005148 
*/

## Output:

## Truthtable
half subtracter
![image](https://user-images.githubusercontent.com/119103865/213092766-f2275fb3-8c33-4de4-b41f-d00b48d5d4df.png)
full subtracter
![image](https://user-images.githubusercontent.com/119103865/213092821-54bf7309-a09c-43fa-9789-9b34e937eb86.png)


##  RTL realization
half subtracter
![image](https://user-images.githubusercontent.com/119103865/213092872-9d1e2cf7-7f61-4b33-9337-6f0eda7fa96b.png)
full subtracter
![image](https://user-images.githubusercontent.com/119103865/213092902-98353abc-51d3-433f-bcfa-eb98ab3e8f67.png)

## Timing diagram 
half subtracter
![image](https://user-images.githubusercontent.com/119103865/213092966-513dd04c-ba6d-4894-acfd-67e77fd97b0f.png)
full subtracter
![image](https://user-images.githubusercontent.com/119103865/213093012-6b0b3b71-77f7-4ab4-b166-0115b1b578d9.png)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
