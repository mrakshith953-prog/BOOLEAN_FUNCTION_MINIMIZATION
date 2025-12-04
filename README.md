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
module exp2(a, b, s, ca);
    input a;
    input b;
    output s;
    output ca;
	 assign#2 s=a^b;
	 assign#2 ca=a&b;
endmodule

```

Developed by: RAKSHITH M
RegisterNumber: 25017980
*/




**Output:**

**RTL**

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2dc4d9d8-fc7f-4a7f-a49d-3fb045f9f2e3" />


**Timing Diagram**

<img width="1921" height="1201" alt="image" src="https://github.com/user-attachments/assets/c8ba456a-8222-4fec-910e-45dcae2101f7" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

