---
title: 'Configuration Prefetching and Reuse for Preemptive Hardware Multitasking on Partially Reconfigurable FPGAs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Rohit Kumar
  - Ann Gordon-Ross

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2016-04-01T00:00:00Z'
doi: '10.3850/9783981537079_0486'

# Schedule page publish date (NOT publication's date).
publishDate: '2016-04-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2016 Design, Automation & Test in Europe Conference & Exhibition DATE*
publication_short: In *Proceedings of the 2016 Design, Automation & Test in Europe Conference & Exhibition DATE*

#abstract: Partially reconfigurable (PR) FPGAs enable preemptive hardware (HW) multitasking using PR regions (PRRs). To enable this multitasking, the HW task's partial bit-stream is downloaded to only the task's PRR, and only that PRR is reconfigured. Since only a small portion of the FPGA fabric is reconfigured, reconfiguration time is significantly reduced as compared to reconfiguring the entire fabric, however this time is not negligible. Reconfiguration time can be reduced/hidden using two techniques: configuration prefetching and configuration reuse. Even though these techniques can effectively reduce/hide reconfiguration overhead, prior works in preemptive HW multi-tasking did not use these techniques. To the best of our knowledge, no prior work evaluated physical implementations of these techniques on PR FPGAs, which precludes consideration of physical-implementation-specific details, such as delays in accessing bitstreams, speed limitations during reconfiguration, etc. In this work, we present a novel implementation of configuration prefetching and reuse for preemptive HW multitasking on a Virtex-5 FPGA, however, our established fundamentals are device-family independent.

# Summary. An optional shortened abstract.
summary: .

#tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_code: ''
#url_dataset: ''
#url_project: ''
#url_source: ''
#url_video: ''
url_pdf: 'https://aureliomoralesv.github.io/publication/conference-paper/DATE16_morales_Prefetch-Reuse.pdf'
url_poster: 'https://aureliomoralesv.github.io/publication/conference-paper/DATE16_morales_Prefetch-Reuse_poster.pdf'
url_slides: 'https://aureliomoralesv.github.io/publication/conference-paper/DATE16_morales_Prefetch-Reuse_slides.pptx'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
