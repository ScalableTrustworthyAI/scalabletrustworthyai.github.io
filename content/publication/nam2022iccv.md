+++
abstract = "The favorable performance of Vision Transformers (ViTs) is often attributed to the multi-head self-attention (MSA). The MSA enables global interactions at each layer of a ViT model, which is a contrasting feature against Convolutional Neural Networks (CNNs) that gradually increase the range of interaction across multiple layers. We study the role of the density of the attention. Our preliminary analyses suggest that the spatial interactions of attention maps are close to dense interactions rather than sparse ones. This is a curious phenomenon, as dense attention maps are harder for the model to learn due to steeper softmax gradients around them. We interpret this as a strong preference for ViT models to include dense interaction. We thus manually insert the uniform attention to each layer of ViT models to supply the much needed dense interactions. We call this method Context Broadcasting, CB. We observe that the inclusion of CB reduces the degree of density in the original attention maps and increases both the capacity and generalizability of the ViT models. CB incurs negligible costs: 1 line in your model code, no additional parameters, and minimal extra operations."
date = "2023-07-01T00:00:00+00:00"
image = "nam2022iccv.png"
math = false
publication = "International Conference on Computer Vision"
publication_short = "ICCV"
selected = false
title = "Scratching Visual Transformer's Back with Uniform Attention"
url_code = ""
url_dataset = ""
url_pdf = "//arxiv.org/abs/2210.08457"
url_project = ""
url_video = ""
url_bibtex = "//coallaoh.github.io/data/nam2022iccv.txt"

[[authors]]
    name = "Hyeon-Woo Nam"
    is_member = false
[[authors]]
    name = "Yu-Ji Kim"
    is_member = false
[[authors]]
    name = "Byeongho Heo"
    is_member = false
[[authors]]
    name = "Dongyoon Han"
    is_member = false
[[authors]]
    name = "Seong Joon Oh"
    is_member = true
    id = "joon"
[[authors]]
    name = "Tae-Hyun Oh"
    is_member = false
+++
