# AC to DC Bridge Rectifier Converter Design

## 1. Project Overview

This project involves the design and development of an AC to DC converter using a Full-Wave Bridge Rectifier topology. The circuit converts an alternating current (AC) input into a pulsating DC output using four semiconductor diodes connected in a bridge configuration.

The project focuses on understanding rectification principles, electronic component selection, circuit schematic development, PCB layout design, and preparation of manufacturing files using KiCad.

## 2. Project Objectives

- Design a full-wave bridge rectifier for AC to DC conversion.
- Understand the working principle of a four-diode bridge rectifier.
- Analyze input and output voltage waveforms.
- Implement a capacitor filter to reduce output voltage ripple.
- Select appropriate electronic components based on voltage and current ratings.
- Design and develop a PCB layout using KiCad.
- Generate manufacturing files for PCB fabrication.

## 3. Working Principle

The full-wave bridge rectifier consists of four diodes connected in a bridge configuration.

- **Positive Half-Cycle:** Two diagonally opposite diodes become forward-biased and conduct current through the load.
- **Negative Half-Cycle:** The other two diodes conduct, maintaining the same direction of current through the load.
- **Filtering:** A capacitor connected across the output smooths the pulsating DC voltage by reducing voltage fluctuations.

The circuit therefore converts both positive and negative half-cycles of the AC input into a unidirectional DC output.

## 4. Main Components

| Component | Description |
|---|---|
| D1–D4 | Rectifier diodes |
| C1 | Filter capacitor |
| R1 | Load resistor |
| J1 | AC input connector |
| J2 | DC output connector |

Component ratings are selected according to the required input voltage, output voltage, load current and ripple specifications.

## 5. Tools and Technologies

- **KiCad:** Circuit schematic capture and PCB design.
- **Circuit Simulation:** Analysis of rectifier operation and output waveforms.
- **PCB Design:** Component placement, track routing and layout development.
- **Gerber Generation:** PCB manufacturing file preparation.
- **BOM Generation:** Component documentation and procurement planning.

## 6. Design Workflow

1. Selection of full-wave bridge rectifier topology.
2. Component selection and electrical rating calculations.
3. Circuit schematic development.
4. Simulation and waveform analysis.
5. PCB footprint assignment.
6. Component placement and PCB routing.
7. Electrical Rules Check (ERC).
8. Design Rules Check (DRC).
9. 3D PCB visualization.
10. Generation of manufacturing files.

## 7. Manufacturing Files

The project includes the following manufacturing outputs:

- Gerber files for PCB fabrication.
- Excellon drill files.
- Bill of Materials (BOM).
- Pick-and-Place files, if required.
- 3D STEP model.


## 8. Expected Outcomes

- Successful conversion of AC into full-wave rectified DC.
- Understanding of diode conduction and rectification.
- Reduction of output voltage ripple using a capacitor filter.
- Practical understanding of electronic component selection.
- Development of a PCB layout ready for manufacturing.
- Generation of complete PCB fabrication documentation.

## 9. Future Improvements

- Addition of a voltage regulation stage.
- Implementation of overcurrent and overvoltage protection.
- Optimization of output voltage ripple.
- PCB size and routing optimization.
- Experimental validation of simulated results.

## 10. Author

**Vishal Chettri**

B.Tech in Electrical Engineering  
National Institute of Technology, Silchar

---

*This project demonstrates practical knowledge of power electronics, AC to DC conversion, electronic circuit design and PCB development.*