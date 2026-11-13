## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |TAMILSELVI S  | **Reg. No.:** | 26016264|
|---|---|---|---|
| **Date:** | 13-11-2026| **Batch / Section:** |26ODJ166 |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

<img width="1600" height="1165" alt="CIRCUIT DIAGRAM 1" src="https://github.com/user-attachments/assets/d64ee650-d640-4810-b97b-22bb3a6dcfcc" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1600" height="1101" alt="CIRCUIT DIAGRAM 2" src="https://github.com/user-attachments/assets/d0414f5c-e2bf-42b8-9d94-3391586a6227" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1920" height="1011" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/85c7d921-a063-4a75-859d-b83212a67def" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1548" height="825" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/8feb6101-8eab-4c7a-89c9-83f8453795b9" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Theoritical | 100 |  16.68 V | 27.8 V | 55.6 V | 100.05 V|
| Practical | 100 | 16.7 V | 27.8 V | 55.6 V | 100.1 |

### B. KCL – Current measurements

| S. No. | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) |$V_A$|
|:---:|:---:|:---:|:---:|:---:|
| Theoritical |-1.48 A | 1.85 A |0.56 A | 52.63 V |
| Practical | 1.58 A | 1.05 A |0.53 A | 52.6 V|

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1600" height="965" alt="CAL1" src="https://github.com/user-attachments/assets/72195af2-0fb8-49b4-bf3c-68043454416e" />
<img width="1600" height="711" alt="CAL 1 B" src="https://github.com/user-attachments/assets/6fabdc2e-4359-4a70-aaab-07addc6aed1e" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1600" height="1361" alt="CAL 2" src="https://github.com/user-attachments/assets/bd555f0f-1f91-4178-bcb3-417e2df9c904" />
<img width="1600" height="1275" alt="CAL 2 B" src="https://github.com/user-attachments/assets/6d31a5ca-e83f-45b8-8c7f-9f7e30fc1ce3" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
