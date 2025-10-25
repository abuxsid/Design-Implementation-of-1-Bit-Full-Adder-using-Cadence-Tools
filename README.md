# Ex No: 05 - Design & Implementation of 1-Bit Full Adder Using Cadence Virtuoso

## Aim
The aim is to design and implement a 1-bit Full Adder using Cadence Virtuoso and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the 1-bit Full Adder design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **Full Adder circuit** using **CMOS**.
- Connect the inputs (**A, B, Cin**) and outputs (**Sum, Cout**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the output logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

<img width="712" height="433" alt="image" src="https://github.com/user-attachments/assets/ac1969f6-b2b5-4394-9dba-d457dfa5ebe9" />


## Truth Table for 1-Bit Full Adder
![image](https://github.com/user-attachments/assets/328fae3c-b83a-4cd6-b394-54323dc59673)


## Schematic Diagram
### 1. Schematic of 1-Bit Full Adder:
<img width="1209" height="656" alt="image" src="https://github.com/user-attachments/assets/6de26df6-de22-4817-abaa-6541155a957c" />


![image](https://github.com/user-attachments/assets/1a962018-9d6b-4246-ab5f-424602551e87)



## Output
### Transient Analysis Output:
<img width="465" height="522" alt="image" src="https://github.com/user-attachments/assets/024be9ea-a97a-4020-b1bf-096c19556e3c" />
<img width="731" height="506" alt="image" src="https://github.com/user-attachments/assets/f49f7ace-cc71-486a-870e-acc6ac7ebfea" />
<img width="1620" height="862" alt="Screenshot 2025-10-25 141612" src="https://github.com/user-attachments/assets/ec6e3355-9d4a-46f7-a746-773a2dbf384f" />

## Results
1. Successfully designed the **1-bit Full Adder** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Full Adder**.
3. Observed **correct logic switching behavior** in response to input signals.
