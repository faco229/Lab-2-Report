# Lab-2-Report
# Lab Report Title: Lab 2—For Good Measure: Basic Circuits

**Authors:** Faith Cox & Quinn Rison  
**Date:** 2/10/2025  

## Introduction
The main goal of this lab was to engage in a comprehensive analysis of electrical circuits. This task focused on measuring voltages across different circuit layouts, as well as currents through these same elements. Three foundational laws we followed were:

- Kirchoff’s Voltage Law (KVL)
- Kirchoff’s Current Law (KCL)
- Ohm’s Law

Additionally, Thevenin’s Theorem (also called Norton’s Law) was used to analyze our data.

This lab involved constructing and soldering circuits with series and parallel elements to validate these principles. The key conclusions are:

- Kirchoff’s Laws were mostly validated with minor deviations.
- Power conservation was maintained within reasonable differences.
- Thevenin and Norton equivalents matched our measured data.

## Methods/Tests
### Components Needed:
- Digital Multimeter (DMM)
- DC Power Supply
- Soldering station & solder
- Solder protoboard
- Resistors: 1kΩ, 2.2kΩ, 4.7kΩ, 5.1kΩ, 6.8kΩ, 15kΩ, 220kΩ

### Part 1: Series Circuit Assembly
1. Verify resistor values with the DMM.
2. Construct a series circuit with **1kΩ, 2.2kΩ, and 5.1kΩ resistors**.
3. Solder the resistors onto the board and attach two wires for connection to **Vin = 10V**.
4. Power the circuit using a **10V DC power supply**.
5. Measure voltage drop across each resistor with the DMM and record the values.
6. Measure circuit current by switching the DMM mode and breaking a circuit connection.

### Part 2: Parallel Circuit Assembly
1. Verify resistor values with the DMM.
2. Construct a parallel circuit using **4.7kΩ, 6.8kΩ, 15kΩ, 220kΩ, and 2.2kΩ resistors**, powered by **Vin = 12V**.
3. Measure and record **current** values for each resistor by placing the DMM in series.
4. Measure and record **voltage drops** across each resistor by placing the DMM in parallel.

### Part 3: Thevenin & Norton Equivalents
1. Remove the fifth resistor and measure **Thevenin voltage (Vth)** across R4.
2. Use the DMM to measure **Norton current (IN)** by short-circuiting the load.
3. Measure **Thevenin resistance (Rth)** by removing the power supply and using the DMM as an Ohm meter.

## Results
### Resistor Measurements
| Resistor | Measured Resistance |
|----------|--------------------|
| R1 | 0.984kΩ |
| R2 | 2.176kΩ |
| R3 | 4.99kΩ |
| **Equivalent Resistance** | 8.15kΩ |

### Part 1: Series Circuit Voltage Drops
| Resistor | Measured Voltage Drop |
|----------|--------------------|
| R1 | 1.21V |
| R2 | 2.66V |
| R3 | 6.1V |
| **Circuit Current** | 1.8mA |

### Part 2: Parallel Circuit
| Resistor | Expected (Ω) | Measured (Ω) |
|----------|------------|--------------|
| R1 | 4.7k | 4.66k |
| R2 | 6.8k | 6.76k |
| R3 | 15k | 15.1k |
| R4 | 220k | 220.12k |
| R5 (RL) | 2.2k | 2.17k |

#### Current Measurements
| Current Label | Measured Value |
|--------------|---------------|
| I1 | 1.83mA |
| I2/3 | -0.14mA |
| I4 | 0.02mA |
| I5/IL | -1.61mA |

### Part 2.2: Kirchhoff’s Voltage Law Validation
| Voltage | Measured (V) | Calculated (V) |
|---------|-------------|---------------|
| V1 | 8.46V | 8.601V |
| V2 | 1.099V | 0.952V |
| V3 | 2.5V | 2.1V |
| V4 | 3.55V | 4.4V |

**Power Calculations:**
- **Power Supplied:** 12V × 1.83mA = **21.96mW**
- **Power Dissipated:** 20.95mW (Minor discrepancy due to rounding errors)

### Part 3: Thevenin & Norton Equivalents
| Measurement | Measured | Calculated |
|------------|----------|------------|
| VTH | 9.72V | 9.65V |
| IN | 2.56mA | 2.56mA |
| RTH/RN | 3.77kΩ | 3.8kΩ |

## Discussion
The results validate Kirchhoff’s Laws, Thevenin’s Theorem, and power conservation principles. Minor deviations can be attributed to:
- Measurement errors
- Rounding differences
- Wire resistance

## Conclusion
This lab reinforced key circuit analysis concepts and provided hands-on experience with:
- Soldering
- Building series and parallel circuits
- Using a DMM for voltage, current, and resistance measurements

Understanding KCL, KVL, and Thevenin’s Theorem in practical applications deepened our knowledge of circuit theory and troubleshooting methods.
