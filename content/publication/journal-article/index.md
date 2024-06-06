---
title: "Peripapillary atrophy classification using CNN deep learning for glaucoma screening"
authors:
- admin
- Mohammed Alawad
- Abdulrhman Aljouie
- Hessa Almatar
- Waseem Qureshi
- Balsam Alabdulkader
- Norah Alkanhal
- Wadood Abdul
- Mansour Almufarrej
- Shiji Gangadharan
- Tariq Aldebasi
- Barrak Alsomaie
- Ahmed Almazroa
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-09-01T00:00:00Z"
doi: "https://doi.org/10.1371/journal.pone.0275446"

# Schedule page publish date (NOT publication's date).
# publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In ***PLOS ONE*** 
# publication_short: ""

abstract: Glaucoma is the second leading cause of blindness worldwide, and peripapillary atrophy (PPA) is a morphological symptom associated with it. Therefore, it is necessary to clinically detect PPA for glaucoma diagnosis. This study was aimed at developing a detection method for PPA using fundus images with deep learning algorithms to be used by ophthalmologists or optometrists for screening purposes. The model was developed based on localization for the region of interest (ROI) using a mask region-based convolutional neural networks R-CNN and a classification network for the presence of PPA using CNN deep learning algorithms. A total of 2,472 images, obtained from five public sources and one Saudi-based resource (King Abdullah International Medical Research Center in Riyadh, Saudi Arabia), were used to train and test the model. First the images from public sources were analyzed, followed by those from local sources, and finally, images from both sources were analyzed together. In testing the classification model, the area under the curve’s (AUC) scores of 0.83, 0.89, and 0.87 were obtained for the local, public, and combined sets, respectively. The developed model will assist in diagnosing glaucoma in screening programs; however, more research is needed on segmenting the PPA boundaries for more detailed PPA detection, which can be combined with optic disc and cup boundaries to calculate the cup-to-disc ratio.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: False

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---