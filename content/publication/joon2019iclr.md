+++
abstract = "Instance embeddings are an efficient and versatile image representation that facilitates applications like recognition, verification, retrieval, and clustering. Many metric learning methods represent the input as a single point in the embedding space. Often the distance between points is used as a proxy for match confidence. However, this can fail to represent uncertainty arising when the input is ambiguous, e.g., due to occlusion or blurriness. This work addresses this issue and explicitly models the uncertainty by hedging the location of each input in the embedding space. We introduce the hedged instance embedding (HIB) in which embeddings are modeled as random variables and the model is trained under the variational information bottleneck principle. Empirical results on our new N-digit MNIST dataset show that our method leads to the desired behavior of hedging its bets across the embedding space upon encountering ambiguous inputs. This results in improved performance for image matching and classification tasks, more structure in the learned embedding space, and an ability to compute a per-exemplar uncertainty measure that is correlated with downstream performance."
date = "2019-04-01T00:00:00+00:00"
image = "joon2019iclr.png"
math = false
publication = "International Conference on Learning Representations"
publication_short = "ICLR"
selected = false
title = "Modeling Uncertainty with Hedged Instance Embedding"
url_code = ""
url_dataset = ""
url_pdf = "//arxiv.org/abs/1810.00319"
url_project = ""
url_poster = "//coallaoh.github.io/data/oh2019iclr_poster.pdf"
url_video = ""
url_bibtex = "//coallaoh.github.io/data/joon2019iclr.txt"

[[authors]]
    name = "Seong Joon Oh"
    is_member = true
[[authors]]
    name = "Kevin Murphy"
    is_member = false
[[authors]]
    name = "Jiyan Pan"
    is_member = false
[[authors]]
    name = "Joseph Roth"
    is_member = false
[[authors]]
    name = "Florian Schroff"
    is_member = false
[[authors]]
    name = "Andrew Gallagher"
    is_member = false
+++