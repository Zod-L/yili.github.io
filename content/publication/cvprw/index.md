---
title: 'Cross-Temporal Spectrogram Autoencoder (CTSAE): Unsupervised Dimensionality Reduction for Clustering Gravitational Wave Glitches'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yunan Wu
  - Aggelos K. Katsaggelos

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-03-08T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF Computer Society Conference on Computer Vision and Pattern Recognition Workshops
publication_short:  *CVPRW*

abstract: The advancement of The Laser Interferometer Gravitational-Wave Observatory (LIGO) has significantly enhanced the feasibility and reliability of gravitational wave detection. However, LIGO's high sensitivity makes it susceptible to transient noises known as glitches, which necessitate effective differentiation from real gravitational wave signals. Traditional approaches predominantly employ fully supervised or semi-supervised algorithms for the task of glitch classification and clustering. In the future task of identifying and classifying glitches across main and auxiliary channels, it is impractical to build a dataset with manually labeled ground-truth. In response to this challenge, we introduce the Cross-Temporal Spectrogram Autoencoder (CTSAE), a pioneering unsupervised method for the dimensionality reduction and clustering of gravitational wave glitches. CTSAE integrates a novel four-branch autoencoder with a hybrid of Convolutional Neural Networks (CNN) and Vision Transformers (ViT). To further extract features across multi-branches, we introduce a novel multi-branch fusion method using the CLS (Class) token. Our model, trained and evaluated on the GravitySpy 1.0 dataset, demonstrates superior performance in clustering tasks when compared to state-of-the-art semi-supervised learning methods. To the best of our knowledge, CTSAE represents the first unsupervised approach tailored specifically for clustering LIGO data, marking a significant step forward in the field of gravitational wave research.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'content/publication/cvprw/paper.pdf'
# url_code: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
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
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
