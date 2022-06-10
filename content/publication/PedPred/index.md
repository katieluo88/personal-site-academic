---
# Activate this widget? true/false
active: false
title: "Safety-Oriented Pedestrian Motion and Scene Occupancy Forecasting"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Katie Luo*
- Sergio Casas*
- Renjie Liao
- Xinchen Yan
- Yuwen Xiong
- Wenyuan Zeng
- Raquel Urtasun

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Intelligent Robots and Systems*
publication_short: In *IROS 2021*

abstract: In this paper, we address the important problem in self-driving of forecasting multi-pedestrian motion and their shared scene occupancy map, critical for safe navigation. Our contributions are two-fold. First, we advocate for predicting both the individual motions as well as the scene occupancy map in order to effectively deal with missing detections caused by postprocessing, e.g., confidence thresholding and non-maximum suppression. Second, we propose a Scene-Actor Graph Neural Network (SA-GNN) which preserves the relative spatial information of pedestrians via 2D convolution, and captures the interactions among pedestrians within the same scene, including those that have not been detected, via message passing. On two large-scale real-world datasets, nuScenes and ATG4D, we showcase that our scene-occupancy predictions are more accurate and better calibrated than those from state-of-the-art motion forecasting methods, while also matching their performance in pedestrian motion forecasting metrics.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["self-driving", "first-author"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2101.02385'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/VW1LBoaXIkU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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
