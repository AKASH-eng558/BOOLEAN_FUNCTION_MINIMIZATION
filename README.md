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
![WhatsApp Image 2024-10-29 at 14 17 16_a150e07b](https://github.com/user-attachments/assets/cbc36a44-ce60-4e5b-a3c0-a774246b781a)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp2(f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and (f_and,a,b);
or(f_or,a,b);
not(f_not,a);
nor(f_nor,a,b);
nand(f_nand,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Akash P RegisterNumber:*/24900264


**RTL realization**
![Screenshot 2024-11-05 142001](https://github.com/user-attachments/assets/aeb13559-1793-4044-b0df-86e6e544016a)

**Timing Diagram**
![Screenshot 2024-11-05 142446](https://github.com/user-attachments/assets/46145ca0-2875-4a29-bb8e-e6ae36c9eea1)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

