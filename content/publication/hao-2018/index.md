---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Vision-Based Surgical Tool Pose Estimation for the da Vinci Robotic Surgical System"
authors: 
 - Ran Hao
 - Orhan Özgüner
 - M. Cenk Çavuşoğlu
date: 2018-10-01T18:20:14-06:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-12-09T18:20:14-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: in *2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS'18)*
publication_short: in *IROS*

abstract: This paper presents an approach to surgical tool tracking using stereo vision for the da Vinci Surgical Robotic System. The proposed method is based on robot kinematics, computer vision techniques and Bayesian state estimation. The proposed method employs a silhouette rendering algorithm to create virtual images of the surgical tool by generating the silhouette of the defined tool geometry under the da Vinci robot endoscopes. The virtual rendering method provides the tool representation in image form, which makes it possible to measure the distance between the rendered tool and real tool from endoscopic stereo image streams. Particle Filter algorithm employing the virtual rendering method is then used for surgical tool tracking. The tracking performance is evaluated on an actual da Vinci surgical robotic system and a ROS/Gazebo-based simulation of the da Vinci system.

# Summary. An optional shortened abstract.
summary: in *2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS'18)*

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

url_pdf:
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
projects:
- vision-based-surgical-tool-tracking

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
