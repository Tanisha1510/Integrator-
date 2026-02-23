## Experiment No: 4
### INTEGRATOR USING OP-AMP (μA741)
## Aim
To design and simulate an Integrator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the integral of the input voltage.
## Apparatus Required
<img width="469" height="192" alt="image" src="https://github.com/user-attachments/assets/dbcd5435-dfc2-48c3-9777-abc453c15e84" />

## Circuit Diagram
<img width="1920" height="1200" alt="Screenshot 2026-01-27 140353" src="https://github.com/user-attachments/assets/7e8fd71e-7911-4917-9d14-7cde7c935b9d" />

## Connection Details:
•	Input signal → Resistor (R) → Inverting terminal (Pin 2)<br>
•	Feedback capacitor (Cf) → Between Output (Pin 6) and Pin 2<br>
•	Non-inverting terminal (Pin 3) → Ground<br>
•	Pin 7 → +15V<br>
•	Pin 4 → −15V<br>
## Theory
An Integrator circuit produces an output voltage proportional to the integral of the input voltage.<br>
## Working Principle:
•	When input is constant → output is ramp signal<br>
•	Output is inverted<br>
•	Output depends on time<br>
**For Sine Wave Input:**
•	Output lags input by 90°<br>
•	Output amplitude decreases with frequency<br>
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistor, capacitor, signal generator, and CRO.
3.	Connect circuit in integrator configuration.
4.	Apply ±15V power supply.
5.	Set input waveform (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
<img width="643" height="100" alt="image" src="https://github.com/user-attachments/assets/5ef0de4f-8e62-400f-9a79-74bf6083ad95" />

## Waveforms
<img width="1380" height="881" alt="Screenshot 2026-01-27 140322" src="https://github.com/user-attachments/assets/192d7ee1-7db3-4297-9f95-b5f7bdd6f340" />

## Result
The Integrator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.<br>
The output waveform is proportional to the integral of the input signal.<br>
The circuit behaves as an integrator.<br>
## Conclusion
•	Output lags input by 90° (for sine input).<br>
•	Output amplitude decreases with increase in frequency.<br>
•	Used in waveform generation and analog computation.<br>
## Viva Questions
**1.	What is an integrator circuit?**
An integrator circuit is an op-amp circuit that produces an output voltage proportional to the integral of the input voltage.<br>

**2.	Write the output equation of integrator.**

<img width="234" height="64" alt="image" src="https://github.com/user-attachments/assets/4d36324f-3c47-46ba-af67-ad742b9ede8e" />

**3.	Why does output lag input?**
Output lags input by 90° because integration causes a phase shift of −90° in the signal.<br>

**4.	What happens at very low frequency?**
At very low frequency, capacitor acts like open circuit, so Output becomes very large and saturation occurs.<br>

**5.	What is practical integrator?**
A practical integrator is an integrator with a resistor connected parallel to capacitor to prevent saturation and improve stability.
