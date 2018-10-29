+++
title = "Almost Event-Rate Independent Monitoring of Metric Temporal Logic"
date = 2018-06-06T00:00:00
draft = false

# Authors. Comma separated list, e.g. `[]`.
authors = ["David Basin", "Bhargav Nagaraja Bhatt", "Sr&#273;an Krsti&#263;", "Dmitriy Traytel"]

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
publication = " *Under Submission* "
publication_short = " *Under Submission* "

# Abstract and optional shortened version.

abstract = "A monitoring algorithm is trace-length independent if its space consumption does not depend on the number of events processed. The analysis of many monitoring algorithms has aimed at establishing their trace-length independence. But a trace-length independent monitor's space consumption can depend on characteristics of the trace other than its size. We put forward the stronger notion of event-rate independence, where the monitor's space usage does not depend on the event rate, i.e., the number of events in a fixed time unit. This property is critical for monitoring voluminous streams of events with a high arrival rate. We propose a new algorithm for metric temporal logic (MTL) that is almost event-rate independent, where *almost* denotes a logarithmic dependence on the event rate: the algorithm must store the event rate as a number. Afterwards, we investigate more expressive logics. In particular, we extend linear dynamic logic with past operators and metric features. The resulting metric dynamic logic (MDL) offers the quantitative temporal conveniences of MTL while increasing its expressiveness. We show how to modify our MTL algorithm in a modular way, yielding an almost event-rate independent monitor for MDL. Finally, we compare our algorithms with traditional monitoring approaches, providing empirical evidence that almost event-rate independence matters in practice."
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
url_pdf = "pubs/FMSD18.pdf"
#url_preprint = "pubs/TACAS17.pdf"
url_code = "https://bitbucket.org/traytel/aerial"
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
#doi = "https://doi.org/10.1007/978-3-662-54580-5_6"

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
