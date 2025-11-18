
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

---

## BLOCK DIAGRAM

*<img width="875" height="344" alt="image" src="https://github.com/user-attachments/assets/ebe76a5e-818f-418d-91a9-110319917b20" />*

---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**

*<img width="964" height="231" alt="image" src="https://github.com/user-attachments/assets/3e075af1-b810-48a4-8207-7b8dd0ea01b1" />*

---

## TABULATION  
**Transmission through Digital Link**
<img width="1280" height="1221" alt="image" src="https://github.com/user-attachments/assets/6ecf8d88-3c0a-4a06-a429-fb053c89d931" />


---

## MODEL GRAPH

*<img width="808" height="407" alt="image" src="https://github.com/user-attachments/assets/2c95ee6a-7163-46a0-aea7-14d8d9864bb0" />*

---

## GRAPH
<img width="1280" height="990" alt="image" src="https://github.com/user-attachments/assets/aa38c649-1c6e-4e1b-bccd-879f4cc945c8" />


## RESULT

*The digital 660 nm fiber optic link accurately reproduced the input square wave at the receiver, confirming proper digital signal transmission and bandwidth response.*
