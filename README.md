#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS

**DATE: 09.08.2025**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM
<img width="624" height="269" alt="image" src="https://github.com/user-attachments/assets/635c9837-d5f5-4d6f-acc9-8a47a4368230" />

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:
![IMG-20251122-WA0003 1](https://github.com/user-attachments/assets/6265e118-a006-48b2-b1d4-f27f6db492e8)


MODEL GRAPH 

![IMG-20251122-WA0001 1](https://github.com/user-attachments/assets/af98be6d-2a3a-4d92-bed7-5ed8d2cdf732)




DESIGN:

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 2kΩ, Rf=20kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![IMG-20251122-WA0002 1](https://github.com/user-attachments/assets/d8a047c0-8f76-431b-9925-bb86f083b664)
		
 


---
## OUT PUT WAVEFORM AND DISCUSSION 
![IMG-20251122-WA0004 1](https://github.com/user-attachments/assets/e2f0ca87-523a-48e7-b48b-7240b38be165)


---
### **Non-Inverting Amplifier**
## **DATE: 19.08.2025**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1
RF = 20kohm
R1 = 2kohm


---

## CIRCUIT DIAGRAM
![IMG-20251122-WA0005 2](https://github.com/user-attachments/assets/c8e1a95d-3b0a-4199-bd6e-5da8cb583862)



---

## MODEL GRAPH
![IMG-20251122-WA0007 1](https://github.com/user-attachments/assets/67fb15eb-9ce0-4c56-a6b8-9f2b0dac0990)



---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION
![IMG-20251122-WA0008 1](https://github.com/user-attachments/assets/9cebfdf4-ed28-4c9b-b559-06b5b43fc456)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![IMG-20251122-WA0006 2](https://github.com/user-attachments/assets/1ff6948b-7356-422e-b697-1efa7ec6824d)


---
## DIFFERENTIAL AMPLIFIER
## **DATE: 23.08.2025**

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1


## CIRCUIT DIAGRAM
![IMG-20251122-WA0012 1](https://github.com/user-attachments/assets/cbb30e75-b76b-40b8-bdab-d67c02116aed)


## MODEL GRAPH
![IMG-20251122-WA0009 1](https://github.com/user-attachments/assets/6e7e8e74-9404-49c1-9bc3-35d93ff0cb96)


---

## DESIGN


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  Rf = 20kohm, R1 = 20kohm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)
![IMG-20251122-WA0010 1](https://github.com/user-attachments/assets/8e948276-de76-43e8-a95d-3344bb820d1a)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![IMG-20251122-WA0011 1](https://github.com/user-attachments/assets/71e16490-d314-4bd4-ba4d-780bf33dfd96)


---
## INSTRUMENTATION AMPLIFIER
## **DATE: 28.08.2025**

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]

## Design

Choose Rf = 30kohm, R1 = 30kohm, R' = 6.6kohm, R = 3kohm
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER
![IMG-20251122-WA0015 1](https://github.com/user-attachments/assets/4c8534fc-9549-4604-b7ea-df3ffabb7c1d)


## MODEL GRAPH
![IMG-20251122-WA0013 1](https://github.com/user-attachments/assets/e58f9a2e-ffcf-4afc-b30a-61cc2ae91d80)


PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)
![IMG-20251122-WA0014 1](https://github.com/user-attachments/assets/26cb7360-c353-4619-b615-864de47b51ef)



---
## OUT PUT WAVEFORM AND DISCUSSION 
![IMG-20251122-WA0016 1](https://github.com/user-attachments/assets/e5c67c86-cc33-4876-a5ba-803057ed6cb8)


---
## RESULT
Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
