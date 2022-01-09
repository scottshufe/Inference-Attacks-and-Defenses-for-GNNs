# Inference Attacks and Defenses for GNNs

# Attacks
- **Inference Attacks Against Graph Neural Network (2022 USENIX)**
  - **Authors**: Zhikun Zhang, Min Chen, Michael Backes, Yun Shen, Yang Zhang
  - **Attacks**: Property Inference, Subgraph Inference, Graph Reconstruction
  - [[paper]](https://www.usenix.org/system/files/sec22summer_zhang-zhikun.pdf)
  - [[code]](https://github.com/Zhangzhk0819/GNN-Embedding-Leaks)
- **Node-Level Membership Inference Attacks Against Graph Neural Networks (2021 arXiv)**
  - **Authors**: Xinlei He, Rui Wen, Yixin Wu, Michael Backes, Yun Shen, Yang Zhang
  - **Attacks**: Membership Inference
  - [[paper]](https://arxiv.org/pdf/2102.05429.pdf)
  <!--- [[code]]()-->
- **Adapting Membership Inference Attacks to GNN for Graph Classification: Approaches and Implications (2021 ICDM)**
  - **Authors**: Bang Wu, Xiangwen Yang, Shirui Pan, Xingliang Yuan
  - **Attacks**: Membership Inference
  - [[paper]](https://arxiv.org/pdf/2110.08760.pdf)
  - [[code]](https://github.com/trustworthygnn/mia-gnn)
- **Quantifying Privacy Leakage in Graph Embedding (2020 MobiQuitous and NeurIPS PPML)**
  - **Authors**: Vasisht Duddu, Antoine Boutet, Virat Shejwalkar
  - **Attacks**: Attribute Inference, Membership Inference, Link Inference, Graph Reconstruction
  - [[paper]](https://arxiv.org/pdf/2010.00906.pdf)
  - [[code]](https://github.com/vasishtduddu/GraphLeaks)


# Defenses
- **Inference Attacks Against Graph Neural Network (2022 USENIX)**
  - **Authors**: Zhikun Zhang, Min Chen, Michael Backes, Yun Shen, Yang Zhang
  - **Defenses**: Differential Privacy - like (add noises)
  - [[paper]](https://www.usenix.org/system/files/sec22summer_zhang-zhikun.pdf)
  - [[code]](https://github.com/Zhangzhk0819/GNN-Embedding-Leaks)
- **NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data (2021 TKDE)**
  - **Authors**: I-Chung Hsieh, Cheng-Te Li
  - **Defenses**: Adversarial Training (Graph structure and node features perturbation)
  - [[paper]](https://arxiv.org/pdf/2106.11865.pdf)
  - [[code]](https://github.com/ICHproject/NetFense/)
- **Privacy-Preserving Representation Learning on Graphs: A Mutual Information Perspective (2021 KDD)**
  - **Authors**: Binghui Wang, Jiayi Guo, Ang Li, Yiran Chen, Hai Li
  - **Defenses**: Adversarial Training
  - [[paper]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467273?casa_token=lyzYuHgLz1QAAAAA:A-Sn-2RXI-uRp7pe-BuvJVVSYNUsbt3mwXANN-DLNTT5NCbEzo11V-cIeT6Y-9z-h8Ea2g7eswM)
  <!--- [[code]] -->
- **Graph Embedding for Recommendation against Attribute Inference Attacks (2021 WWW)**
  - **Authors**: Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Lizhen Cui, Xiangliang Zhang
  - **Defenses**: Differential Privacy
  - [[paper]](https://dl.acm.org/doi/abs/10.1145/3442381.3449813?casa_token=QJftjQKsufcAAAAA%3Aqpy41OVvbRVL9OId9qiUPgC5I8Knc-QYZIocdut4eSj2_L2Z9dDCwBIo7oYXF2A7_0hihQLh4Kg)
  <!--- [[code]] -->
- **Information Obfuscation of Graph Neural Networks (ICML2021)**
  - **Authors**: Peiyuan Liao, Han Zhao, Keyulu Xu, Tommi Jaakkola, Geoffrey Gordon, Stefanie Jegelka, Ruslan Salakhutdinov
  - **Defenses**: Adversarial Training
  - [[paper]](http://proceedings.mlr.press/v139/liao21a/liao21a.pdf)
  - [[code]](https://github.com/liaopeiyuan/GAL)
- **Personalized privacy protection in social networks through adversarial modeling (2021 AAAI)**
  - **Authors**: Sachin Biradar, Elena Zheleva
  - **Defenses**: Adversarial Training
  - [[paper]](https://www.cs.uic.edu/~elena/pubs/biradar-ppai21.pdf)
  <!--[[code]]-->
- **Adversarial Privacy Preserving Graph Embedding Against Inference Attack (2020 IoTJ)**
  - **Authors**: Kaiyang Li, Guangchun Luo, Yang Ye, Wei Li
  - **Defenses**: Adversarial Training
  - [[paper]](https://arxiv.org/pdf/2008.13072.pdf)
  - [[code]](https://github.com/KaiyangLi1992/Privacy-Preserving-Social-Network-Embedding)