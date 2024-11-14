---
title: "I-ROD: An Ensemble CNNs for Object Detection in Unconstrained Road Scenarios"
authors:
- Abhishek Mukhopadhyay
- admin
- Prashant T Gaikwad
- Imon Mukherjee
- Pradipta Biswas

author_notes:

date: "2024-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Signal, Image and Video Processing Journal, Springer*"
publication_short: "Signal, Image and Video Processing Journal, Springer; (Accepted, November 2024)"

abstract: Solving the problem of object detection in complex and unstructured environments is crucial for enhancing the safety and efficiency of autonomous system. This paper introduces a semantic segmentation model capable of accurate object detection in complex backgrounds by integrating multiple Convolutional Neural Networks (CNNs). The system incorporates two distinct types of segmentation models, an encoder-decoder architecture for acquiring abstract feature representations and a dilated convolutional branch to tackle variations in object sizes. The model employs a dynamic fusion mechanism based on confidence scores from each branch, allowing it to adapt to varying and dynamic situations. The model is evaluated on the Indian Driving Dataset (IDD), featuring unstructured road environments, and the Cityscape dataset. Comparative pixel-wise analysis shows the proposed model outperforming four other state-of-the-art segmentation models by 12.91% on the IDD and by 19.7% over the second-best model on the Cityscape dataset in terms of F1 score. Furthermore, an extensive ablation study validates the efficacy of the ensemble approach and underscores the effectiveness of categorical cross-entropy as the chosen loss function.

# Summary. An optional shortened abstract.
summary: Solving the problem of object detection in complex and unstructured environments is crucial for enhancing the safety and efficiency of autonomous system. This paper introduces a semantic segmentation model capable of accurate object detection in complex backgrounds by integrating multiple Convolutional Neural Networks (CNNs). The system incorporates two distinct types of segmentation models, an encoder-decoder architecture for acquiring abstract feature representations and a dilated convolutional branch to tackle variations in object sizes. The model employs a dynamic fusion mechanism based on confidence scores from each branch, allowing it to adapt to varying and dynamic situations.

tags:
- Object Detection
- Semantic Segmentation
- Convolutional Neural Network (CNN)

featured: True

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
