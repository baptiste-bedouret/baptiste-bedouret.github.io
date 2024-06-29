---
layout: post
title: 'Projet 9: Parallel computing'
---

The aim of this project was to improve the quality of Renault's services for its clients by the aid of Generative AI. Opinions expressed by clients in Google reviews are analyzed and the objective is to detect in verbatim the category of Renault service to which the comment refers and the sentiment polarity of the opinion. To accomplish this task, a pre-trained Large Language Model  named Mistral was used. By the implementation of fine tuning techniques and the use of ICL for the prompt template, the model generated answers. In the end, our results demonstrate the model's ability to detect sentiment associated with each review. For the categories, we observed that it was much more difficult to match them with the ground truth categories due to the model's need to discern them from a list of 72 predefined categories.


{% include image.html url="https://github.com/baptiste-bedouret/Parallel_Computing" image="projects/proj-8/renault.png" %}
