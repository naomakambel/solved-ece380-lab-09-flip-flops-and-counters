Download Link: https://assignmentchef.com/product/solved-ece380-lab-09-flip-flops-and-counters
<br>
<strong>Flip-Flops and Counters </strong>

<ol>

 <li>Implement Design A-1 and A-2 (for the Cyclone® V device) of the pre-lab. Verify the correctness of the design by simulating it in Quartus using the waveform from Figure 1 of the prelab.</li>

 <li>Download Design A-1 and A-2 on the Cyclone® V device. Use inputs SW[0] for the input D and KEY[0] for the clock.  Use LEDR[0] for the output Q.  Test the design for correct functionality.</li>

 <li>Implement Design B-1 and B-2 (for the Cyclone® V device) of the pre-lab. Verify the correctness of the design by simulating it in Quartus II using the waveform from Figure 2 of the prelab.</li>

 <li>Download Design B-1 and B-2 on the Cyclone® V device. Use inputs SW[0] for J, SW[1] for K and KEY[0] for the clock.  Use LEDR[0] for the output Q.  Test the design for correct functionality.</li>

 <li>Implement Design C-1. Verify the correctness of the design by simulating it in Quartus.</li>

</ol>




<ol start="6">

 <li>Implement Design C-2. Download the <strong>Design C-2 </strong>to the DE1 board. Use the following inputs: Pushbuttons KEY0 for <strong>CLEAR</strong>; and toggle switch SW [0] for <strong>ENABLE</strong>.</li>

</ol>




Use seven digit display HEX0 [6..0] (HEX0 [0] is the MSB and HEX0[6] is the LSB) for the hex [0..6] outputs .




Use PIN_AF14 for the 50 MHz internal clock (see Lab 2 Part II for details).

<strong>Q1 : </strong>Complete the timing diagram for the following device (Q starts as 0):

<strong>Q2 : </strong>Draw the circuit of a JK flip flop using a D flip-flop. Write down its characteristic table. In what condition, the JK flip flop can be turned into a T flip-flop?

<strong>Q3 ): Synchronous 3-digit counters based on T flip-flops. </strong>

1) Write down the input logic functions for three T flip-flops for 3-digit synchronous up-counter. 2) Write down the input logic functions for three T flip-flops for 3-digit synchronous downcounter.

3) Draw the schematic of a synchronous 3-digit up/down counter, which can count either upward or downward, controlled by a control signal up/.

<strong>Q4 : </strong>Synchronous two-digit BCD counter, with the two four-bit up-counters with synchronous loading function as shown below. Draw the circuit that counts from 0 to 65.


