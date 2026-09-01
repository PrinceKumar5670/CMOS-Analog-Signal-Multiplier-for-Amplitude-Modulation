Analog Signal Multiplier / AM Modulator
📌 Project Overview

This project focuses on the design and simulation of an analog signal multiplier for Amplitude Modulation (AM). The circuit combines two input signals and produces an output whose amplitude varies according to the input information signal.

The complete design was implemented and simulated at the circuit level using Cadence, including transistor-level blocks, op-amp based signal processing, and transient/frequency-domain analysis.

🎯 Objectives
Design an analog signal multiplier for AM generation.
Implement the circuit using MOS transistor and op-amp based blocks.
Study the multiplication of carrier and information signals.
Verify the circuit through transient and AC simulations.
Observe the generated AM waveform at the output.
Analyze the frequency response of the designed op-amp block.
🏗️ Circuit Implementation

The project consists of different analog building blocks that work together to perform signal multiplication.

Main Blocks
Op-Amp Circuit
Used for analog signal processing.
Designed and simulated at transistor level.
Its frequency response was analyzed using AC simulation.
Signal Input Stage
Provides the information/modulating signal and carrier-related input.
Proper biasing is provided for transistor-level operation.
Analog Multiplier
Combines the input signals through analog circuit techniques.
The output amplitude changes according to the applied input signals.
Output Stage
Produces the final AM waveform.
Transient simulation is used to verify the modulation behavior.
🔬 Simulation & Results

The design was verified through Cadence simulation.

1. Frequency Response

The AC analysis was performed to study the frequency characteristics of the op-amp block. The simulation provides the gain and phase response over frequency.

2. Transient Response

Transient analysis was performed to observe the time-domain output waveform.

The resulting waveform shows a high-frequency carrier whose amplitude follows the lower-frequency information signal, demonstrating the expected AM behavior.

📊 Key Analyses
Analysis	Purpose
DC Analysis	Verify transistor biasing and operating points
AC Analysis	Study gain and phase response
Transient Analysis	Verify AM output waveform
Circuit-Level Simulation	Validate analog circuit operation
🛠️ Tools Used
Cadence Virtuoso
Analog Circuit Design
MOSFET-based Circuit Design
Operational Amplifier
AC Analysis
DC Analysis
Transient Analysis

💡 Working Principle

The basic idea of the project is to perform analog multiplication between the input signals:

$$ v_{out}(t) \propto v_m(t)\times v_c(t) $$

where:

\(v_m(t)\) = information/modulating signal
\(v_c(t)\) = carrier signal
\(v_{out}(t)\) = resulting modulated signal

For sinusoidal inputs, the multiplication produces an output containing the characteristic AM frequency components.

✅ Conclusion

The project demonstrates the design and simulation of an analog multiplier for AM signal generation using transistor-level analog circuitry. The Cadence simulations were used to verify circuit operation, frequency response, biasing, and the final time-domain output waveform.

This project provides practical exposure to analog IC design, MOSFET circuits, op-amp design, circuit simulation, and amplitude modulation.
