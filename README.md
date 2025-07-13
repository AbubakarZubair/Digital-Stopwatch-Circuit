# ⏱️ Digital Stopwatch Circuit

## 📌 Description
A simple hardware-based digital stopwatch circuit designed using a 555 timer IC, CD4033 counter ICs, and 7-segment displays to measure time intervals from 00 to 99 seconds. It’s built for precision timekeeping in lab experiments, sports, and other daily tasks.

## 🛠️ Components Used
- IC 4033 (x2)
- 555 Timer IC
- Common Cathode 7 Segment Display (x2)
- Resistors: 150Ω, 100KΩ, 33KΩ, 56KΩ
- Capacitor: 10µF
- 9V Battery & Connector
- Voltage Regulator 7805
- LEDs
- Push Buttons
- Breadboard
- Connecting Wires

## 📐 Circuit Working
The 555 timer is configured in astable mode to generate a 1-second pulse using:
F = 1.44 / ((R1 + 2R2) * C1)
Where R1 = 33KΩ, R2 = 56KΩ, and C1 = 10µF.

This pulse triggers the CD4033 counter ICs, incrementing the connected 7-segment displays by 1 every second, counting up to 99 seconds.

- **Start/Stop Button**: Toggles counting
- **Reset Button**: Resets count to zero
- **9V Power Supply**: Powers the circuit via a 7805 voltage regulator

## 🎛️ Applications
- Lab experiments
- Sports event timing
- Billing time intervals
- Daily task management (meditation, chores, workouts, etc.)

## 📚 Documentation
- `docs/Final-Project-Proposal.docx` – Complete project report and explanation.

## 📸 Screenshots / Circuit Image (if available)
![check Circuit Diagram and picture 2](Circuit_Diagram.png)

