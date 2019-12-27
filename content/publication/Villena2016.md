+++
title = "Fast electromagnetic analysis of MRI transmit RF coils based on accelerated integral equation methods"

# Date first published.
date = "2016-11-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["J. F. Villena", "A. G. Polimeridis", "Y. Eryaman", "E. Adalsteinsson", "L. L. Wald", "J. K. White", "L. Daniel"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*IEEE Trans. Biomed. Eng.*, vol. 63, no. 11, pp. 2250-2261, Nov. 2016. [[This paper has been selected to appear on the cover of IEEE TBM]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7593438)"
publication_short = "*IEEE Trans. Biomed. Eng.*, vol. 63, no. 11, pp. 2250-2261, Nov. 20116. [[This paper has been selected to appear on the cover of IEEE TBM]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7593438)"

# Abstract and optional shortened version.
abstract = "A fast frequency domain, full-wave electromagnetic simulation method is introduced for the analysis of MRI coils loaded with realistic human body models. The approach is based on integral equation methods decomposed into two domains: 1) the RF coil array and shield, and 2) the human body region where the load is placed. The analysis of multiple coil designs is accelerated by introducing the pre-computed magnetic resonance Green functions (MRGFs), which describe how the particular body model used responds to incident fields from external sources. These MRGFs, which are pre- computed once for a given body model, can be combined with any integral equation solver and re-used for the analysis of many coil designs. This approach provides a fast, yet comprehensive, analysis of coil designs, including the port S-parameters and the electromagnetic field distribution within the inhomogeneous body. The method solves the full wave electromagnetic problem for a head array in few minutes, achieving a speed up of over 150 fold with root mean square errors in the electromagnetic field maps smaller than 0.4% when compared to the unaccelerated integral equation based solver. This enables the characterization of a large number of RF coil designs in a reasonable time, which is a first step towards automatic optimization of multiple parameters in the design of transmit arrays, as illustrated in the manuscript, but also receive arrays."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://tbme.embs.org/2016/10/23/fast-electromagnetic-analysis-mri-transmit-rf-coils-based-accelerated-integral-equation-methods/"
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
[header]
image = ""
caption = ""

+++
