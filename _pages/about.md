---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Introduction

Welcome to my homepage! My name is Zefan Zhang, and I am a Ph.D. student in Computer Science advised by [Prof. Tian Bai](https://ccst.jlu.edu.cn/info/1026/17630.htm) at Jilin University since 2023. Before that, I received my Master's Degree from Soochow University in 2023, supervised by [Prof. Yi Ji](https://scst.suda.edu.cn/0e/3a/c11250a527930/page.htm) and [Prof. Chunping Liu](https://scst.suda.edu.cn/f5/ff/c30505a521727/page.htm). I received my Bachelor's Degree from Zhejiang University of Technology in 2020.

## Research Interests

My research interests include **visual dialog**, **video question answering**, **medical visual question answering**, and **multimodal relation extraction**. My research focuses on the **multimodal relation interaction** and **multimodal event relation reasoning** for building intelligent computer models that can reason the complex world. Furthermore, I am also interested in research on the applications of deep learning in various scenarios, such as the legal and judicial fields.  

## Research Experience

During the period of 2022.11-2023.2, I interned at Microsoft Research Asia (MSRA) advised by Huaying Xue. My main research content is accent conversion.

## Academic Activities

2018.10 CNCC 2018 (China National Computer Conference), Hangzhou.

2021.10 VALSE 2021 (Vision And Learning SEminar), Hangzhou.

2022.08 China MM 2022 (China Multimedia), Guizhou, [Oral paper](https://link.springer.com/article/10.1007/s13735-022-00257-2).

2023.10 CNCC 2023 (China National Computer Conference), Shenyang.

## Publications

**1. Zhang Z, Weiqi Z, Yanhui L, Tian B. Caption-Aware Multimodal Relation Extraction with Mutual Information Maximization[C]//Proceedings of the 2024 ACM International Conference on Multimedia. 2024.**  

Abstract: Multimodal Relation Extraction (MRE) has achieved great improvements. However, modern MRE models are easily affected by irrelevant objects during multimodal alignment which are called error sensitivity issues. The main reason is that visual features are not fully aligned with textual features and the reasoning process may suppress redundant and noisy information at the risk of losing critical information. In light of this, we propose a \textbf{C}aption-\textbf{A}ware Multimodal Relation Extraction Network with \textbf{M}utual \textbf{I}nformation \textbf{M}aximization (\textbf{CAMIM}). Specifically, we first generate detailed image captions through the Large Language Model (LLM). Then, the Caption-Aware Module (CAM) hierarchically aligns the fine-grained visual entities and textual entities for reasoning. In addition, for preserving crucial information within different modalities, we leverage a Mutual Information Maximization method to regulate the multimodal reasoning module. Experiments show that our model outperforms the state-of-the-art MRE models on the benchmark dataset MNRE. Further ablation studies prove the pluggable and effective performance of our Caption-Aware Module and Mutual Information Maximization method. Our code is available at \url{https://github.com/zefanZhang-cn/CAMIM}.

---

**2. Zhang Z, Ji Y, Liu C. Knowledge-Aware Causal Inference Network for Visual Dialog[C]//Proceedings of the 2023 ACM International Conference on Multimedia Retrieval. 2023: 253-261.**  [Paper](https://dl.acm.org/doi/abs/10.1145/3591106.3592272)

Abstract: The effective knowledge and interaction within multi-modalities are key to Visual Dialog. Classic graph-based framework with the direct connection between history dialog and answer fails to give the right answer for the spurious guidance and strong bias induced from history dialog. Recent causal inference framework without this direct connection improves the generalization while worse accuracy. In this work, we propose a novel Knowledge-Aware Causal Inference framework(KACI-Net) in which the commonsense knowledge is introduced into the causal inference framework to achieve both high accuracy and generalization. Specifically, the commonsense knowledge is first generated according to the entities extracted from the question and fused with language and visual features with the co-attention to get the final answer. Comparisons with knowledge-unaware framework and graph-based knowledge-aware framework on VisDial v1.0 dataset show the superiority of our proposed framework and verify the effectiveness the usage of commonsense knowledge for good reasoning in Visual Dialog. Both high NDCG and MRR metrics indicate a good trade-off between accuracy and generalization.

---

**3. Jiang T, Zhang Z(co-author), Li X, et al. Multi-view semantic understanding for visual dialog[J]. Knowledge-Based Systems, 2023, 268: 110427.**  [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705123001776)

Abstract: Visual dialog, as a challenging cross-media task, requires answering a sequence of questions based on a given image and dialog history. Hence the key problem becomes how to answer visually grounded questions based on ambiguous reference information from dialog. In this work, we propose a novel method called Multi-View Semantic Understanding for Visual Dialog (MVSU) to resolve the visual coreference resolution problem. The model consists of two main textual processing modules, SRR (Semantic Retention RNN) and CRoT (Coreference Resolution on Text). Specifically, the SRR module generates word features that have semantical meaning by considering contextual information. The CRoT module is from a textual perspective to divide all useful nouns and pronouns into different clusters that serve as the supplement of the detailed information for semantic understanding. In experiments, we demonstrate that MVSU enhances the ability to understand the semantical information on the VisDial v1.0 dataset.

---

**4. Zhang Z, Jiang T, Liu C, et al. Coupling Attention and Convolution for Heuristic Network in Visual Dialog[C]//2022 IEEE International Conference on Image Processing (ICIP). IEEE, 2022: 2896-2900.**  [Paper](https://ieeexplore.ieee.org/abstract/document/9898003)

Abstract: Visual Dialog is a typical AI-agent task on images, in which the agent interprets information from heterogeneous modalities and provides the correct answer. In this area, most approaches are based on the attention mechanism. When the agent enjoys the large-capacity advantage of attention, the lack of the right inductive bias compared with convolution hinders its success. Therefore, in order to utilize their advantages and compensate for their respective shortcomings, inspired by the paraventricular thalamus (PVT) in the brain, we couple convolution and attention, termed as Attention Convolution Enhanced (ACE) method to enhance the agent’s activation of key features and strengthening the semantic understanding of visual and textual data. Meanwhile, we propose Heuristic Adjustment (HA) module to globally strengthen the agent’s semantic understanding and reduce language bias that is easy to occur after using the enhanced features. Finally, we concatenate the ACE and the HA in our Coupling Attention and Convolution for Heuristic Network (CACH-Net) to train the agent for better semantic comprehension and generalization ability. Extensive experiments on the VisDial v1.0 benchmark show that our CACH-Net has a better performance.

---

**5. Zhang Z, Li S, Ji Y, et al. Infer unseen from seen: Relation regularized zero-shot visual dialog[J]. Journal of Visual Communication and Image Representation, 2023, 97: 103961.**  [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1047320323002110)

Abstract: The Visual Dialog task requires retrieving the correct answer based on detected objects, a current question, and history dialogs. However, in real-world scenarios, most existing models face the hard-positive problem and are unable to reason about unseen features, which limits their generalization ability. To address this issue, we propose two Relation Regularized Modules (RRM) in this article. The first is the Visual Relation Regularized Module (VRRM), which seeks known visual features that have semantic relations with unknown visual features and leverages these known features to assist in understanding the unknown features. The second is the Text Relation Regularized Module (TRRM), which enhances the keywords in the answers to strengthen the understanding of unknown text features. To evaluate the effectiveness of these modules, we propose two zero-shot Visual Dialog splits for verification: Visual Zero-shot VisDial with unseen visual features and Text Zero-shot VisDial with unseen answers. Experimental results demonstrate that our proposed modules achieve state-of-the-art performance in zero-shot Visual Dialog with unseen visual features and unseen answers, while also producing comparable results on the benchmark VisDial v1.0 test dataset.

---

**6. Zhang Z, Jiang T, Liu C, et al. Multi-aware coreference relation network for visual dialog[J]. International Journal of Multimedia Information Retrieval, 2022, 11(4): 567-576.**  [Paper](https://link.springer.com/article/10.1007/s13735-022-00257-2)

Abstract: As a challenging cross-media task, visual dialog assesses whether an AI agent can converse in human language based on its understanding of visual content. So the critical issue is to pay attention not only to the problem of coreference in vision, but also to the problem of coreference in and between vision and language. In this paper, we propose the multi-aware coreference relation network (MACR-Net) to solve it from both textual and visual perspectives and to do fusion in complementary awareness. Specifically, its textual coreference relation module identifies textual coreference relations based on multi-aware textual representation from textual view. Furthermore, the visual coreference relation module adaptively adjusts visual coreference relations based on contextual-aware relations representation from visual view. Finally, the multi-modals fusion module fuses multi-aware relations to get an aligned representation. Extensive experiments on the VisDial v1.0 benchmarks show that MACR-Net achieves state-of-the-art performance.

## Others

Feel free to explore, connect, and engage with me on topics related to my research. I look forward to exchanging ideas and collaborating with like-minded individuals who share my enthusiasm for pushing the boundaries of technological advancement. Thank you for visiting my homepage, and I hope you find my work insightful and inspiring!


