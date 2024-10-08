---
title: Design and Implementation of a 32-bit RISC Pipeline CPU on a FPGA
summary: Project developed at the Research Institue of the College of Electrical and Electronics Engineering (IIFIEE) at the University Nacional de Ingeniería (UNI), Perú, before being engaged in a doctoral program at the University of Florida.
tags:
  - Mips
date: '2009-07-12T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Aurelio Morales, 2009
  focal_point: Smart

links:
  - icon: linkedin
    icon_pack: fab
    name: Follow
    url: https://www.linkedin.com/in/aurelio-morales-phd-1505ba1b/
url_code: ''
#url_pdf: ''
url_slides: ''
url_video: ''
url_pdf: 'https://aureliomoralesv.github.io/project/mips/Pipeline-RISC-CPU-on-FPGA.pdf'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
The purpose of the project was the design of a 32-bit RISC CPU architecture and the prototype-level implementation of this CPU using an FPGA programmable logic device for teaching and research purposes. Given the need to have a hardware platform for teaching and research at an affordable cost, and the software tools that allow us to design the organization of the CPU, the project proposed the development of a prototype of a 32-bit RISC CPU based on an FPGA. In this project, a 32-bit scalar RISC CPU was designed and implemented at the prototype level, based on the MIPS architecture, in such a way that a CPU with 5 pipeline stages with the Hazard Detection Unit (HDU) and the Forwarding Unit (FU) was implemented. The design was restricted to a subset of the integer instructions of the MIPS R2000 CPU, and floating-point instructions were not implemented. It is worth mentioning that the MIPS architecture is widely studied worldwide in universities at the undergraduate and graduate levels. The project emphasized the use of the VHDL hardware description language, and the design was implemented in the DE2 board from Terasic. Simulations were carried out with different instructions and different sequences of instructions in order to check the internal behavior of the CPU, prior to configuring the FPGA device on the selected development board.

