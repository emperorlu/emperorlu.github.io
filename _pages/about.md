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

<!-- I\'m Kai Lu, currently serving as an Assistant Researcher and Postdoctoral Fellow at Huazhong University of Science and Technology (HUST). My major is storage systems and techniques. I\'m in Parallel Data Storage Lab ([PDSL](https://github.com/PDS-Lab)) led by Prof. Jiguang Wan and Prof. Changsheng Xie. PDSL has long been devoted to the research of distributed storage systems, key-value storage and AI storage. -->

## 🙋🏻‍♂️ About Me
I am **Kai Lu**, a Postdoctoral Fellow at Huazhong University of Science and Technology (HUST).
I work in the [Parallel Data Storage Lab (PDSL)](https://github.com/PDS-Lab) under Prof. Jiguang Wan and Prof. Changsheng Xie. I obtained my Ph.D. in Computer Architecture from the Wuhan National Laboratory for Optoelectronics at HUST in 2023, following a B.E. in Computer Science and Technology from the same university. 
My research focuses on distributed storage systems and AI storage, aiming to enable high-performance, scalable, and efficient distributed storage infrastructures for next-generation computing workloads.

## 🔬 Research Interests
My current research focuses on **disaggregated memory systems for LLM inference**. Specifically, my work includes:
- **Disaggregated memory systems** with low-latency and high-throughput, encompassing architectural optimizations (RCMP, TACO 2024), indexing techniques (SepHash, VLDB 2024), transaction management (Scythe, TACO 2025), and DPU-accelerated operations (DFlush, SIGMOD 2025; DShuffle, USENIX ATC 2025; DComp, TACO 2024).  
- **Storage solutions tailored for LLM inference**, balancing bandwidth, latency, and resource utilization, including edge-cloud collaborative systems (EC-RAG, ICDE 2026), heterogeneous memory management (Q-Infer, TACO 2025), KV caching (ScoutAttention, DAC 2026), quantization and compression techniques (ACL 2026, TACO 2026, AAAI 2025, DATE 2025), and vector indexing.  

If you are interested in academic collaboration, please feel free to contact me at <kailu@hust.edu.cn>.


# 🏅 Projects and Awards
- **2022-now**: #1 in [IO500 10 Node Research](https://io500.org/list/sc25/ten)  
- **2024**: China Postdoctoral Science Foundation Funded Project  
- **2024**: Hubei Provincial Postdoctoral Innovative Talent Training Project, A Grade  
- **2025**: Young Scientists Fund-Type C, National Natural Science Foundation of China   
- **2025**: Gold Award, Hubei Provincial Overseas Talent Innovation and Entrepreneurship Competition 
- **2025**: Bronze Award, 3rd China Postdoctoral Innovation and Entrepreneurship Competition 

# 📝 Publications 
(* denotes corresponding author)
## 2026

* Qiuyang Zhang, Kai Zhou, Ding Tang, **Kai Lu**\*, Cheng Li, Zhenyu Yang, Peng Xu, Jiguang Wan. ScoutAttention: Efficient KV Cache Offloading via Layer-Ahead CPU Pre-computation for LLM Inference. (DAC 2026, CCF-A)

*  **Kai Lu**, Yuanhui Zhou, Nengjie Wang, Jiguang Wan, Bisheng Huang, Yang Zhang, Jinpeng Zhang, Yu Dong. HeapKV: Enabling Efficient Garbage Collection for KV-Separated LSM Stores on Modern SSDs. (TACO 2026, CCF-A) [Code](https://github.com/PDS-Lab/HeapKV)

* Liang Wang, Kai Wang, Ranjun Jia, **Kai Lu**\*, Jiguang Wan, Hao Huo, Yulong Zhai, Zhiyuan Liang, Di Wang. EC-RAG: Towards Efficient Edge-Cloud Retrieval-Augmented Generation Systems (ICDE 2026, CCF-A)

* Qiuyang Zhang, Jiapin Wang, You Zhou\*, Peng Xu, **Kai Lu**\*, Jiguang Wan, Fei Wu, Tao Lu. CEMU: Enabling Full-System Emulation of Computational Storage beyond Hardware Limits (ASPLOS 2026, CCF-A)

## 2025

*  **Kai Lu**, Qiang Wei, Yier Lin, Pengyu Liu, Haipeng Wang, Jiguang Wan\*, Ting Yao, Huatao Wu, Daohui Wang. [Q-Infer: Towards Efficient GPU-CPU Collaborative LLM Inference via Sparsity-Aware Dynamic Scheduling](https://dl.acm.org/doi/10.1145/3764589) (TACO 2025, CCF-A) [Code](https://github.com/PDS-Lab/Q-Infer)

* Yuanhui Zhou, **Kai Lu***, Zhonghua Wang, Peng Xu, Kai Wang, Ranjun Jia, Jiguang Wan. [RaKV: A Write-Optimized LSM Store for Cloud Block Storage with Robust SLA](https://dl.acm.org/doi/abs/10.1145/3774424) (TACO 2025, CCF-A)

* Chen Ding, Sicen Li, **Kai Lu***, Ting Yao, Daohui Wang, Huatao Wu, Jiguang Wan, Zhihu Tan, Changsheng Xie. [DShuffle: DPU-Optimized Shuffle Framework for Large-scale Data Processing](https://www.usenix.org/conference/atc25/presentation/ding) (USENIX  ATC 2025, CCF-A)

*  Chen Ding, **Kai Lu**\*, QuanYi Zhang, Zekun Ye, Ting Yao, Daohui Wang, Huatao Wu, Jiguang Wan. [DFlush: DPU-Offloaded Flush for Disaggregated LSM-based Key-Value Stores](https://dl.acm.org/doi/10.1145/3725284) (SIGMOD 2025, CCF-A)

*  Wei Tao, Haocheng Lu, Xiaoyang Qu*, Bin Zhang, **Kai Lu**\*, Jiguang Wan, Jianzong Wang. [MoQAE: Mixed-Precision Quantization for Long-Context LLM Inference via Mixture of Quantization-Aware Experts](https://aclanthology.org/2025.acl-long.531/) (ACL 2025 Main, CCF-A)

*  Junjie Li, Nan Zhang, Xiaoyang Qu, **Kai Lu**, Guokuan Li, Jiguang Wan, Jianzong Wang. [RATE-Nav: Region-Aware Termination Enhancement for Zero-shot Object Navigation with Vision-Language Models](https://aclanthology.org/2025.findings-acl.341/) (ACL 2025 Findings, CCF-A)

*  Wei Tao, Xiaoyang Qu\*, **Kai Lu**\*, Jiguang Wan, Guokuan Li, Jianzong Wang. MADLLM: Multivariate Anomaly Detection via Pre-trained LLMs (ICME 2025, CCF-B)

*  Bin Zhang, Jinggang Chen, Xiaoyang Qu, Guokuan Li, **Kai Lu**\*, Jiguang Wan, Jing Xiao, Jianzong Wang\*. [RUNA: Object-level Out-of-Distribution Detection via Regional Uncertainty Alignment of Multimodal Representations](https://ojs.aaai.org/index.php/AAAI/article/view/34841) (AAAI 2025, CCF-A)

## 2024
*  Yixiao Chen, Haomai Yang, **Kai Lu***, Wenlve Huang, Jibin Wang, Jiguang Wan, Jian Zhou, Fei Wu, Changsheng Xie. [PeakFS: An Ultra-high Performance Parallel File System via Computing-Network-Storage Co-optimization for HPC Applications](https://ieeexplore.ieee.org/document/10735121) (TPDS 2024, CCF-A) [Code](https://github.com/PDS-Lab/PeakFS-Experiments)

*  **Kai Lu**, Siqi Zhao, Haikang Shan, Qiang Wei, Guankuan Li, Jiguang Wan, Ting Yao, Huatao Wu, Daohui Wang. [Scythe: A Low-latency RDMA-enabled Distributed Transaction System for Disaggregated Memory](https://dl.acm.org/doi/10.1145/3666004) (TACO 2024, CCF-A) [Code](https://github.com/PDS-Lab/scythe)

*  Zhonghua Wang, **Kai Lu***, Jiguang Wan, Hong Jiang, Zeyang Zhao, Peng Xu, Biliang Lai, Guokuan Li, and Changsheng Xie. [NStore: A High-Performance NUMA-Aware Key-Value Store for Hybrid Memory](https://www.computer.org/csdl/journal/tc/5555/01/10761975/223Ey6jTUwE) (TC 2024, CCF-A) [Code](https://github.com/PDS-Lab/NStore)

*  Xinhao Min, **Kai Lu***, Pengyu Liu, Jiguang Wan, Changsheng Xie, Daohui Wang, Ting Yao, Huatao Wu. [SepHash: A Write-Optimized Hash Index on Disaggregated Memory via Separate Segment Structure](https://www.vldb.org/pvldb/vol17/p1091-lu.pdf) (VLDB 2024, CCF-A) [Code](https://github.com/minxinhao/SepHash)

*  Yiwen Zhang, Guokuan Li\*, **Kai Lu**\*, Jiguang Wan, Ting Yao, Huatao Wu, Daohui Wang. [PhatKV: Towards an Efficient Metadata Engine for KV-based File Systems on Modern SSD](https://www.msstconference.org/MSST-history/2024/Papers/msst24-9.3.pdf) (MSST 2024, CCF-B)

*  Chen Ding, Jian Zhou, **Kai Lu**, Sicen Li, Yiqin Xiong, Jiguang Wan, Ling Zhan. [D2Comp: Efficient Offload of LSM-tree Compaction with Data Processing Units on Disaggregated Storage](https://dl.acm.org/doi/abs/10.1145/3656584) (TACO 2024, CCF-A)

*  Yuanhui Zhou, Jian Zhou, **Kai Lu**, Ling Zhan, Peng Xu, Peng Wu, Shuning Chen, Xian Liu, Jiguang Wan. [A contract-aware and cost-effective LSM Store for Cloud Storage with Low Latency Spikes](https://dl.acm.org/doi/10.1145/3643851) (TOS 2024, CCF-A)

## 2023 and before
*  Zhonghua Wang, Yixing Guo, **Kai Lu***, Jiguang Wan, Daohui Wang, Ting Yao, Huatao Wu. [Rcmp: Reconstructing RDMA-based Memory Disaggregation via CXL](https://dl.acm.org/doi/10.1145/3634916) (TACO 2023, CCF-A) [Code](https://github.com/PDS-Lab/Rcmp)

*  Liang Wang, **Kai Lu**(co-primary author), Nan Zhang, Xiaoyang Qu, Jianzong Wang, Jiguang Wan, Guokuan Li, Jing Xiao. [Shoggoth: Towards Efficient Edge-Cloud Collaborative Real-Time Video Inference via Adaptive Online Learning](https://ieeexplore.ieee.org/abstract/document/10247821/) (DAC 2023, CCF-A)

*  **Kai Lu**, Guokuan Li, Jiguang Wan, Ruixiang Ma, Wei Zhao. [ADSTS: Automatic Distributed Storage Tuning System Using Deep Reinforcement Learning](https://dl.acm.org/doi/abs/10.1145/3545008.3545012) (ICPP 2022, CCF-B)

*  **Kai Lu**, Nannan Zhao, Jiguang Wan, Changhong Fei, Wei Zhao, Tongliang Deng. [RLRP: High-Efficient Data Placement with Reinforcement Learning for Modern Distributed Storage Systems](https://ieeexplore.ieee.org/document/9820675/) (IPDPS 2022, CCF-B) [Code](https://github.com/emperorlu/Replica-Placement)

*  **Kai Lu**, Nannan Zhao, Jiguang Wan, Changhong Fei, Wei Zhao, and Tongliang Deng. [TridentKV: A Read-Optimized LSM-tree Based KV Store via Adaptive Indexing and Space-Efficient Partitioning](https://ieeexplore.ieee.org/document/9563237) (TPDS, CCF-A) [Code](https://github.com/emperorlu/Learned-Rocksdb)

*  Zhonghua Wang, Chen Ding, Fengguang Song, **Kai Lu**, Jiguang Wan, Zhihu Tan, Changsheng Xie and Guokuan Li. [WIPE: a Write-Optimized Learned Index for Persistent Memory](https://dl.acm.org/doi/10.1145/3634915) (TACO 2023, CCF-A) [Code](https://github.com/olemon111/WIP)

*  Chen Ding, Jian Zhou, Jiguang Wan, Yiqin Xiong, Sicen Li, Shuning Chen, Hanyang Liu, Liu Tang, Ling Zhan, **Kai Lu**, Peng Xu. [DComp: Efficient Offload of LSM-tree Compaction with Data Processing Units](https://dl.acm.org/doi/fullHtml/10.1145/3605573.3605633) (ICPP 2023, CCF-B)

*  Wei Tao, Shenglin He, **Kai Lu**, Xiaoyang Qu, Guokuan Li, Jiguang Wan, Jianzong Wang, Jing Xiao. [Value-Driven Mixed-Precision Quantization for Patch-Based Inference on Microcontrollers](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10546541) (DATE 2023, CCF-B)

*  Daping Li, Jiguang Wan, Jun Wang, Jian Zhou, **Kai Lu**, Peng Xu, Fei Wu and Changsheng Xie. [Disperse Access Considered Energy Inefficiency in Intel Optane DC Persistent Memory Servers](https://ieeexplore.ieee.org/document/9355739) (ICDCS 2020, CCF-B) [Code](https://github.com/emperorlu/Sprint-AEP)

*  Ling Zhan, **Kai Lu**, Zhilong Cheng and Jiguang Wan. [RangeKV: An Efficient Key-Value Store Based on Hybrid DRAM-NVM-SSD Storage Structure](https://ieeexplore.ieee.org/document/9170492)

*  Ling Zhan, **Kai Lu**\*, Yiqin Xiong, Jiguang Wan and Zixuan Yang. [TrickleKV: A High-Performance Key-Value Store on Disaggregated Storage with Low Network Traffic](https://ieeexplore.ieee.org/document/10752495)



# 💬 Contact
* Email: <kailu@hust.edu.cn>
* Github: [emperorlu](https://github.com/emperorlu); [PDS-Lab](https://github.com/PDS-Lab)
