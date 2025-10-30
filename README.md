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

Developed by: RegisterNumber:25003547;module funct1(a,b,c,d,f1); input a,b,c,d; output f1; assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); endmodule ii) module funct2(w,x,y,z,f2); input w,x,y,z; output f2; assign f2=((~y & z)|( w & y )|(x & y)); endmodule


**RTL realization**: F1:<img width="698" height="386" alt="Screenshot 2025-10-28 103750" src="https://github.com/user-attachments/assets/3aee41cc-8949-4c3b-9432-2ee34deb95a7" />
                     F2:<img width="712" height="375" alt="Screenshot 2025-10-28 103804" src="https://github.com/user-attachments/assets/bbc373b6-328c-4453-81ed-67e557f6f42c" />

**Output:**

**RTL**

**Timing Diagram**:F1:<img width="968" height="529" alt="Screenshot 2025-10-28 103704" src="https://github.com/user-attachments/assets/c2a4d6e8-6e5e-4919-bc7f-0feda513499
                   F2:<img width="973" height="392" alt="Screenshot 2025-10-28 103720" src="https://github.com/user-attachments/assets/1e7dc8d0-4cde-4a81-ba02-b1ebdead4910" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

