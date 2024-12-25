# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
![Screenshot 2024-12-25 183425](https://github.com/user-attachments/assets/eecf0cf7-97e2-4209-8487-bd63c494859c)
![Screenshot 2024-12-25 183955](https://github.com/user-attachments/assets/1fc4bfbf-fa86-4525-bd0c-51872c1908c0)


**Procedure**

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram.

DEVELOPED BY KISHOR K R REFERENCE NO 24003621

**Program:**

![Screenshot 2024-12-25 184028](https://github.com/user-attachments/assets/025c0330-6c67-4a89-850f-32c6f83edf89)


**RTL Schematic**
![Screenshot 2024-12-25 184038](https://github.com/user-attachments/assets/b5e25dae-cc40-42e6-977d-3a74bc51f296)
![Screenshot 2024-12-25 184046](https://github.com/user-attachments/assets/7e21d079-e3aa-40be-a280-7c72013395e3)

**Output Timing Waveform**
![Screenshot 2024-12-25 184059](https://github.com/user-attachments/assets/0e8c5542-ebda-471c-9d60-db4e6760004c)
![Screenshot 2024-12-25 184111](https://github.com/user-attachments/assets/add53eed-6889-4a12-862c-aafc6193f950)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



