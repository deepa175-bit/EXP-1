## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |Deepalakshmi S | **Reg. No.:** |26014071 |
|---|---|---|---|
| **Date:** |12-11-2026 | **Batch / Section:** | 260DJ084|

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

*[ Insert the KVL circuit diagram here ]*

**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

*[ Insert the KCL circuit diagram here ]*

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

* <img width="1211" height="727" alt="Screenshot 2026-11-12 155214" src="https://github.com/user-attachments/assets/54b9fc73-5cab-4804-98a6-725fbfa0d993" />*

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

* <img width="925" height="560" alt="Screenshot 2026-10-15 154045" src="https://github.com/user-attachments/assets/a1c67c4d-702a-4d44-8a3e-ddbc912f472e" />*

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 |100 |16.68V |27.8V |55.6V |100.05 |
| 2 |100 |16.7V |27.8V |55.6V |100.1 |


### B. KCL – Current measurements

| S. No. | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | V(A) |
|:---:|:---:|:---:|:---:|:---:|
| 1 |-1.48A |1.85A |0.56A |52.63V | 
| 2 |1.58A |1.05A |0.53A |52.6V | 


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

*[ Paste the KVL calculation screenshot here ]*

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

*[ Paste the KCL calculation screenshot here ]*

**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
