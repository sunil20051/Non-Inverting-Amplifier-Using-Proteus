## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="905" height="668" alt="image" src="https://github.com/user-attachments/assets/5aee75e7-664a-48c5-b9c6-26b7caf3597b" />

Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="1916" height="1143" alt="image" src="https://github.com/user-attachments/assets/faf9e4ec-2099-49d9-ab15-390a19770238" />

## Tabulation
<img width="1165" height="286" alt="image" src="https://github.com/user-attachments/assets/a0362641-b6b8-4d3b-bc1f-3a5cdcff4d49" />

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?
2. What is the gain formula?
3.	What is the gain formula?
4.	Why is output in phase?
5.	What happens if Rf increases?
6.	What is the input impedance of non-inverting amplifier?

## Answers
1.A non-inverting amplifier is an op-amp configuration where the input signal is applied to the non-inverting (+) terminal, and the output is fed back to the inverting (−) terminal through a resistor. The output voltage is amplified and in phase with the input.<br>
2.Av=1+(Rf/R1)<br>
3.The input is applied to the non-inverting terminal (+). Since there is no phase reversal in this configuration, the output follows the same polarity as the input. Therefore, the output is in phase (0° phase shift) with the input.<br>
4.​If increases, the gain increases. Therefore, the output voltage increases for the same input voltage.<br>
5.The input impedance is very high (ideally infinite). Practically, it is in the megaohms range because the input is connected directly to the op-amp input terminal.<br>


