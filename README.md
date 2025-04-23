# BOOLEAN_FUNCTION_MINIMIZATION

Developed by: Preetha.K

Register Number: 212224100044

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
```
 module EX2(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
 endmodule

module EX2(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule
```

**RTL realization**

**Output:**

**RTL**

![image](https://github.com/user-attachments/assets/e1a31b17-c92f-4dd8-bf10-092e7b88b6aa)

![image](https://github.com/user-attachments/assets/717c0198-a3aa-44b6-9fa9-c6f692ba849c)

**Timing Diagram**

![image](https://github.com/user-attachments/assets/f4fe302d-9fca-4cfd-a797-12cf63020989)

![image](https://github.com/user-attachments/assets/b8e8b30e-2628-43f3-af26-1476726d8b89)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

