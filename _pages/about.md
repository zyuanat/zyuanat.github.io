---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# 👋 About Me
Hi, I am Zheng YUAN, a second-year Ph.D. student (since 2023.09) in [DEEP Lab](https://www4.comp.polyu.edu.hk/~xiaohuang/deeplab.html) at The Hong Kong Polytechnic University ([PolyU](https://www.polyu.edu.hk/)), Department of Computing, under the supervision of Prof. [Xiao HUANG](https://www4.comp.polyu.edu.hk/~xiaohuang/). I received a B.E. from Shenzhen University ([SZU](https://en.szu.edu.cn/)), Computer Science and Technology, supervised by Prof. [Weike PAN](https://csse.szu.edu.cn/staff/panwk/).

My current research interests focus on **Large Language Models (LLMs) and their applications in data-driven scenarios**, including **Retrieval-Augmented Generation (RAG)**, **Natural Language to SQL Query (Text-to-SQL)**, and **Recommender Systems (RecSys)**.

📧 yzheng[dot]yuan[at]connect[dot]polyu[dot]hk

<span class='anchor' id='-news'></span>
# 🔥 News

- *2025.10*: 🎉🎉 Our paper **"Knapsack Optimization-based Schema Linking for LLM-based Text-to-SQL Generation"** is accepted by ICDE 2026.
- *2025.09*: 🎉🎉 Our paper **"Neuro-symbolic Entity Alignment via Variational Inference"** is accepted by NeurIPS 2025.
- *2025.09*: 🎉🎉 Our text-to-SQL survey **"Next-Generation Database Interfaces: A Survey of LLM-based Text-to-SQL"** is accepted by TKDE 2025.
- *2025.08*: 🎉🎉 Our paper **"Exploring the Limits of Text-Based Collaborative Filtering Using LLMs: Discoveries and Insights"** is accepted by CIKM 2025.
- *2025.02*: 🔥🔥 Our Graph-RAG survey **"A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models"** has been released. Take a look!
- *2024.05*: 🎉🎉 Our paper **"Knowledge-to-SQL: Enhancing SQL Generation with Data Expert LLM"** is accepted by ACL 2024.

<span class='anchor' id='-projects'></span>
# ⚒️ Projects

- [Awesome-GraphRAG](https://github.com/DEEP-PolyU/Awesome-GraphRAG) [![GitHub Repo stars](https://img.shields.io/github/stars/DEEP-PolyU/Awesome-GraphRAG?style=social)](https://github.com/DEEP-PolyU/Awesome-GraphRAG)
- [IDvs.MoRec](https://github.com/westlake-repl/IDvs.MoRec) [![GitHub Repo stars](https://img.shields.io/github/stars/westlake-repl/IDvs.MoRec?style=social)](https://github.com/westlake-repl/IDvs.MoRec)

<span class='anchor' id='-publications'></span>
# 📝 Publications 

- [Probing Latent Knowledge Conflict for Faithful Retrieval-Augmented Generation](https://arxiv.org/abs/2510.12460)

  Linfeng Gao, Baolong Bi, **Zheng Yuan**, Le Wang, Zerui Chen, Zhimin Wei, Shenghua Liu, Qinggang Zhang, Jinsong Su

  *arXiv Preprint*

- [You Don't Need Pre-built Graphs for RAG: Retrieval Augmented Generation with Adaptive Reasoning Structures](https://arxiv.org/pdf/2508.06105)

  Shengyuan Chen, Chuang Zhou, **Zheng Yuan**, Qinggang Zhang, Zeyang Cui, Hao Chen, Yilin Xiao, Jiannong Cao, Xiao Huang

  *arXiv Preprint*
  
- [Knapsack Optimization-based Schema Linking for LLM-based Text-to-SQL Generation](https://arxiv.org/abs/2502.12911)

  **Zheng Yuan**, Hao Chen, Zijin Hong, Qinggang Zhang, Feiran Huang, Qing Li, Xiao Huang

  *The 42nd IEEE International Conference on Data Engineering: ICDE 2026*

- [Neuro-symbolic Entity Alignment via Variational Inference](https://arxiv.org/pdf/2410.04153)

  Shengyuan Chen, **Zheng Yuan**, Qinggang Zhang, Wen Hua, Jiannong Cao, Xiao Huang

  *In Proceedings of the 39th Annual Conference on Neural Information Processing Systems: NeurIPS 2025*

- [A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models](https://arxiv.org/abs/2501.13958)

  Qinggang Zhang, Shengyuan Chen, Yuanchen Bei, **Zheng Yuan**, Huachi Zhou, Zijin Hong, Junnan Dong, Hao Chen, Yi Chang, Xiao Huang

  *arXiv Preprint*

- [Next-Generation Database Interfaces: A Survey of LLM-based Text-to-SQL](https://arxiv.org/abs/2406.08426)

  Zijin Hong, **Zheng Yuan**, Qinggang Zhang, Hao Chen, Junnan Dong, Feiran Huang, Xiao Huang

  *IEEE Transactions on Knowledge and Data Engineering (2025): TKDE 2024*

- [Knowledge-to-SQL: Enhancing SQL Generation with Data Expert LLM](https://arxiv.org/abs/2402.11517)

  Zijin Hong, **Zheng Yuan**, Hao Chen, Qinggang Zhang, Feiran Huang, Xiao Huang

  *In Findings of the Association for Computational Linguistics: ACL 2024*

- [Multi-Behavior Collaborative Filtering with Partial Order Graph Convolutional Networks](https://arxiv.org/pdf/2402.07659)

  Yijie Zhang, Yuanchen Bei, Hao Chen, Qijie Shen, **Zheng Yuan**, Huan Gong, Senzhang Wang, Feiran Huang, Xiao Huang

  *In Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining: KDD 2024*

- [NineRec: A Benchmark Dataset Suite for Evaluating Transferable Recommendation](https://ieeexplore.ieee.org/document/10461053)

  Jiaqi Zhang, Yu Cheng, Yongxin Ni, Yunzhu Pan, **Zheng Yuan**, Junchen Fu, Youhua Li, Jie Wang, Fajie Yuan

  *IEEE Transactions on Pattern Analysis and Machine Intelligence (2024): TPAMI 2024*

- [Exploring Adapter-based Transfer Learning for Recommender Systems: Empirical Studies and Practical Insights](https://dl.acm.org/doi/pdf/10.1145/3616855.3635805)

  Junchen Fu, Fajie Yuan, Yu Song, **Zheng Yuan**, Mingyue Cheng, Shenghui Cheng, Jiaqi Zhang, Jie Wang, Yunzhu Pan

  *In Proceedings of the 17th ACM International Conference on Web Search and Data Mining: WSDM 2024*

- [Exploring the Limits of Text-Based Collaborative Filtering Using LLMs: Discoveries and Insights](https://arxiv.org/pdf/2305.11700)

  Ruyu Li, Wenhao Deng, Yu Cheng, **Zheng Yuan**, Jiaqi Zhang, Fajie Yuan

  *In Proceedings of the 34th ACM International Conference on Information and Knowledge Management: CIKM 2025*

- [Where to go next for recommender systems? id-vs. modality-based recommender models revisited](https://dl.acm.org/doi/pdf/10.1145/3539618.3591932)

  **Zheng Yuan**, Fajie Yuan, Yu Song, Youhua Li, JunChen Fu, Fei Yang, Yunzhu Pan, YongXin Ni

  *In Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval: SIGIR 2023*

- [SQL-Rank++: A Novel Listwise Approach for Collaborative Ranking with Implicit Feedback](https://ieeexplore.ieee.org/abstract/document/9891935)

  **Zheng Yuan**, Dugang Liu, Weike Pan, Zhong Ming

  *In 2022 International Joint Conference on Neural Networks: IJCNN 2022*

<span class='anchor' id='-experiences'></span>
# 💻 Experiences

- *2023.04 - 2023.09*, Reseach Intern, Laboratory for High Performance Data Mining, Shenzhen Institute of Advanced Technology (SIAT), Advisor: [Min YANG](https://minyang.me/), Shenzhen, China.
- *2021.07 - 2023.03*, Reseach Assistant, Representation Learning Lab, Westlake University @[westlake-repl](https://huggingface.co/westlake-repl), Advisor: [Fajie YUAN](https://fajieyuan.github.io/), Hangzhou, China.
