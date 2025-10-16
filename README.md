# JKFLIPFLOP-USING-IF-ELSE

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

**Procedure**

 1. Type the program in Quartus software.
 
 2. Compile and run the program.
 
 3. Generate the RTL schematic and save the logic diagram.
 
 4. Create nodes for inputs and outputs to generate the timing diagram.


/* write all the steps invloved */

**PROGRAM**

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f1803b20-4866-4bbc-9a42-5a447f9d0a07" />


/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by: R Tharun Rathish

RegisterNumber:25018411

Date:24/05/25
*/

**RTL LOGIC FOR FLIPFLOPS**

<img width="478" height="262" alt="image" src="https://github.com/user-attachments/assets/84b1b965-0a4e-495d-9205-e86010a1068f" />


**TIMING DIGRAMS FOR FLIP FLOPS**

<img width="433" height="70" alt="image" src="https://github.com/user-attachments/assets/f1167407-9a73-4368-82ac-6f2a73ed8f88" />


**RESULTS**

Implementation of JK flipflop using verilog and validating their functionality using their functional tables is executed and the output is verified successfully.
