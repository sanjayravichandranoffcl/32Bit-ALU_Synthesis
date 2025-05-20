# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![Screenshot 2025-05-20 111802](https://github.com/user-attachments/assets/1e038154-14c8-40f7-818e-a4761929232c)


#### Area report:
![Screenshot 2025-05-20 112727](https://github.com/user-attachments/assets/cebeeb50-67fa-4ab7-b3da-b05d02812349)


#### Power Report:
![Screenshot 2025-05-20 112222](https://github.com/user-attachments/assets/4393bed4-18b3-4abc-80df-1c79bcc9ec51)


#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
