+++
abstract = "The class activation mapping, or CAM, has been the cornerstone of feature attribution methods for multiple vision tasks. Its simplicity and effectiveness have led to wide applications in the explanation of visual predictions and weakly-supervised localization tasks. However, CAM has its own shortcomings. The computation of attribution maps relies on ad-hoc calibration steps that are not part of the training computational graph, making it difficult for us to understand the real meaning of the attribution values. In this paper, we improve CAM by explicitly incorporating a latent variable encoding the location of the cue for recognition in the formulation, thereby subsuming the attribution map into the training computational graph. The resulting model, class activation latent mapping, or CALM, is trained with the expectation-maximization algorithm. Our experiments show that CALM identifies discriminative attributes for image classifiers more accurately than CAM and other visual attribution baselines. CALM also shows performance improvements over prior arts on the weakly-supervised object localization benchmarks."
date = "2021-10-01T00:00:00+00:00"
image = "kim2021iccv.png"
math = false
publication = "International Conference on Computer Vision"
publication_short = "ICCV"
selected = false
title = "Keep CALM and Improve Visual Feature Attribution"
url_code = "//github.com/naver-ai/calm"
url_dataset = ""
url_pdf = "//arxiv.org/abs/2106.07861"
url_project = ""
url_poster = ""
url_bibtex = "//coallaoh.github.io/data/kim2021iccv.txt"

[[authors]]
    name = "Jae Myung Kim*"
    is_member = false
[[authors]]
    name = "Junsuk Choe*"
    is_member = false
[[authors]]
    name = "Zeynep Akata"
    is_member = false
[[authors]]
    name = "Seong Joon Oh"
    is_member = false
+++
