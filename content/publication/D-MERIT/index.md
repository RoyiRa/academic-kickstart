---
# Documentation: Conjunct Resolution in The Face of Verbal Omissions

title: "Evaluating D-MERIT of Partial-annotation on Information Retrieval"
authors: ["Royi Rassin", "Yaron Fairstein", "Oren Kalinsky", "Guy Kushilevitz", "Nachshon Cohen", "Alexander Libov", "Yoav Goldberg"]
               
date: 2023-06-15
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-03T15:16:19+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Evaluating D-MERIT of Partial-annotation on Information Retrieval"
publication_short: ""

abstract: "Retrieval models are often evaluated on partially-annotated datasets. Each query is mapped to a few relevant texts and the remaining corpus is assumed to be irrelevant. As a result, models that successfully retrieve false negatives are punished in evaluation. Unfortunately, completely annotating all texts for every query is not resource efficient. In this work, we show that using partially-annotated datasets in evaluation can paint a distorted picture. We curate D-MERIT, a passage retrieval evaluation set from Wikipedia, aspiring to contain all relevant passages for each query. Queries describe a group (e.g., ``journals about linguistics'') and relevant passages are evidence that entities belong to the group (e.g., a passage indicating that Language is a journal about linguistics). We show that evaluating on a dataset containing annotations for only a subset of the relevant passages might result in misleading ranking of the retrieval systems and that as more relevant texts are included in the evaluation set, the rankings converge. We propose our dataset as a resource for evaluation and our study as a recommendation for balance between resource-efficiency and reliable evaluation when annotating evaluation sets for text retrieval."



# Summary. An optional shortened abstract.
summary: "This work curates D-MERIT, a passage retrieval evaluation set from Wikipedia, aspiring to contain all relevant passages for each query, and proposes it as a resource for evaluation and a recommendation for balance between resource-efficiency and reliable evaluation when annotating evaluation sets for text retrieval."
tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/abs/2406.16048"
url_code: "https://drive.google.com/drive/folders/1g64CFSuSIJIf8q57WjkJhfp_-S6eu7_A"
url_dataset:
url_poster:
url_project:
url_slides: ""
url_source:
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
