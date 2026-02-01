---
title: VLSI implementation of a simple 32-bit floating-point adder based on IEEE754 using open-source software tools
summary: Project developed at the College of Electrical and Electronics Engineering, Universidad Nacional de Ingeniería (UNI) as part of the Universalization in IC Design by IEEE CAS Society (UNIC-CASS).
tags:
  - vlsi
date: '2026-01-31T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Aurelio Morales using Openroad software
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
url_pdf: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
The Universalization in IC Design by IEEE CAS Society (UNIC-CASS) is a structured end-to-end Integrated Circuit (IC) design-to-test experimental learning program that aims to improve the know-how and accessibility to IC design technologies for enthusiasts and design communities worldwide. Design teams submit designs to CASS-sponsored fabrication runs via Efabless chipIgnite program and bringup the fabricated chip at selected testing facilities. In particular, the project used Verilog hardware description language as the specification of a basic 32-bit floating-point adder based on IEEE754 unsig the FSM+D (controller+datapath) design approach, synthesized and simulated the design using Quartus Prime Lite Edition 25.1 on a Cyclone V SoC FPGA as validation, and adapted the design to Librelane, which is an open-source, Python-based infrastructure designed for automating the entire digital Application-Specific Integrated Circuit (ASIC) design flow, from RTL to CGSII (tape-out), using IHP-SG13G2 Open PDK (130nm CMOS).
