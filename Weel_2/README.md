# 🧩 Week 2 – AI-Assisted Circuit Design of SRAM Building Blocks

## 🎯 Objective

The objective of Week 2 was to understand the circuit-level implementation of the fundamental building blocks used in a 6T SRAM cell. During this week, I focused on learning CMOS inverter design, transistor-level operation, and circuit simulation using open-source EDA tools. Instead of directly reproducing a complete SRAM design, the goal was to understand each building block individually and verify its functionality.

---

# 📚 Topics Studied

- CMOS Inverter Design
- PMOS and NMOS Transistor Operation
- Voltage Transfer Characteristics (VTC)
- Switching Threshold
- Noise Margins
- CMOS Logic Fundamentals
- Xschem Schematic Capture
- Ngspice Circuit Simulation
- SKY130 Device Models
- Introduction to SRAM Bitcell Design

---

# 🛠️ Tools Used

| Tool | Purpose |
|------|----------|
| Xschem | Schematic Capture |
| Ngspice | Circuit Simulation |
| Magic VLSI | Layout Exploration |
| SKY130 PDK | Technology Library |
| Ubuntu Linux | Development Environment |

---

# 🔬 Work Performed

During Week 2, I completed the following tasks:

- Installed and configured the required open-source EDA tools.
- Studied CMOS inverter operation at the transistor level.
- Designed a CMOS inverter schematic using Xschem.
- Configured a pulse voltage source as the input signal.
- Added transient simulation commands using Ngspice.
- Explored the simulation workflow for verifying inverter functionality.
- Investigated common setup issues related to missing libraries, device symbols, and simulator configuration.
- Understood how CMOS inverter behavior forms the basis of SRAM storage circuits.

---

# 📖 Concepts Learned

## CMOS Inverter

A CMOS inverter consists of one PMOS transistor connected to VDD and one NMOS transistor connected to Ground. Both transistor gates share the same input, while their drains are connected to produce the output.

The inverter provides:

- Low static power consumption
- High noise immunity
- Rail-to-rail output voltage
- Fundamental building block of SRAM cells

---

## Why CMOS Inverter is Important for SRAM

The storage element of a 6T SRAM cell is formed by connecting two CMOS inverters back-to-back. Therefore, understanding inverter operation is essential before designing the complete SRAM bitcell.

---

# 📂 Files Included

```
Week_2/
│── README.md
│── Schematics/
│── Simulations/
│── Images/
```

---

# 📈 Learning Outcome

After completing Week 2, I gained a practical understanding of CMOS inverter design, transistor operation, simulation setup, and the role of CMOS logic in SRAM circuit implementation. This knowledge provides the foundation for designing and analyzing a complete 6T SRAM cell in the next stage of the internship.

---

# 📚 References

- OpenRAM Documentation
- SKY130 Open PDK Documentation
- Ngspice Documentation
- Xschem Documentation
- Magic VLSI Documentation
