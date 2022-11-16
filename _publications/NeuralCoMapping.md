---
title: "Multi-Robot Active Mapping via Neural Bipartite Graph Matching"
collection: publications
permalink: /publication/NeuralCoMapping
excerpt: 'Abstract We study the problem of multi-robot active mapping, which aims for complete scene map construction in minimum time steps. The key to this problem lies in the goal position estimation to enable more efficient robot movements. Previous approaches either choose the frontier as the goal position via a myopic solution that hinders the time efficiency, or maximize the long-term value via reinforcement learning to directly regress the goal position, but does not guarantee the complete map construction. In this paper, we propose a novel algorithm, namely NeuralCoMapping, which takes advantage of both approaches. We reduce the problem to bipartite graph matching, which establishes the node correspondences between two graphs, denoting robots and frontiers. We introduce a multiplex graph neural network (mGNN) that learns the neural distance to fill the affinity matrix for more effective graph matching. We optimize the mGNN with a differentiable linear assignment layer by maximizing the long-term values that favor time efficiency and map completeness via reinforcement learning. We compare our algorithm with several state-of-the-art multi-robot active mapping approaches and adapted reinforcement-learning baselines. Experimental results demonstrate the superior performance and exceptional generalization ability of our algorithm on various indoor scenes and unseen number of robots, when only trained with 9 indoor scenes.'
date: 2022-03-01
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2022/papers/Ye_Multi-Robot_Active_Mapping_via_Neural_Bipartite_Graph_Matching_CVPR_2022_paper.pdf'
citation: 'Ye, Kai, et al. &quot;Multi-Robot Active Mapping via Neural Bipartite Graph Matching.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition.</i> 2022.'
---

[Download paper here](https://openaccess.thecvf.com/content/CVPR2022/papers/Ye_Multi-Robot_Active_Mapping_via_Neural_Bipartite_Graph_Matching_CVPR_2022_paper.pdf)

[Code](https://github.com/siyandong/NeuralCoMapping)
