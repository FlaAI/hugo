---
title: 'TSFool: Crafting Highly-imperceptible Adversarial Time Series through Multi-objective Black-box Attack to Fool RNN Classifiers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dehui Du
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

abstract: Neural network (NN) classifiers are vulnerable to adversarial attacks. Although the existing gradient-based attacks achieve state-of-the-art performance in feed-forward NNs and image recognition tasks, they do not perform as well on time series classification with recurrent neural network (RNN) models. This is because the cyclical structure of RNN prevents direct model differentiation and the visual sensitivity of time series data to perturbations challenges the traditional local optimization objective of the adversarial attack. In this paper, a black-box method called TSFool is proposed to efficiently craft highly-imperceptible adversarial time series for RNN classifiers. We propose a novel global optimization objective named Camouflage Coefficient to consider the imperceptibility of adversarial samples from the perspective of class distribution, and accordingly refine the adversarial attack as a multi-objective optimization problem to enhance the perturbation quality. To get rid of the dependence on gradient information, we also propose a new idea that introduces a representation model for RNN to capture deeply embedded vulnerable samples having otherness between their features and latent manifold, based on which the optimization solution can be heuristically approximated. Experiments on 10 UCR datasets are conducted to confirm that TSFool averagely outperforms existing methods with a 46.3% higher attack success rate, 87.4% smaller perturbation and 25.6% better Camouflage Coefficient at a similar time cost.

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

