# HALF_ADDER_SUBTRACTOR
name : imthiyas ahamed .m
reg no : 212224050012

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

![WhatsApp Image 2025-04-16 at 09 28 30_2cb057d2](https://github.com/user-attachments/assets/4a33b19c-3efd-4d9a-9fab-d10e686a587d)

![WhatsApp Image 2025-04-16 at 09 28 30_b80c876f](https://github.com/user-attachments/assets/968607e4-a97b-4ce4-b6cb-c0fc0b363cdd)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![Screenshot 2025-04-15 104428](https://github.com/user-attachments/assets/85b3f69c-fff3-49a9-baf7-c28046fc2030)

![Screenshot 2025-04-16 085635](https://github.com/user-attachments/assets/077b0333-cd21-49e7-9f35-f3ca291fb0c6)


**RTL Schematic**

![Screenshot 2025-04-15 104524](https://github.com/user-attachments/assets/a2b8beb8-72b7-4858-a7b4-7f8e5ed5e498)

![Screenshot 2025-04-16 085653](https://github.com/user-attachments/assets/c966e1f5-8bbe-48d0-832d-1fab8e454e98)

**Output/TIMING Waveform**

![Screenshot 2025-04-15 111145](https://github.com/user-attachments/assets/5d7cf35d-b062-4f87-b4b1-9a98b75d0b4b)

![Screenshot 2025-04-16 091642](https://github.com/user-attachments/assets/1bb7a10b-64df-4037-87c4-f76f1605ab61)

**Result:**
successfully output come FULL ADDER AND SUBTRACTOR
