+++
abstract = "Weakly-supervised object localization (WSOL) has gained popularity over the last years for its promise to train localization models with only image-level labels. Since the seminal WSOL work of class activation mapping (CAM), the field has focused on how to expand the attention regions to cover objects more broadly and localize them better. However, these strategies rely on full localization supervision to validate hyperparameters and for model selection, which is in principle prohibited under the WSOL setup. In this paper, we argue that WSOL task is ill-posed with only image-level labels, and propose a new evaluation protocol where full supervision is limited to only a small held-out set not overlapping with the test set. We observe that, under our protocol, the five most recent WSOL methods have not made a major improvement over the CAM baseline. Moreover, we report that existing WSOL methods have not reached the few-shot learning baseline, where the full-supervision at validation time is used for model training instead. Based on our findings, we discuss some future directions for WSOL."
date = "2020-06-01T00:00:00+00:00"
image = "choe2020cvpr.gif"
math = false
publication = "Conference on Computer Vision and Pattern Recognition"
publication_short = "CVPR"
selected = false
title = "Evaluating Weakly-Supervised Object Localization Methods Right"
url_code = "//github.com/clovaai/wsolevaluation"
url_dataset = ""
url_pdf = "//arxiv.org/abs/2001.07437"
url_project = ""
url_slides = "//coallaoh.github.io/data/choe2020cvpr_slides.pdf"
url_poster = ""
url_video = "//www.youtube.com/watch?v=D_dEkeb-fto&list=PLcD_yLvcdUll95mAnBDV0rZKhfClJMZMr&index=6"
url_bibtex = "//coallaoh.github.io/data/choe2020cvpr.txt"

[[authors]]
    name = "Junsuk Choe*"
    is_member = false
[[authors]]
    name = "Seong Joon Oh*"
    is_member = true
[[authors]]
    name = "Seungho Lee"
    is_member = false
[[authors]]
    name = "Sanghyuk Chun"
    is_member = false
[[authors]]
    name = "Zeynep Akata"
    is_member = false
[[authors]]
    name = "Hyunjung Shim"
    is_member = false
+++
