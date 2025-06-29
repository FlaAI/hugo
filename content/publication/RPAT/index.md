---
title: 'Failure Cases Are Better Learned But Boundary Says Sorry: Facilitating Smooth Perception Change for Accuracy-Robustness Trade-Off in Adversarial Training'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Li Liu

# Author notes (optional)
author_notes:
  -
  - 'Corresponding Author'

date: '2025-06-26T00:00:00Z'
# doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision (ICCV'25)*.
publication_short: In *International Conference on Computer Vision (ICCV'25)*. Accepted to appear

abstract: 'Adversarial Training (AT) is one of the most effective methods to train robust Deep Neural Networks (DNNs). However, AT creates an inherent trade-off between clean accuracy and adversarial robustness, which is commonly attributed to the more complicated decision boundary caused by the insufficient learning of hard adversarial samples. In this work, we reveal a counterintuitive fact for the first time: from the perspective of perception consistency, hard adversarial samples that can still attack the robust model after AT are already learned better than those successfully defended. Thus, different from previous views, we argue that it is rather the over-sufficient learning of hard adversarial samples that degrades the decision boundary and contributes to the trade-off problem. Specifically, the excessive pursuit of perception consistency would force the model to view the perturbations as noise and ignore the information within them, which should have been utilized to induce a smoother perception transition towards the decision boundary to support its establishment to an appropriate location. In response, we define a new AT objective named Robust Perception, encouraging the model perception to change smoothly with input perturbations, based on which we propose a novel Robust Perception Adversarial Training (RPAT) method, effectively mitigating the current accuracy-robustness trade-off. Experiments on CIFAR-10, CIFAR-100, and Tiny-ImageNet with ResNet-18, PreActResNet-18, and WideResNet-34-10 demonstrate the effectiveness of our method beyond four common baselines and 12 state-of-the-art (SOTA) works.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# url_pdf: 'https://arxiv.org/abs/2410.12671'
# url_code: 'https://github.com/FlaAI/DUCAT'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: 'https://github.com/FlaAI/hugo/blob/main/content/publication/TSFool/TSFool_Slide.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://github.com/FlaAI/hugo/edit/main/content/publication/TSFool/TSFool.mp4'
---

