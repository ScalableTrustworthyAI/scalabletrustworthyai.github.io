+++
title = "Trustworthy Machine Learning"
semester = "Winter Semester 2022-2023"
university = "University of Tübingen"
image = "DALLE_TML.png"
sort_position = 1
description = "As machine learning technology gets applied to actual products and solutions, new challenges have emerged. Models unexpectedly fail to generalise well to small changes in the distribution; some models are found to utilise sensitive features that could treat certain demographic user groups unfairly; models tend to be confident on novel types of data; models cannot communicate the rationale behind their decisions effectively with the end users like medical staff to maximise the human-machine synergies. Collectively, we face a trustworthiness issue with the current machine learning technology. A large fraction of the machine learning research nowadays is dedicated to expanding the frontier of Trustworthy Machine Learning (TML). The course covers a theoretical and technical background for key topics in TML. We conduct a critical review of important classical and contemporary research papers on related topics and provide hands-on practicals to implement TML techniques."
+++

### Lecturer

- [Seong Joon Oh](../../member/joon/)

### Tutors

- [Alexander Rubinstein](../../member/alex/)
- [Elif Akata](../../member/elif/)
- [Elisa Nguyen](../../member/elisa/)

### Central email

Please use the STAI group email `stai.there@gmail.com` to
- Submit your Colab exercises;
- Ask questions; and
- Send us feedback.

### Slack forum

Ask the lecturer or tutors to add you to the Slack channel. We need your name and email address. There, you can
- Ask questions and
- Send us feedback.

### Goal

1. Students will be able to critically read, assess, and discuss research work in Trustworthy Machine Learning (TML).
2. Students will gain the technical background to implement basic TML techniques in a deep learning framework.
3. Students will be ready to conduct their own research in TML and make contributions to the research community.

### Prerequisites

- Familiarity with Python and PyTorch coding.
- A pass grade from the Deep Learning Course (or equivalent).
- Basic knowledge of machine learning concepts.
- Basic maths: multivariate calculus, linear algebra, probability, statistics, and optimisation.

### Reading list

Recommended papers from each topic.

{{< details "OOD Generalisation" >}}
- Generalizing from a Few Examples: A Survey on Few-Shot Learning
- Generalizing to Unseen Domains: A Survey on Domain Generalization
- In Search of Lost Domain Generalization
- Underspecification Presents Challenges for Credibility in Modern Machine Learning
- Shortcut Learning in Deep Neural Networks
- Which Shortcut Cues Will DNNs Choose? A Study from the Parameter-Space Perspective
- Environment Inference for Invariant Learning
- ImageNet-trained CNNs are biased towards texture; increasing shape bias improves accuracy and robustness
{{< /details >}}

{{< details "Explainability" >}}
- Explanation in artificial intelligence: Insights from the social sciences
- Sanity Checks for Saliency Maps
- A benchmark for interpretability methods in deep neural networks
- Expanding Explainability: Towards Social Transparency in AI systems
- Human-Centered Explainable AI: Towards a Reflective Sociotechnical Approach
- Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps
- Axiomatic attribution for deep networks
- SmoothGrad: removing noise by adding noise
- A Unified Approach to Interpreting Model Predictions
- Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)
- Visualizing Deep Neural Network Decisions: Prediction Difference Analysis
- Learning Deep Features for Discriminative Localization
- Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization
- "Why Should I Trust You?": Explaining the Predictions of Any Classifier
- Feature Visualization
- Understanding Black-box Predictions via Influence Functions
- Estimating Training Data Influence by Tracing Gradient Descent
{{< /details >}}

{{< details "Uncertainty" >}}
- A Baseline for Detecting Misclassified and Out-of-Distribution Examples in Neural Networks
- On calibration of modern neural networks
- Deep Anomaly Detection with Outlier Exposure
- A Simple Unified Framework for Detecting Out-of-Distribution Samples and Adversarial Attacks
- Dropout as a Bayesian Approximation: Representing Model Uncertainty in Deep Learning
- Simple and Scalable Predictive Uncertainty Estimation using Deep Ensembles
- Loss Surfaces, Mode Connectivity, and Fast Ensembling of DNNs
- Averaging weights leads to wider optima and better generalization
- Efficient and scalable Bayesian neural nets with rank-1 factors
- What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?
- Addressing Failure Prediction by Learning Model Confidence
- Why M Heads are Better than One: Training a Diverse Ensemble of Deep Networks
- Multiple Choice Learning: Learning to Produce Multiple Structured Outputs
- DiverseNet: When One Right Answer is not Enough
{{< /details >}}

{{< details "Evaluation" >}}
- Question and Answer Test-Train Overlap in Open-Domain Question Answering Datasets
- A Metric Learning Reality Check
- Evaluating Weakly-Supervised Object Localization Methods Right
- Do ImageNet Classifiers Generalize to ImageNet?
- Challenging Common Assumptions in the Unsupervised Learning of Disentangled Representations.
- Realistic Evaluation of Deep Semi-Supervised Learning Algorithms
- Zero-Shot Learning-The Good, the Bad and the Ugly
- Sanity Checks for Saliency Maps
- In Search of Lost Domain Generalization
- Are We Learning Yet? A Meta-Review of Evaluation Failures Across Machine Learning
- How to avoid machine learning pitfalls: a guide for academic researchers
- Show Your Work: Improved Reporting of Experimental Results
{{< /details >}}

### Registration

We can take only 60 students for the course. The registration is on a first-come-first-served basis.

### Grading policy

![TML_grading](/img/grading_scheme.png)

The final grade is essentially based on your exam performance. However, to encourage the participation in the exercises,
we award bonus boosts on the final grade based on the exercise performance.

**Exercise 0 and admission to course**

- We admit only those who submit the zeroth exercise to the course.
- Exercise 0 is an individual exercise.

**Exercise 1-4 score E% (0 - 100%)**

- Average score from Exercises 1-4.
- Exercises 1-4 are group exercises.

**Admission to exam**

- When the exercise grade is $>60$%, you are granted the right to participate in the exam.
- Can take care of exceptional cases on an individual basis.

**Exam score (0 - 100%)**

- Based on your performance on your exam.
- The pass threshold for the course will be $\geq 50$% on the exam.
- When you cannot attend the first exam or have failed the first one, you may take the **make-up exam**.

**Final score (0 - 100%)**

- The final score is your exam score with possible increments from your exercise performance.
- Increment from exercise = $(E-60)/40 \times 20$%, where $E$% is your exercise score.
    - If $E=100$, you will get 20%p additional points on top of your exam grade.
    - If $E=60$, no additional points will be awarded.
    - If $E< 60$, you will not be admitted to the exam.
- Increments from exercise will not let you pass the course if your exam score is below $50\%$.

**Final grade (1,0 - 5,0)**

- The final grade of the course will be based on the final score.

### Lecture times

- Fridays
- 1st session: 14:15-15:00
- 5-min break: 15:00-15:05
- 2nd session: 15:05-15:50

### Tutorial times

- Fridays 16:00-18:00
- Up to discussion

### Exam dates

- Main exam: 21/02/2023 (tentative)
- Make-up exam: 11/04/2023 (tentative)

### Schedule & exercises

{{<table "table table-striped table-bordered">}}
|   #  	|   Date  	|   Content  	|   Exercises  	|   Lead tutor  	|
|---	|---	|---	|---	|---	|
|   L1  	|   21/10/2022  	|   Introduction  	|   [Exercise 0](TBD)   (Due: 28/10/2022)  	|   Alex  	|
|   L2  	|   28/10/2022  	|   OOD Generalisation - Definition and limitations  	|   [Exercise 1](TBD) (Due: 17/11/2022)  	|   Alex  	|
|   L3  	|   04/11/2022  	|   OOD Generalisation - Cue selection problem  	|     	|   Alex  	|
|   L4  	|   11/11/2022  	|   OOD Generalisation - Worst-case generalisation  	|     	|   Alex  	|
|   L5  	|   18/11/2022  	|   Explainability - Definition and limitations  	|   [Exercise 2](TBD) (Due: 08/12/2022)  	|   Elisa  	|
|   L6  	|   25/11/2022  	|   Explainability - Attribution  	|     	|   Elisa  	|
|   L7  	|   02/12/2022  	|   Explainability - Model explanation  	|     	|   Elisa  	|
|   L8  	|   09/12/2022  	|   Uncertainty - Definition and evaluation  	|   [Exercise 3](TBD) (Due: 26/01/2023)  	|   Elif  	|
|       	|                	|   Christmas Break  	|     	|     	|
|   L9  	|   13/01/2023  	|   Uncertainty - Epistemic uncertainty  	|     	|   Elif  	|
|   L10  	|   20/01/2023  	|   Uncertainty - Aleatoric uncertainty  	|     	|   Elif  	|
|   L11  	|   27/01/2023  	|   Evaluation - Concepts and definitions  	|   [Exercise 4](TBD) (Due: 09/02/2023)  	|   Elisa  	|
|   L12  	|   03/02/2023  	|   Evaluation - Weak & strong supervision  	|     	|   Elisa  	|
{{</table>}}
