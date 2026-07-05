# 🚀 AI-Assisted 4KB SRAM Design using OpenRAM and SKY130

<h3 align="center">VLSI System Design (VSD) Internship Project</h3>

<p align="center">
  <b>Author:</b> Bhavani Guni
</p>

---

# 📖 Project Overview

This repository documents my learning journey during the **VLSI System Design (VSD) Internship** focused on **AI-Assisted 4KB SRAM Design using OpenRAM and SKY130**.

The project emphasizes understanding SRAM circuit building blocks through AI-assisted learning using open-source EDA tools. Rather than focusing only on the final SRAM macro, this repository documents the complete engineering workflow including theory, circuit design, simulation attempts, debugging, observations, and documentation.

---

# 🎯 Internship Objectives

- Study SRAM architecture
- Understand CMOS inverter operation
- Design and analyze a 6T SRAM bitcell
- Learn Read, Write and Hold operations
- Understand Read Stability and Write Margin
- Study Butterfly Curve analysis
- Learn Precharge Circuit operation
- Understand Sense Amplifier
- Study Write Driver circuit
- Learn Row & Column Decoder basics
- Understand SRAM timing sequence
- Explore OpenRAM Compiler workflow
- Document AI-assisted engineering workflow

---

# 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Ubuntu | Development Environment |
| Xschem | Circuit Design |
| Ngspice | Circuit Simulation |
| Magic VLSI | Layout Visualization |
| Yosys | Logic Synthesis |
| OpenRAM | SRAM Compiler |
| SKY130 PDK | Process Design Kit |
| GitHub | Version Control |
| ChatGPT | AI-Assisted Learning |

---

# 🤖 AI-Assisted Workflow

This internship follows an AI-assisted engineering workflow.

For every SRAM building block:

1. Study theoretical concepts
2. Generate AI prompts
3. Design circuit
4. Create schematic
5. Attempt simulation
6. Debug errors
7. Record observations
8. Document learning

---



# 📚 Learning Outcomes

Through this internship I aim to:

- Strengthen CMOS circuit fundamentals
- Understand SRAM architecture
- Gain hands-on experience with open-source VLSI tools
- Learn AI-assisted hardware design workflow
- Improve debugging skills
- Develop professional technical documentation

---
# AI Usage Reflection: Mistakes, Challenges, and Solutions

Throughout this internship, AI was used as a learning assistant for understanding SRAM concepts, installing EDA tools, debugging Linux errors, and documenting progress. While AI significantly accelerated learning, several situations required manual verification and problem-solving.

| Task | How AI Helped | Where AI Was Incorrect / Limited | How I Solved It |
|------|---------------|----------------------------------|-----------------|
| Ubuntu & VirtualBox Setup | Provided installation commands and explained each step. | Installation differed because my VM configuration and Ubuntu version were different from the expected environment. | Verified each step manually, shared terminal output/screenshots, and corrected the process accordingly. |
| OpenRAM Installation | Guided the installation process and explained dependencies. | Some packages were already installed, missing, or had different names in my Ubuntu version. | Used terminal error messages to identify missing dependencies and installed the correct packages. |
| SKY130 PDK Setup | Explained the purpose of the SKY130 PDK and directory structure. | AI assumed the PDK already existed in the expected location. | Verified directory paths using Linux commands and corrected the installation path manually. |
| Linux Commands | Explained commands such as `cd`, `ls`, `mkdir`, `git`, and `vim`. | Some commands failed because they were executed from the wrong directory. | Checked the current directory using `pwd`, navigated to the correct location, and reran the commands. |
| OpenRAM Execution | Suggested commands to run OpenRAM. | Execution failed because the environment variables and installation were not completely configured. | Verified environment setup, checked error logs, and completed the missing configuration before rerunning. |
| SRAM Concepts | Simplified difficult concepts such as the 6T SRAM cell, read/write operations, and peripheral circuits. | Some explanations were simplified and did not include implementation-level details. | Referred to OpenRAM documentation and additional technical resources to gain a deeper understanding. |
| GitHub Documentation | Generated README files, Markdown formatting, and project documentation. | AI occasionally assumed tasks had already been completed. | Updated the documentation to accurately reflect the actual work performed during each week. |
| Error Debugging | Suggested possible reasons for installation and execution errors. | AI could not identify the exact issue without seeing the terminal output. | Shared screenshots and terminal logs so the problem could be diagnosed based on actual error messages. |
| Learning Strategy | Broke complex topics into smaller learning modules. | AI could not determine my progress automatically. | Followed a milestone-based learning approach and completed each task before moving to the next one. |
| Tool Configuration | Explained configuration files and directory structure. | Configuration file locations differed slightly from the reference tutorial. | Compared the project structure with the official repository and adjusted the paths accordingly. |

---

# Key Lessons Learned

- AI accelerated learning but could not replace practical verification.
- Terminal outputs and error logs were more reliable than assumptions.
- Official documentation remained the primary source of truth.
- Sharing screenshots and exact error messages greatly improved AI assistance.
- Every generated command and explanation should be verified before use.
- AI is most effective when combined with critical thinking and hands-on experimentation.

---

# Overall Reflection

During this internship, AI served as an effective mentor for learning concepts, understanding SRAM architecture, troubleshooting Linux issues, and creating technical documentation. However, successful completion of the tasks required continuous validation using terminal outputs, official documentation, and practical experimentation. This experience reinforced that AI is a powerful engineering assistant, but accurate VLSI development still depends on careful verification and problem-solving by the engineer.



---
# 📌 References

- OpenRAM Documentation
- SKY130 Documentation
- Xschem Documentation
- Ngspice User Manual
- Magic VLSI Documentation

---

# 👩‍💻 Author

**Bhavani Guni**

Electronics and Communication Engineering Student

Aspiring VLSI Design & Verification Engineer

---

⭐ *This repository documents my AI-assisted learning journey throughout the VSD Internship on 4KB SRAM Design using OpenRAM and SKY130.*
