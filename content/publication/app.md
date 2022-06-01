+++
abstract = "With the latest advances in deep learning, there has been a lot of focus on the online learning paradigm due to its relevance in practical settings. Although many methods have been investigated for optimal learning settings in scenarios where the data stream is continuous over time, sparse networks training in such settings have often been overlooked. In this paper, we explore the problem of training a neural network with a target sparsity in a particular case of online learning: the anytime learning at macroscale paradigm (ALMA). We propose a novel way of progressive pruning, referred to as ${Anytime Progressive Pruning}$ (APP); the proposed approach significantly outperforms the baseline dense and Anytime OSP models across multiple architectures and datasets under short, moderate, and long-sequence training. Our method, for example, shows an improvement in accuracy of ≈ 7% and a reduction in the generalization gap by ≈ 22%, while being ≈ 1/3 rd the size of the dense baseline model in few-shot restricted imagenet training. We further observe interesting nonmonotonic transitions in the generalization gap in the high number of megabatches-based ALMA. The code and experiment dashboards can be accessed at [code](https://github.com/landskape-ai/Progressive-Pruning) and [wandb](https://wandb.ai/landskape/APP), respectively."
abstract_short = "Short version of abstract."
date = "2022-04-04"
image = ""
image_preview = ""
math = true
publication = "Preprint"
publication_short = ""
selected = false
title = "APP: Anytime Progressive Pruning"
url_code = "https://github.com/landskape-ai/Progressive-Pruning"
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/2204.01640.pdf"
url_project = ""
url_slides = ""
url_video = ""
url_custom = [{name = "Cite", url = "https://github.com/landskape-ai/Progressive-Pruning#cite"}, {name = "WandB dashboard", url = "https://wandb.ai/landskape/APP"}, {name = "Neural Scaling Laws course presentation", url = "https://bluejeans.com/playback/s/jFFH3X6y1UxAuLKW5kau2WRQHbMojKfpaySI6xGRQ56lqpaEmbdKsC9wBwWTJUag"}, {name = "MLC Research Jam #8", url = "https://youtu.be/GbHpaqwkgxE?t=924"}, {name = "Continual AI Seminar", url = "https://youtu.be/EZS2PzfyfXY"}]


[[authors]]
    name = "Diganta Misra"
    id = "diganta"
    is_member = true

[[authors]]
    name = "Bharat Runwal"
    id = "Bharat"
    is_member = true

[[authors]]
    name = "Tianlong Chen"
    is_member = false

[[authors]]
    name = "Zhangyang Wang"
    is_member = false

[[authors]]
    name = "Irina Rish"
    is_member = false
+++