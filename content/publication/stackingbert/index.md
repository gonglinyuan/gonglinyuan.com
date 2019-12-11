---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient Training of BERT by Progressively Stacking"
authors: [
    "Linyuan Gong",
    "Di He",
    "Zhuohan Li",
    "Tao Qin",
    "Liwei Wang",
    "Tieyan Liu"
]
date: 2019-06-15T00:00:00+00:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-12-11T15:55:21+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "StackingBERT"
publication_short: "StackingBERT"

abstract: "Unsupervised pre-training is popularly used in natural language processing. By designing proper unsupervised prediction tasks, a deep neural network can be trained and shown to be effective in many downstream tasks. As the data is usually adequate, the model for pre-training is generally huge and contains millions of parameters. Therefore, the training efficiency becomes a critical issue even when using high-performance hardware. In this paper, we explore an efficient training method for the state-of-the-art bidirectional Transformer (BERT) model. By visualizing the self-attention distribution of different layers at different positions in a well-trained BERT model, we find that in most layers, the self-attention distribution will concentrate locally around its position and the start-of-sentence token. Motivating from this, we propose the stacking algorithm to transfer knowledge from a shallow model to a deep model; then we apply stacking progressively to accelerate BERT training. The experimental results showed that the models trained by our training strategy achieve similar performance to models trained from scratch, but our algorithm is much faster."

# Summary. An optional shortened abstract.
summary: "Visualize the self-attention distribution of BERT. Propose an iterative algorithm to train BERT faster."

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

url_pdf: "http://proceedings.mlr.press/v97/gong19a/gong19a.pdf"
url_code: "//github.com/gonglinyuan/StackingBERT"
url_dataset:
url_poster:
url_project:
url_slides: "//icml.cc/media/Slides/icml/2019/hallb(13-11-00)-13-12-15-4936-efficient_train.pdf"
url_source:
url_video:

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
