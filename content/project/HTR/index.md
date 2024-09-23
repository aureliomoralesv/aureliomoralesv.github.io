---
title: On-Chip Hardware Task Relocation on Partially Reconfigurable FPGAs
summary: Project developed as a graduate research volunteer student at National Science Foundation (NSF) Center for High-Performance Reconfigurable Computing (CHREC), as part of the doctoral program at the University of Florida.
tags:
  - HTR
date: '2013-06-04T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by Aurelio Morales at CHREC Mid Year 2012
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
url_pdf: 'https://aureliomoralesv.github.io/content/project/HTR/CMW13_F4-CSR+HTR_poster.pdf'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
Partial reconfiguration (PR) enables shared FPGA systems to non-intrusively time multiplex hardware tasks in partially reconfigurable regions (PRRs). To fully exploit PR, higher priority tasks should preempt lower priority tasks and preempted tasks should resume execution in any PRR with available resources. This preemption/resumption requires saving/restoring the preempted task’s execution context and relocating the task to another PRR. The on-chip hardware task relocation (HTR) software enables a task’s execution state to be saved, relocated to, and restored in any heterogeneous PRR with sufficient resources. HTR has high potentical for applications such as dynamic load balancing and task migration between pooled FPGA resources in a network of FPGAs, target tracking where fast moving, critical targets must be continually monitored (e.g., incoming missiles), etc. The HTR tool is C-based and currently supports CLB/BRAM/LUTRAM-based hardware tasks on Xilinx Virtex-5 devices, and can be easily ported to new Xilinx device families.

