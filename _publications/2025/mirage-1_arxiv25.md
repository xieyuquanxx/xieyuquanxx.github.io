---
title:          "Mirage-1: Augmenting and Updating GUI Agent with Hierarchical Multimodal Skills"
date:           2025-06-12 00:01:00 +0800
selected:       true
pub:            "Arxiv"
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Poster</span>'
pub_date:       "2025"

abstract: >-
    Recent efforts to leverage the Multi-modal Large Language Model (MLLM) as GUI agents have yielded promising outcomes. However, these agents still struggle with long-horizon tasks in online environments, primarily due to insufficient knowledge and the inherent gap between offline and online domains. In this paper, inspired by how humans generalize knowledge in open-ended environments, we propose a Hierarchical Multimodal Skills (HMS) module to tackle the issue of insufficient knowledge. It progressively abstracts trajectories into execution skills, core skills, and ultimately meta-skills, providing a hierarchical knowledge structure for long-horizon task planning. To bridge the domain gap, we propose the Skill-Augmented Monte Carlo Tree Search (SA-MCTS) algorithm, which efficiently leverages skills acquired in offline environments to reduce the action search space during online tree exploration. Building on HMS, we propose Mirage-1, a multimodal, cross-platform, plug-and-play GUI agent. To validate the performance of Mirage-1 in real-world long-horizon scenarios, we constructed a new benchmark, AndroidLH. Experimental results show that Mirage-1 outperforms previous agents by 32\%, 19\%, 15\%, and 79\% on AndroidWorld, MobileMiniWob++, Mind2Web-Live, and AndroidLH, respectively.

cover:          /assets/images/covers/optimus.png
authors:
  - <b>Yuquan Xie</b>
  - Zaijing Li
  - Rui Shao
  - Gongwei Chen
  - Kaiwen Zhou
  - Yinchun Li
  - Dongmei Jiang
  - Liqiang Nie
links:
  Paper: https://arxiv.org/abs/2506.10387
---
