---
title: 'Meta Pattern Concern Score: A Novel Evaluation Measure with Human Values for Multi-classifiers'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dehui Du
  - Yuanhao Liu

# Author notes (optional)
author_notes:
  -
  - 'Corresponding Author'
  -

date: '2023-05-01T00:00:00Z'
# doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Conference on Systems, Man, and Cybernetics* (SMC'23).
publication_short: In *2023 IEEE International Conference on Systems, Man, and Cybernetics* (SMC'23)

abstract: While advanced classifiers have been increasingly used in real-world safety-critical applications, how to properly evaluate the black-box models given specific human values remains a concern in the community. Such human values include punishing error cases of different severity in varying degrees and making compromises in general performance to reduce specific dangerous cases. In this paper, we propose a novel evaluation measure named Meta Pattern Concern Score based on the abstract representation of probabilistic prediction and the adjustable threshold for the concession in prediction confidence, to introduce the human values into multi-classifiers. Technically, we learn from the advantages and disadvantages of two kinds of common metrics, namely the confusion matrix-based evaluation measures and the loss values, so that our measure is effective as them even under general tasks, and the cross entropy loss becomes a special case of our measure in the limit. Besides, our measure can also be used to refine the model training by dynamically adjusting the learning rate. The experiments on four kinds of models and six datasets confirm the effectiveness and efficiency of our measure. And a case study shows it can not only find the ideal model reducing 0.53% of dangerous cases by only sacrificing 0.04% of training accuracy, but also refine the learning rate to train a new model averagely outperforming the original one with a 1.62% lower value of itself and 0.36% fewer number of dangerous cases.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10394380'
url_code: 'https://github.com/FlaAI/MPCS'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: 'https://github.com/FlaAI/hugo/blob/main/content/publication/RNNWFA/RNNWFASlide.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://www.youtube.com/watch?v=Di7zFfocAvU'
---

