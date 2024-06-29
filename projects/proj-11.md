---
layout: post
title: 'Projet 11: NLP'
---

The aim of this project is to explore the BERT tokenizer and embeddings. First, IMDb data was loaded and the sequences were tokenized (with padding). Then, a few tokens that appear several times in the data were chosen and their embeddings were visualized (with t-SNE) at the input, at the output, and in one of the middle layers. Finally, utterance embeddings were visualized.

In another part, a basic classification model was developed where each utterance is represented as a single embedding, and a feed-forward classifier was built on top. Additionally, an LSTM classifier was constructed.


{% include image.html url="https://github.com/baptiste-bedouret/Machine-Learning-for-NLP" image="projects/proj-11/NLP.png" %}
