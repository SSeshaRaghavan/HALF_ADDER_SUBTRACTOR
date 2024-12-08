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

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

![image](https://github.com/user-attachments/assets/28c210b0-1f44-48dc-ac52-cabfc286e95f)
![image](https://github.com/user-attachments/assets/e8db687d-f93b-4951-ac1f-f99c152f127d)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
![Quartus II 64-Bit - C__altera_13 0sp1_half_adder - half_adder 08-12-2024 12_39_22 PM](https://github.com/user-attachments/assets/c339dba4-6145-4a9d-b756-8044ec01d94d)
![Quartus II 64-Bit - C__altera_13 0sp1_half_substracter - half_substracter 08-12-2024 01_07_54 PM](https://github.com/user-attachments/assets/62820276-42fc-42ff-8c56-6831f4be316b)
/* Program to design a half adder and half substracter circuit and verify its truth table in quartus using Verilog programming.

Developed by:S Sesha Raghavan 
RegisterNumber:24900320

**RTL Schematic**
![WhatsApp Image 2024-12-02 at 14 28 44_7ababeb3](https://github.com/user-attachments/assets/6718ea3b-0e98-492b-9ac5-452746967b30)
![WhatsApp Image 2024-12-02 at 14 28 44_f6570acd](https://github.com/user-attachments/assets/f827c555-2249-400a-bfa5-63fcc03df86b)

**Output/TIMING Waveform**
![WhatsApp Image 2024-12-02 at 14 28 43_0d979251](https://github.com/user-attachments/assets/89475d65-02c7-48ac-8efc-e37607116ab4)
![WhatsApp Image 2024-12-02 at 14 28 44_a28a5a38](https://github.com/user-attachments/assets/515d5cdb-d3ea-4831-9d0a-7347b4f39576)
**Result:**
![Quartus II 64-Bit - C__altera_13 0sp1_half_adder - half_adder 08-12-2024 12_39_33 PM](https://github.com/user-attachments/assets/64201b6e-0661-49e9-b349-bbe75568e820)
![Quartus II 64-Bit - C__altera_13 0sp1_half_substracter - half_substracter 08-12-2024 01_07_45 PM](https://github.com/user-attachments/assets/924b2239-9574-4b8f-b53c-01d2ff87edb3)
