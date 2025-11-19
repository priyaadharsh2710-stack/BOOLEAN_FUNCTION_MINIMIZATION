# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module ex2 (a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d;
assign f2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y;
endmodule
```
Developed by: Priyadharshini V

RegisterNumber: 25018161


**RTL realization**
<img width="1920" height="1080" alt="Screenshot 2025-11-19 200903 - Copy" src="https://github.com/user-attachments/assets/575c6b8d-8ab0-4164-9952-29d05742aa66" />

**Timing Diagram**
<img width="1920" height="1080" alt="Screenshot 2025-11-19 203341" src="https://github.com/user-attachments/assets/bd47ecfb-bf7a-4af0-97ba-41dcf2fa0c17" />
<img width="1920" height="1080" alt="Screenshot 2025-11-19 203752" src="https://github.com/user-attachments/assets/2c4be9c8-b0fc-4526-934b-f259ba73e1b1" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

