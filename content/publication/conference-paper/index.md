---
title: 'Cov Loss: Covariance-Based Loss for Deep Face Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ibrahim Alkanhal
  - admin
  - Lamia Alsalloom
  - Raied Aljadaany 
  - Marios Savvides

# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-07-01T00:00:00Z'
doi: 'https://doi.org/10.1109/ICASSP49357.2023.10095678'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Acoustics, Speech, and Signal Processing*
publication_short: In ***ICASSP*** 

abstract: Recently, deep neural networks (DNNs) have emerged as state-of-the-art approaches for various computer vision areas. In this paper, we propose an optimized approach for large-scale face recognition. Our work is motivated through the recent development of deep convolutional neural networks (CNNs) that use different loss functions to learn deep features from face images to perform face recognition. As opposed to previous works, we model Cov loss to optimize deep features along the covariance matrix to enhance discriminative power. We formulate Cov loss to maximize inter-class variance and minimize intra-class variance by optimizing the distance between the deep features and their corresponding class covariances in the Euclidean space. The proposed Cov loss is evaluated on large-scale face recognition problems and present results on LFW, IJB-A Janus, IJB-C Janus, and Celebrity Frontal-Profile (CFP). By optimizing features along both Euclidean and angular spaces, our novel loss function learns more robust feature representations of faces, and improves general performance results comparable to the state-of-the-art results..

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
  # - Large Language Models

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://doi.org/10.1109/ICASSP49357.2023.10095678'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ''
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---