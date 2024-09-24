---
# Activate this widget? true/false
active: false
title: "Unsupervised Domain Adaptation for Self-Driving from Past Traversal Features"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Travis Zhang
- Katie Luo
- Cheng Perng Phoo
- Yurong You
- Wei-Lun Chao
- Bharath Hariharan
- Mark Campbell
- Kilian Q Weinberger

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-06-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *roBustness and Reliability of Autonomous Vehicles in the Open-world Workshop, International Conference on Computer Vision 2023*
publication_short: In *BRAVO Workshop, ICCV 2023*

abstract: "The rapid development of 3D object detection systems for self-driving cars has significantly improved accuracy. However, these systems struggle to generalize across diverse driving environments, which can lead to safety-critical failures in detecting traffic participants. To address this, we propose a method that utilizes unlabeled repeated traversals of multiple locations to adapt object detectors to new driving environments. By incorporating statistics computed from repeated LiDAR scans, we guide the adaptation process effectively. Our approach enhances LiDAR-based detection models using spatial quantized historical features and introduces a lightweight regression head to leverage the statistics for feature regularization. Additionally, we leverage the statistics for a novel self-training process to stabilize the training. The framework is detector model-agnostic and experiments on real-world datasets demonstrate significant improvements, achieving up to a 20-point performance gain, especially in detecting pedestrians and distant objects."

# Summary. An optional shortened abstract.
summary: "<i>BRAVO, ICCV 2023</i>  <br>
Improving domain adaptation for 3D object detection with repeated traversals."
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["self driving"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content/ICCV2023W/BRAVO/papers/Zhang_Unsupervised_Domain_Adaptation_for_Self-Driving_from_Past_Traversal_Features_ICCVW_2023_paper.pdf'
url_code: 'https://github.com/zhangtravis/Hist-DA'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Our methodology identifies a source of information to improve self-supervised adaptation, and we designed a model-agnostic adaptation framework to leverage repeated traversals effectively.'
  focal_point: ""
  preview_only: false

---