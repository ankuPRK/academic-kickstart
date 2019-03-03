+++
title = "An online algorithm for constrained face clustering in videos"
date = 2018-10-03T04:58:32+05:30

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Prakhar Kulshreshtha", "Tanaya Guha"]

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
publication = "2018 25th IEEE International Conference on Image Processing"
publication_short = "ICIP"

# Abstract.
abstract = "We address the problem of face clustering in long, real world videos. This is a challenging task because faces in such videos exhibit wide variability in scale, pose, illumination, expressions, and may also be partially occluded. The majority of the existing face clustering algorithms are offline, i.e., they assume the availability of the entire data at once. However, in many practical scenarios, complete data may not be available at the same time or may be too large to process or may exhibit significant variation in the data distribution over time. We propose an online clustering algorithm that processes data sequentially in short segments of variable length. The faces detected in each segment are either assigned to an existing cluster or are used to create a new one. Our algorithm uses several spatiotemporal constraints, and a convolutional neural network (CNN) to obtain a robust representation of the faces in order to achieve high clustering accuracy on two benchmark video databases (82.1% and 93.8%). Despite being an online method (usually known to have lower accuracy), our algorithm achieves comparable or better results than state-of-the-art offline and online methods."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "http://tanayag.com/Pub_files/Kulshreshtha_Online_face.pdf"
url_preprint = ""
url_code = "https://github.com/ankuPRK/COFC"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "https://github.com/ankuPRK/COFC/blob/master/ICIP/kulshreshtha_ICIP_poster.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Overview of the Online Face Clustering algorithm"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
