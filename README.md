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
![WhatsApp Image 2024-10-29 at 14 17 13_27099bc4](https://github.com/user-attachments/assets/33073048-db6a-4200-9dae-f5c780649b9d)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module experiment2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Akash P RegisterNumber:24900264


**RTL realization**
![Screenshot 2024-12-06 205758](https://github.com/user-attachments/assets/5c4176dd-9e8a-4a9f-a23d-e26bcdbc8c18)

**Timing Diagram**
![387574673-4bfc069b-5f93-4d1a-b89d-8529cbe889b7](https://github.com/user-attachments/assets/60f9587c-9209-4d51-8d8d-d42119bdd210)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

