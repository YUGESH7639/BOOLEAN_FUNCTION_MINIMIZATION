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
![Function1 circuit diagram](https://github.com/user-attachments/assets/3ba10d1e-0ab6-407c-93d9-c660b02f7b92)
![Function 2 logic diagram](https://github.com/user-attachments/assets/aeb81439-7780-4e11-9438-3e97d6aa1df8)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

module Function1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module Function2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule


Developed by:YUGESH M 
RegisterNumber:24900164*/


**RTL realization**

**Output:**
![RTL output ](https://github.com/user-attachments/assets/531b71cb-8f01-4032-b40a-3bed9f908163)
![RTl output](https://github.com/user-attachments/assets/da6aaff0-a6ab-4439-a339-e7664179a674)


**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

