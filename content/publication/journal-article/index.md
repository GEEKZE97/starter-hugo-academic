---
title: "A Rough to Fine Method for Industrial Robot Sensing and High-precision Guidance"
authors:
- admin
- Wei Liu
- Binchao Yu
- Dazhi Ma

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-27"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Instrumentation and Measurement"
publication_short: ""

abstract: Robot end effector localization is very important in undertaking high-precision tasks. This paper addresses the precise localization and guidance of the robotic end effector by introducing an industrial stereo-vision sensing and robot guidance system which is based on a high-precision artificial vision target extraction. Firstly, a new hand-eye calibration method is introduced to acquire the relation between the cameras and the robot end effector without considering the common field of view (FoV) of two cameras. Secondly, the method based on yolov3 is used to guide the end effector to a rough position from its initial position by recognizing the target work piece and reconstructing the 3D coordinate of its center. Finally, the end effector is guided to the precise position by repeatedly updating the difference between the current position and the desired position with the help of Control Points, which are used to establish the relation between the world coordinate system (CS) and camera CS. Experimental results indicate that this system can accurately localize the target position and guide the end effector with a position error of 84.8µm, which is enabled by achieving a higher precision stereo vision with root mean square (RMS) value of errors 59.4µm.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: A Rough to Fine Method for Industrial Robot Sensing and High-precision Guidance.pdf
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
  caption: ''
  focal_point: ""
  preview_only: true

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
slides: 
---

