# EXPERIMENT NO. 5 – ZENER DIODE AS VOLTAGE REGULATOR

| **Name:** | GUGAN U| **Reg. No.:** | 26017494 |
|---|---|---|---|
| **Date:** | 23-11-2026 | **Batch / Section:** |  19EE305 |

---

## AIM

To study the Zener diode as a voltage regulator and to obtain its line regulation and load regulation characteristics.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Zener diode | 1N4735A | 1 |
| 2 | Resistors | 1 kΩ, 10 kΩ | 1 each |
| 3 | Regulated power supply | (0–30) V DC | 1 |
| 4 | Breadboard | — | 1 |
| 5 | Digital ammeter | (0–200) mA | 1 |
| 6 | Digital voltmeter | (0–20) V DC | 1 |
| 7 | Decade resistance box (load RL) | — | 1 |
| 8 | Connecting wires | — | As required |
| 9 | Simulation software | Proteus Design Suite | 1 |

## THEORY

A Zener diode is a heavily doped p-n junction diode, specially made to operate in the breakdown region. When reverse biased beyond a particular voltage, called the Zener breakdown voltage (Vz), it starts conducting heavily. Once it conducts, it maintains an almost constant voltage across its terminals whatever the current through it, i.e. it has a very low dynamic resistance. A series resistor Rs is connected to limit the current, since a high current can permanently damage the device.

In a Zener voltage regulator, the Zener diode is connected in reverse bias in parallel with the load, and the series resistor Rs is connected between the supply and the load. Any change in input voltage or load current changes the Zener current, while the output voltage across the load stays nearly constant at Vz.

**Line regulation:** the ability of the regulator to keep the output voltage constant when the input voltage varies, with the load kept constant.

**Load regulation:** the ability of the regulator to keep the output voltage constant when the load resistance (load current) varies, with the input voltage kept constant.

## PRECAUTIONS

1. While doing the experiment, do not exceed the ratings of the Zener diode; this may damage the diode.
2. Connect the voltmeter and ammeter in correct polarities as shown in the circuit diagram.
3. Do not switch ON the power supply unless the circuit connections have been checked as per the circuit diagram.

## PROCEDURE

### A. Line regulation

1. Connections are made as per the line regulation circuit diagram, with a fixed load resistance RL.
2. Vary the regulated power supply (input) voltage Vin in steps.
3. For each input voltage, note the output voltage Vo across the load and tabulate the readings.
4. Plot a graph of input voltage Vin (x-axis) versus output voltage Vo (y-axis).

### B. Load regulation

1. Connections are made as per the load regulation circuit diagram.
2. Set the input voltage Vin to a constant value above the Zener voltage.
3. Note the no-load output voltage VNL with the load disconnected.
4. Connect the load and vary the load resistance RL in steps; note the output voltage Vo for each value and tabulate the readings.
5. Plot a graph of load resistance RL (x-axis) versus output voltage Vo (y-axis).

## CIRCUIT DIAGRAM

### A. Line regulation
<img width="1496" height="744" alt="WhatsApp Image 2026-11-23 at 6 59 40 PM" src="https://github.com/user-attachments/assets/c3b06eff-9b0b-4828-9ba5-334a37df56b0" />


**Figure 1:** Zener voltage regulator – line regulation

### B. Load regulation
<img width="1600" height="785" alt="WhatsApp Image 2026-11-23 at 7 00 04 PM" src="https://github.com/user-attachments/assets/c0956607-108c-48b8-b61b-c4837ca5f7d6" />


**Figure 2:** Zener voltage regulator – load regulation

## SIMULATION USING PROTEUS

Build the Zener regulator circuit in Proteus using the 1N4735A, the series resistor and the load. Vary the input voltage (line regulation) and the load resistance (load regulation), and paste screenshots showing the meter readings.

### A. Line regulation – simulation

<img width="1340" height="547" alt="Screenshot 2026-11-15 132124" src="https://github.com/user-attachments/assets/97d61b25-d5ac-4caa-abd5-cde843c683c4" />


**Figure 3:** Proteus simulation – line regulation

### B. Load regulation – simulation

<img width="1316" height="531" alt="Screenshot 2026-11-15 132247" src="https://github.com/user-attachments/assets/1d3a7327-1924-44a2-86d0-dffc915d3ad2" />


**Figure 4:** Proteus simulation – load regulation

## TABULATION

### A. Line regulation (RL = ________ Ω, constant)

<img width="1600" height="700" alt="WhatsApp Image 2026-11-23 at 7 01 01 PM" src="https://github.com/user-attachments/assets/20611b13-4493-483e-8cba-3e623cb652fb" />

### B. Load regulation (Vin = ________ V, constant; VNL = ________ V)

<img width="1599" height="1196" alt="WhatsApp Image 2026-11-23 at 7 01 31 PM" src="https://github.com/user-attachments/assets/447b7ed3-f285-4c70-a053-08271b345b2a" />

## FORMULAE

- **% Line regulation = (ΔVo / ΔVin) × 100**
- **% Load regulation = (VNL − VFL) / VFL × 100**
- **Series resistance Rs = (Vin − Vz) / (Iz + IL)**

ΔVo – change in output voltage; ΔVin – change in input voltage; VNL – no-load output voltage; VFL – full-load output voltage; Vz – Zener voltage; Iz – Zener current; IL – load current.

## MODEL GRAPH

### A. Line regulation (Vin vs Vo)

<img width="1399" height="994" alt="WhatsApp Image 2026-11-23 at 7 02 08 PM" src="https://github.com/user-attachments/assets/2ad80260-9226-4d72-8162-5bb4a8f768c4" />


**Figure 5:** Line regulation characteristics

### B. Load regulation (RL vs Vo)
<img width="1382" height="1061" alt="WhatsApp Image 2026-11-23 at 7 02 25 PM" src="https://github.com/user-attachments/assets/09283d8e-f525-4778-a931-563613418edc" />


**Figure 6:** Load regulation characteristics

## RESULT

Thus, the Zener diode was used as a voltage regulator, and its line regulation and load regulation characteristics were obtained.
