---
title: "HTR: On-Chip Hardware Task Relocation for Partially Reconfigurable FPGAs"
authors:
  - admin
  - Ann Gordon-Ross

#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2013-03-27T00:00:00Z"
doi: "10.1007/978-3-642-36812-7_18"

# Schedule page publish date (NOT publication's date).
publishDate: "2013-03-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Reconfigurable Computing: Architectures, Tools and Applications, 9th International Symposium, ARC2013. Lecture Notes in Computer Science, vol. 7806*"
publication_short: "*Reconfigurable Computing: Architectures, Tools and Applications, 9th International Symposium, ARC2013. Lecture Notes in Computer Science, vol. 7806*"

abstract: Partial reconfiguration (PR) enables shared FPGA systems to non-intrusively time multiplex hardware tasks in partially reconfigurable regions (PRRs). To fully exploit PR, higher priority tasks should preempt lower priority tasks and preempted tasks should resume execution in any PRR. This preemption/resumption requires saving/restoring the preempted task’s execution context and relocating the task to another PRR, however, prior works only provide partial solutions and impose limitations and/or overheads. We propose on-chip hardware task relocation (HTR) software, which enables a task’s execution state to be saved, relocated to, and restored in any PRR with sufficient resources. The HTR software executes on a soft-core processor in the FPGA’s static region, and is thus portable across any system/application. Experimental results evaluate HTR execution times, enabling designers to tradeoff task/PRR granularity and HTR execution times based on application requirements.

# Summary. An optional shortened abstract.
summary: .

#tags:
#- Source Themes
featured: true

# links:
# - name: ""
#   url: "https://link.springer.com/10.1007/978-3-642-36812-7_18"
#url_code: ''
#url_dataset: ''
#url_project: ''
#url_source: ''
#url_video: ''
url_pdf: 'https://aureliomoralesv.github.io/publication/journal-article/ARC13_morales_HTR-licensed.pdf'
#url_poster: ''
url_slides: 'https://aureliomoralesv.github.io/publication/journal-article/ARC13_morales_HTR_slides.pptx'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false
---

