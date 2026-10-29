# RTL Design and Synthesis Workshop — Initial Setup

## 1. Overview

This repository documents my hands-on learning and practical work as part of the **RTL Design and Synthesis Workshop** using the SKY130 technology ecosystem.

This initial stage focuses on cloning the workshop repository, exploring its directory structure, identifying Verilog design files, and checking the available library files and tool setup in an Ubuntu virtual machine.

## 2. Development Environment

- **Operating System:** Ubuntu Linux
- **Environment:** Ubuntu running in a virtual machine
- **Version Control:** Git and GitHub
- **Hardware Description Language:** Verilog HDL
- **Synthesis Tool:** Yosys
- **Simulation Tool:** Icarus Verilog
- **Waveform Viewer:** GTKWave
- **Technology Ecosystem:** SKY130

## 3. Cloning the Repository

The workshop repository was cloned from GitHub using the following command:

```bash
git clone https://github.com/vsdip/vsd-rtl.git
```

After cloning, I navigated into the repository and accessed the RTL Design and Synthesis Workshop directory.

```bash
cd ~/VLSI/vsd-rtl/sky130RTLDesignAndSynthesisWorkshop
```

**Screenshot:** `images/01_git_clone.png`

## 4. Exploring the Repository Structure

I inspected the workshop directory to understand how the design files, libraries, and synthesis scripts are organized.

```bash
ls
```

The workshop directory contains the following important files and folders:

| File or Directory | Description |
|---|---|
| `lib/` | Library-related workshop resources |
| `my_lib/` | Additional library-related resources |
| `verilog_files/` | Verilog HDL design files |
| `yosys_run.sh` | Shell script provided for the synthesis workflow |
| `README.md` | Workshop instructions and documentation |

**Screenshot:** `images/02_repository_structure.png`

## 5. Inspecting the Design and Library Files

I explored the available Verilog files and library directories to understand the resources provided for the workshop.

Commands used:

```bash
ls -lah verilog_files
ls -lah lib
ls -lah my_lib
```

This step helped me become familiar with the workshop's source files and supporting library resources.

**Screenshots:**
- `images/03_verilog_files.png`
- `images/04_library_files.png`

## 6. Checking the Installed Tools

I checked the availability and versions of the tools used in the RTL design and synthesis workflow.

```bash
iverilog -V
yosys -V
gtkwave --version
```

These tools support Verilog simulation, logic synthesis, and waveform inspection, respectively.

**Screenshot:** `images/05_tool_setup.png`

## 7. Learning Outcomes

Through these initial setup activities, I learned how to:

- Clone a GitHub repository into a local Ubuntu environment.
- Navigate and inspect a project directory using Linux commands.
- Identify Verilog source files, library resources, and synthesis scripts.
- Check the availability of the tools required for RTL simulation and synthesis.
- Organize screenshots and document practical work using Markdown.

## 8. Conclusion

The initial repository setup and file exploration were completed as preparation for the subsequent RTL design and synthesis exercises.

This documentation will be updated with additional commands, implementation steps, simulation results, synthesis outputs, and screenshots as I progress through the workshop.

---

**Workshop:** RTL Design and Synthesis  
**Technology:** SKY130  
**Environment:** Ubuntu Linux Virtual Machine
