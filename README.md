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
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/


**RTL realization**

**Output:**

**RTL**
logic diagram:<img width="987" height="691" alt="EXP 2 BOOLEAN FUNCTION" src="https://github.com/user-attachments/assets/75494a42-3bed-4860-ad11-3a9668c40391" />

**Timing Diagram**
<img width="1293" height="798" alt="EXP 2 BOOLEAN FUNCTION" src="https://github.com/user-attachments/assets/3488baec-da90-41a5-9789-44a4df884c40" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

