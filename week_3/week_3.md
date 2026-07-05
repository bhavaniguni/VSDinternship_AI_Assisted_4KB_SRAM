# Week 3: AI-Assisted Design of SRAM Peripheral Circuits

## Objective
The objective of Week 3 was to understand and recreate the major peripheral circuits used in SRAM using AI-assisted learning. Instead of memorizing circuit diagrams, the focus was on understanding the function of each block, how they interact during memory operations, and how these circuits are implemented in the SKY130 technology.

---

## Topics Covered

### 1. SRAM Peripheral Circuits
Studied the architecture and purpose of:

- Row Decoder
- Column Decoder
- Precharge Circuit
- Sense Amplifier
- Write Driver
- Wordline Driver
- Bitlines (BL & BLB)
- Control Logic

---

### 2. Row Decoder

#### Purpose
Selects one wordline from many rows based on the input address.

#### Learning Outcomes

- Converts binary address into one active wordline.
- Ensures only one SRAM row is accessed.
- Importance of decoder delay in SRAM performance.

---

### 3. Column Decoder

#### Purpose

Selects the required column during read/write operations.

#### Learning Outcomes

- Multiplexing columns
- Address selection
- Data routing

---

### 4. Precharge Circuit

#### Purpose

Charges both bitlines (BL and BLB) to VDD before every read operation.

#### Learning Outcomes

- Equalizes BL and BLB
- Reduces read delay
- Improves sensing accuracy

---

### 5. Sense Amplifier

#### Purpose

Detects the tiny voltage difference generated on the bitlines during a read operation.

#### Learning Outcomes

- Differential sensing
- Fast read operation
- High sensitivity

---

### 6. Write Driver

#### Purpose

Forces data onto BL and BLB during write operation.

#### Learning Outcomes

- Drives complementary bitlines
- Overwrites previous SRAM cell value
- Requires stronger drive strength than SRAM cell

---

### 7. Wordline Driver

#### Purpose

Activates the selected wordline after decoding.

#### Learning Outcomes

- Drives long wordlines
- Reduces delay
- Improves timing

---

### 8. Complete SRAM Read Operation

Studied complete sequence:

1. Precharge BL and BLB
2. Decode address
3. Activate wordline
4. SRAM cell slightly changes bitline voltage
5. Sense amplifier detects voltage difference
6. Output data generated
7. Wordline disabled
8. Bitlines precharged again

---

### 9. Complete SRAM Write Operation

Studied sequence:

1. Decode address
2. Write driver forces BL/BLB
3. Wordline activated
4. Cell state changes
5. Wordline disabled
6. Write complete

---

### 10. AI-Assisted Learning

Used AI tools to:

- Explain circuit functionality
- Understand transistor-level operation
- Clarify SRAM timing
- Simplify difficult concepts
- Compare different SRAM blocks

---

## Skills Gained

- Understanding SRAM peripheral circuits
- Read path analysis
- Write path analysis
- Decoder operation
- Sense amplifier basics
- Precharge mechanism
- SRAM timing concepts
- AI-assisted circuit understanding

---

## Key Takeaways

- SRAM performance depends heavily on peripheral circuits.
- Sense amplifiers enable fast read operations.
- Proper precharging improves reliability.
- Decoders determine memory access speed.
- AI can significantly accelerate understanding of complex VLSI circuits.

---

## Tools Used

- ChatGPT
- Ubuntu Linux
- VirtualBox
- OpenRAM
- SKY130 PDK
- Git
- GitHub

---

## Repository Progress

- ✅ Week 1 – SRAM Fundamentals
- ✅ Week 2 – 6T SRAM Cell Design
- ✅ Week 3 – SRAM Peripheral Circuit Design
- ⏳ Week 4 – OpenRAM Integration and SRAM Generation

---

## Author

**Bhavani Guni**

