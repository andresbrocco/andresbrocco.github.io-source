---
# About widget.
widget: "project"  # See https://sourcethemes.com/academic/docs/page-builder/
#headless : false  # This file does not represent a page section.
active : true  # Activate this widget? true/false
weight : 37  # Order that this section will appear in.

# Project title.
title : "Chroma Jammer"

# Date this page was created.
date : 2019-02-27T00:00:00

# Project summary to display on homepage.
summary : "Music visualization tool to assist the learning process."

# Tags: can be used for filtering projects.
tags : ["Audio Visual", "Music Visualization", "Signal Processing", "Audio Analysis", "Feature Extraction", "Pure Data", "Real Time", "Music Information Retrieval"]

# Optional external URL for project (replaces project detail page).
external_link : ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides : ""

# Links (optional).
url_pdf : ""
url_slides : ""
url_video : ""
url_code : ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom : [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
image:
  # Caption (optional)
  caption : ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point : "Center"
  
  preview_only: false
  
# Choose the user profile to display
# This should be the username of a profile in your `content/authors/` folder.
# See https://sourcethemes.com/academic/docs/get-started/#introduce-yourself
author : "admin"
---

ChromaJammer is personal project of a music visualization tool that "forces" synesthesia by associating colors with notes. The main goal is to assist the music learning process, by attaching vision and audition.

The ChromaJammer was written in the <a href="http://puredata.info/">PureData</a> programming language. The patch gets the audio from an external source (mic or music player) and analyses which notes are being played. Each note has an associated color. The color scheme was based on the circle of fifths, since it arranges the notes in an interesting manner: the interval between adjacent notes is the most consonant possible. The circle of fifths is drawn alongside a representation of a guitar arm. When a note is identified, its respective frets lights up on the guitar arm.

As an amateur musician, I've always wanted to improvise on the guitar, but struggled in learning music theory. On the other hand, I found myself with the right knowledge to develop a tool to enhance my capabilities. The project is open-source and can be downloaded from my <a href="https://github.com/andresbrocco/ChromaJammer">GitHub repository</a>. I hope more people enjoy the tool, and maybe some day I'll go back to this project.

I have made a video presenting the patch and showing it in action! 

<video width="320" height="240" controls>
  <source src="/project/chroma-jammer/ChromaJammer_Demo.mp4" type="video/mp4">
Your browser does not support the video tag.
</video> 
