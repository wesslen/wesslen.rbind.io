+++
title = "Towards rapid interactive machine learning: evaluating tradeoffs of classification without representation"
date = 2019-03-15T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dustin Arendt","Emily Saldanha","Ryan Wesslen","Svitlana Volkova","Wenwen Dou"]

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
publication = "In *Proceedings of the 24th International Conference on Intelligent User Interfaces (IUI)*, ACM."
publication_short = "In *IUI*"

# Abstract and optional shortened version.
abstract = "Our contribution is the design and evaluation of an interactive machine learning interface that rapidly provides the user with model feedback after every interaction. To address visual scalability, this interface communicates with the user via a 'tip of the iceberg' approach, where the user interacts with a small set of recommended instances for each class. To address computational scalability, we developed an O (n) classification algorithm that incorporates user feedback incrementally, and without consulting the data's underlying representation matrix. Our computational evaluation showed that this algorithm has similar accuracy to several off-the-shelf classification algorithms with small amounts of labeled data. Empirical evaluation revealed that users performed better using our design compared to an equivalent active learning setup."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["visual interactive labeling","interactive machine learning","active learning","representation-free classifier"]

# Links (optional).
url_pdf = "files/p591-arendt.pdf"
url_preprint = ""
url_code = "https://github.com/pnnl/chissl"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++