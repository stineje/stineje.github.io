---
layout: page
title: VLSI Research at the University of Nebraska–Lincoln
tagline: Open-Source Tools for VLSI
description: VLSI, computer architecture, and open-source chip design research at the University of Nebraska–Lincoln.
---

<img src="nebraska-n.jpg" width="150" alt="Nebraska N logo">

We are a research group at the University of Nebraska–Lincoln working in very-large-scale integration (VLSI), computer architecture and arithmetic, memory systems, and electronic design automation (EDA). We develop open-source tools, libraries, and teaching materials that make it easier to design, verify, and implement integrated circuits.

Open process design kits such as [SkyWater SKY130](https://www.skywatertechnology.com) and [GlobalFoundries GF180](https://opensource.googleblog.com/2022/08/GlobalFoundries-joins-Googles-open-source-silicon-initiative.html) help make chip design more accessible to students, researchers, and independent designers. Our projects build on open silicon efforts involving SkyWater, GlobalFoundries, Google, and Efabless.

## Getting started

- [Project overview](pages/overview.html)
- [Layout tutorial using Magic](https://docs.google.com/document/d/1hSLKsz9xcEJgAMmYYer5cDwvPqas9_JGRUAgEORx1Yw/edit?usp=sharing)
- [Video presentation on SKY130 standard cells](https://youtu.be/Svus4uQ_CAA)
- [Additional resources](pages/resources.html)

## RISC-V design and verification

- [*RISC-V System-on-Chip Design*](https://pages.hmc.edu/harris/ddca/rvsocd.html) is an Elsevier textbook with an accompanying open-source processor project. The book is available from [Elsevier](https://shop.elsevier.com/books/risc-v-system-on-chip-design/harris/978-0-323-99498-9) and [Amazon](https://www.amazon.com/RISC-V-Microprocessor-System-Chip-Design/dp/0323994989).
- [CORE-V Wally](https://github.com/openhwfoundation/cvw) is a configurable RISC-V processor with support for multiple ISA extensions. Developed in collaboration with Harvey Mudd College and UNLV, it provides a working example of processor design and verification in SystemVerilog.

## Design and teaching tools

- [CharLib](https://github.com/stineje/CharLib) is a Python tool for characterizing standard-cell libraries.
- [Drop-In JTAG](https://github.com/stineje/Drop-In-JTAG) adds a modular JTAG interface for boundary scan and debugging to an existing HDL design.
- [Prefix Adder Generation](https://github.com/tdene/synth_opt_adders), developed by Teo Ene, lets users explore prefix adder structures and sparsity and generate HDL.
- [Stick Diagramming Tool](https://stixu.io/), developed by Nick Overacker after taking our VLSI course, lets users draw stick diagrams in a browser. The [source code](https://github.com/NickOveracker/StickDiagrammer) is available on GitHub.
- [AES in SystemVerilog](https://github.com/Open-Source-Hardware-Initiative/AES) contains open-source AES implementations by Ryan Swann.
- [DES in SystemVerilog](https://github.com/stineje/DES) contains S-DES and DES implementations used in digital logic design courses at Oklahoma State University.

## Standard-cell libraries

| Process | Libraries |
| --- | --- |
| MOSIS SCMOS | [MOSIS SCMOS](https://github.com/stineje/MOSIS_SCMOS) |
| FreePDK45 | [FreePDK45 library developed for SRC](https://github.com/stineje/FreePDK_SRC) |
| SkyWater SKY130 | [12-track](https://foss-eda-tools.googlesource.com/skywater-pdk/libs/sky130_osu_sc_t12), [15-track](https://foss-eda-tools.googlesource.com/skywater-pdk/libs/sky130_osu_sc_t15), and [18-track](https://foss-eda-tools.googlesource.com/skywater-pdk/libs/sky130_osu_sc_t18) |
| SkyWater SKY130, radiation hardened by design | [SKY130 RHBD standard-cell library](https://github.com/stineje/sky130RHBDLib) |
| GlobalFoundries GF180MCU | [12-track GF180MCU library](https://github.com/google/globalfoundries-pdk-libs-gf180mcu_osu_sc) |

## Contact

We welcome questions, feedback, and corrections. Please reach out through
[James Stine’s UNL faculty page](https://engineering.unl.edu/ece/person/james-stine/).

