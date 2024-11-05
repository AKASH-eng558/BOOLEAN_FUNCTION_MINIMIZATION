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
![WhatsApp Image 2024-10-29 at 14 17 16_f195bd17](https://github.com/user-attachments/assets/e5889f5f-d657-4266-86c8-e963b3e60abb)

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
![Screenshot 2024-11-05 142001](https://github.com/user-attachments/assets/9389f191-5a27-47d5-8f57-d8d9776a85cc)

**Timing Diagram**
![Screenshot 2024-11-05 142446](https://github.com/user-attachments/assets/01710550-7a4e-4678-89f0-9fa42532c769)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

