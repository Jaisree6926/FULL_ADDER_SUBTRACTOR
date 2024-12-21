
 NAME:JAISREE B
 
 REGISTRATION NO:24002225
 
 **EXPERIMENT 2 - FULL_ADDER_SUBTRACTOR**


**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**FULL ADDER AND FULL SUBTRACTOR**

**FULL ADDER**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**FIGURE-1 FULL ADDER**

**FULL SUBTRACTOR**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**TRUTHTABLE**

![Screenshot (60)](https://github.com/user-attachments/assets/2ca8c80a-d9df-43cc-8b11-dd3eb94c93fa)

![Screenshot (61)](https://github.com/user-attachments/assets/7889171b-c0da-4abb-92b2-0caef5a9103d)


**PROCEDURE**

**FULL ADDER:**
1. Open Quartus II and create a new project.
2. Use schematic design entry to draw the full adder circuit. 
3. The circuit consists of XOR, AND, and OR gates. 
4. Compile the design, and verify its functionality through simulation. 
5. Implement the design on the target device and program it.

**FULL SUBTRACTOR:** 
1. Follow the same steps as for the full adder. 
2. Draw the full subtractor circuit using schematic design. 
3. The circuit includes XOR, AND, OR gates to perform subtraction. 
4. Compile, simulate, implement, and program the design similarly to the full adder.


**PROGRAM:**

![Screenshot (63)](https://github.com/user-attachments/assets/df6dca31-348c-4d71-980d-9881663aba45)

![Screenshot (65)](https://github.com/user-attachments/assets/c2b95696-4330-4e23-9424-5aa9362bc3db)


**RTL SCHEMATIC**

![Screenshot (62)](https://github.com/user-attachments/assets/c07cf050-2457-4043-b9ed-68124ce4b85d)

![Screenshot (64)](https://github.com/user-attachments/assets/2d283497-ec5e-4ab0-abf6-758b17f310ac)



**OUTPUT TIMING WAVEFORM**

![Screenshot (67)](https://github.com/user-attachments/assets/7d405ddc-dffd-42f9-ba89-d79f7c50e879)

![Screenshot (68)](https://github.com/user-attachments/assets/115e9a2c-9812-4f36-ae8e-ce232ba46f1d)


**RESULT:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



