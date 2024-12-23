---
title: "Crash analysis method and device for Internet of Things Firmware."
authors:
- Wei Zhou
- Ruibo Lu
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Chinese Patent CN202410308925.6"
publication_short: "Chinese Patent"

abstract: The present application provides a method and apparatus for firmware crash analysis based on the Internet of Things (IoT), which pertains to the field of computer information processing technology. The method includes, during the operation of IoT devices, recording interaction data and snapshot information with the IoT devices; after the IoT device crashes, loading the firmware of the IoT device, and restoring the firmware's state information at the current snapshot and subsequent states based on the snapshot information; automating the reasoning of hardware feedback and interrupt events based on the restored real-time state information of the firmware, to reconstruct the execution flow of the firmware from the current snapshot to the crash; analyzing the reconstructed execution flow through dynamic and static program analysis to determine the cause of the crash. This application example automates the analysis of the causes of IoT system crashes, which not only greatly simplifies the complexity of system debugging but also significantly reduces the workload of manual debugging, providing strong support for shortening the fault resolution time window and improving system maintainability.

# Summary. An optional shortened abstract.
summary: This application offers an automated IoT firmware crash analysis method that simplifies system debugging, reduces manual workload, and enhances maintainability by analyzing execution flows and determining crash causes.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.patentguru.com/cn/CN117909160A
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**testing.vs.debugging**](https://qa.world/wp-content/uploads/2023/05/testing-vs-debugging.png)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
