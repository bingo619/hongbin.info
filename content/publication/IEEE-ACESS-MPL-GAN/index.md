+++
title = "MPL-GAN: Towards Realistic Meteorological Predictive Learning Using Conditional GAN"
date = 2020-05-18T19:31:57+10:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Hong-Bin Liu**", "Ickjai Lee"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEEE ACCESS"
publication_short = "IEEE ACCESS"

# Abstract.
abstract = "Meteorological imagery prediction is an important and challenging problem for weather forecasting. It can also be seen as a video frame prediction problem that estimates future frames based on observed meteorological imageries. Despite it is a widely-investigated problem, it is still far from being solved. Current state-of-the-art deep learning based approaches mainly optimise the mean square error loss resulting in blurry predictions. We address this problem by introducing a Meteorological Predictive Learning GAN model (in short MPL-GAN) that utilises the conditional GAN along with the predictive learning module in order to handle the uncertainty in future frame prediction. Experiments on a real-world dataset demonstrate the superior performance of our proposed model. Our proposed model is able to map the blurry predictions produced by traditional mean square error loss based predictive learning methods back to their original data distributions, hence it is able to improve and sharpen the prediction. In particular, our MPL-GAN achieves an average sharpness of 52.82, which is 14% better than the baseline method. Furthermore, our model correctly detects the meteorological movement patterns that traditional unconditional GANs fail to do."
#abstract = "Trajectory classification is a fundamental problem of location-based services with many real world applications such as travel mode classification, animal mobility detection, and location recommendation. In the literature, many approaches have been proposed to solve this task including some deep learning models like LSTM recently for sequence classification. However, these approaches have drawbacks, either treating spatial and temporal information as a whole or omitting the temporal information. Moreover, some models like Time-LSTM, have been proposed to handle the temporal information in the trajectory but do not take into account spatial information. We argue that spatio-temporal information is crucial for the trajectory classification task and should be further studied. Consequently, we propose a trajectory classifier called Spatio-temporal GRU (in short ST-GRU) to better model the spatio-temporal correlations. We introduce a novel segmented convolutional weight mechanism for capturing short-term local spatial correlations in trajectories and proposes an additional temporal gate to control the information flow related to the temporal information. Our approach has achieved the state-of-the-art performance in the trajectory classification task (especially for the travel mode classification task)."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1109/ACCESS.2020.2995187"

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
url_pdf = "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9094665"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "Bibtex", url = "files/mpl-gan-access.bib"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
