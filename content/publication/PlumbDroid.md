+++
title = "Automatic Repair for Resource Leaks in Android Applications"
date = 2020-03-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `[]`.
authors = ["Bhargav Nagaraja Bhatt", "Carlo A. Furia"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "*Under Submission*"
publication_short = "*Under Submission*"
# Abstract and optional shortened version.

abstract = "Resource leaks—a program does not release resources it previously acquired—are a common kind of bug in Android applications. Even with the help of existing techniques to automatically detect leaks, writing a leak-free program remains tricky. One of the reasons is Android’s event-driven programming model, which complicates the understanding of an application’s overall control flow. In this paper, we present PlumbDroid: a technique to automatically detect and fix resource leaks in Android applications. PlumbDroid uses static analysis to find execution traces that may leak a resource. The information built for detection also undergirds automatically building a fix—consisting of release operations performed at appropriate locations—that removes the leak and does not otherwise affect the application’s usage of the resource. An empirical evaluation on resource leaks from the DroidLeaks curated collection demonstrates that PlumbDroid’s approach is scalable and produces correct fixes for a variety of resource leak bugs. This indicates it can provide valuable support to enhance the quality of Android applications in practice"
abstract_short = ""

# Featured image thumbnail (optional)
#image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "pubs/PlumbDroid.pdf"
#url_preprint = "pubs/TACAS17.pdf"
#url_code = "https://bitbucket.org/traytel/aerial"
#url_dataset = "#"
#url_project = "#"
#url_slides = "pubs/TACAS17.pptx"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
#doi = "https://doi.org/10.1007/s10703-018-00328-3"

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

#More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
