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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
   Developed by:JAHAN J
   RegisterNumber:24004359
*/
```
```
module ha(a,b,sum,carry);
input a,b;
output sum,carry;
assign sum= (a ^ b);
assign carry= ( a & b);
endmodule
```


**RTL realization**


![Screenshot 2024-12-04 000326](https://github.com/user-attachments/assets/a725dc67-548c-4e1c-8d35-2f88965b12e7)



**Output:**


![Screenshot 2024-12-04 000344](https://github.com/user-attachments/assets/9d63d15a-d922-4461-b056-fca8b4fe9e7e)


**RTL & Timing Diagram**

![Screenshot 2024-12-04 000412](https://github.com/user-attachments/assets/96f3fd33-86b6-461a-b51d-2b7151988b33)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

