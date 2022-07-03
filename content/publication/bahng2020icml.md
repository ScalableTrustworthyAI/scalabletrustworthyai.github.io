+++
abstract = "Many machine learning algorithms are trained and evaluated by splitting data from a single source into training and test sets. While such focus on in-distribution learning scenarios has led to interesting advancement, it has not been able to tell if models are relying on dataset biases as shortcuts for successful prediction (e.g., using snow cues for recognising snowmobiles), resulting in biased models that fail to generalise when the bias shifts to a different class. The cross-bias generalisation problem has been addressed by de-biasing training data through augmentation or re-sampling, which are often prohibitive due to the data collection cost (e.g., collecting images of a snowmobile on a desert) and the difficulty of quantifying or expressing biases in the first place. In this work, we propose a novel framework to train a de-biased representation by encouraging it to be different from a set of representations that are biased by design. This tactic is feasible in many scenarios where it is much easier to define a set of biased representations than to define and quantify bias. We demonstrate the efficacy of our method across a variety of synthetic and real-world biases; our experiments show that the method discourages models from taking bias shortcuts, resulting in improved generalisation."
date = "2020-07-01T00:00:00+00:00"
image = "bahng2020icml.png"
math = false
publication = "International Conference on Machine Learning"
publication_short = "ICML"
selected = false
title = "Learning De-biased Representations with Biased Representations"
url_code = "//github.com/clovaai/rebias"
url_dataset = ""
url_pdf = "//arxiv.org/abs/1910.02806"
url_project = ""
url_slides = ""
url_poster = ""
url_video = "//www.youtube.com/watch?v=lkjMxZDGubA"
url_bibtex = "//coallaoh.github.io/data/hyojin2020icml.txt"

[[authors]]
    name = "Hyojin Bahng"
    is_member = false
[[authors]]
    name = "Sanghyuk Chun"
    is_member = false
[[authors]]
    name = "Sangdoo Yun"
    is_member = false
[[authors]]
    name = "Jaegul Choo"
    is_member = false
[[authors]]
    name = "Seong Joon Oh"
    is_member = true
+++
