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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Half adder:

![image](https://github.com/premalatha-sureshbabu/HALF_ADDER_SUBTRACTOR/assets/120620842/58968bab-4f5e-4bcd-969b-c5ff620b57ce)

Half subtractor:

![image](https://github.com/premalatha-sureshbabu/HALF_ADDER_SUBTRACTOR/assets/120620842/69bdfb18-e21b-41eb-bb17-5fbbf98be008)

Developed by:S.Prema Latha RegisterNumber:212222230112

**RTL Schematic**
Half adder:

![image](https://github.com/premalatha-sureshbabu/HALF_ADDER_SUBTRACTOR/assets/120620842/5fb7a45a-9584-4145-bc1e-86378c8fec80)

Half subtractor:

![image](https://github.com/premalatha-sureshbabu/HALF_ADDER_SUBTRACTOR/assets/120620842/3baaf205-c7e1-4e83-90ea-f02f600a5958)

**Output/TIMING Waveform**
Half adder:

![image](https://github.com/premalatha-sureshbabu/HALF_ADDER_SUBTRACTOR/assets/120620842/e7b172a3-12ce-435f-ba76-eb5f2033eb77)

Half subtractor:

![image](https://github.com/premalatha-sureshbabu/HALF_ADDER_SUBTRACTOR/assets/120620842/7748e515-74ed-4e90-8f6d-576f8f2f778b)

**Result:**

Thus the half adder and half subtractor circuits are designed and the truth tables is verified using quartus software.
