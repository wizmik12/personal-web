+++
title = "Classifying Prostate Histological Images Using Deep Gaussian Processes on a New Optical Density Granulometry-Based Descriptor"

# Date first published.
date = "2019-07-04"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Miguel López-Pérez", "Adrián Colomer", "María A. Sales", "Rafael Molina", "Valery Naranjo"]

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
publication = "*Intelligent Data Engineering and Automated Learning – IDEAL 2019*. IDEAL 2019. Lecture Notes in Computer Science, vol 11871. Springer, Cham "
publication_short = "*Intelligent Data Engineering and Automated Learning – IDEAL 2019*"

# Abstract and optional shortened version.
abstract = "The increasing use of whole slide digital scanners has led to an enormous interest in the application of machine learning techniques to detect prostate cancer using eosin and hematoxylin stained histopathological images. In this work the above problem is approached as follows: the optical density of each whole slide image is calculated and its eosin and hematoxylin concentration components estimated. Then, hand-crafted features, which are expected to capture the expertise of pathologists, are extracted from patches of these two concentration components. Finally, patches are classified using a Deep Gaussian Process on the extracted features. The new approach outperforms current state of the art shallow as well as deep classifiers like InceptionV3, Xception and VGG19 with an AUC value higher than 0.98."
abstract_short = "We introduce the use of a new optical density descriptor together with deep gaussian processes for cancer detection in histological prostate images. This combination outperforms the current state of the art in histopathology both shallow classifiers and deep neural networks like InceptionV3, Xception and VGG19 with an AUC value higher than 0.98. "
 
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
url_dataset = "https://cvblab.synology.me/PublicDatabases/SICAPv1.zip"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Paper", url = "https://link.springer.com/chapter/10.1007/978-3-030-33607-3_5"}]

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
