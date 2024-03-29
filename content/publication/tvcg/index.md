---
title: "An example journal article"
authors:
- Yuda Qiu
- admin
- Xiao Zitong
- Xianggang Yu
- Yushuang Wu
- Xiaoguang Han
date: "2024-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to *IEEE Transactions on Visualization and Computer Graphics*"
publication_short: "Submitted to *TVCG*"

abstract: While significant progresses has been made in stylizing face images, such as Toonme, modelling stylized 3D faces remains a labor-intensive task and existing popular solutions strongly rely on abundant 3D supervision. Our goal is to efficiently learn a reconstruction network with only a little supervision, which generates textured face meshes that accurately captures the features of target stylized face images, for example Toonme. To achieve this, we propose a reconstruction framework, Toonme3D , to incorporate the rich reconstruction knowledge learned in the real face domain and transfer them into the Toonme style domain for both the face shape and texture generation. The shape generator is based on a well-designed 3D morphable model pre-trained on the real face domain. A novel cartoon shape prior is fused with the real shape one to stylize the shape outputs, which is distilled from a 3D Toonme dataset with uniform topology via Principal Component Analysis. For the texture generation, a pre-trained StyleGAN, which can generate delicate stylized albedos for real face meshes, is fine-tuned on the 2D Toonme style images to provide stylized texture information. We show that the shape and texture prior together enable faithful reconstruction of textured face meshes from target images. In addition, our method also shows great generalizablity when applied in the reconstruction of caricature-style faces.



tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
slides: []
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
