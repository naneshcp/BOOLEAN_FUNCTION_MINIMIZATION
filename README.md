# BOOLEAN_FUNCTION_MINIMIZATION
Date:04/10/2024
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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Naneshvaran
RegisterNumber: 24900972
*/
module boolean(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```



**RTL realization**

**Output:**
![output02(de)](https://github.com/user-attachments/assets/ea1a5b5f-d17b-4b6d-88e8-f1cf0b7449ad)



**RTL**

**Timing Diagram**
![waveform02(de)](https://github.com/user-attachments/assets/2c73bd5c-9ba0-44b8-902b-9ada7dcd1e01)



**Result:**
Thus the result was successfully verified

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

