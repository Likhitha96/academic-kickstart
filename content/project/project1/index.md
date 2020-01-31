---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Vision and Language Navigation"
summary: " "
authors: []
tags: [Computer vision, Natural Language Processing, Deep Learning]
categories: []
date: 2018-10-01

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: true

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

Mutimodal learning has gained importance with the plethora of data being available through different modes. 
One such problem in this field is Vision and Language Navigation. 
In this project, we developed a framework in which an agent navigates through a path from a given starting point by following the natural language instructions provided in an indoor house setting.
Each subsequent point location in the path was perceived by the agent as a 360° image of what a human eye sees by standing on that location. 

In order to solve this problem, we leveraged both the natural language instructions and the images at each location to output navigation directions at each location and hence finally reaching the intended destination. 
The framework makes use of dynamic memory networks and reinforcement learning. 

Technical tools: Pytorch 
