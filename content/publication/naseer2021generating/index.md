+++
title = "On Generating Transferable Targeted Perturbations"
date = "2021-08-01"
authors = ["M. Naseer", "S. Khan", "M. Hayat", "F. Khan", "F. Porikli"]
tags = []
publication_types = ["1"]
publication = "_Proceedings of the IEEE International Conference on Computer Vision_ **(ICCV 2021)**"
publication_short = ""
summary = "<p style='text-align: justify;'> While the untargeted black-box transferability of adversarial perturbations has been extensively studied before, changing an unseen model's decisions to a specific targeted class remains a challenging feat. In this paper, we propose a new generative approach for highly transferable targeted perturbations. We note that the existing methods are less suitable for this task due to their reliance on class-boundary information that changes from one model to another, thus reducing transferability. In contrast, our approach matches the perturbed image `distribution' with that of the target class, leading to high targeted transferability rates. To this end, we propose a new objective function that not only aligns the global distributions of source and target images, but also matches the local neighbourhood structure between the two domains. Based on the proposed objective, we train a generator function that can adaptively synthesize perturbations specific to a given input. Our generative approach is independent of the source or target domain labels, while consistently performs well against state-of-the-art methods on a wide range of attack settings. As an example, we achieve 32.63% target transferability from (an adversarially weak) VGG19BN to (a strong) WideResNet on ImageNet val. set, which is 4x higher than the previous best generative attack and 16x better than instance-specific iterative attack.  </p>"
featured = true
projects = []
slides = ""
url_pdf = "https://arxiv.org/abs/2103.14641"
url_code = "https://github.com/Muzammal-Naseer/TTP"
url_dataset = ""
url_poster = ""
url_slides = ""
url_source = ""
url_video = ""
math = true
highlight = true
[image]
image = ""
caption = ""
+++

