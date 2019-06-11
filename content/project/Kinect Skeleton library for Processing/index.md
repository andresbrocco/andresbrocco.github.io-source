---
# About widget.
widget: "project"  # See https://sourcethemes.com/academic/docs/page-builder/
#headless : false  # This file does not represent a page section.
active : true  # Activate this widget? true/false
weight : 35  # Order that this section will appear in.

# Project title.
title : "Kinect Skeleton library for Processing"

# Date this page was created.
date : 2019-02-27T00:00:00

# Project summary to display on homepage.
summary : "Library to preprocess the Kinect skeleton data and extract body movement features."

# Tags: can be used for filtering projects.
tags : ["Human-Computer Interface", "Multimodal Interaction", "Kinect", "Java", "Processing", "Audio Visual", "Feature Extraction"]

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
  caption : "Kinect Skeleton View"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point : "Center"
  
  preview_only: false
  
# Choose the user profile to display
# This should be the username of a profile in your `content/authors/` folder.
# See https://sourcethemes.com/academic/docs/get-started/#introduce-yourself
author : "admin"
---

The Group 'Perception, Action, and Interaction' at <a href="https://www.nics.unicamp.br/">NICS</a> explores the interaction between humans and digital media; 'Perception' stands for audio analysis, psychoacoustics and visual cognition; 'Action' stands for designing sound and visual arts; 'Interaction' stands for how humans interfaces with the digital environment. One ongoing research example is the sonification of human body movement with application purposes in music therapy. 

One of the devices used by the laboratory to sense the body movements is the <a href="https://developer.microsoft.com/en-us/windows/kinect">Microsoft Kinect</a>. Therefore, some projects rely on a robust tool to preprocess the incoming data and extract body movement features. My role is to develop that tool and make it available as an user friendly software for people with low level of knowledge in software development.

The main features implemented in the library available on my <a href="https://github.com/andresbrocco/Processing_KinectV2_SkeletonTools" >github</a> are: 

- Interface with KinectV2
- Smooth skeleton
- Calibrate for the floor position and room size
- Extract body features
- Send features through network via OSC

The video below is a brief demonstration of the library and its features.

<video width="320" height="240" controls>
  <source src="/project/kinect-skeleton-library-for-processing/KinectV2SkeletonToolsDemo.mp4" type="video/mp4">
Your browser does not support the video tag.
</video> 
