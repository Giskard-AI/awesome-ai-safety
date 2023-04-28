# Awesome AI Safety [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![License](https://img.shields.io/github/license/Giskard-AI/awesome-ai-safety?color=blue)](./LICENSE)
[![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](./CONTRIBUTING.md)
[![Discord](https://img.shields.io/discord/939190303397666868?label=Discord)](https://gisk.ar/discord)
[![Mastodon](https://img.shields.io/mastodon/follow/109377499153541532?domain=https%3A%2F%2Ffosstodon.org&style=social)](https://fosstodon.org/@Giskard)
[![HitCount](https://hits.dwyl.com/Giskard-AI/awesome-ai-safety.svg?style=flat)](http://hits.dwyl.com/Giskard-AI/awesome-ai-safety)

Figuring out how to make your AI safer? How to avoid ethical biases, errors, privacy leaks or robustness issues in your AI models? 

This repository contains a curated list of papers & technical articles on AI Quality & Safety that should help 📚

## Table of Contents

You can browse papers by Machine Learning task category, and use hashtags like `#robustness` to explore AI risk types.

1. [Tabular Machine Learning](#tabular-machine-learning)
2. [Natural Language Processing](#natural-language-processing)
3. [Computer Vision](#computer-vision)
4. [Recommendation System](#recommendation-system)
5. [Time Series](#time-series)
6. [General ML Testing](#general-ml-testing)

## Tabular Machine Learning

* [Machine Learning Model Drift Detection Via Weak Data Slices](https://arxiv.org/pdf/2108.05319.pdf) (Ackerman et al., 2021) `#DataSlice` `#Debugging` `#Drift`
* [Automated Data Slicing for Model Validation: A Big Data - AI Integration Approach](https://ieeexplore.ieee.org/abstract/document/8713886) (Chung et al., 2020) `#DataSlice`
* [Interacting with Predictions: Visual Inspection of Black-box Machine Learning Models](https://dl.acm.org/doi/abs/10.1145/2858036.2858529) (Krause et al., 2016) `#Explainability`

## Natural Language Processing

* [Beyond Accuracy: Behavioral Testing of NLP Models with CheckList](http://homes.cs.washington.edu/~marcotcr/acl20_checklist.pdf) (Ribeiro et al., 2020) `#Robustness`
* [Pipelines for Social Bias Testing of Large Language Models](https://openreview.net/pdf/8be28761ea130113e3be7747870c434f53e9b309.pdf) (Nozza et al., 2022) `#Bias` `#Ethics`
* [Why Should I Trust You?": Explaining the Predictions of Any Classifier](https://arxiv.org/abs/1602.04938) (Ribeiro et al., 2016) `#Explainability`
* [A Unified Approach to Interpreting Model Predictions](https://arxiv.org/abs/1705.07874) (Lundberg et al., 2017) `#Explainability`
* [Anchors: High-Precision Model-Agnostic Explanations](https://homes.cs.washington.edu/~marcotcr/aaai18.pdf) (Ribeiro et al., 2018) `#Explanability`
* [Explanation-Based Human Debugging of NLP Models: A Survey](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00440/108932/Explanation-Based-Human-Debugging-of-NLP-Models-A) (Lertvittayakumjorn, et al., 2021) `#Debugging`
* [SEAL: Interactive Tool for Systematic Error Analysis and Labeling](https://arxiv.org/abs/2210.05839) (Rajani et al., 2022) `#DataSlice` `#Explainability`

### Large Language Models

* [Holistic Evaluation of Language Models](https://arxiv.org/abs/2211.09110) (Liang et al., 2022) `#General`
* [Learning to summarize from human feedback](https://proceedings.neurips.cc/paper/2020/file/1f89885d556929e98d3ef9b86448f951-Paper.pdf) (Stiennon et al., 2020) `#HumanFeedback`

## Computer Vision

* [DOMINO: Discovering Systematic Errors with Cross-modal Embeddings Domino](https://arxiv.org/pdf/2203.14960.pdf) (Eyuboglu et al., 2022) `#DataSlice`
* [Explaining in Style: Training a GAN to explain a classifier in StyleSpace](https://arxiv.org/pdf/2104.13369.pdf) (Lang et al., 2022) `#Robustness`
* [Model Assertions for Debugging Machine Learning](https://ddkang.github.io/papers/2018/omg-nips-ws.pdf) (Kang et al., 2018) `#Debugging`

## Recommendation System

[Contributions are welcome 💕](CONTRIBUTING.md)

## Time Series

[Contributions are welcome 💕](CONTRIBUTING.md)

## General ML Testing

* [Machine learning testing: Survey, landscapes and horizons](https://ieeexplore.ieee.org/abstract/document/9000651/) (Zhang et al., 2020) `#General`
* [Quality Assurance for AI-based Systems: Overview and Challenges](https://arxiv.org/abs/2102.05351) (Felderer et al., 2021) `#General`
* [Metamorphic testing of decision support systems: A case study](https://digital-library.theiet.org/content/journals/10.1049/iet-sen.2009.0084) (Kuo et al., 2010) `#Robustness`
* [A Survey on Metamorphic Testing](https://ieeexplore.ieee.org/document/7422146) (Segura et al., 2016) `#Robustness`
* [Testing and validating machine learning classifiers by metamorphic testing](https://www.sciencedirect.com/science/article/abs/pii/S0164121210003213) (Xie et al., 2011) `#Robustness`
* [The ML Test Score: A Rubric for ML Production Readiness and Technical Debt Reduction](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/aad9f93b86b7addfea4c419b9100c6cdd26cacea.pdf) (Breck et al., 2017) `#General`
* [The Disagreement Problem in Explainable Machine Learning: A Practitioner’s Perspective](https://arxiv.org/pdf/2202.01602.pdf) (Krishna et al., 2022) `#Explanability`
* [InterpretML: A Unified Framework for Machine Learning Interpretability](https://arxiv.org/abs/1909.09223) (Nori et al., 2019) `#Explainability` `#General`