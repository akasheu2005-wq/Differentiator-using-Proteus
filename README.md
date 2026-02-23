## Experiment No: 3
DIFFERENTIATOR USING OP-AMP (μA741)
## Aim
To design and simulate a Differentiator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the rate of change of input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Capacitor C = 0.01 µF
•	Resistor Rf = 10 kΩ
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1297" height="757" alt="Screenshot 2026-02-23 093335" src="https://github.com/user-attachments/assets/c558cf79-ca23-4f62-9579-b3b5dcc83dbd" />

## Connection Details:
•	Input signal → Capacitor (C) → Inverting terminal (Pin 2)
•	Feedback resistor (Rf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Differentiator circuit produces an output voltage proportional to the rate of change of input voltage.
## Working Principle:
•	When input changes rapidly → output amplitude increases
•	When input is constant → output is zero
•	Output is inverted
## Procedure
1.	Open Proteus software.
2.	Select μA741, capacitor, resistor, signal generator, and CRO.
3.	Connect circuit in differentiator configuration.
4.	Apply ±15V power supply.
5.	Set input sine wave (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
<img width="794" height="281" alt="Screenshot 2026-02-23 093519" src="https://github.com/user-attachments/assets/9fc88a1b-4388-43ce-89f9-24d2cd771f1f" />

S.No 	         Input Signal	              Frequency	            Expected  Output	            Practical Observation
## Waveforms
<img width="1611" height="1023" alt="Screenshot 2026-02-23 093408" src="https://github.com/user-attachments/assets/21490b8c-31d5-41f0-a9f9-4ab4673c14be" />

•	Sine input → Cosine output (90° phase shift)
•	Square input → Positive & negative spikes
•	Triangular input → Square wave
## Result
The Differentiator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the rate of change of input voltage.
The circuit behaves as a differentiator.
## Conclusion
•	Output depends on frequency.
•	Output leads input by 90° (for sine input).
•	Higher frequency → Higher output amplitude.
•	Used in wave shaping and signal processing applications.
## Viva Questions
1.	What is a differentiator?
  A circuit that produces output proportional to the derivative of input voltage.
2.	Write the output equation of differentiator.
  Vout​=−Rf​CdtdVin
3.	Why is output leading input?
  Because derivative of sine is cosine, which leads by 90°.
4.	What happens at very high frequency?
  Output amplitude becomes very large and noise increases.
5.	What is practical differentiator?
   A modified differentiator with additional resistor and capacitor to reduce noise and improve stability.

