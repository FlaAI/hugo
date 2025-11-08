---
title: 'Revitalizing Canonical Pre-Alignment for Irregular Multivariate Time Series Forecasting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ziyu Zhou
  - Yiming Huang
  - admin
  - Yuankai Wu
  - James Kwok
  - Yuxuan Liang


# Author notes (optional)
author_notes:
  -
  - 
  - 
  -
  - 
  - 'Corresponding Author'

date: '2025-09-23T00:00:00Z'
# doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *AAAI Conference on Artificial Intelligence (AAAI'26)*.
publication_short: In *AAAI Conference on Artificial Intelligence (AAAI'26)*. Accepted to appear

abstract: 'Irregular multivariate time series (IMTS), characterized by uneven sampling and inter-variate asynchrony, fuel many forecasting applications yet remain challenging to model efficiently. Canonical Pre-Alignment (CPA) has been widely adopted in IMTS modeling by padding zeros at every global timestamp, thereby alleviating inter-variate asynchrony and unifying the series length, but its dense zero-padding inflates the pre-aligned series length, especially when numerous variates are present, causing prohibitive compute overhead. Recent graph-based models with patching strategies sidestep CPA, but their local message passing struggles to capture global inter-variate correlations. Therefore, we posit that CPA should be retained, with the pre-aligned series properly handled by the model, enabling it to outperform state-of-the-art graph-based baselines that sidestep CPA. Technically, we propose KAFNet, a compact architecture grounded in CPA for IMTS forecasting that couples (1) Pre-Convolution module for sequence smoothing and sparsity mitigation, (2) Temporal Kernel Aggregation module for learnable compression and modeling of intra-series irregularity, and (3) Frequency Linear Attention blocks for the low-cost inter-series correlations modeling in the frequency domain. Experiments on multiple IMTS datasets show that KAFNet achieves state-of-the-art forecasting performance, with a 7.2x parameter reduction and a 8.4x training-inference acceleration.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/abs/2508.01971'
# url_code: ''
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: 'https://github.com/FlaAI/hugo/blob/main/content/publication/TSFool/TSFool_Slide.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://github.com/FlaAI/hugo/edit/main/content/publication/TSFool/TSFool.mp4'
---

