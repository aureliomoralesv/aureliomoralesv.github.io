---
title: On-Chip Context Save and Restore on Partially Reconfigurable FPGAs
summary: Project developed as a graduate research volunteer student at National Science Foundation (NSF) Center for High-Performance Reconfigurable Computing (CHREC), as part of the doctoral program at the University of Florida.
tags:
  - CSR
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
#url_pdf: 'https://aureliomoralesv.github.io/content/project/CSR/CMW12_F4-DDRM_CSR_BR_poster.pdf'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
Partial reconfiguration (PR) enables hardware tasks to time multiplex partially reconfigurable regions (PRRs) by isolating reconfiguration to only the reconfigured PRR, which avoids halting the entire FPGA’s execution. Time multiplexing PRRs requires support for unloading/loading hardware tasks and for resuming a task’s execution state. The execution state (context) must be saved when the task is unloaded so that the execution state can be restored when the task resumes — context save (CS) and context restore (CR), respectively. This context save and restore (CSR) process can significantly enhance system functionality by eliminating lengthy re-execution time. CSR has high potential for applications such as dynamic load balancing and task migration between pooled FPGA resources, target tracking where fast moving, critical targets must be continually monitored (e.g., incoming missiles), etc. The CSR tool is C-based and currently supports CLB/BRAM/LUTRAM-based hardware tasks on Xilinx Virtex-5 devices, and can be easily ported to new Xilinx device families.

