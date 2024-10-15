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

Developed by: RAHUL VIJAY V
RegisterNumber: 212223040164

```
F1
module exp02(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d) | (a & b & ~c) | (~a & b & d));
endmodule

F2
module project22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2= ((~y&z)|(w&y)|(x&y));
endmodule
```

**TRUTH TABLE**
![image](https://github.com/user-attachments/assets/22370d1b-17b9-4c79-b5ad-9c9c1422cef6)

![image](https://github.com/user-attachments/assets/01a37c85-5a5d-43cb-a5dd-f9bbe50557e7)



**RTL realization**

**F1**
![rtl1](https://github.com/user-attachments/assets/57bf5229-518c-4d3b-86a1-898448e24614)



**F2**
![rtl2](https://github.com/user-attachments/assets/678edeef-bc05-4b5f-801c-45da58114179)



**Output:**

**F1**
![td1](https://github.com/user-attachments/assets/e21f4e3e-25a2-4b86-8b9a-534f757c814c)



**F2**
![td](https://github.com/user-attachments/assets/6c6f9ab7-8aa8-4eeb-b276-89bfa4151994)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

