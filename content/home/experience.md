+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experiences"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research Intern"
  company = "Machine Learning Group, Microsoft Research Asia"
  company_url = "//www.microsoft.com/en-us/research/lab/microsoft-research-asia/"
  location = "Beijing, China"
  date_start = "2018-07-10"
  date_end = "2019-06-07"
  description = """Advised by [Di He](https://scholar.google.co.jp/citations?user=orVoz4IAAAAJ&hl=en), [Tao Qin](https://www.microsoft.com/en-us/research/people/taoqin/), and [Jiang Bian](https://sites.google.com/site/jiangbianhome/)
- Researched self-supervised pre-training for natural languages.
- Reproduced [BERT](https://arxiv.org/abs/1810.04805) before Google released its code, wrote 6,800 lines of code.
- Proposed a faster and more computationally efficient pre-training algorithm for BERT, ran large-scale experiments for 10,000 GPU-hours, published our results on [ICML 2019](http://proceedings.mlr.press/v97/gong19a.html).
- Paper cited by Google [ALBERT](https://arxiv.org/pdf/1909.11942.pdf), codebase used by Bing team to train question-answering systems.
- Ranked first in four tasks of [WMT19](https://www.aclweb.org/anthology/W19-5348/) machine translation competition with our new technologies.
"""

[[experience]]
  title = "Research Intern"
  company = "Machine Learning Department, Carnegie Mellon University"
  company_url = "//www.ml.cmu.edu"
  location = "Pittsburgh, United States"
  date_start = "2019-06-25"
  date_end = "2019-09-08"
  description = """Advised by [Pradeep Ravikumar](https://www.cs.cmu.edu/~pradeepr/)
- Explored multiple approaches for clinical abbreviation expansion. Designed a new self-supervised pre-training algorithm, which outperforms the state-of-the-art on multiple datasets by a large margin, especially when the data is limited. Submitted to *ACL 2020*.
- Researched the application of machine learning in healthcare.
"""

[[experience]]
  title = "Research Intern"
  company = "Key Lab of Machine Perception (MOE), Peking University"
  company_url = "//www.microsoft.com/en-us/research/lab/microsoft-research-asia/"
  location = "Beijing, China"
  date_start = "2019-05-25"
  date_end = ""
  description = """Advised by [Liwei Wang](https://scholar.google.com/citations?user=VZHxoh8AAAAJ&hl=zh-CN)
- Proposed a Gram-Gauss-Newton optimization algorithm that converges better than SGD/Adam, where I sped up training by 3.5x by writing CUDA kernels and designed a communication algorithm that enables large-scale distributed training.
- Earlier results on small regression tasks: [arxiv.org/abs/1905.11675](https://arxiv.org/abs/1905.11675)
"""

+++
