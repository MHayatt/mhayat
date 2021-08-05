+++
title = "Orthogonal Projection Loss"
date = "2021-10-01"
authors = ["A. Mustafa","S. Khan","M. Hayat","R. Goecke","J. Shen","L. Shao"]
tags = []
publication_types = ["1"]
publication = "_Proceedings of the IEEE International Conference on Computer Vision_ **(ICCV 2021)**"
publication_short = ""
summary = "<p style='text-align: justify;'> 
Deep neural networks have achieved remarkable performance on a range of classification tasks, with softmax cross-entropy (CE) loss emerging as the de-facto objective function. The CE loss encourages features of a class to have a higher projection score on the true class-vector compared to the negative classes. However, this is a relative constraint and does not explicitly force different class features to be well-separated. Motivated by the observation that ground-truth class representations in CE loss are orthogonal (one-hot encoded vectors), we develop a novel loss function termed “Orthogonal Projection Loss” (OPL) which imposes orthogonality in the feature space. OPL augments the properties of CE loss and directly enforces inter-class separation alongside intra-class clustering in the feature space through orthogonality constraints on the mini-batch level. As compared to other alternatives of CE, OPL offers unique advantages e.g., no additional learnable parameters, does not require careful negative mining and is not sensitive to the batch size. Given the plug-and-play nature of OPL, we evaluate it on a diverse range of tasks including image recognition (CIFAR-100), large-scale classification (ImageNet), domain generalization (PACS) and few-shot learning (miniImageNet, CIFAR-FS, tiered-ImageNet and Meta-dataset) and demonstrate its effectiveness across the board. Furthermore, OPL offers better robustness against practical nuisances such as adversarial attacks and label noise. </p>"
featured = true
projects = []
slides = ""
url_pdf = "/publication/ranasinghe2021orthogonal/manuscript.pdf"
url_code = "https://github.com/kahnchana/opl"
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

