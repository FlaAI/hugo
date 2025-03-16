---
title: 'TSFool: Crafting Highly-Imperceptible Adversarial Time Series Through Multi-Objective Attack'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dehui Du
  - Haibo Hu
  - Zi Liang
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
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *27th European Conference on Artificial Intelligence (ECAI'24)*.
publication_short: In *27th European Conference on Artificial Intelligence (ECAI'24)*. **Oral.**

abstract: Recent years have witnessed the success of recurrent neural network (RNN) models in time series classification (TSC). However, neural networks (NNs) are vulnerable to adversarial samples, which cause real-life adversarial attacks that undermine the robustness of AI models. To date, most existing attacks target at feed-forward NNs and image recognition tasks, but they cannot perform well on RNN-based TSC. This is due to the cyclical computation of RNN, which prevents direct model differentiation. In addition, the high visual sensitivity of time series to perturbations also poses challenges to local objective optimization of adversarial samples. In this paper, we propose an efficient method called TSFool to craft highly-imperceptible adversarial time series for RNN-based TSC. The core idea is a new global optimization objective known as “Camouflage Coefficient” that captures the imperceptibility of adversarial samples from the class distribution. Based on this, we reduce the adversarial attack problem to a multi-objective optimization problem that enhances the perturbation quality. Furthermore, to speed up the optimization process, we propose to use a representation model for RNN to capture deeply embedded vulnerable samples whose features deviate from the latent manifold. Experiments on 11 UCR and UEA datasets showcase that TSFool significantly outperforms six white-box and three black-box benchmark attacks in terms of effectiveness, efficiency and imperceptibility from various perspectives including standard measure, human study and real-world defense.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA240644'
url_code: 'https://github.com/FlaAI/TSFool'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
url_slides: 'https://github.com/FlaAI/hugo/edit/main/content/publication/TSFool/TSFool.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: 'https://github.com/FlaAI/hugo/edit/main/content/publication/TSFool/TSFool.mp4'
---

