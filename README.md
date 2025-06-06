# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools
## Register Number : 212223060082
## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. CMOS Inverter:

![image](https://github.com/user-attachments/assets/e3e06487-52b2-4b56-9dcd-03c5c9394a4c)


#### 2. Schematic of CMOS Inverter:
![447229285-e8bebe41-dac1-48cf-96af-f107c692e142](https://github.com/user-attachments/assets/8730b808-073e-43f2-b00e-bd4df68e02de)

 

#### 3. Transient Response Setup:

![image](https://github.com/user-attachments/assets/ecdf8ecc-5dfe-404d-ba08-85b1982881cf)


![image](https://github.com/user-attachments/assets/2611bd19-13be-4413-a662-9de3b555981d)



## Output
#### 1.Transient Analysis Output

![447229400-1940763a-c4d9-40a7-ad4a-2beee3a5e58e](https://github.com/user-attachments/assets/3eabebab-259f-445c-a88e-e0c9e3f9ccdf)
  ![image](https://github.com/user-attachments/assets/b86fd87f-7a66-47f5-bc26-2b5f4cb5679d)


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











