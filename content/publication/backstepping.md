+++
title = "Adaptive backstepping control of uncertain nonlinear systems with input backlash"

# Date first published.
date = "2016-08-12"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ali Anwar", "Xiaodong Shao", "Qinglei Hu", "Aidana Moldabayeva", "Bo Li"]

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
publication = "IEEE Chinese Guidance, Navigation and Control Conference (CGNCC2016)"
publication_short = "IEEE Chinese Guidance, Navigation and Control Conference (CGNCC2016)"

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

In this paper a generic model of perturbed nonlinear systems is considered which is affected by hard backlash nonlinearity at its input. The nonlinearity is modelled by a dynamic differential equation which presents a more precise shape as compared to the existing linear models and is compatible with nonlinear design technique such as backstepping. Moreover, a novel backstepping based nonlinear control law is designed which explicitly incorporates a continuous-time adaptive backlash inverse model. It provides a significant flexibility to control engineers, whereby during the control design, they can use the estimated backlash spacing value specified on actuators such as gears etc. in the adaptive Backlash Inverse model. It ensures not only global stability but also stringent transient performance with desired precision. It is also robust to external disturbances upon which the bounds are considered as unknown and traverses the backlash spacing efficiently with underestimated information about the actual value. The continuous-time backlash inverse model is distinguished in the sense that other models are either discrete-time or involve complex computations. Furthermore, numerical simulations are presented which not only illustrate the effectiveness of proposed control law but also its comparison with PID and other backstepping controllers.
