### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

Define the 8-to-3 encoder truth table, ensuring only one input is high at a time.

Create a Verilog module using dataflow modeling with assign and ternary (? :) operators.

Assign the output bits (dout) based on which input (din[7:0]) is high.

Write a testbench to apply one-hot input combinations and monitor outputs.

Simulate and verify the output matches the expected binary values from the truth table.
**PROGRAM**

![program](https://github.com/user-attachments/assets/a92fec13-a23d-414d-999a-8e05f5bf6f41)


**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![simulation](https://github.com/user-attachments/assets/8f7fc3d6-87b7-4592-8955-3a6b53ae3e4c)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![waveform](https://github.com/user-attachments/assets/160c1ca2-06b9-44b1-a9a1-28ee8c880f4c)

**RESULTS**
The 8-to-3 encoder was successfully implemented using dataflow modeling in Verilog and verified through simulation with its functional truth table.



