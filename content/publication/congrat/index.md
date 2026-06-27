---
title: "ConGraT: Self-Supervised Contrastive Pretraining for Joint Graph and Text Embeddings"
authors:
- William Brannon
- Wonjune Kang
- admin
- Hang Jiang
- Brandon Roy
- Jad Kabbara
- Deb Roy
date: "2024-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Association for Computational Linguistics (ACL) 2024 TextGraphs Workshop*"
publication_short: "*ACL 2024 TextGraphs Workshop*"

abstract: "We propose ConGraT(Contrastive Graph-Text pretraining), a general, self-supervised method for jointly learning separate representations of texts and nodes in a parent (or ``supervening'') graph, where each text is associated with one of the nodes. Datasets fitting this paradigm are common, from social media (users and posts), to citation networks over articles, to link graphs over web pages. We expand on prior work by providing a general, self-supervised, joint pretraining method, one which does not depend on particular dataset structure or a specific task. Our method uses two separate encoders for graph nodes and texts, which are trained to align their representations within a common latent space. Training uses a batch-wise contrastive learning objective inspired by prior work on joint text and image encoding. As graphs are more structured objects than images, we also extend the training objective to incorporate information about node similarity and plausible next guesses in matching nodes and texts. Experiments on various datasets reveal that ConGraT outperforms strong baselines on various downstream tasks, including node and text category classification and link prediction."

# Summary. An optional shortened abstract.
summary: "We propose a contrastive method to jointly learn graph and text embeddings."

# tags:
# - Source Themes
featured: true

# links:
# - name: Arxiv 2023
#   url: 'https://arxiv.org/abs/2305.14321'
url_pdf: 'https://arxiv.org/abs/2305.14321'
url_code: 'https://github.com/wwbrannon/congrat'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
