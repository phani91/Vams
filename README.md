# Vams
Verilog AMS programs.

// Index to be updated as new files are added

Index:

(I). Basic - Folder Contains Basic Analog Circuits:
		-> Current Controlled Current Source
		-> Current Controlled Voltage Source
		-> Voltage Controlled Voltage Source
		-> Voltage Controlled Current Source
		-> Simple Resistor
		-> Resistor module for both low and high resistances
		-> Simple Capacitor
		-> Capacitor module with min conductance that checks for initial condition
		-> Simple Inductor
		-> Inductor with a series resistance
		-> Series RLC (t1)
		-> Series RLC (t2)
		-> Shunt RLC (t1)
		-> Shunt RLC (t2)
		-> Voltage Source, DC
		-> Voltage Source, DC+AC
		-> Voltage Source, DC+AC with a series resistance
		-> Current Source, DC+AC
		-> Current Source, DC+AC with a shunt conductance
		-> Voltage Follower
		-> Voltage Follower with level shift
		-> Current Mirror
		-> Voltage Amplifier
		-> Current Amplifier
		-> Ideal Op-Amp
		-> Ideal Diode
		-> Ideal Relay
		-> Non ideal relay with on resistance and off conductance
		-> Non ideal relay with on resistance and off conductance and discontinuity
		-> Digitally controlled non ideal relay, AMS model
		-> Resistive Port with series resistor and added thermal noise
		-> Simple Clock Generator Module
		-> Lossy Inductor
		-> Skin Effect module for lossy inductor
		-> Lossy Inductor with ac current stimulus

(II). Gates - Folder Contains Basic Analog Gates:
		-> Simple Inverter
		-> 2 bit analog OR gate
		-> 2 bit analog NOR gate
		-> 2 bit analog AND gate
		-> 2 bit analog NAND gate
		-> 2 bit analog XOR gate
		-> 2 bit analog XNOR gate
		-> 2 bit analog NOT gate
		-> 2n bit analog OR gate
		-> 2n bit analog NOR gate
		-> 2n bit analog AND gate
		-> 2n bit analog NAND gate
		-> 2n bit analog XOR gate
		-> 2n bit analog XNOR gate
		-> 2n bit analog NOT gate
		-> 2n bit level sensitive analog OR gate
		-> 2n bit level sensitive analog NOR gate
		-> 2n bit level sensitive analog AND gate
		-> 2n bit level sensitive analog NAND gate
		-> 2n bit level sensitive analog XOR gate
		-> 2n bit level sensitive analog XNOR gate
		-> 2n bit level sensitive analog NOT gate

(III). Ff - Folder contains Flipflop models:
		-> array of n D Flip Flops
		-> RF model array of n D Flip Flops
		-> array of n T Flip Flops
		-> RF model array of n T Flip Flops
		->
		->

(IV). DataConverter - Folder contains Data Converters
		-> n bit DAC
		-> n bit ADC
		-> n bit Quantizer
		-> n bit DAC, AMS model
		-> n bit ADC, AMS model
		
(V). Connect - Folder contains connect modules
		-> Electrical to Logic connect module just for 0,1 states
		-> Electrical to Logic connect module for 0,1,X,Z states
		-> Digital to Analog connect module for 0,1,X,Z states
		-> Bidirectional connect module for 0,1,X,Z states
		-> Enhanced Bidirectional connect module for 0,1,X,Z states
		->
		
(VI). Frequency - Folder contains frequency based models
		-> Phase Frequency Detector
		-> Noisy Phase Frequency Detector
		-> Frequency Divider
		-> Noisy Frequency Divider with Accumulating white jitter
		-> Noisy Frequency Divider with Accumulating and Synchronous white jitter
		-> Divide by N Noisy Frequency Divider with Accumulating and Synchronous white jitter
		-> 
		
(VII). Oscillator - Folder contains oscillator modules
		-> Voltage Controlled Oscillator
		-> Voltage Controlled Oscillator, AMS model
		-> Noisy Voltage Controlled Oscillator		
		-> Noisy Differential Quadruple Voltage Controlled Oscillator
		-> Noisy Differential Multiple Voltage Controlled Oscillator
		-> Noisy Sinusoidal Wave Voltage Controlled Oscillator
		-> Fixed Frequency Oscillator
		-> Noisy Fixed Frequency Oscillator with accumulating white jitter
		-> 
		
(VIII). Modulator - Folder contains modulator modules
		-> Amplitude Modulator
		-> Phase Modulator
		-> Frequency Modulator
		-> 16 Quadrature Amplitude Modulator
		->
		->
		
(IX). Semiconductor - Folder contains semiconductor modules
		-> Simple Junction Diode
		->
		->
		->
		->
		->
		->
		->
		->
		->
		
(X). Other - Folder contains other modules
		-> Period Meter
		-> Time Interval Meter
		-> Delay Meter
		-> Breakdown Generator
		-> Ideal Sample and Hold for internal periods
		-> Ideal Sample and Hold for external clock
		-> Ideal Track and Hold for internal periods with no hidden state
		-> Ideal Track and Hold for external clock with no hidden state
		-> Current Limited Voltage Regulator
		-> Random Bitstream Generator
		-> Comparator
		-> nxn Comparator
		->
		->
		

