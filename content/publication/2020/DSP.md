+++
title = "A TV-based image processing framework for blind color deconvolution and classification of histological images"

# Date first published.
date = "2020-06-04"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Fernando Pérez-Bueno", "Miguel López-Pérez", "Miguel Vega", "Javier Mateos", "Valery Naranjo", 
"Rafael Molina", "Aggelos K. Katsaggelos"]

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
publication = "*Digital Signal Processing*. Volume 101, no. 6, June 2020. "
publication_short = "*Digital Signal Processing*"

# Abstract and optional shortened version.
abstract = "In digital histopathological image analysis, two conflicting objectives are often pursued: closeness to the original tissue and high classification performance. The former objective tries to recover images (stains) that are as close as possible to the ones obtained by staining the tissue with a single dye. The latter objective requires images that allow the extraction of better features for an improved classification, even if their appearance is not close to single stained tissues. In this paper we propose a framework that achieves both objectives depending on the number of stains used to mathematically decompose the scanned image. The proposed framework uses a total variation prior for each stain together with the similarity to a given reference color-vector matrix. Variational inference and an evidence lower bound are utilized to automatically estimate all the latent variables and model parameters. The proposed methodology is tested on real images and compared to classical and state-of-the-art methods for histopathological blind image color deconvolution and prostate cancer classification."
#abstract_short = ""
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
url_custom = [{name = "Paper", url = "https://www.sciencedirect.com/science/article/abs/pii/S1051200420300725"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption 😄"

+++
