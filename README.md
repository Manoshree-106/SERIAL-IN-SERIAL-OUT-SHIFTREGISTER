# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER
**AIM:**
To implement  SISO Shift Register using verilog and validating their functionality using their functional tables
**SOFTWARE REQUIRED:**
Quartus prime
**THEORY**
**SISO shift Register**
A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.
The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.
**Procedure**
/* write all the steps invloved */
**PROGRAM**
/* Program for flipflops and verify its truth table in quartus using Verilog programming.
<img width="656" height="417" alt="Screenshot 2025-12-06 171207" src="https://github.com/user-attachments/assets/4a7d6ce4-d704-449e-aa54-c7a5b13fe79b" />

Developed by:Manoshree.N RegisterNumber:25017532
*/
**RTL LOGIC FOR SISO Shift Register**
<img width="1340" height="885" alt="Screenshot 2025-12-06 171645" src="https://github.com/user-attachments/assets/27fb52a2-f4d9-462b-b1c7-557c89e8ae63" />

**TIMING DIGRAMS FOR SISO Shift Register**
<img width="1907" height="935" alt="Screenshot 2025-12-06 171814" src="https://github.com/user-attachments/assets/d8f135bd-fc21-4347-b69e-674397f8b3dd" />

**RESULTS**
thus,implemented  SISO Shift Register using verilog and validating their functionality using their functional tables
