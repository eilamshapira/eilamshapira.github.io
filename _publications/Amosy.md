---
title: "Text2Model: Text-based Model Induction for Zero-shot Image Classification"
collection: publications
permalink: /publication/Text2Model
excerpt: 'We consider the problem of off-policy evaluation for human decision prediction in non-cooperative non-zero-sum games, collect an extensive novel dataset and present a simulation-based algorithm.'
date: 2024-10-27
# venue: 'Under Review'
paperurl: 'https://arxiv.org/abs/2210.15182'
citation: 'Ohad Amosy, Tomer Volk, <b>Eilam Shapira</b>, Eyal Ben-David, Roi Reichart, Gal Chechik (2024). "Text2Model: Text-based Model Induction for Zero-shot Image Classification".'
---

We address the challenge of building task-agnostic classifiers using only text descriptions, demonstrating a unified approach to image classification, 3D point cloud classification, and action recognition from scenes. Unlike approaches that learn a fixed representation of the output classes, we generate at inference time a model tailored to a query classification task. To generate task-based zero-shot classifiers, we train a hypernetwork that receives class descriptions and outputs a multi-class model. The hypernetwork is designed to be equivariant with respect to the set of descriptions and the classification layer, thus obeying the symmetries of the problem and improving generalization. Our approach generates non-linear classifiers and can handle rich textual descriptions. We evaluate this approach in a series of zero-shot classification tasks, for image, point-cloud, and action recognition, using a range of text descriptions: From single words to rich descriptions. Our results demonstrate strong improvements over previous approaches, showing that zero-shot learning can be applied with little training data. Furthermore, we conduct an analysis with foundational vision and language models, demonstrating that they struggle to generalize when describing what attributes the class lacks.

[Paper](https://arxiv.org/abs/2210.15182)