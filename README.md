### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

```
module two (a,b,y1,y2,y3, y4,у5,уб,у7);
input a,b;
output y1,y2,y3, y4,у5,у6,у7;
and g1 (y1,a,b);
or g2 (y2,a, b);
not g3 (y3,a);
nand g4 (y4, a,b) ;
nor g5 (y5,a, b);
xor g6 (y6, a,b);
xnor g7 (y7,a, b) ;
endmodule
```
![WhatsApp Image 2025-03-21 at 09 12 04_e1c43496](https://github.com/user-attachments/assets/fd59e686-f76e-459f-89ca-a62f3c36f45a)

 Developed by: Yugabharathi M
 RegisterNumber: 212224230314
 
**Logic symbol & Truthtable**

AND gate

![WhatsApp Image 2025-03-22 at 21 17 19_66078078](https://github.com/user-attachments/assets/0530ae8d-626e-410a-8da1-80eebc1b7d9d)

OR gate

![WhatsApp Image 2025-03-22 at 21 17 19_f8a5c266](https://github.com/user-attachments/assets/59f3e22e-1384-4f06-a93b-2446be4adb75)

NOT gate

![WhatsApp Image 2025-03-22 at 21 17 18_fee78f41](https://github.com/user-attachments/assets/ab195da6-6aac-4c9d-9841-50dc2057464c)

NAND gate

![WhatsApp Image 2025-03-22 at 21 17 19_954a72be](https://github.com/user-attachments/assets/5569154b-6772-4138-95c8-e014a5809332)

NOR gate

![WhatsApp Image 2025-03-22 at 21 17 20_0e5e4374](https://github.com/user-attachments/assets/c0fce2e9-07f5-473e-891d-9fdfe38c7c4d)

Ex-OR gate

![WhatsApp Image 2025-03-22 at 21 17 18_a445c601](https://github.com/user-attachments/assets/fe249478-1586-4d8d-b31d-87e48ec1dbc2)

Ex-NOR gate

![WhatsApp Image 2025-03-22 at 21 17 20_f92f5b1a](https://github.com/user-attachments/assets/10f62567-c70c-4170-98c2-17f1c2a30ec8)

**RTL realization Output:** 


![WhatsApp Image 2025-03-21 at 09 12 06_bf88e06f](https://github.com/user-attachments/assets/88765b0f-456c-46e7-84de-2d0acb8049db)

**RTL**


![WhatsApp Image 2025-03-21 at 09 12 07_fec2a634](https://github.com/user-attachments/assets/94649f12-6348-4ff0-bf63-90a5bf439e16)

**Result:**
Thus the Basic digital Ics and the verification of truthtable for 
different logic gates where studied and successfully realized using Verilog
