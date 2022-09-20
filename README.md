# On Steering Multi-Annotations per Sample for Multi-task Learning

Author: Yuanze Li, Yiwen Guo, Qizhang Li, Hongzhi Zhang and Wangmeng Zuo

Code release for ["On Steering Multi-Annotations per Sample for Multi-task Learning"](https://arxiv.org/abs/2203.02946)

Abstract:

The study of multi-task learning has drawn great attention from the community. Despite the remarkable progress, the challenge of optimally learning different tasks simultaneously remains to be explored. Previous works attempt to mitigate this issue by accounting the information of batch-level losses or gradients while do not balance from the exemplar level.In this paper, we introduce Stochastic Task Allocation~(STA), a sampling mechanism which randomly samples a subset of tasks for every exemplar independently. The exemplar-level conflicts disappear when STA only samples one task. For solving the weak supervised issue, we propose Interleaved Stochastic Task Allocation~(ISTA) to iteratively allocate all tasks to each example during several consecutive iterations.We evaluate STA and ISTA on various datasets and applications: NYUv2, Cityscapes, and COCO for scene understanding and instance segmentation. Our experimental results show both STA and ISTA outperform current state-of-the-art methods. 
