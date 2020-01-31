---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Distributed Stochastic Gradient Descent"
summary: " "
authors: []
tags: [Distributed Computing, Machine Learning]
categories: []
date: 2017-10-01

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
Gradient descent is an optimization algorithm used to find the minimum of a function.  By iterative moving in the direction of the steepest descent, we arrive at a minimum of the cost function. 
Gradient descent is used in a lot of machine  learning techniques to update model parameters, be it the coefficient in linear regression or the weights in neural networks.
While stochastic gradient descent calculates gradient for seeing each data point and updates the parameters each time, parallelizing SGD is an approach to leverage the effectiveness of stochastic gradient descent but also reduction in time.   
It also satisfies the requirement of huge computational power in a distributed fashion and reduce load on a single machine.

The motivation behind this project is to explore the current distributed stochastic gradient descent algorithms and compare their performance between different datasets.  
It intends to examine the sensitivity of different datasets to different algorithms.

Techincal tools: Python, Apache Spark
