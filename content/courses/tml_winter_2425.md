+++
title = "Trustworthy Machine Learning"
semester = "Winter Semester 2024-2025"
university = "University of Tübingen"
image = "compass-2024.jpeg"
sort_position = 1
description = "As machine learning technology gets applied to actual products and solutions, new challenges have emerged. Models unexpectedly fail to generalise well to small changes in the distribution; some models are found to utilise sensitive features that could treat certain demographic user groups unfairly; models tend to be confident on novel types of data; models cannot communicate the rationale behind their decisions effectively with the end users like medical staff to maximise the human-machine synergies. Collectively, we face a trustworthiness issue with the current machine learning technology. A large fraction of the machine learning research nowadays is dedicated to expanding the frontier of Trustworthy Machine Learning (TML). The course covers a theoretical and technical background for key topics in TML. We conduct a critical review of important classical and contemporary research papers on related topics and provide hands-on practicals to implement TML techniques."
+++

## Overview

### Goal

1. Students will be able to critically read, assess, and discuss research work in Trustworthy Machine Learning (TML).
2. Students will gain the technical background to implement basic TML techniques in a deep learning framework.
3. Students will be ready to conduct their own research in TML and make contributions to the research community.

### Prerequisites

- Familiarity with Python and PyTorch coding.
- A pass grade from the Deep Learning Course (or equivalent).
- Basic knowledge of machine learning concepts.
- Basic maths: multivariate calculus, linear algebra, probability, statistics, and optimisation.

## TML Book

Last year's course materials are now a book. You can find it here: https://trustworthyml.io/. It's also on arXiv: https://arxiv.org/abs/2310.08215.

Special thanks to [Bálint](../../member/balint/) for the majority of the work. Also, kudos to last year's tutors: [Alex](../../member/alex/), [Elisa](../../member/elisa/), and [Michael](../../member/michael/).

Note: The course materials are updated yearly to stay aligned with the latest research. The book will be useful for the TML24/25 course. However, it won't cover new topics added to the course.


## Policies

### Registration & Exercise 0

The **registration** link is here: https://forms.gle/7YbUM4dSHeBgVUeB8. We start accepting registration from **30 September 2024 at 12:00 (noon)** Central European Time (Berlin time).

Upon registration, you will get access to Exercise 0.
The Exercise 0 is an individual exercise and will be based on the prerequisite materials for the course.
Students who wish to enrol must submit their work on Exercise 0.
The necessary prerequisite materials will be taught in the first lecture.
Exercise 0 serves two purposes:
- For us to admit students who are sufficiently motivated for the course.
- For you to gauge your own readiness for the course.

Submit Exercise 0 by **23 October 2024**. **If you do not submit Exercise 0, we'll assume that you do not wish to register for the course and the exams.**

The timeline for registration is as follows:
- 30.09.2024 at 12:00 (noon): Register for the course ([link](https://forms.gle/NQ8ZgqZhZadkG1dq6)).
- 30.09.2024 - 23.10.2024: Work on Exercise 0 and submit. 

### Grading policy

![TML_grading](/img/TML2324-policy.png)

The final grade is essentially based on your exam performance. However, to encourage the participation in the exercises,
we award top-ups on the final grade based on the exercise performance.
We make sure, though, that it is still possible to get the maximal performance (grade 1,0) even without any top-up from the exercises.

**Exercise 0**

- Submission of Exercise 0 is the minimal requirement for taking the exam.

**Exercise 1-3 average score E (0 - 100%)**

- Average score from Exercises 1-3.
- Exercises 1-3 are group exercises.

**Admission to exam**

- When you have submitted Exercise 0 and the average score for Exercises 1-3 is $E\geq 60$%, you are granted the right to sit the exam.

**Exam score X (0 - 100%)**

- Based on your performance on your exam.
- The pass threshold for the course will be $X\geq 50$% on the exam, independent of the exercise performance.
- There will be two exams: Exam 1 and Exam 2.
    - Case A: Sit Exam 1 and pass → Exam 1 score will be final (cannot sit Exam 2).
    - Case B: Sit Exam 1 and fail → You may sit Exam 2; Exam 2 score will be final.
    - Case C: Choose to skip Exam 1 and take Exam 2 → Exam 2 score will be final.


**Final score S (0 - 100%)**

- The final score is your exam score with possible increments from your exercise performance.
- Top-up from exercise: $T=(E-60$%$)/40$%$\times 10$%p, where $E$ is your average exercise score.
- The final score is clipped at 100%: $S=\min (100$%$, X+T)$.
- Examples:
    - If $E=100$% and $X=100$%, there will be no further top-up from the exercise scores $S=100$%.
    - If $E=100$% and $X=80$%, you will get $T=$ 10%p additional points on top of your exam grade $S=90$%.
    - If $E=100$% and $X=45$%, you may still fail the course because of the minimal requirement for passing the exam $X\geq 50$%.
    - If $E=60$%, no additional points will be awarded $T=0$.
    - If $E< 60$%, you will not be admitted to the exam.

**Final grade G (1,0 - 5,0)**

- The mapping from final score to final grade $S\mapsto G$ is determined after each exam, taking the overall difficulty of the exam into account.

### Use of Language Models

Students may use language models for exercises. If you choose to do so, please follow the guideline below.

- **Transparency**: Clearly specify the language models you’ve used. Identify the text or code generated by these models.
- **Verification and Academic Integrity**: Validate the model’s output rigorously. Ensure it reflects your intentions and understanding of the subject. You’re responsible for its accuracy. In case the model's output contains someone else's work, failing to provide appropriate references will breach academic integrity rules.
- **Diversity and Personal Touch**: Language models often yield less diverse responses. Add your unique perspectives and solutions to enrich your work. This reduces the risk of identical solutions, which could lead to suspicions of copied work among students.
- **Critical Thinking**: Language models can reinforce existing thoughts, even incorrect ones. Don’t use them as your primary source for verification.


## Communication

### Lecturer

- [Joon](../../member/joon/)

### Tutors

- [Johannes](../../member/johannes/): OOD Generalisation
- [Ankit](../../member/ankit/): Explainability
- [Lennart](../../member/lennart/): Uncertainty

### Central email

Please use the STAI group email `stai.there@gmail.com` to
- Submit your Colab exercises;
- Ask questions; and
- Send us feedback.

### Discord forum

For those who're registered for the course, ask the lecturer or tutors to add you to the Discord channel. We need your name and email address. Use it for

- Asking questions;
- Sending us feedback;
- Receiving official announcements; and
- Communicating others (e.g. finding exercise group members).

## When & where

### Lecture & tutorial location and time

**Lecture**: Hörsaal TTR2 (Cyber Valley / Tübingen AI Center - TTR2) ([Maria-von-Linden-Straße 6](https://maps.app.goo.gl/T8vaWib3FYsuTfCn7))

- Thursdays
- 1st session: 12:15-13:00
- 5-min break: 13:00-13:05
- 2nd session: 13:05-13:50

**Tutorial**: Hörsaal TTR2 (Cyber Valley / Tübingen AI Center - TTR2) ([Maria-von-Linden-Straße 6](https://maps.app.goo.gl/T8vaWib3FYsuTfCn7))

- Thursdays 14:00-16:00

### Exam dates and locations

- Exam 1: Tuesday 11.02.2025 13:00 - 15:00, Location TBD.
- Exam 2: Thursday 10.04.2025 13:00 - 15:00 (not confirmed yet), Location TBD.

## Schedule & exercises

{{<table "table table-striped table-bordered">}}
|   #   |   Date    |   Lecture content     |   Exercises   | Tutorial session |
|---    |---    |---    |---    |---    |
|    -      |   30/09/2024   |   -      |   [Exercise 0](https://www.kaggle.com/code/seongjoonoh/0-prelim) (Due:23.10.2024) - [Joon](../../member/joon/)  | - |
|   L1      |   17/10/2024   |   [Introduction](https://docs.google.com/presentation/d/149sqUybRkRFL-MJ1AbX9c7LNUkwGvVmbcIChj-u5Ozw/edit) - [Video](https://youtu.be/OoLAafHghGQ)   |   -  | - |
|   L2      |   24/10/2024   |   OOD Generalisation (Definitions & underspecification) - Video   |   Exercise 1 (Due:20.11.2024) - [Johannes](../../member/johannes/)  | [Johannes](../../member/johannes/): Introduce Exercise 1 |
|   L3      |   31/10/2024   |   OOD Generalisation (Cue selection methods) - Video   |   -   | [Joon](../../member/joon/): Recap Exercise 0 |
|   L4      |   07/11/2024   |   OOD Generalisation (Domain generalisation & adversarial ML) - Video   |   -  | [Johannes](../../member/johannes/): Co-working / Q&A |
|   L5      |   14/11/2024   |   OOD Generalisation (Attacking LLMs) & Explainability (Definitions) - Video   |   Exercise 2 (Due:11.12.2024) - [Ankit](../../member/ankit/)   | [Ankit](../../member/ankit/): Introduce Exercise 2<br>[Johannes](../../member/johannes/): Co-working / Q&A  |
|   L6      |   21/11/2024   |   Explainability (Feature attribution) - Video   |   -  |  [Ankit](../../member/ankit/): Co-working / Q&A  |
|   L7      |   28/11/2024   |   Explainability (Feature attribution, Training data attribution) - Video   |   -   | [Johannes](../../member/johannes/): Recap Exercise 1 |
|   L8      |   05/12/2024   |   Explainability (Training data attribution) - Video   |   -   | [Ankit](../../member/ankit/): Co-working / Q&A |
|   L9      |   09/01/2024   |   Uncertainty (Definitions & evaluation) - Video   |   Exercise 3 (Due:29.01.2025) - [Lennart](../../member/lennart/)   | [Lennart](../../member/lennart/): Introduce Exercise 3 |
|   L10     |   16/01/2024   |   Uncertainty (Evaluation, Epistemic uncertainty) - Video   |   -   | [Ankit](../../member/ankit/): Recap Exercise 2 |
|   L11     |   23/01/2024   |   Uncertainty (Aleatoric uncertainty, Factorisation) - Video   |   -   | [Lennart](../../member/lennart/): Co-working / Q&A |
|   L12     |   30/01/2024   |   Conclusion (Exam, Final topics, Research at STAI) - Video   |   -   | [Lennart](../../member/lennart/): Co-working / Q&A |
|      -    |   06/02/2024   |   -   |   -   | [Lennart](../../member/lennart/): Recap Exercise 3 |
{{</table>}}

