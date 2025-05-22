---
title: 'New Paradigm of Adversarial Training: Breaking Inherent Trade-Off between Accuracy and Robustness via Dummy Classes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Li Liu
  - Zi Liang
  - Yi R. (May) Fung
  - Qingqing Ye
  - Haibo Hu

# Author notes (optional)
author_notes:
  -
  - 'Corresponding Author'
  - 
  -
  - 
  - 

date: '2024-05-22T00:00:00Z'
# doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: ArXiv Preprint.
publication_short: ArXiv Preprint

abstract: 'Adversarial Training (AT) is recognized as one of the most effective methods to enhance the robustness of Deep Neural Networks (DNNs). However, existing AT methods suffer from an inherent trade-off between adversarial robustness and clean accuracy, which seriously hinders their real-world deployment. Previous works have studied this trade-off within the current AT paradigm, exploring various factors such as perturbation intensity, label noise and class margin. Despite these efforts, current AT methods still typically experience a reduction in clean accuracy by over 10% to date, without significant improvements in robustness compared with simple baselines like PGD-AT. This inherent trade-off raises a question: whether the current AT paradigm, which assumes to learn the corresponding benign and adversarial samples as the same class, inappropriately combines clean and robust objectives that may be essentially inconsistent. In this work, we surprisingly reveal that up to 40% of CIFAR-10 adversarial samples always fail to satisfy such an assumption across various AT methods and robust models, explicitly indicating the improvement room for the current AT paradigm. Accordingly, to relax the tension between clean and robust learning derived from this overstrict assumption, we propose a new AT paradigm by introducing an additional dummy class for each original class, aiming to accommodate the hard adversarial samples with shifted distribution after perturbation. The robustness w.r.t. these adversarial samples can be achieved by runtime recovery from the predicted dummy classes to their corresponding original ones, eliminating the compromise with clean learning. Building on this new paradigm, we propose a novel plug-and-play AT technology named DUmmy Classes-based Adversarial Training (DUCAT). Extensive experiments on CIFAR-10, CIFAR-100, and Tiny-ImageNet demonstrate that the DUCAT concurrently improves clean accuracy and adversarial robustness compared with state-of-the-art benchmarks, effectively releasing the existing inherent trade-off.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2410.12671'
url_code: 'https://github.com/FlaAI/DUCAT'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: 'https://github.com/FlaAI/hugo/blob/main/content/publication/TSFool/TSFool_Slide.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://github.com/FlaAI/hugo/edit/main/content/publication/TSFool/TSFool.mp4'
---

