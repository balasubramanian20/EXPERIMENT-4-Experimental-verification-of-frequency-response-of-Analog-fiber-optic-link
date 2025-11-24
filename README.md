
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.
- <img width="461" height="187" alt="image" src="https://github.com/user-attachments/assets/a7e2198d-b620-4de2-921f-52706c11e17a" />
<img width="438" height="187" alt="image" src="https://github.com/user-attachments/assets/050900b6-ccc6-4809-be8e-f20bf577d599" />

<img width="476" height="193" alt="image" src="https://github.com/user-attachments/assets/ffacd889-d32b-433c-b151-b2b3cc27767b" />


- 

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="1189" height="704" alt="512738953-08881b61-42f8-4e62-95b9-13ff3e4be597" src="https://github.com/user-attachments/assets/b20d5794-291d-45dc-aefc-9ee5898b84a2" />


---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

*(Insert connection diagram here)*

---

## TABULATION  
**Transmission through Analog Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|            800 |	120 mV |	0.024 |	-32.395
1.5k |	216 mV	|0.0432	|-27.290
3k|	412 mV|	0.134	|-21.681
5k	|670 mV|	0.1848	|-17.457
7k	|924 mV|	0.19|	-14.665
9k|	950 mV	|0.19	|-14.424
11k|	950 mV|	0.19|	-14.424
13k|	950 mV|	0.19|	-14.424
15k|	950 mV|	0.19|	-14.424
50k|	840 mV|	0.168	|-15.493
200k	|385 mV|	0.077|	-22.270
600k|	280 mV	|0.056|	-25.036
800k|	95 mV|	0.19|	-34.424
1M	|58 mV|	0.011	|-39.172    |                              |              |            |

---

## MODEL GRAPH

<img width="1080" height="538" alt="512742160-25ece563-cf37-448d-8b86-19078ca43f90" src="https://github.com/user-attachments/assets/0be14b6e-0a81-4df5-bb4c-f312bc2802de" />


---
## graph
![WhatsApp Image 2025-11-16 at 6 27 19 PM](https://github.com/user-attachments/assets/e80d271e-2e8e-4528-8a58-23561f3e7143)


## RESULT

Thus, the frequency response of analog fiber optic link was studied and the determined bandwidth is 95 kHz.


