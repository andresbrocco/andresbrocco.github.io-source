---
# About widget.
widget: "project"  # See https://sourcethemes.com/academic/docs/page-builder/
#headless : false  # This file does not represent a page section.
active : true  # Activate this widget? true/false
weight : 42  # Order that this section will appear in.

# Project title.
title : "Bachelor Thesis"

# Date this page was created.
date : 2019-02-27T00:00:00

# Project summary to display on homepage.
summary : "Acoustic Model of a Steel Tongue Drum"

# Tags: can be used for filtering projects.
tags : ["Acoustics", "Modes of Vibration", "Musical Instrument", "Modal Simulation"]

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
url_pdf : "/files/Bachelor_Thesis.pdf"
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
  caption : "Modal Simulation of the Steel Tongue Drum"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point : "Center"
  
  preview_only: false
  
# Choose the user profile to display
# This should be the username of a profile in your `content/authors/` folder.
# See https://sourcethemes.com/academic/docs/get-started/#introduce-yourself
author : "admin"
---

The Steel Tongue Drum is a recently invented musical instrument that consists of a curved and cutted steel plate, shown at the image below.

<img src="Steel_Tongue_Drum.png" alt="Steel Tongue Drum" style="width:40%">

The instrument is mainly handcrafted, so by the time of this research there wasn't any study on its acoustic properties. For this reason, the idea of my bachelor thesis was to propose a scientific approach on designing this instrument.

The first step was to understand which mechanical characteristics determines the acoustic response. After some experiments, I have found that the interaction with the fluid is negligible, and the only relevant characteristics were the geometry and material of the instrument. 

Therefore, the frequencies of the instruments notes can be determined by a simple modal analysis. The cover image of this page shows the displacement of one of the instruments vibration modes. You can take a look at the full report (in portuguese) at the "PDF" link.
