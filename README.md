# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB


![de6](https://github.com/user-attachments/assets/30b7dd18-a02a-4262-855c-13161947af20)


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B


![de7](https://github.com/user-attachments/assets/a1f74479-46ac-4054-bd9b-d1476be4e763)

 

Figure -02 HALF Subtractor

**Truthtable**
a b sum (a ^ b) carry (a & b) 0 0 0 0 0 1 1 0 1 0 1 0 1 1 0 1 
![de8](https://github.com/user-attachments/assets/08ba03b7-266a-4260-add1-5918551c0d51)

a b difference (a ⊕ b) borrow (~a & b) 0 0 0 0 0 1 1 1 1 0 1 0 1 1 0 0
![de9](https://github.com/user-attachments/assets/ce5d78dc-68b4-42e8-ad85-d4ce8263cec0)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:SHAABIN R S RegisterNumber:*/24006663

**RTL Schematic**

![de10](https://github.com/user-attachments/assets/9441945f-d5a8-4bc2-964e-169cb40dd32a)

**Output/TIMING Waveform**

![de11](https://github.com/user-attachments/assets/b6c24af6-a1d0-4160-baee-02d045246ee3)

**Result:**
Thus the given half adder and half subtractor fuctions are implemented and their operators
 are verified using Verilog programming
