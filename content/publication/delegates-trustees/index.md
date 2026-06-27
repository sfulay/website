---
title: "From Delegates to Trustees: How Optimizing for Long-Term Interests Shapes Bias and Alignment in LLMs"
authors:
- admin
- Jocelyn Zhu
- Michiel Bakker
date: "2026-03-24"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-03-24"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Chapter of the Association for Computational Linguistics (EACL) 2026*
publication_short: In *EACL 2026*

abstract: "Large language models (LLMs) have shown promising accuracy in predicting survey responses and policy preferences, which has increased interest in their potential to represent human interests in various domains. Most existing research has focused on \"behavioral cloning\", effectively evaluating how well models reproduce individuals' expressed preferences. Drawing on theories of political representation, we highlight an underexplored design trade-off: whether AI systems should act as delegates, mirroring expressed preferences, or as trustees, exercising judgment about what best serves an individual's interests. This trade-off is closely related to issues of LLM sycophancy, where models can encourage behavior or validate beliefs that may be aligned with a user's short-term preferences, but is detrimental to their long-term interests. Through a series of experiments simulating votes on various policy issues in the U.S. context, we apply a temporal utility framework that weighs short and long-term interests (simulating a trustee role) and compare voting outcomes to behavior-cloning models (simulating a delegate). We find that trustee-style predictions weighted toward long-term interests produce policy decisions that align more closely with expert consensus on well-understood issues, but also show greater bias toward models' default stances on topics lacking clear agreement. These findings reveal a fundamental trade-off in designing AI systems to represent human interests. Delegate models better preserve user autonomy but may diverge from well-supported policy positions, while trustee models can promote welfare on well-understood issues yet risk paternalism and bias."

# Summary. An optional shortened abstract.
summary: "Examining how optimizing LLMs for long-term interests shapes bias and alignment."

# tags:
# - AI Alignment
# - LLMs
# - Political Bias

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://aclanthology.org/2026.eacl-long.239.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
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
