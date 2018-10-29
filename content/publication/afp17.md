+++
title = "Game-based cryptography in HOL"
date = 2017-07-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `[]`.
authors = ["Andreas Lochbihler", "S Reza Sefidgar", "Bhargav Nagaraja Bhatt"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Archive of Formal Proofs*, August 2017."
publication_short = "In *AFP 2017*"

# Abstract and optional shortened version.
abstract = "In this AFP entry, we show how to specify game-based cryptographic security notions and formally prove secure several cryptographic constructions from the literature using the CryptHOL framework. Among others, we formalise the notions of a random oracle, a pseudo-random function, an unpredictable function, and of encryption schemes that are indistinguishable under chosen plaintext and/or ciphertext attacks. We prove the random-permutation/random-function switching lemma, security of the Elgamal and hashed Elgamal public-key encryption scheme and correctness and security of several constructions with pseudo-random functions. Our proofs follow the game-hopping style advocated by Shoup and Bellare and Rogaway, from which most of the examples have been taken. We generalise some of their results such that they can be reused in other proofs. Thanks to CryptHOL's integration with Isabelle's parametricity infrastructure, many simple hops are easily justified using the theory of representation independence."
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
url_pdf = "pubs/AFP17.pdf"
#url_code = "https://bitbucket.org/traytel/aerial"
#url_dataset = "#"
#url_project = "#"
#url_slides = "pubs/TACAS17.pptx"
#url_video = "#"
#url_poster = "#"
url_source = "https://www.isa-afp.org/entries/Game_Based_Crypto.html"

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
