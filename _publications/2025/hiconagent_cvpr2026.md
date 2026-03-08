---
title:          "HiconAgent: History Context-aware Policy Optimization for GUI Agents"
date:           2026-03-1 00:01:00 +0800
selected:       true
pub:            "Proceedings of the Computer Vision and Pattern Recognition Conference (CVPR)"
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Poster</span>'
pub_date:       "2026"

abstract: >-
  Graphical User Interface (GUI) agents require effective use of historical context to perform sequential navigation tasks. While incorporating past actions and observations can improve decision making, naive use of full history leads to excessive computational overhead and distraction from irrelevant information. To address this, we introduce HiconAgent, a GUI agent trained with History Context-aware Policy Optimization (HCPO) for efficient and effective utilization of historical information. HCPO optimizes history usage in both sampling and policy updates through two complementary components: (1) Dynamic Context Sampling (DCS) presents the agent with variable length histories during sampling, enabling adaptive use of the most relevant context; (2) Anchor-guided History Compression (AHC) refines the policy update phase with a dual branch strategy where the compressed branch removes history observations while keeping history actions as information flow anchors. The compressed and uncompressed branches are coupled through a history-enhanced alignment loss to enforce consistent history usage while maintaining efficiency. Experiments on mainstream GUI navigation benchmarks demonstrate strong performance. Despite being smaller, HiconAgent-3B outperforms GUI-R1-7B by +8.46 percent grounding accuracy and +11.32 percent step success rate on GUI-Odyssey, while achieving comparable results on AndroidControl and AITW with up to 2.47x computational speedup and 60 percent FLOPs reduction.



# cover:          /assets/images/covers/optimus.png
authors:
  - Xurui Zhou
  - Gongwei Chen
  - <b>Yuquan Xie</b>
  - Zaijing Li
  - Kaiwen Zhou
  - Shuai Wang
  - Shuo Yang
  - Zhuotao Tian
  - Rui Shao
links:
  Paper: https://github.com/JiuTian-VL/HiconAgent
  Code: https://github.com/JiuTian-VL/HiconAgent
---
