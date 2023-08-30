+++
abstract = "In the era of foundation models with huge pre-training budgets, the downstream tasks have been shifted to the narrative of efficient and fast adaptation. For classification-based tasks in the domain of computer vision, the two most efficient approaches have been linear probing (LP) and visual prompting/reprogramming (VP); the former aims to learn a classifier in the form of a linear head on the features extracted by the pre-trained model, while the latter maps the input data to the domain of the source data on which the model was originally pre-trained on. Although extensive studies have demonstrated the differences between LP and VP in terms of downstream performance, we explore the capabilities of the two aforementioned methods via the sparsity axis: (a) Data sparsity: the impact of few-shot adaptation and (b) Model sparsity: the impact of lottery tickets (LT). We demonstrate that LT are not universal reprogrammers, i.e., for certain target datasets, reprogramming an LT yields significantly lower performance than the reprogrammed dense model although their corresponding upstream performance is similar. Further, we demonstrate that the calibration of dense models is always superior to that of their lottery ticket counterparts under both LP and VP regimes. Our empirical study opens a new avenue of research into VP for sparse models and encourages further understanding of the performance beyond the accuracy achieved by VP under constraints of sparsity. Code and logs can be accessed at [url](https://github.com/landskape-ai/Reprogram_LT)."
abstract_short = "Short version of abstract."
date = "2023-08-29"
image = ""
image_preview = ""
math = true
publication = "Preprint"
publication_short = "ArXiv"
selected = false
title = "Reprogramming under constraints: Revisiting efficient and reliable transferability of lottery tickets"
url_code = "https://github.com/landskape-ai/Reprogram_LT"
url_dataset = ""
url_pdf = "https://arxiv.org/abs/2308.14969"
url_project = ""
url_slides = ""
url_video = ""
url_custom = [{name = "Cite", url = "https://github.com/landskape-ai/Reprogram_LT#cite"}, {name = "WandB dashboard", url = "https://wandb.ai/landskape/Reprogram-Sparse"}]


[[authors]]
    name = "Diganta Misra"
    id = "diganta"
    is_member = true

[[authors]]
    name = "Agam Goyal"
    is_member = false

[[authors]]
    name = "Bharat Runwal"
    id = "Bharat"
    is_member = true

[[authors]]
    name = "Pin Yu Chen"
    is_member = false
+++