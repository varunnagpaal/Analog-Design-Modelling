# Hands On Analog Design, Modelling and Simulation(SPICE)
This project involves hands-on design, modelling and simulation(SPICE - MultiSim) of mainly Analog Circuits. Idea is to build variety of circuits using real parts sourced from various vendors and complement these hand-on labs with Multisim based SPICE Simulations. This is an ongoing work.


###Following references serve as rough guide for this project work
- [Learning the Art of Electronics(LAOE)](http://learningtheartofelectronics.com/)
- [Practicing Electronics For Inventors(PEFI)](https://accessengineeringlibrary.com/browse/practical-electronics-for-inventors-fourth-edition)
- Intuitive Analog Circuit Design by Marc T. Thompson
- [TI Analog Engineer's Pocket Reference by Art Kay and Tim Green](http://www.ti.com/lit/slyw038)
- TI Op Amps for Everyone
- [Tektronix XYZs of Oscilloscopes Primer](http://info.tek.com/in-xyzs-of-oscilloscopes-primer.html)
- [Tektronix Logic Analyzer Fundamentals Primer](http://info.tek.com/www-logic-analyzer-fundamentals.html)
- [Digilent Real Analog Video Lectures](https://learn.digilentinc.com/classroom/realanalog/)
- [Analog Devices - Electronics I and II](https://www.wiki.analog.com/university/courses/electronics/text/electronics-toc)
- [Analog Devices - Analog Electronics](https://www.wiki.analog.com/university/courses/tutorials/index)

###Following is the bill of materials(BOM) of the list of parts used in various labs
- [LAOE-PE-PartsList.xlsx](https://github.com/varunnagpaal/Analog-Design-Modelling/blob/master/Parts/LAOE-PE-PartsList.xlsx)

The part numbers in the above BOM List above corresponds to Mouser specific part numbers. You may order parts from other vendors if cheaper(see Octopar t BOM Tool)

###Following are the Analog Circuit topics which are dealt with in this project
 - Passive Circuits
   - Linear
     - Resistive: Resistance(R)
     - Reactive: Inductance(L), Capacitance(C)
     - Reactance(X), Impedance(Z)
     - Switches, Relays
     - Connectors
     - LEDS and Displays
     - Variable Devices: R, L, C, Transformers
     - Inductors and Transformers
   - Non-linear
     - Diodes
     - Memristor
 - Active Device Circuits(Non-Linear or Linearized)
   - Bipolar Junction Transistors(BJT)
     - Switches
     - Amplifiers
   - Field Effect Transistors (FET)
     - JFET (Junction Field Effect Transistors)
     - MOSFET (Metal Oxide Semiconductor FET)
     - Switches
     - Amplifiers
   - Operational Amplifiers Integrated Circuits(OpAmp)
 - Synchronization Circuits
   - Oscillators and Timers
 - Analog Filters
   - Active, Passive(LC, RC), Notch and Digital Filters
     - Low Pass or Baseband or High-Cut Filter: Anti-alisasing, Smoothing 
     - High Pass or Low-Cut Filter
     - Bandpass and Bandstop Filter
     - All pass Filter
     - Bessel, Butterworth, Chebyshev
     - Notch Filter
     - FIR and IIR Filter
 - Interfacing Circuits
   - Digital to Analog Convertes (DAC)
   - Analog to Digital Convertes (ADC)
     - Parallel Flash
     - Successive Approximation (SAR)
     - Integrating
     - Delta-Sigma
 - Frequency Synthesis
   - Phase Locked Loops (PLL)
     - Frequency multiplication and frequency synthesis
     - Clock generation and clock recovery
     - Tone decoding and demodulation