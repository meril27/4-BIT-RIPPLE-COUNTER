# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**PROGRAM**

Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: MERIL GOLDLINA A  RegisterNumber: 24007299

![image](https://github.com/user-attachments/assets/1168fa92-ecd1-4bec-a254-be76db3861f3)

**RTL LOGIC FOR 4 Bit Ripple Counter**

![image](https://github.com/user-attachments/assets/17947050-93fe-485c-8444-ee6d566f8f3c)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![398784626-86022d16-fca8-448e-9cf6-e5102ab45087](https://github.com/user-attachments/assets/4efc0a47-c692-4abb-94a4-a47011776970)

**RESULTS**

Thus the 4 Bit Ripple Counter using verilog and validating their functionality using the fuctionality table is implemented successfully.
