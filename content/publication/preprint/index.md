---
title: "Low-Cost Ex-Vivo Record-Replay-Diagnosis for IoT Devices"
authors:
- admin
date: "2024-09-24T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Postmortem program analysis is a daunting task. This is especially true for deeply embedded systems which lack basic facilities to record the context at crash points, not to mention advanced mechanisms such as program tracing that can record the problematic instruction trace ahead of the crash. Worse, without basic hardware features to promptly capture faulty states, the device can execute for days after a memory corruption happens, making fault diagnosis even harder. This paper presents μ RnR, a lightweight ex-vivo record-and-replay architecture for deeply embedded IoT devices, with a primary application on effortless postmortem fault diagnosis. We target a popular IoT architecture in which IoT devices are locally managed by a centralized hub or edge, which further connects to the cloud for remote functions. In these systems, the attack payload carried on external inputs also passes through the IoT hub. Therefore, our system leverages the IoT hub to collect these suspicious external inputs, with which we try to recover the execution trace before the crash. Although edge observable inputs are not sufficient to fully replay previous execution, we found that the rest device inputs including internal hardware signals can be inferred via program analysis techniques. To demonstrate the application of μRnR, we also developed a bug diagnosis system named μARCUS, which uses the recovered execution trace to find the root cause of crashed execution. Our prototype shows promising results in terms of both trace reconstruction and bug diagnosis.

# Summary. An optional shortened abstract.
summary: Postmortem program analysis for deeply embedded systems based on Record-Replay-Diagnosis.

tags:
- Program Analysis

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://www.scribbr.co.uk/wp-content/uploads/2023/11/root-cause-analysis-preview.webp)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
