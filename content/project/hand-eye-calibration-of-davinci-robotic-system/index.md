---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hand-Eye Calibration of the Da Vinci Surgical Robotic Systems"
summary: " "
authors: []
tags: 
 - Robotic Hand-Eye Calibration
 - Da Vinci Robotic System
#categories: []
date: 2019-09-06T13:30:08-06:00

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

Due to the nature of the master–slave teleoperation required to operate systems, such as the da Vinci robotic surgical system (Intuitive Surgical, Inc., Sunnyvale, CA, USA), robotic minimally invasive surgery (RMIS) usually results in longer operation times, and the learning curve is steeper than other minimally invasive surgical techniques. In order to perform these automated tasks with precision, it is necessary to know the transformation between the base frame of the robot manipulators (“hands”) and the stereo endoscopic camera (“eye”). Once the hand-eye transformation is known, a detected object in the camera coordinate system can be located in the manipulator coordinate system, and the necessary motions to manipulate the object can be performed autonomously.

In this project, the hand-eye calibration was performed using a Polaris Vicra optical tracking system (Northern Digital Inc., Waterloo, ON, Canada) and da Vinci robotic surgery system, but the methods developed can be used to calibrate any remote-center-of-motion (RCM)-based robot with any tracking system. In order to reduce the accumulation of error, we proposes a procedure that is divided into systematic steps instead of finding a hand-eye transformation directly. The first step computes the transformation between the camera and the marker is computed via a custom-built calibration board and a fixed marker attached to the camera. The second step of the procedure calculates the transformation between the robot base and an optical marker attached onto the robot manipulator base. The third step calculates the transformation between the fixed markers using the optical tracking system. The final hand-eye calibration is computed by using these three intermediate transformations.

This key idea of this work is that most of the time-consuming elements of the calibration are performed offline in a manner which allows them to be retained between movements and even between surgical procedures, leaving the remainder able to be computed in real time without sacrificing precision. This enables the intraoperative updates of the hand-eye transformation to be performed instantly.  The resulting accuracy of the system after calibration is better than the earlier hand-eye calibration results reported in the literature for the dVRK system.