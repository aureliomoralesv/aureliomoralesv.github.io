---
title: 'Partial Region and Bitstream Cost Models for Hardware Multitasking on Partially Reconfigurable FPGAs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ann Gordon-Ross

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2015-05-25T00:00:00Z'
doi: '10.1109/IPDPSW.2015.148'

# Schedule page publish date (NOT publication's date).
publishDate: '2015-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2015 IEEE International Parallel and Distributed Processing Symposium Workshop*
publication_short: In *2015 IEEE International Parallel and Distributed Processing Symposium Workshop*

abstract: Partial reconfiguration (PR) on field-programmable gate arrays (FPGAs) enables multiple PR modules (PRMs) to time multiplex partially reconfigurable regions (PRRs), which affords reduced reconfiguration time, area overhead, etc., as compared to non-PR systems. However, to effectively leverage PR, system designers must determine appropriate PRR sizes/organizations during early stages of PR system design, since inappropriate PRRs, given PRM requirements, can negate PR benefits, potentially resulting in system performance worse than a functionally-equivalent non-PR design. To aid in PR system design, we present two portable, high-level cost models, which are based on the synthesis report results generated by Xilinx tools. These cost models estimate PRR size/organization given the PRR’s associated PRMs to maximize the PRRs’ resource utilizations and estimate the PRM's associated partial bitstream sizes based on the PRR sizes/organizations. Experiments evaluate our cost models’ accuracies for different PRMs and required resources, which enable our models to afford enhanced designer productivity since these models preclude the lengthy PR design flow, which is typically required to attain such analysis.

# Summary. An optional shortened abstract.
summary: ' '

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
url_pdf: 'https://aureliomoralesv.github.io/publication/conference-paper/RAW15_morales_PR-cost-models.pdf'
#url_poster: ''
url_slides: 'https://aureliomoralesv.github.io/publication/conference-paper/RAW15_morales_PR-cost-models_slides.pptx'

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

