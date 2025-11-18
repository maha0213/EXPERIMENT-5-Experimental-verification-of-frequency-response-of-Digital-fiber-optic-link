
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

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

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

## BLOCK DIAGRAM
<img width="669" height="390" alt="image" src="https://github.com/user-attachments/assets/557723fe-108b-4f13-bdf8-b23bfbd90575" />

## TABULATION  
![WhatsApp Image 2025-11-18 at 22 03 23_85611b01](https://github.com/user-attachments/assets/f8efea64-b039-4ef8-8a9c-7238d48b818f)

## MODEL GRAPH
<img width="591" height="294" alt="image" src="https://github.com/user-attachments/assets/e9b2ba76-bb74-49b7-a2a8-9221fb87a628" />

##Graph
![WhatsApp Image 2025-11-18 at 22 06 50_a0efdf72](https://github.com/user-attachments/assets/14b685d8-0934-4821-87c0-a4eec10f1734)

## RESULT
Thus the experimental verification of frequency response of digital fiber optic link was studied and verified successfully.
