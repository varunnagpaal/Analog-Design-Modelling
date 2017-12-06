# Hands On Design, Modelling, Simulation(SPICE) and Prototyping of Discrete & Integrated Analog Circuits
This work involves hands-on design, modelling,  simulation and analysis (SPICE - MultiSim) of Discrete & Integrated Analog Circuits. Kind of activities involved in this work include:
- Understanding device structure and operating characteristsics.
- Learn Circuit design modelling and analysis theory.
- Design and analyze circuits using pen-paper.
- Model and analyze circuits using simulation software (SPICE).
- Whenever possible, build circuits using real parts sourced from various vendors. Make measurement using real instruments and compare them with simulation results.

This is an ongoing work.

### Following are the Analog Circuit topics which are dealt in this work. As work progresses, the list of topics expand accordingly.
 - [X] Measurment and Analysis
   -  [x] Oscilloscope
     - [x] transient response
     - [x] frequency sweep
     - [x] AM/FM Modulation
   - [X] Spectrum Analyzer
     - [x] Bode Plots (Magnitude/Phase Frequency response)
     - [x] FFT
   - [x] Network Analyzer
 - [ ] Passive Circuits
   - [ ] Linear
     - [x] Resistive: Resistance(R)
     - [x] Reactive(X): Inductance(L), Capacitance(C)
     - [x] Impedance(Z)
     - [X] Switches
     - [ ] Relays
     - [ ] Connectors
     - [ ] LEDS and Displays
     - [ ] Variable Devices: R, L, C, Transformers
     - [x] Inductors and Transformers
   - [ ] Non-linear
     - [x] Diodes
     - [ ] Memristor
   - [ ] Linear Circuit and Signal Analysis [1]
     - [x] Independent and dependent sources
     - [x] Nodal/Mesh Analysis, KCL/KVL
     - [x] Maximum Power Transfer
     - [x] Importance of Input and Output Impedance(Thevenin)
     - [x] DC/AC Concepts(Phasors, RMS, Frequency dependent Impedance)
     - [x] Gain/Attenuation
     - [x] dB scale(octave/decade), Cascade gains
     - [x] Magnitude/Phase Frequency response (Bode Plots)
     - [x] Fourier Series(periodic), Fourier Transforms(aperiodic) and Laplace Transforms
     - [x] Transfer function (s-domain/z-domain), Pole-Zero plots
     - [ ] Domain transformations(time-domain to s-domain to z-domain)
     - [ ] Group Delay
 - [x] Modeling circuits as multi-port networks
     - [x] 2-port networks
        - [x] T and Pi-networks
        - [x] Symmetrical and Reciprocal Networks
        - [ ] Network Analysis
            - [x] Basics
            - [x] Types of 2-port parameters
                - [x] [z] or open circuit impedance paramater
                - [x] [y] or short circuit admittance parameter
                - [x] finding [z], [y] for networks with and without dependent sources
                - [x] hybrid [h] and inverse hybrid [g] parameters
                - [x] chain or transmission [T] or ABCD parameters
            - [x] Interrelationshio between different 2-port parameters
            - [x] Interconnecting 2-port networks
            - [x] Parallel interconnection of 2-port networks
            - [x] Series connection of 2-port networks
            - [x] Cascade connection of 2-port networks
            - [x] Series-Parallel connection
            - [x] Objectives of 2-port network analysis
            - [x] Need for 2-port analysis
            - [ ] To be continued..
 - [ ] Active Device Circuits(Non-Linear or Linearized)
   - [ ] Bipolar Junction Transistors(BJT)
     - [ ] Switches
     - [ ] Amplifiers
   - [x] Field Effect Transistors (FET)
     - [x] JFET (Junction Field Effect Transistors)
     - [ ] MOSFET (Metal Oxide Semiconductor FET)
         - [x] Switches
         - [ ] Amplifiers
   - [ ] Operational Amplifiers Based Circuits(OpAmp)
    - [ ] Basic concepts
      - [x] Voltage/Current/Power gain of Amplifier for DC/AC signals
      - [x] 2-port models of Ideal Voltage(VCVS) and Current(CCCS) Amplifiers
      - [ ] Real OpAmp vs Ideal OpAmp(VCVS) model
        - [x] Terminals: Power supply, Double ended differential inputs, Sngle ended output
        - [x] Differential amplifier characteristsics (Open loop gain, I/O Impedance)
        - [x] Voltage constraints on I/O terminals
        - [x] Operation modes(linear, saturation)
        - [x] Negative feedback(virtual short)
        - [x] Closed loop gain parameters
        - [x] Circuit analysis of OpAmp based Negative feedback circuits
        - [x] Open loop vs Closed loop gain
        - [x] Impedance and Loading effects on gain
        - [ ] Noise gain, Gain-Bandwidth Product, Phase Margin
      - [x] OpAmp based Voltage Amplifier Active circuits in Negative feedback configuration
        - [x] Gain inversion based on biased input terminal
        - [x] Inverting Amplifier(virtual ground)
        - [x] Non-inverting Amplifier
        - [x] Voltage follower or Non-inverting Buffer(virtual ground)
        - [x] Difference(subtracting) Amplifier
        - [x] Inverting Summing(Adder) Amplifier
        - [x] Non-inverting Summer(Averager) Amplifier
        - [x] Differantiating Amplifier(Inverting type, stability)
        - [x] Integrator Amplifier(Inverting type)
        - [x] Negative resistor converter
        - [x] Comparators
      - [ ] OpAmp Applications
      - [x] Negative feedback concepts
        - [x] Open vs Closed loop gain
        - [x] Gain desensitivity and Error
        - [x] Linearizing effect
        - [x] Effects on noise and distrubances
 - [ ] Analog Filters
   - [ ] Basic Filter Concepts
     - [x] Types: Low Pass(Baseband), High Pass, Bandpass, Bandstop(Notch), All Pass
     - [x] Magnitude/Phase Frequency response (Bode Plots)
     - [x] Passband/Stopband/Transition-band Characteristics and Approximations
       - [x] Cut-off(-3 dB), Stopband edge and Center Frequency
       - [x] Closed loop Gain, Filter order, Bandwidth
       - [x] Monotonocity(Ripple, Flatness)
       - [x] Roll-off slope (attenuation rate in transition band)
       - [x] Reasonance, Q-factor(Sharpness), Frequency selectivity, Tunability
       - [x] Transient response, Impulse/step response
       - [x] Filter loading effects: Source side output and Load side input impedance
       - [ ] Phase and Group Delay
       - [ ] Causality and Stability analysis
       - [ ] Filter transformations
   - [x] Higher Order Filters
     - [x]  Butterworth, Chebyshev, Bessel, Elliptic
   - [ ] Filter circuits
     - [x] Passive RLC Filters
     - [ ] Active RC-OpAmp Filters
     - [ ] Switched Capacitor Filters
   - [ ] FIR and IIR Filters
   - [ ] Filter Applications
     - [ ] Anti-aliasing, Smoothing(reconstruction), Noise filtering
     - [ ] Radio(FM/AM), TV, Telephone(FDM), Communication, Audio(Equalization)
 - [ ] Timing and Synchronization Circuits
   - [ ] Oscillators and Timers
 - [ ] Interfacing Circuits
   - [ ] Digital to Analog Convertes (DAC)
   - [ ] Analog to Digital Convertes (ADC)
     - [ ] Parallel Flash
     - [ ] Successive Approximation (SAR)
     - [ ] Integrating
     - [ ] Delta-Sigma
 - [ ] Frequency Synthesis
   - [ ] Phase Locked Loops (PLL)
     - [ ] Frequency multiplication and frequency synthesis
     - [ ] Clock generation and clock recovery
     - [ ] Tone decoding and demodulation
 - [ ] Analog Integrated Circuits
   - [ ] To be updated

### Notes
I do write lot of notes in notebook or on whiteboards. Due to space constraints on github and fact that most of my notes are written on paper, it is not possible to share all of them. I plan to digitze my notes soon. Meanwhile some of my notes are shared in the following public google drive folder:
- [Analog Circuits Notes](https://drive.google.com/open?id=0B2-DQjqZAsLsVlZ4SUp6bzFhYVU)

### Following references serve as rough guide for this work
* *Signal Measurement*
   * [XYZs of Oscilloscopes](http://info.tek.com/in-xyzs-of-oscilloscopes-primer.html) by Tektronix
    * [Logic Analyzer Fundamentals](http://info.tek.com/www-logic-analyzer-fundamentals.html) by Tektronix
    * [Real Analog Video Lectures](https://learn.digilentinc.com/classroom/realanalog/) by Digilent
* *Linear Circuit Analysis*
    * [The Analysis and Design of Linear Circuits](http://amzn.in/gmD5WMM) by Roland E. Thomas, Albert J. Rosa, Gregory J. Toussaint-Wiley
* *Active Circuits*
    * [TI - Op Amps for Everyone](http://web.mit.edu/6.101/www/reference/op_amps_everyone.pdf) by Ron Mancini
* *Filters*
    * [A Basic Introduction to Filters — Active, Passive, and Switched-Capacitor](http://www.ti.com/lit/an/snoa224a/snoa224a.pdf) by Kerry Lacanette
* *Analog Integrated Circuits*
  * [Design With Operational Amplifiers And Analog Integrated Circuits](http://a.co/6rilSqs) by Sergio Franco
* *References*
    * [TI Analog Engineer's Pocket Reference](http://www.ti.com/lit/slyw038) by Art Kay and Tim Green
    * [Learning the Art of Electronics(LAOE)](http://learningtheartofelectronics.com/) by Thomas C. Hayes and Paul Horowitz
    * [Practicing Electronics For Inventors(PEFI)](https://accessengineeringlibrary.com/browse/practical-electronics-for-inventors-fourth-edition) by Paul Scherz, Dr. Simon Monk
    * [Electronic Circuits - Handbook for Design and Application](https://searchworks.stanford.edu/view/8441411) by Ulrich Tietze, Christoph Schenk, Eberhard Gamm

### Following is the bill of materials(BOM) of the list of parts used in various labs
- [LAOE-PE-PartsList.xlsx](https://github.com/varunnagpaal/Analog-Design-Modelling/blob/master/Parts/LAOE-PE-PartsList.xlsx)

The part numbers in the above BOM List above corresponds to Mouser specific part numbers. You may order parts from your country specific vendors(see Octopart BOM Tool)
