## Name: Ragavan E
## Reg no: 212223040160
# EXP4 IMPLEMENTATION OF JK FLIPFLOP
**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

# Procedure

1.Open Quartus II and create a new project wizard.

2.Create a Verilog HDL file and enter the JK Flip-Flop code.

3.Save the file.

4.Click Compile to check for errors and build the design.

5.Go to Tools > Netlist Viewers > RTL Viewer to view and save the RTL schematic.

6.Create a Vector Waveform File (.vwf) via File > New > University Program VWF.

7.Add input/output nodes using Node finder.

8.Apply different input combinations (J, K, Clock) in the waveform.

9.Run Simulation from Processing > Start Simulation.

10.View and save the timing diagram showing the JK flip-flop behavior.


**PROGRAM**


![flipflop](https://github.com/user-attachments/assets/46926786-a2a7-4852-8e09-cbbc0cfff529)


**RTL LOGIC FOR FLIPFLOPS**
![exp7 rtl](https://github.com/user-attachments/assets/749110ee-18e8-4b46-ba49-4589329d3bd6)


**TIMING DIGRAMS FOR FLIP FLOPS**
![WAVE FORM 2](https://github.com/user-attachments/assets/119b3214-9683-4d9a-bbbb-6d8d9f6fd0e7)


**RESULT**

JK flipflop using verilog and validating their functionality using their functional tables are verified.

