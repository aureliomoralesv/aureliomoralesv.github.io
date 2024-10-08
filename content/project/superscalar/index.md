---
title: Design and Implementation of Superscalar CPU on a FPGA for Teaching and Research Purposes
summary: Project developed at the Research Institue of the College of Electrical and Electronics Engineering (IIFIEE) at the University Nacional de Ingeniería (UNI), Perú, before being engaged in a doctoral program at University of Florida. This project was presented at IEEE INTERCON 2011 held at UNI.
tags:
  - Superscalar
date: '2009-07-12T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Aurelio Morales, 2011
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
url_pdf: 'https://aureliomoralesv.github.io/project/superscalar/INTERCON11_morales_Superscalar_CPU_on_FPGA.pdf'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
The purpose of the project was the design of a Superscalar RISC CPU architecture and the prototype-level implementation of this CPU using an FPGA programmable logic device, for teaching and research purposes. It is widely known that the development of microprocessors has boomed in recent decades, especially those of RISC architecture, and specifically those of the superscalar type. They are increasingly more powerful, and capable of performing complex calculations in less time. However, for teaching and research purposes, it is not possible to have specific hardware platforms based on RISC architecture CPUs due to their high cost. On the other hand, there are software applications for CPU simulation, but they only simulate the execution of the software at the assembly language level, without seeing the influence of the software execution on the behavior of the CPU hardware, which would allow a complete understanding of the operation of the CPU. In this project, a RISC Superscalar CPU will be designed and implemented at prototype level, based on the MIPS architecture, in such a way that a 2-way Superscalar CPU with 3 pipeline queues will be implemented, along with the Hazard Detection Unit (HDU), Data Forwarding Unit (FU) and Branch Prediction Unit (BU). The design will be restricted to a subset of the integer instructions of the MIPS32 architecture CPU, and floating point instructions will not be implemented. It is worth mentioning that the MIPS architecture is widely studied worldwide in universities at the undergraduate and graduate levels. The project will emphasize the use of the VHDL hardware description language, and the design will be implemented in the DE2 board from Terasic. Tests will be carried out with different instructions and different instruction sequences in order to check the internal behavior of the CPU, showing the results in a VGA display.
