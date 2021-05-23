---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "splithalf: robust estimates of split half reliability"
authors: [Sam Parsons]
date: 2021-05-21T13:58:57+01:00
doi: "10.21105/joss.03041"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-23T01:01:01+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Open Source Software"
publication_short: "JOSS"

abstract: "The R package splithalf provides tools to estimate the internal consistency reliability of cognitive measures. In particular, the tools were developed for application to tasks that use difference scores as the main outcome measure, for instance the Stroop score or dot-probe attention bias index (average RT in incongruent trials minus average RT in congruent trials). The methods in splithalf are built around split half reliability estimation. To increase the robustness of these estimates, the package implements a permutation approach that takes a large number of random (without replacement) split halves of the data. For each permutation the correlation between halves is calculated, with the Spearman-Brown correction applied (Spearman, 1904). This process generates a distribution of reliability estimates from which we can extract and plot summary statistics (e.g. average and 95% HDI)."

# Summary. An optional shortened abstract.
summary: ""

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

url_pdf: https://joss.theoj.org/papers/10.21105/joss.03041
url_code: https://github.com/sdparsons/splithalf
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=FhqyKxH4kyk&t=24s

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
