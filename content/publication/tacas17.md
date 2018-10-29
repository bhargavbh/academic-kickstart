+++
title = "Almost Event-Rate Independent Monitoring of Metric Temporal Logic"
date = 2017-04-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `[]`.
authors = ["David Basin", "Bhargav Nagaraja Bhatt", "Dmitriy Traytel"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In Legay, A., Margaria, T. (eds.) *23rd International Conference on Tools and Algorithms for the Construction and Analysis of Systems (TACAS 2017)*, Springer, 2017, LNCS 10206, pp. 94–112."
publication_short = "In *Tools and Algorithms for the Construction and Analysis of Systems (TACAS)*"

# Abstract and optional shortened version.
abstract = "A monitoring algorithm is trace-length independent if its space consumption does not depend on the number of events processed. The analysis of many monitoring algorithms has aimed at establishing trace-length independence. But a trace-length independent monitor’s space consumption can depend on characteristics of the trace other than its size. We put forward the stronger notion of event-rate independence, where the monitor’s space usage does not depend on the event rate. This property is critical for monitoring voluminous streams of events arriving at a varying rate. Some previously proposed algorithms for past-only temporal logics satisfy this new property. However, when dealing with future operators, the traditional approach of using a queue to wait for future obligations to be resolved is not event-rate independent. We propose a new algorithm that supports metric past and bounded future operators and is almost event-rate independent, where “almost” denotes a logarithmic dependence on the event rate: the algorithm must store the event rate as a number. We compare our algorithm with traditional ones, providing evidence that almost event-rate independence matters in practice."
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
url_pdf = "https://link.springer.com/chapter/10.1007/978-3-662-54580-5_6"
url_preprint = "pubs/TACAS17.pdf"
url_code = "https://bitbucket.org/traytel/aerial"
#url_dataset = "#"
#url_project = "#"
url_slides = "pubs/TACAS17.pptx"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "https://doi.org/10.1007/978-3-662-54580-5_6"

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

#More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
