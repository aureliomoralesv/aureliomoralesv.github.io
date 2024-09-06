---
title: "Uncertainty Evaluation of a Gas Turbine Model Based on a Nonlinear Autoregressive Exogenous Model and Monte Carlo Dropout"
authors:
- Armando Cajahuaringa
- Rubén Aquize Palacios
- Juan M. Mauricio Villanueva
- admin
- José Machuca
- Juan Contreras
- Kiara Rodríguez Bautista

#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2024-01-01T00:00:00Z"
doi: "10.3390/s24020465"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Sensors*"
publication_short: "*Sensors*"

abstract: Gas turbines are thermoelectric plants with various applications, such as large-scale electricity production, petrochemical industry, and steam generation. In order to optimize the operation of a gas turbine, it is necessary to develop system identification models that allow for the development of studies and analyses to increase the system’s reliability. Current strategies for modeling complex and non-linear systems can be based on artificial intelligence techniques, using autoregressive neural networks of the NARX and LSTM type. In this context, this work aims to develop a model of a gas turbine capable of estimating the rotation speed of the turbine and simultaneously estimating the uncertainty associated with the estimation. These methodologies are based on artificial neural networks and the Monte Carlo dropout simulation method. The results were obtained from experimental data from a 215 MW gas turbine, getting the best model with a MAPE of 0.02\% and an uncertainty associated with the turbine rotation speed of 2.2 RPM.

# Summary. An optional shortened abstract.
summary: .

#tags:
#- Source Themes
featured: true

# links:
# - name: ""
#   url: "https://www.mdpi.com/1424-8220/24/2/465"
#url_code: ''
#url_dataset: ''
#url_project: ''
#url_source: ''
#url_video: ''
url_pdf: 'https://www.mdpi.com/1424-8220/24/2/465/pdf?version=1705028686'
#url_poster: ''
#url_slides: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

---
title: 'On-chip Context Save and Restore of Hardware Tasks on Partially Reconfigurable FPGAs'

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

date: '2013-04-01T00:00:00Z'
doi: '10.1109/FCCM.2013.13'

# Schedule page publish date (NOT publication's date).
publishDate: '2013-04-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2013 IEEE 21st Annual International Symposium on Field-Programmable Custom Computing Machines*
publication_short: In *2013 IEEE 21st Annual International Symposium on Field-Programmable Custom Computing Machines*

abstract: Partial reconfiguration (PR) of field-programmable gate arrays (FPGAs) enables hardware tasks to time multiplex PR regions (PRRs) by isolating reconfiguration to only the reconfigured PRR, which avoids halting the entire FPGA's execution. Time multiplexing PRRs requires support for unloading/loading tasks and for resuming a task's execution state. In order to resume a task's execution state, the execution state (context) must be saved when the task is unloaded so that the execution state can be restored when the task resumes- context save (CS) and context restore (CR), respectively. In this paper, we present a software-based, on-chip context save and restore (CSR) for PR-capable FPGAs. As compared to prior work, our CSR is autonomous (i.e., does not require any external host support), does not require custom on-chip hardware, is portable across any system design, and does not require tool flow modifications or special tools. Experimental results extensively evaluate the CSR execution time based on PRR size, enabling designers to trade off PRR granularity for CSR execution time based on application requirements.

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
url_pdf: 'https://aureliomoralesv.github.io/publication/conference-paper/FCCM13_morales_CSR.pdf'
url_poster: 'https://aureliomoralesv.github.io/publication/conference-paper/FCCM13_morales_CSR-poster.pdf'
url_slides: 'https://aureliomoralesv.github.io/publication/conference-paper/FCCM13_morales_CSR.pptx'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
