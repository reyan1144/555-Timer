# 555-Timer
## MONOSTABLE MULTIVIBRATOR USING 555 TIMER IC
# 1.AIM
Generate a waveform with pulse width of 0.5 ms under different trigger conditions using 555 timer IC.
# 2.Theory  
A monostable multivibrator, also known as a one-shot pulse generator, is a circuit that generates a single output pulse in response to an external trigger input. When built using a 555 timer IC, the circuit operates in monostable mode, where the timer produces a high output pulse of predetermined width (also called time period) upon receiving a trigger signal. The duration of this output pulse is determined by an external resistor (R) and capacitor (C) connected to the timer. When the trigger input (applied to pin 2) goes momentarily low, it initiates a timing cycle, causing the output (pin 3) to go high. This high state persists for a time period 𝑇=1.1RC after which the output returns to its stable low state. The 555 timer’s internal flip-flop and discharge transistor control the charging and discharging of the capacitor, defining the duration of the pulse. The circuit is commonly used for pulse generation, timing applications, and creating precise time delays.  
# Features  
1.Single stable state: It has one stable (low) state and one quasi-stable (high) state that persists for a specific duration upon triggering.  
2.Trigger input sensitivity: The circuit is triggered by a negative pulse (a momentary low signal) applied to the trigger pin (pin 2).  
3.Automatic reset: After the set time duration, the output automatically returns to the stable low state without the need for an additional reset signal.  
4.Edge-triggered operation: The monostable mode responds to the falling edge (negative-going transition) of the trigger pulse.  
5.High output drive capability: The 555 timer can source or sink up to 200 mA of current, sufficient to drive LEDs, relays, or other loads. 

# Circuit Diagram  
![Image](https://github.com/user-attachments/assets/0750370d-0d58-4146-8e35-5b9c5a835ab7)  

# Calculation  
We need T=0.5ms  
WKT:T = 1.1 x R x C  
Lets assume C=1u  
We will get R as 454.54ohms  

# Transient Analysis  

  

V(n001) is voltage across capacitor  
V(n002) is the output voltage  






