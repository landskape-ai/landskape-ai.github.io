+++
date = "2022-03-03"
title = "AP/GP: Anytime Progressive Growing + Pruning"
description = "Progressive Growing and Pruning for ALMA."
short_description = ""
project_id = "AP/GP"
picture = "projects/apgp.jpg"
external_link = ""
participants_block_position = "down"
include_participants_portraits = true
sort_position = 1

[[participants]]
    name = "Richeek Das"
    id = "richeek"

[[participants]]
    name = "Diganta Misra"
    id = "diganta"

[[participants]]
    name = "Bharat Runwal"
    id = "Bharat"

+++

**Ongoing Project**

## Abstract

In this work, we propose effective and efficient solutions in regards to the issues presented in Misra et al. (2022) "APP: Anytime Progressive Pruning". Precisely, we propose a new algorithm "Anytime Progressive Pruning + Growing" (AP/GP) that solves the issue of APP with no replay and high target sparsity while inducing similar regularization effect as that of APP. The proposed algorithm takes advantage of progressive growing and pruning techniques to achieve the same effective target sparsity as that of APP while not requiring the prior knowledge of the total number of megabatches in the stream.

## References:

[1] Misra, Diganta, Bharat Runwal, Tianlong Chen, Zhangyang Wang, and Irina Rish. "APP: Anytime Progressive Pruning." arXiv preprint arXiv:2204.01640 (2022).

[2] Caccia, Lucas, Jing Xu, Myle Ott, Marc'Aurelio Ranzato, and Ludovic Denoyer. "On Anytime Learning at Macroscale." arXiv preprint arXiv:2106.09563 (2021).

[3] Chen, Tianlong, Zhenyu Zhang, Pengjun Wang, Santosh Balachandra, Haoyu Ma, Zehao Wang, and Zhangyang Wang. "Sparsity Winning Twice: Better Robust Generaliztion from More Efficient Training." arXiv preprint arXiv:2202.09844 (2022).