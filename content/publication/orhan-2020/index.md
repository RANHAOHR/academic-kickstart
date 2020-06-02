---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Camera-Robot Calibration for the Da Vinci Robotic Surgery System"
authors:
 - Orhan Özgüner
 - Thomas Shkurti
 - Siqi Huang 
 - Ran Hao
 - Russell C. Jackson
 - Wyatt S. Newman
 - M. Cenk Çavuşoğlu
date: 2020-05-01T18:20:14-06:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-12-09T18:20:14-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: in *IEEE Transactions on Automation Science and Engineering*
publication_short: in *T-ASE*

abstract: The development of autonomous or semiautonomous surgical robots stands to improve the performance of existing teleoperated equipment but requires fine hand-eye calibration between the free-moving endoscopic camera and patient-side manipulator arms (PSMs). A novel method of solving this problem for the da Vinci robotic surgical system and kinematically similar systems is presented. First, a series of image-processing and optical-tracking operations are performed to compute the coordinate transformation between the endoscopic camera view frame and an optical-tracking marker permanently affixed to the camera body. Then, the kinematic properties of the PSM are exploited to compute the coordinate transformation between the kinematic base frame of the PSM and an optical marker permanently affixed thereto. Using these transformations, it is then possible to compute the spatial relationship between the PSM and the endoscopic camera using only one tracker snapshot of the two markers. The effectiveness of this calibration is demonstrated by successfully guiding the PSM end-effector to points of interest identified through the camera. Additional tests on a surgical task, namely, grasping a surgical needle, are also performed to validate the proposed method. The resulting visually guided robot positioning accuracy is better than the earlier hand-eye calibration results reported in the literature for the da Vinci system while supporting the intraoperative update of the calibration and requiring only devices that are already commonly used in the surgical environment.

# Summary. An optional shortened abstract.
summary: in *IEEE Transactions on Automation Science and Engineering*

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 09084276.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
