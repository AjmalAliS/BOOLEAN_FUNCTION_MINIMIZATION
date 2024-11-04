# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**
![WhatsApp Image 2024-10-14 at 2 06 00 PM](https://github.com/user-attachments/assets/b3ee66d1-0102-4364-ab9d-f4541feaccfd)

**Theory**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module expl1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/24009653


**RTL realization**
![WhatsApp Image 2024-11-04 at 1 50 01 PM](https://github.com/user-attachments/assets/04a4777a-5e80-426c-b236-eb4477ff55a3)
![WhatsApp Image 2024-11-04 at 1 50 34 PM](https://github.com/user-attachments/assets/ad854c1d-4d34-4a68-96c9-ad20509ab043)


**Timing Diagram**
![WhatsApp Image 2024-11-04 at 1 51 12 PM](https://github.com/user-attachments/assets/d6c0f325-dd3e-4d59-a70d-65bf39f15a02)
![WhatsApp Image 2024-11-04 at 1 51 25 PM](https://github.com/user-attachments/assets/9ebacb35-e60a-45ca-9edd-d9650844e8e8)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

