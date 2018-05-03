+++
title = "Tracking the power port of remote radio unit (RRU) using computer vision"

# Date first published.
date = "2017-10-29"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ali Anwar", "Weiyang Lin", "Hengbo Ma", "Huijun Gao", "Wenbo Dong", "Chenglu Liu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "IEEE 43rd Annual Conference of the Industrial Electronics Society (IECON2017)"
publication_short = "IEEE 43rd Annual Conference of the Industrial Electronics Society (IECON2017)"

# Abstract and optional shortened version.
abstract = ""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# [header]
# image = "headers/bubbles-wide.jpg"
# caption = "My caption 😄"

+++

**Abstract**

In this paper, problem of identifying and tracking the power port of remote radio unit (RRU) is addressed. The testing of RRU requires the inspection robot to insert the probes into its power and network ports. In order to solve this problem, an experimental setup of visual servoing with 6 degrees of freedom (DoF) manipulator has been established. The initial problem of recognizing and tracking the power port of RRU has been resolved using template matching and camshift tracking algorithms. Furthermore, camshift tracking algorithm has been improved to work more accurately in this application. Modified algorithm addresses the problem of swapping of major and minor axes of camshift and enhances its application to 6 DoF from 4 DoF. Experimental results have been presented to support the research claims, and computational comparison of modified tracking algorithm with camshift has been shown.
