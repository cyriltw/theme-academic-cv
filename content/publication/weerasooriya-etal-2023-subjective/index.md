---
title: 'Subjective Crowd Disagreements for Subjective Data: Uncovering Meaningful
  CrowdOpinion with Population-level Learning'
authors:
- Tharindu Cyril Weerasooriya
- Sarah Luger
- Saloni Poddar
- Ashiqur KhudaBukhsh
- Christopher M. Homan
date: '2023-07-01'
publishDate: '2024-10-09T01:52:51.922774Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)*'
abstract: Human-annotated data plays a critical role in the fairness of AI systems,
  including those that deal with life-altering decisions or moderating human-created
  web/social media content. Conventionally, annotator disagreements are resolved before
  any learning takes place. However, researchers are increasingly identifying annotator
  disagreement as pervasive and meaningful. They also question the performance of
  a system when annotators disagree. Particularly when minority views are disregarded,
  especially among groups that may already be underrepresented in the annotator population.
  In this paper, we introduce CrowdOpinion, an unsupervised learning based approach
  that uses language features and label distributions to pool similar items into larger
  samples of label distributions. We experiment with four generative and one density-based
  clustering method, applied to five linear combinations of label distributions and
  features. We use five publicly available benchmark datasets (with varying levels
  of annotator disagreements) from social media (Twitter, Gab, and Reddit). We also
  experiment in the wild using a dataset from Facebook, where annotations come from
  the platform itself by users reacting to posts. We evaluate CrowdOpinion as a label
  distribution prediction task using KL-divergence and a single-label problem using
  accuracy measures.
links:
- name: URL
  url: https://aclanthology.org/2023.acl-long.54
---
