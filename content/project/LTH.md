+++
date = "2022-01-01"
title = "APP: Anytime Progressive Pruning"
description = ""
short_description = "Progressive pruning deep networks in anytime learning regime"
project_id = "LTH1"
picture = "projects/DACL.jpg"
external_link = ""
participants_block_position = "down"
include_participants_portraits = true
sort_position = 2

[[participants]]
    name = "Diganta Misra"
    id = "diganta"

[[participants]]
    name = "Bharat Runwal"
    id = "Bharat"

+++

**Ongoing Project**

## Abstract

With the latest advancements in deep learning, there has been a lot of focus on the online learning paradigm due to its relevance in industrial and practical settings. While many methods have been investigated for optimal learning settings in scenarios where the data stream is continuous over time, training sparse networks in such settings have often been overlooked. In this paper, we explore the problem statement of training a neural network with a target sparsity in a subbranch of online learning, specifically the anytime learning paradigm, and propose a novel way of progressive pruning that we term Anytime Progressive Pruning(APP), which strongly outperforms the baseline dense and Anytime OSP models across multiple architectures and datasets under short, moderate, and long sequence training. Our method, for instance, demonstrates an accuracy improvement of ≈7% and reduction of the generalization gap by ≈34% while being ≈1/3rd the size of the baseline dense model on CIFAR-100. We further support our results by investigating the regularization effect induced by APP, which we hypothesize to be the primary reason for the drastic reduction of the generalization gap and observe interesting non-monotonic phase transitions in long sequence-based training.

## References:

[1] Frankle, Jonathan, and Michael Carbin. "The lottery ticket hypothesis: Finding sparse, trainable neural networks." arXiv preprint arXiv:1803.03635 (2018).

[2] Caccia, Lucas, Jing Xu, Myle Ott, Marc'Aurelio Ranzato, and Ludovic Denoyer. "On Anytime Learning at Macroscale." arXiv preprint arXiv:2106.09563 (2021).

[3] Lee, Namhoon, Thalaiyasingam Ajanthan, and Philip HS Torr. "Snip: Single-shot network pruning based on connection sensitivity." arXiv preprint arXiv:1810.02340 (2018).