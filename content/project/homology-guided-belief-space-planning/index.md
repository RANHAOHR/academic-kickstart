---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: " Homology-Class Guided Rapidly-Exploring Random Tree For Belief Space Planning"
summary: " "
authors: []
tags: 
 - Belief Space Planning
#categories: []
date: 2022-09-06T13:30:08-06:00

# Optional external URL for project (replaces project detail page).
#external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

In this work, an efficient homology guided belief
space planning method for obstacle-cluttered environments is
presented. The proposed planner follows a two-step approach.
First, a h-signature guided rapidly-exploring random tree
(HRRT) algorithm is proposed to provide nominal trajecto-
ries in different homology classes by constructing homology
aware sub-trees in a parallel manner. The HRRT planner is
extended to a h-signature guided RRT* algorithm, where an
inter-homology-class rewire procedure is proposed, increasing
the probability of discovering homology classes in narrow
space/passages. The iLQG-based belief space planning algo-
rithm is then employed to find locally optimal trajectories
minimizing uncertainties in each homology class