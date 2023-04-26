---
layout: post
title: Our paper was accepted to ICLR 2023.
date: 2023-04-26 16:00:00+0900
inline: false
related_posts: false
---

Our paper "<a href="https://iclr.cc/Conferences/2023/Schedule?showEvent=11163">This Looks Like It Rather Than That: ProtoKNN For Similarity-Based Classifiers</a>" was accepted to <a href="https://iclr.cc/Conferences/2023">ICLR2023</a>.

***

### This Looks Like It Rather Than That: ProtoKNN For Similarity-Based Classifiers

*Yuki Ukai · Tsubasa Hirakawa · Takayoshi Yamashita · Hironobu Fujiyoshi*

In International Conference on Learning Representations (ICLR), 2023

#### Abstract

Among research on the interpretability of deep learning models, the 'this looks like that' framework with ProtoPNet has attracted significant attention. By combining the strong power of deep learning models with the interpretability of case-based inference, ProtoPNet can achieve high accuracy while keeping its reasoning process interpretable. Many methods based on ProtoPNet have emerged to take advantage of this benefit, but despite their practical usefulness, they run into difficulty when utilizing similarity-based classifiers, e.g., in domains where unknown class samples exist. This is because ProtoPNet and its variants adopt the training process specific to linear classifiers, which allows the prototypes to represent useful image features for class recognition. Due to this difficulty, the effectiveness of similarity-based classifiers (e.g., k-nearest neighbor (KNN)) on the 'this looks like that' framework have not been sufficiently examined. To alleviate this problem, we propose ProtoKNN, an extension of ProtoPNet that adopts KNN classifiers. Extensive experiments on multiple open datasets demonstrate that the proposed method can achieve competitive results with a state-of-the-art method.
