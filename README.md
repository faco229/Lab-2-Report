# Lab-2-Report
# Lab Report Title: Lab 2—For Good Measure: Basic Circuits

**Authors:** Faith Cox & Quinn Rison  
**Date:** 2/10/2025  

## Introduction
The main goal of this lab was to engage in a comprehensive analysis of electrical circuits. This task focused on measuring voltages across different circuit layouts, as well as currents through these same elements. Three foundational laws we followed were Kirchoff’s voltage law, Kirchoff’s current law, and Ohm’s law. In addition, we also used Thevenin’s law (also called Norton’s Law) to analyze our data. 
This lab consisted of measuring currents and voltages on a circuit we built and soldered ourselves. The circuits consisted of both series and parallel elements in order to verify Kirchoff’s Voltage Law (KVL), Kirchoff’s Current Law (KCL), Thevenin’s, and Norton’s Law. This process involved soldering to gain skills on practical skills and help the understanding of electrical principles through taking our own measurements and observations. Our outcomes conclude the following points:

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
Before soldering, the resistor values need to be verified. Next, the task is building a simple series circuit with the 1k, 2.2k, and 5.1k resistor and soldering them to the board, see Photo 1 for pre soldering, Photo 2 for the process, and Photo 3 for final product.

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Image5.Blank%20Circuit.jpg" width="500">
  <br>
  <b>Photo 1:</b> Blank Circuit Before Soldering
</p>

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Image4.%20Soldering%20Process.jpg" width="500">
  <br>
  <b>Photo 2:</b> Circuit Soldering Process
</p>

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Image3.%20Completed%20Circuit.jpg" width="500">
  <br>
  <b>Photo 3:</b> Completed Soldered Circuit
</p>

Once the resistors are in place, two more wires can be soldered to each end of R1 and R3 respectively to connect to Vin which is 10 volts.

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Fig1.%20Series%20Circuit%20Instructed%20to%20Build.jpg" width="500">
  <br>
  <b>Figure 1:</b> Series Circuit Instructed to Build
</p>


Now that our circuit is built on the solder protoboard, the DC power supply can be set to 10 volts and be connected to the circuit. With our circuit now powered, use the DMM to measure the voltage drop across each resistor. To do so, make sure that the DMM is set to read voltage. Next, using the two nodes, place the red (+) on the left and the black (-) on the right side of the resistor. The DMM should produce a positive reading. Although we are just looking for the magnitude, if the nodes were swapped in position the DMM would produce the same magnitude but a negative reading. Record the measurements for each voltage drop across each resistor on a table. 

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Fig2.%20Measuring%20voltage%20Drop%20on%20Series%20Circuit.jpg" width="500">
  <br>
  <b>Figure 2:</b> Measuring voltage Drop on Series Circuit
</p>

After the voltage drop across the resistors has been measured in the circuit, change the DMM wires to measure current and make sure the DMM is set to read current in DC and not AC. If not properly set up, the DMM will start beeping. If this occurs, immediately turn it off and figure out the issue. Once properly setup, measure and record the current in the circuit. To be able to measure current, one of the circuit elements must be unplugged as current is measured in series contrary to measuring voltage or resistance which is in parallel illustrated above. Due to this being a series circuit, the current remains constant and only one measurement will be necessary.

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Fig3.Measuring%20Current%20Through%20Series%20Circuit.jpg" width="500">
  <br>
  <b>Figure 3:</b> Measuring Current Through Series Circuit
</p>

Now the second part of the lab. This part of the lab involves building a parallel circuit with resistors of values 4.7k, 6.8k, 15k, 220k, 2.2k, and a voltage supply of 12 volts. Before building the circuit, just like in the first part, the resistor values should be tested with the DMM. Having just measured the current, make sure to switch the lead in the DMM back over to measure resistance and voltage. After doing so, verify the resistance of each resistor and also ensure that the voltage being supplied on the power supply is within 11.99-12.01 volts. Now the circuit can be constructed. It should demonstrate as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Fig4.Series_Parallel%20Circuit%20Instructed%20to%20Build.jpg" width="500">
  <br>
  <b>Figure 4:</b> Series & Parallel Circuit Instructed to Build
</p>

In this circuit the current will be measured. Therefore, switch the lead in the DMM back over to measure current and make sure that it is set to read DC and not AC. As mentioned earlier, current is being measured. Therefore, circuit elements must be broken to attach the DMM in series with the circuit. Repeat this process for each parallel element to measure the different currents. Record your findings in a table. 

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Fig5.Measuring%20Current%20Through%20Parallel%20Circuit.jpg" width="500">
  <br>
  <b>Figure 5:</b> Measuring Current Through Parallel Circuit
</p>

Now, with this same circuit we are going to measure the voltage drop across all the resistors. To do so, ensure that the lead connected to the DMM is set to read in voltage and begin by hooking the nodes up in parallel to each resistor as follows:

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Fig6.%20Measuring%20Voltage%20Drop%20Across%20Resistor%20in%20Parallel%20Circuit.jpg" width="500">
  <br>
  <b>Figure 6:</b> Measuring Voltage Drop Across Resistor in Parallel Circuit
</p>

Make sure to record the voltage drop across each resistor on a table. 
The last part of this method section is dropping the fifth resistor in this parallel circuit to test Thevenin's theorem. Now the circuit should look like this:

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Fig7.Removing%20R5_Measuring%20Thevenin%20Equivalent.jpg" width="500">
  <br>
  <b>Figure 7:</b> Removing R5 & Measuring Thevenin Equivalent
</p>


With the circuit constructed like this, now measure the voltage drop across R4. Record this as your Vth. Now, switch the lead over on the DMM to measure current and ensure it is set to read DC current. Now, use the nodes of the DMM to hook into the nodes of R4. What this does is create a short circuit and allows us to measure the Norton current. Record the result on a table. 
Lastly, we are going to use the DMM as an Ohm meter to record the equivalent resistance which is (Rth/Rn) for the circuit. To do so, remove the nodes from the DC power supply and exchange them with a wire from the end of R1 and the end of R4. Measure and record the result on a table. 

## Results
### Resistor Measurements
| Resistor | Measured Resistance |
|----------|---------------------|
| R1 | 0.984kΩ |
| R2 | 2.176kΩ |
| R3 | 4.99kΩ |
| **Equivalent Resistance** | 8.15kΩ |

### Part 1: Series Circuit Voltage Drops
After we set the DC Power Supply at 10VDC and connected it to the circuit, we used the DMM to measure the voltage drop across each resistor in the circuit shown in Figure 1. This was to confirm the rationality of Thevenin’s theorem. The following table displays our results:

| Resistor | Measured Voltage Drop |
|----------|-----------------------|
| R1 | 1.21V |
| R2 | 2.66V |
| R3 | 6.1V |
| **Circuit Current** | 1.8mA |

### Part 2: Parallel Circuit
Using the DMM to verify the resistances, we built the circuit shown in Figure 2 on a regular prototype breadboard. We were given values for voltage and resistances, and we compared them to our measured values in the chart below:

| Resistor | Expected (Ω) | Measured (Ω) |
|----------|--------------|--------------|
| R1 | 4.7k | 4.66k |
| R2 | 6.8k | 6.76k |
| R3 | 15k | 15.1k |
| R4 | 220k | 220.12k |
| R5 (RL) | 2.2k | 2.17k |

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Image1.12V%20Power%20Supply.jpg" width="500">
  <br>
  <b>Image 1:</b> 12V Power Supply
</p>

Next, we measured all of the current in the circuit from Figure 5
#### Current Measurements
| Current Label | Measured Value |
|--------------|---------------|
| I1 | 1.83mA |
| I2/3 | -0.14mA |
| I4 | 0.02mA |
| I5/IL | -1.61mA |
*Note: We swapped black and red measurement tools, resulting in a negative current.

## Discussion Question 1: Are the measured currents in agreement with Kirchhoff’s Current Law?

If we check the sum of currents for Kirchoff’s Current Law, we can verify our results.

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Calc1_Discussion%20Question%201.jpg" width="500">
  <br>
  <b>Image 2:</b> Calculations for Discussion Question 1
</p>

There is a small difference (0.06mA), which could be due to measurement errors. The values are very close, which suggests that KCL agrees with our findings within a reasonable margin of error.


### Part 2.2: Kirchhoff’s Voltage Law Validation
For this part, we measured the voltage across all of the resistors in the circuit and calculated the expected voltage drop for each resistor using Ohm’s Law and the currents.

| Voltage | Measured (V) | Calculated (V) |
|---------|--------------|----------------|
| V1 | 8.46V | 8.601V |
| V2 | 1.099V | 0.952V |
| V3 | 2.5V | 2.1V |
| V4 | 3.55V | 4.4V |

## Discussion Question 2: Compare the measured values and the calculated values. Are these in agreement with Kirchhoff’s Voltage Law?

If we sum up all of the Measured Voltages, we get 15.609V
If we sum up all of the Calculated Voltages, we get 16.053V

Since the supply voltage is 12V, there is some deviation which can be explained by either measurement inaccuracies or resistance in the wires, or both. KVL overall is valid since the measurements themselves are close.

## Discussion Question 3: Calculate the power delivered by the power supply and the power dissipated by every resistor. Is the power delivered by the power supply equal to the total power dissipated?

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Calc3_Discussion%20Question%203.jpg" width="500">
  <br>
  <b>Image 3:</b> Calculations for Discussion Question 3
</p>

There is a slight discrepancy in the two powers, but this can likely be explained by rounding differences. Overall, the power balance still holds true.

### Part 3: Thevenin & Norton Equivalents
After changing the circuit shown in Figure 3, we measured the voltage across R4 and used the DMM in DC current to act as a short circuit at the load terminals. This allowed us to measure Norton’s Current. We continued to use the DMM as an Ohm meter to measure the equivalent resistance for the entire passive circuit.

## Discussion Question 4: Using circuit analysis, calculate RTH, IN, and VTH, and compare them with the measured values. Are the calculated values in agreement with the measured values?

<p align="center">
  <img src="https://github.com/faco229/Lab-2-Report/blob/main/Calc4_Discussion%20Question%204.jpg" width="500">
  <br>
  <b>Image 4:</b> Calculations for Discussion Question 4
</p>

The calculated values are very reasonable and in agreement with the measured values shown in Table 3. Thevenin-Norton Equivalents.

| Measurement | Measured | Calculated |
|-------------|----------|------------|
| VTH | 9.72V | 9.65V |
| IN | 2.56mA | 2.56mA |
| RTH/RN | 3.77kΩ | 3.8kΩ |

## Discussion
It can be seen that our measured values line up very nicely to our calculated values. Overall, measuring current with this method is exactly what we expected it to be. It can be said when measuring the voltage and resistance there could be some slight derivation. 

The results validate Kirchhoff’s Laws, Thevenin’s Theorem, and power conservation principles. Minor deviations can be attributed to:
- Measurement errors
- Rounding differences
- Wire resistance

## Conclusion
The most important things derived/ learned from this lab were a few different things. One being soldering. Faith had some experience soldering in the past, but I didn’t have any experience so getting to learn some of the equipment and what it is used for I thought was important. This lab also did a good job reintroducing the process of building series and parallel circuits and being able to properly measure them with the DMM and not damage the equipment. These are important not only for this individual lab but for several more to come as the equipment will be common throughout this course. Another important lesson learned from this lab was the usefulness of KCL and KVL. It is important to see what we use in theory actually demonstrated in practice to gain a more insightful understanding of circuits. 

This lab reinforced key circuit analysis concepts and provided hands-on experience with:
- Soldering
- Building series and parallel circuits
- Using a DMM for voltage, current, and resistance measurements

Understanding KCL, KVL, and Thevenin’s Theorem in practical applications deepened our knowledge of circuit theory and troubleshooting methods.




### Acknowledgment
This document was formatted with assistance from ChatGPT.

```plaintext
ChatGPT. (2025). Assistance in formatting lab report to Markdown/LaTeX. OpenAI. Retrieved from https://openai.com
