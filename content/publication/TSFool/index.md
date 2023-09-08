---
title: 'TSFool: Crafting Highly-Imperceptible Adversarial Time Series through Multi-Objective Gray-Box Attack'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dehui Du
  - Haibo Hu
  - Yuanhao Liu

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-02T00:00:00Z'
# doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: ArXiv preprint
publication_short: ArXiv preprint

abstract: Recent years have witnessed the success of recurrent neural network (RNN) models in time series classification (TSC). However, neural networks (NNs) are vulnerable to adversarial samples, and cause real-life adversarial attacks that undermine AI technologies. But to date, most existing attacks target at feed-forward NNs and image recognition tasks, and they do not perform well on RNN-based TSC. This is due to the cyclical computation of RNN, which prevents direct model differentiation. In addition, the high visual sensitivity of time series data to perturbations also poses challenges to the conventional local objective optimization of adversarial samples. In this paper, a gray-box method called TSFool is proposed to efficiently craft highly-imperceptible adversarial time series for RNN-based TSC. We propose a novel global optimization objective known as "Camouflage Coefficient" to capture the imperceptibility of adversarial samples from the perspective of class distribution. Based on this, we refine the adversarial attack as a multi-objective optimization problem to enhance the perturbation quality. Furthermore, to speed up this optimization process, we also propose a representation model for RNN to capture deeply embedded vulnerable samples whose features deviate from the latent manifold. Experiments on 11 UCR and UEA datasets are conducted to showcase that TSFool significantly outperforms five white-box or black-box benchmark methods in terms of effectiveness and imperceptibility from real-world human studies.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2209.06388.pdf'
url_code: 'https://github.com/FlaAI/TSFool'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: 'https://github.com/FlaAI/hugo/blob/main/content/publication/RNNWFA/RNNWFASlide.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://www.youtube.com/watch?v=Di7zFfocAvU'
---

