+++
title = "Semantic-Aware Domain Generalized Segmentation"
date = "2022-06-01"
authors = ["D. Peng","Y. Lei","M. Hayat","Y. Guo","W. Li"]
tags = []
publication_types = ["1"]
publication = "_Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition_ **(CVPR 2022)**"
publication_short = ""
summary = " <p style='text-align: justify;'> Deep models trained on source domain lack generalization when evaluated on unseen target domains with different data distributions. The problem becomes even more pronounced when we have no access to target domain samples for adaptation. In this paper, we address domain generalized semantic segmentation, where a segmentation model is trained to be domain-invariant without using any target domain data. Existing approaches to tackle this problem standardize data into a unified distribution. We argue that while such a standardization promotes global normalization, the resulting features are not discriminative enough to get clear segmentation boundaries. To enhance separation between categories while simultaneously promoting domain invariance, we propose a framework including two novel modules: Semantic-Aware Normalization (SAN) and Semantic-Aware Whitening (SAW). Specifically, SAN focuses on category-level center alignment between features from different image styles, while SAW enforces distributed alignment for the already center-aligned features. With the help of SAN and SAW, we encourage both intra-category compactness and inter-category separability. We validate our approach through extensive experiments on widely-used datasets (i.e. GTAV, SYNTHIA, Cityscapes, Mapillary and BDDS). Our approach shows significant improvements over existing state-of-the-art on various backbone networks.  </p>"
featured = true
projects = []
slides = ""
url_pdf = "/publication/peng2022semantic/manuscript.pdf"
url_code = "https://github.com/leolyj/SAN-SAW"
url_dataset = ""
url_poster = ""
url_slides = ""
url_source = ""
# url_video = "https://www.youtube.com/watch?v=41XKXY--7_E"
math = true
highlight = true
[image]
image = ""
caption = ""
+++

