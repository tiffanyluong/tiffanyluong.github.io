---
title: "Towards Real-Time Recognition of Users’ Mental Workload Using Integrated Physiological Sensors Into a VR HMD"
authors:
- admin
- Nicolas Martin
- Anais Raison
- Jean-Marc Diverrez
- Ferran Argelaguet
- Anatole Lécuyer
date: "2020-11-06T00:00:00Z"
doi: ""

author_notes:
- "Equal contribution"
- "Equal contribution"
- ""
- ""
- ""
- ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Mixed and Augmented Reality (ISMAR)* 
publication_short: In *International Symposium on Mixed and Augmented Reality (ISMAR)*  

abstract: This paper describes an ``all-in-one'' solution for the real-time recognition of users' mental workloads in virtual reality through the customization of a commercial HMD with physiological sensors. First, we describe the hardware and software solution employed to build the system. Second, we detail the machine learning methods used for the automatic recognition of the users' mental workload, which are based on the well-known Random Forest algorithm. In order to gather data to train the system, we conducted an extensive user study with 75 participants using a VR flight simulator to induce different levels of mental workload. In contrast to previous works which label the data based on a standardized task (e.g., n-back task) or on a pre-defined task-difficulty, participants were asked about their perceived mental workload level along the experiment. With the data collected, we were able to train the system in order to classify four different levels of mental workload with an accuracy up to 65%. In addition, we discuss the role of the signal normalization procedures, the contribution of the different physiological signals on the recognition accuracy and compare the results obtained with the sensors embedded in the HMD with commercial grade systems. Preliminary results show our pipeline is able to recognize mental workload in real-time. Taken together, our results suggest that such all-in-one approach, with physiological sensors directly embedded in the HMD, is a promising path for VR applications in which the real-time or off-line estimation of Mental Workload assessment is beneficial.

# Summary. An optional shortened abstract.
summary: This paper describes an ``all-in-one'' solution for the real-time recognition of users' mental workloads in VR through the customization of a commercial HMD with physiological sensors. We conducted an extensive user study (N = 75) to collect mental workload data. The classification accuracy of 4 levels of mental workload using sensors embedded in the HMD is compared to the classification performance using commercial grade systems. In addition, we discuss the role of the signal normalization procedures and the contribution of the different physiological signals on the recognition accuracy.

tags:
- Virtual Reality
- Mental Workload
- UX
- Affective Computing
- Real-Time Classification
- Supervised Machine Learning
- Individual Variabilities
- Physiological Sensing
- Cardiac
- EDA
- Pupilary Activity
# - Subjective Ratings
- Task Performance
# - Pilots Training
featured: true

links:
- name: DOI
  url: https://doi.org/10.1109/ISMAR50242.2020.00068
- name: Talk
  url: https://youtu.be/gbeXBg-XmHk
url_pdf: https://hal.archives-ouvertes.fr/hal-03008918/document 
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
  caption: ''
  focal_point: Center
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
slides: ""
---
