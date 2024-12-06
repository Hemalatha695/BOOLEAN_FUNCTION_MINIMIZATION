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

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module ex_2(a,b,c,d,w,x,y,z,f1,f2)

intput a,b,c,d,w,x,y,z;

output f1,f2;

assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));

assign f2=((~y&z)|(x&y)|(w&y));

endmodule

Developed by:Hemalatha.A

RegisterNumber:24900150.


**RTL realization**
**Output:**

![logic diagram 2](https://github.com/user-attachments/assets/b0f8d754-4241-4356-ae21-f9dab27f78c2)


**RTL**
**Timing Diagram**
![RTL 2](https://github.com/user-attachments/assets/1830d2a3-f97e-465d-874e-0c29ad51785e)

**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

