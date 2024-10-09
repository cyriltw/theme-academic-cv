---
title: 'Disagreement Matters: Preserving Label Diversity by Jointly Modeling Item
  and Annotator Label Distributions with DisCo'
authors:
- Tharindu Cyril Weerasooriya
- Alexander G. Ororbia II
- Raj Bhensadadia
- Ashiqur KhudaBukhsh
- Christopher M. Homan
date: '2023-07-01'
publishDate: '2024-10-09T01:52:51.930856Z'
publication_types:
- paper-conference
publication: '*Findings of the Association for Computational Linguistics: ACL 2023*'
abstract: Annotator disagreement is common whenever human judgment is needed for supervised
  learning. It is conventional to assume that one label per item represents ground
  truth. However, this obscures minority opinions, if present. We regard ``ground
  truth″ as the distribution of all labels that a population of annotators could produce,
  if asked (and of which we only have a small sample). We next introduce DisCo (Distribution
  from Context), a simple neural model that learns to predict this distribution. The
  model takes annotator-item pairs, rather than items alone, as input, and performs
  inference by aggregating over all annotators. Despite its simplicity, our experiments
  show that, on six benchmark datasets, our model is competitive with, and frequently
  outperforms, other, more complex models that either do not model specific annotators
  or were not designed for label distribution learning.
links:
- name: URL
  url: https://aclanthology.org/2023.findings-acl.287
---
