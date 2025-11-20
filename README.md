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
<img width="643" height="481" alt="image" src="https://github.com/user-attachments/assets/fead6f3b-77f4-42db-bd3a-a11625349b97" />

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module ex2 (a,b,c,d,w,x,y,z,f1,f2);  
input a,b,c,d,w,x,y,z;  
output f1,f2;  
assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d;  
assign f2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y;  
endmodule  
Developed by: RegisterNumber:25011333


**RTL**
<img width="775" height="893" alt="Screenshot 2025-11-20 094131" src="https://github.com/user-attachments/assets/0eed83cf-afb5-4948-9232-39a230073175" />

**Timing Diagram**
<img width="1919" height="583" alt="Screenshot 2025-11-20 095323" src="https://github.com/user-attachments/assets/71f05424-54e8-47f6-9123-d570dd742408" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

