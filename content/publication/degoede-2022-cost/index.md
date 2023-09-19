---
title: "The Cost of Reinforcement Learning for Game Engines: The AZ-Hive Case-study"
authors:
  - Danilo de Goede
  - Duncan Kampert
  - Ana Lucia Varbanescu
date: "2022-04-09T00:00:00Z"
doi: ""

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Performance Engineering ([ICPE 2022](https://icpe2022.spec.org/))"
publication_short: ""

abstract: Although utilising computers to play board games has been a topic of research for many decades, the recent rapid developments in the field of reinforcement learning - like AlphaZero and variants - brought unprecedented progress in games such as chess and Go. However, the efficiency of this process remains unknown. In this work, we analyse the cost and efficiency of the AlphaZero approach when building a new game engine. Thus, we present our experience building AZ-Hive, an AlphaZero-based playing engine for the game of Hive. Using only the rules of the game and a quality of play assessment, AZ-Hive learns to play the game from scratch. Getting AZ-Hive up and running requires encoding the game in AlphaZero, i.e., capturing the board, the game state, the rules and the assessment of play-quality. And different encodings lead to significantly different AZ-Hive engines, with very different performance results. Thus, we propose a design space for configuring AZ-Hive, and demonstrate the costs and benefits of different configurations in this space. We find that different configurations lead to a less or more competitive playing-engine, but the training and evaluation for different such engines is prohibitively expensive. Moreover, no systematic, efficient exploration or pruning of the space is possible. In turn, an exhaustive exploration can easily take tens of training-years.

# Summary. An optional shortened abstract.
summary: We analyse the cost and efficiency of the AlphaZero approach when building a new game engine. Thus, we present our experience building AZ-Hive, an AlphaZero-based playing engine for the game of Hive.

tags:
- Energy efficiency 
- Reinforcement learning
- AlphaZero: Hive
- Game-playing engines
- Computational cost
- Design space exploration
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3489525.3511685
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
# slides: example
---
