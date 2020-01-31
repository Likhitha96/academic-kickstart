---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi Object Style Transfer"
summary: " "
authors: []
tags: [Vision, Deep Learning]
categories: []
date: 2018-05-01

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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
Style transfer is a technique of applying the style of another image on a base image called as the content image in our project. The main focus in our project was on doing style transfer for indoor house objects. 
Given a content image of an indoor setting containing an object like a sofa and style image of another sofa design that we want, the goal was to apply the style to the content image without changing the other objects or background.

We have explored different techniques like segmentation, GANs to develop this framework

Technical tools: Python, Tensorflow

