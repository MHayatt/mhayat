+++
title = "Deeply Supervised Discriminative Learning for Adversarial Defense"
date = "2020-03-01"
authors = ["A. Mustafa","S. H Khan","M. Hayat","R. Goecke","J. Shen","L. Shao"]
tags = []
publication_types = ["2"]
publication = "_IEEE Transactions on Pattern Analysis and Machine Intelligence_"
publication_short = ""
summary = "<p style='text-align: justify;'> Deep neural networks can easily be fooled by an adversary using minuscule perturbations to input images. The existing defense techniques suffer greatly under white-box attack settings, where an adversary has full knowledge about the network and can iterate several times to find strong perturbations. We observe that the main reason for the existence of such vulnerabilities is the close proximity of different class samples in the learned feature space of deep models. This allows the model decisions to be totally changed by adding an imperceptible perturbation in the inputs. To counter this, we propose to class-wise disentangle the intermediate feature representations of deep networks specifically forcing the features for each class to lie inside a convex polytope that is maximally separated from the polytopes of other classes. In this manner, the network is forced to learn distinct and distant decision regions for each class. We observe that this simple constraint on the features greatly enhances the robustness of learned models, even against the strongest white-box attacks, without degrading the classification performance on clean images. We report extensive evaluations in both black-box and white-box attack scenarios and show significant gains in comparison to state-of-the-art defenses.</p>"
featured = false
projects = []
slides = ""
url_pdf = "/publication/mustafa2020deeply/manuscript.pdf"
url_code = "https://github.com/aamir-mustafa/pcl-adversarial-defense"
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

