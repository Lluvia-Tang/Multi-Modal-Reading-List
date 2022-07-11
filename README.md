# MultiModal-Reading-List
Reading List of Multi-Modal tasks.


### Contents

- [1. Multimodal-Sentiment-Analysis](#1-msa)
  - [1.1 Paper](#11-paper)
  - [1.2 Datasets](#12-datasets)
  
- [2. Multimodal-Aspect-based-Sentiment-Analysis](#2-mabsa)
  - [2.1 Paper](#21-paper)
  - [2.2 Datasets](#22-datasets)

- [3. Multimodal-Targeted-Sentiment-Analysis](#3-mtsc)
  - [3.1 Paper](#31-paper)
  - [3.2 Datasets](#32-datasets)
  
- [4. Multimodal-Sarcasm-Detection](#4-msd)
  - [4.1 Paper](#41-paper)
  - [4.2 Datasets](#42-datasets)
 
- [5. Multimodal-Emotion-Recognition](#5-mer)
  - [5.1 Paper](#51-paper)
  - [5.2 Datasets](#52-datasets)

- [6. Multimodal-Complaint-Identification](#6-mci)
  - [6.1 Paper](#61-paper)
  - [6.2 Datasets](#62-datasets)

- [7. Multimodal-Rumor-Detection](#7-mrd)
  - [7.1 Paper](#71-paper)
  - [7.2 Datasets](#72-datasets)

- [8. Multimodal-Hate-Detection](#8-mhd)
  - [8.1 Paper](#81-paper)
  - [8.2 Datasets](#82-datasets)

- [9. Others](#9-others)
  - [9.1 Paper](#91-paper)
  - [9.2 Datasets](#92-datasets)

<!--
  - [1.2 Aspect Extraction](#12-aspect-extraction)
  - [1.3 Opinion Extraction](#13-opinion-extraction)
  - [1.4 Category Detection](#14-category-detection)
  - [1.5 Aspect-Opinion Co-Extraction](#15-aspect-opinion-co-extraction)
  - [1.6 Aspect-Oriented Opinion Extraction](#16-aspect-oriented-opinion-extraction)
  - [1.7 Aspect-Opinion Pair Extraction](#17-aspect-opinion-pair-extraction)
  - [1.8 Aspect-Sentiment Pair Extraction](#18-aspect-sentiment-pair-extraction)
  - [1.9 Category-Oriented Sentiment Classification](#19-category-oriented-sentiment-classification)
  - [1.10 Category-Sentiment Hierarchical Classification](#110-category-sentiment-hierarchical-classification)
  - [1.11 Aspect-Category-Sentiment Triple Extraction](#111-aspect-category-sentiment-triple-extraction)
  - [1.12 Aspect-Opinion-Sentiment Triple Extraction](#112-aspect-opinion-sentiment-triple-extraction)
  - [1.13 Aspect-Category-Opinion-Sentiment Quadruple Extraction](#113-aspect-category-opinion-sentiment-quadruple-extraction)
- [2. Cross-Domain ABSA](#2-cross-domain-absa)
  - [2.1 Cross-Domain Aspect Extraction](#21-cross-domain-aspect-extraction)
  - [2.2 Cross-Domain Aspect-Opinion Co-Extraction](#22-cross-domain-aspect-opinion-co-extraction)
  - [2.3 Cross-Domain Aspect-Oriented Sentiment Classification](#23-cross-domain-aspect-oriented-sentiment-classification)
  - [2.4 Cross-Domain Aspect-Sentiment Pair Extraction](#24-cross-domain-aspect-sentiment-pair-extraction)
- [3. Multi-Modal ABSA](#3-multi-modal-absa)
  - [3.1 Multi-Modal Aspect Extraction (& Multi-Modal Named Entity Recognition)](#31-multi-modal-aspect-extraction--multi-modal-named-entity-recognition)
  - [3.2 Multi-Modal Category-Oriented Sentiment Classification](#32-multi-modal-category-oriented-sentiment-classification)
  - [3.3 Multi-Modal Aspect-Oriented Sentiment Classification](#33-multi-modal-aspect-oriented-sentiment-classification)
  - [3.4 Multi-Modal Aspect-Sentiment Pair Extraction](#34-multi-modal-aspect-sentiment-pair-extraction)
-->

## 1. Multimodal-Sentiment-Analysis
### 1.1 paper
1. Yang Wu, Yanyan Zhao, Hao Yang, Song Chen, Bing Qin, Xiaohuan Cao, Wenting Zhao. **Sentiment Word Aware Multimodal Refinement for Multimodal Sentiment Analysis with ASR Errors**. ACL findings 2022. [[paper]](https://aclanthology.org/2022.findings-acl.109/) [[code]](https://github.com/albertwy/SWRM)

1. Devamanyu Hazarika, Yingting Li, Bo Cheng, Shuai Zhao, Roger Zimmermann, Soujanya Poria. **Analyzing Modality Robustness in Multimodal Sentiment Analysis**. NAACL short 2022. [[paper]](https://arxiv.org/abs/2205.15465) [[code]](https://github.com/declare-lab/MSA-Robustness)

1. Zhen Li, Bing Xu, Conghui Zhu, Tiejun Zhao. **CLMLF: A Contrastive Learning and Multi-Layer Fusion Method for Multimodal Sentiment Detection**. NAACL findings 2022. [[paper]](https://arxiv.org/abs/2204.05515) [[code]](https://github.com/Link-Li/CLMLF)

1. Georgios Paraskevopoulos, Efthymios Georgiou, Alexandros Potamianos. **Mmlatch: Bottom-Up Top-Down Fusion For Multimodal Sentiment Analysis**. ICASSP 2022. [[paper]](https://ieeexplore.ieee.org/document/9746418) [[code]](https://github.com/georgepar/mmlatch)

1. 	Luwei Xiao, Xingjiao Wu, Wen Wu, Jing Yang, Liang He. **Multi-Channel Attentive Graph Convolutional Network with Sentiment Fusion for Multimodal Sentiment Analysis**. ICASSP 2022. [[paper]](https://ieeexplore.ieee.org/document/9747542)

1. 	Xianbing Zhao, Yixin Chen, Wanting Li, Lei Gao, Buzhou Tang. **MAG+: An Extended Multimodal Adaptation Gate for Multimodal Sentiment Analysis**. ICASSP 2022. [[paper]](https://ieeexplore.ieee.org/document/9746536)

1. Xiaocui Yang, Shi Feng, Yifei Zhang, Daling Wang. **Multimodal Sentiment Detection Based on Multi-channel Graph Neural Networks**. ACL 2021. [[paper]](https://aclanthology.org/2021.acl-long.28/) [[code]](https://github.com/YangXiaocui1215/MGNNS)

1. Jiajia Tang, Kang Li, Xuanyu Jin, Andrzej Cichocki, Qibin Zhao, Wanzeng Kong. **CTFN: Hierarchical Learning for Multimodal Sentiment Analysis Using Coupled-Translation Fusion Network**. ACL 2021. [[paper]](https://aclanthology.org/2021.acl-long.412/)[[code]](https://github.com/deepsuperviser/CTFN)

1. Yang Wu, Zijie Lin, Yanyan Zhao, Bing Qin, Li-Nan Zhu. **A Text-Centered Shared-Private Framework via Cross-Modal Prediction for Multimodal Sentiment Analysis**. ACL findings 2021. [[paper]](https://aclanthology.org/2021.findings-acl.417/)[[code]](https://github.com/lzjjeff/TCSP)

1. YJunyan Cheng, Iordanis Fostiropoulos, Barry Boehm, Mohammad Soleymani. **Multimodal Phased Transformer for Sentiment Analysis**. EMNLP 2021. [[paper]](https://aclanthology.org/2021.emnlp-main.189/)[[code]](https://github.com/chengjunyan1/sp-transformer)

1. Wei Han, Hui Chen, Soujanya Poria. **Improving Multimodal Fusion with Hierarchical Mutual Information Maximization for Multimodal Sentiment Analysis**. EMNLP 2021. [[paper]](https://aclanthology.org/2021.emnlp-main.723/)[[code]](https://github.com/declare-lab/Multimodal-Infomax)

1. Ying Zeng, Sijie Mai, Haifeng Hu. **Which is Making the Contribution: Modulating Unimodal and Cross-modal Dynamics for Multimodal Sentiment Analysis**. EMNLP findings 2021. [[paper]](https://aclanthology.org/2021.findings-emnlp.109/)

1. Wenmeng Yu, Hua Xu, Ziqi Yuan, Jiele Wu. **Learning Modality-Specific Representations with Self-Supervised Multi-Task Learning for Multimodal Sentiment Analysis**. AAAI 2021. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/17289)[[code]](https://github.com/thuiar/Self-MM)

1. Sunny Verma, Jiwei Wang, Zhefeng Ge, Rujia Shen, Fan Jin, Yang Wang, Fang Chen, Wei Liu. **Deep-HOSeq: Deep Higher Order Sequence Fusion for Multimodal Sentiment Analysis**. ICDM 2020. [[paper]](https://arxiv.org/abs/2010.08218)[[code]](https://github.com/sverma88/Deep-HOSeq--ICDM-2020)

1. Sijie Mai, Haifeng Hu, Songlong Xing. **Divide, Conquer and Combine: Hierarchical Feature Fusion Network with Local and Global Perspectives for Multimodal Affective Computing**. ACL 2019. [[paper]](https://aclanthology.org/P19-1046/)

1. Dushyant Singh Chauhan, Md Shad Akhtar, Asif Ekbal, Pushpak Bhattacharyya. **Context-aware Interactive Attention for Multi-modal Sentiment and Emotion Analysis**. EMNLP 2019. [[paper]](https://www.iitp.ac.in/~ai-nlp-ml/resources.html)

1. Quoc-Tuan Truong, Hady W. Lauw. **VistaNet: Visual Aspect Attention Network for Multimodal Sentiment Analysis**. AAAI 2019. [[paper]](https://ojs.aaai.org//index.php/AAAI/article/view/3799) [[code]](https://github.com/PreferredAI/vista-net)

1. Sunny Verma, Chen Wang, Liming Zhu, Wei Liu. **DeepCU: Integrating both Common and Unique Latent Information for
Multimodal Sentiment Analysis**. IJCAI 2019. [[paper]](https://www.ijcai.org/Proceedings/2019/0503.pdf) [[code]](https://github.com/sverma88/DeepCU-IJCAI19)

1. Jianfei Yu, Jing Jiang. **Adapting BERT for Target-Oriented Multimodal Sentiment Classification**. IJCAI 2019. [[paper]](https://www.ijcai.org/Proceedings/2019/0751.pdf) [[code]](https://github.com/jefferyYu/TomBERT)

### 1.2 datasets
1. Wenmeng Yu, Hua Xu, Fanyang Meng, Yilin Zhu, Yixiao Ma, Jiele Wu, Jiyun Zou, Kaicheng Yang. **CH-SIMS: A Chinese Multimodal Sentiment Analysis Dataset with Fine-grained Annotation of Modality**. ACL 2020. [[paper]](https://aclanthology.org/2020.acl-main.343/)[[code]](https://github.com/thuiar/MMSA)

1. 【Sentiment analysis & Emotion Recognition】AmirAli Bagher Zadeh, Paul Pu Liang, Soujanya Poria, Erik Cambria, Louis-Philippe Morency. **Multimodal Language Analysis in the Wild: CMU-MOSEI Dataset and Interpretable Dynamic Fusion Graph**. ACL 2018. [[paper]](https://aclanthology.org/P18-1208/) [[code]](http://immortal.multicomp.cs.cmu.edu/) https://github.com/A2Zadeh/CMU-MultimodalSDK

1. Amir Zadeh, Rowan Zellers, Eli Pincus, Louis-Philippe Morency. **MOSI: Multimodal Corpus of Sentiment Intensity and Subjectivity Analysis in Online Opinion Videos**. 2016. [[paper]](https://arxiv.org/abs/1606.06259) [[code]](http://immortal.multicomp.cs.cmu.edu/)

1. Verónica Pérez-Rosas, Rada Mihalcea, Louis-Philippe Morency. **Utterance-Level Multimodal Sentiment Analysis**. ACL 2013. [[paper]](https://aclanthology.org/P13-1096/) [[code]](https://web.eecs.umich.edu/~mihalcea/downloads.html)

## 2. Multimodal-Aspect-based-Sentiment-Analysis
### 2.1 paper
1. 【all sub-tasks】 Yan Ling, Jianfei Yu, Rui Xia. **Vision-Language Pre-Training for Multimodal Aspect-Based Sentiment Analysis**. ACL 2022. [[paper]](https://aclanthology.org/2022.acl-long.152/) [[code]](https://github.com/NUSTM/VLP-MABSA)

1. 【all sub-tasks】 Xincheng Ju, Dong Zhang, Rong Xiao, Junhui Li, Shoushan Li, Min Zhang, Guodong Zhou. **Joint Multi-modal Aspect-Sentiment Analysis with Auxiliary Cross-modal Relation Detection**. EMNLP 2021. [[paper]](https://aclanthology.org/2021.emnlp-main.360/) [[code]](https://github.com/manlp-suda/jml)

1. 	Nan Xu, Wenji Mao, Guandan Chen. **Multi-Interactive Memory Network for Aspect Based Multimodal Sentiment Analysis**. AAAI 2019. [[paper]](https://ojs.aaai.org//index.php/AAAI/article/view/3807) [[code]](https://github.com/xunan0812/MIMN)

### 2.2 datasets


## 3. Multimodal-Targeted-Sentiment-Analysis
### 3.1 paper
1. Jianfei Yu, Jieming Wang, Rui Xia, Junjie Li. **Targeted Multimodal Sentiment Classification based on Coarse-to-Fine Grained Image-Target Matching**. IJCAI 2022. 


### 3.2 datasets


## 4. Multimodal-Sarcasm-Detection
### 4.1 paper
1. Bin Liang, Chenwei Lou, Xiang Li, Min Yang, Lin Gui, Yulan He, Wenjie Pei, Ruifeng Xu. **Multi-Modal Sarcasm Detection via Cross-Modal Graph Convolutional Network**. ACL 2022. [[paper]](https://aclanthology.org/2022.acl-long.124/) [[code]](https://github.com/HITSZ-HLT/CMGCN)

1.【Joint sentiment】 Yaochen Liu, Yazhou Zhang, Qiuchi Li, Benyou Wang, Dawei Song. **What Does Your Smile Mean? Jointly Detecting Multi-Modal Sarcasm and Sentiment Using Quantum Probability**. EMNLP findings 2021. [[paper]](https://aclanthology.org/2021.findings-emnlp.74/)

1. Dushyant Singh Chauhan, Dhanush S R, Asif Ekbal, Pushpak Bhattacharyya. **Sentiment and Emotion help Sarcasm? A Multi-task Learning Framework for Multi-Modal Sarcasm, Sentiment and Emotion Analysis**. ACL 2020. [[paper]](https://aclanthology.org/2020.acl-main.401/) [[code]](https://www.iitp.ac.in/~ai-nlp-ml/resources.html)
 
1. Hongliang Pan, Zheng Lin, Peng Fu, Yatao Qi, Weiping Wang. **Modeling Intra and Inter-modality Incongruity for Multi-Modal Sarcasm Detection**. EMNLP findings 2020. [[paper]](https://aclanthology.org/2020.findings-emnlp.124/) [[code]](https://www.iitp.ac.in/~ai-nlp-ml/resources.html)

1. Santiago Castro, Devamanyu Hazarika, Verónica Pérez-Rosas, Roger Zimmermann, Rada Mihalcea, Soujanya Poria. **Towards Multimodal Sarcasm Detection (An _Obviously_ Perfect Paper)**. ACL 2019. [[paper]](https://aclanthology.org/P19-1455/) [[code]](https://github.com/soujanyaporia/MUStARD)

### 4.2 datasets


## 5. Multimodal-Emotion-Recognition
### 5.1 paper
1. Yi Zhang, Mingyuan Chen, Jundong Shen, Chongjun Wang. **Tailor Versatile Multi-modal Learning for Multi-label Emotion Recognition**. AAAI 2022. [[paper]](https://arxiv.org/pdf/2201.05834.pdf) [[code]](https://github.com/kniter1/TAILOR)

1. Jingwen Hu, Yuchen Liu, Jinming Zhao, Qin Jin. **MMGCN: Multimodal Fusion via Deep Graph Convolution Network for Emotion Recognition in Conversation**. ACL 2021. [[paper]](https://aclanthology.org/2021.acl-long.440/) [[code]](https://github.com/hujingwen6666/MMGCN)

1. Jinming Zhao, Ruichen Li, Qin Jin. **Missing Modality Imagination Network for Emotion Recognition with Uncertain Missing Modalities**. ACL 2021. [[paper]](https://aclanthology.org/2021.acl-long.203/) [[code]](https://github.com/AIM3-RUC/MMIN)

1. Wenliang Dai, Samuel Cahyawijaya, Zihan Liu, Pascale Fung. **Multimodal End-to-End Sparse Model for Emotion Recognition**. NAACL 2021. [[paper]](https://aclanthology.org/2021.naacl-main.417/) [[code]](https://github.com/wenliangdai/Multimodal-End2end-Sparse)

1. Vandana Rajan; Alessio Brutti; Andrea Cavallaro. **Is Cross-Attention Preferable to Self-Attention for Multi-Modal Emotion Recognition?**. ICASSP 2022. [[paper]](https://ieeexplore.ieee.org/document/9746924)

1. Licai Sun; Bin Liu; Jianhua Tao; Zheng Lian. **Multimodal Cross- and Self-Attention Network for Speech Emotion Recognition**. ICASSP 2021. [[paper]](https://ieeexplore.ieee.org/document/9414654)

1. 【Multi-label Emotion Detection】Dong Zhang, Xincheng Ju, Junhui Li, Shoushan Li, Qiaoming Zhu, Guodong Zhou. **Multi-modal Multi-label Emotion Detection with Modality and Label Dependence**. EMNLP 2020. [[paper]](https://aclanthology.org/2020.emnlp-main.291/) [[code]](https://github.com/MANLP-suda/MMS2S)

1. Gustavo Aguilar, Viktor Rozgic, Weiran Wang, Chao Wang. **Multimodal and Multi-view Models for Emotion Recognition**. ACL 2019. [[paper]](https://aclanthology.org/P19-1095/) [[code]](https://github.com/MANLP-suda/MMS2S)

1. Md Shad Akhtar, Dushyant Chauhan, Deepanway Ghosal, Soujanya Poria, Asif Ekbal, Pushpak Bhattacharyya. **Multi-task Learning for Multi-modal Emotion Recognition and Sentiment Analysis**. NAACL 2019. [[paper]](https://aclanthology.org/N19-1034/) [[code]](https://github.com/DushyantChauhan/NAACL-19-CIM)

1. Runnan Li, Zhiyong Wu, Jia Jia, Yaohua Bu, Sheng Zhao, Helen Meng. **Towards Discriminative Representation Learning for Speech Emotion Recognition**. IJCAI 2019. [[paper]](https://www.ijcai.org/Proceedings/2019/0703.pdf) [[code]](https://github.com/thuhcsi/IJCAI2019-DRL4SER/)

### 5.2 datasets
1. 【Conversations Emotion Recognition】Soujanya Poria, Devamanyu Hazarika, Navonil Majumder, Gautam Naik, Erik Cambria, Rada Mihalcea. **MELD: A Multimodal Multi-Party Dataset for Emotion Recognition in Conversations**. ACL 2019. [[paper]](https://aclanthology.org/P19-1050/)[[code]](http://affective-meld.github.io)

## 6. Multimodal-Complaint-Identification
### 6.1 paper
1. Apoorva Singh, Soumyodeep Dey, Anamitra Singha, Sriparna Saha. **Sentiment and Emotion-aware Multi-modal Complaint Identification**. AAAI 2022. [[paper]](https://www.aaai.org/AAAI22Papers/AISI-12009.SinghA.pdf)

### 6.2 datasets

## 7. Multimodal-Rumor-Detection
### 7.1 paper
1. Jiaqi Zheng, Xi Zhang, Sanchuan Guo, Quan Wang, Wenyu Zang, Yongdong Zhang. **MFAN: Multi-modal Feature-enhanced Attention Networks for Rumor Detection**. IJCAI 2022.

1. 【Fake News Detection】 Yang Wu, Pengwei Zhan, Yunjian Zhang, Liming Wang, Zhen Xu. **Multimodal Fusion with Co-Attention Networks for Fake News Detection**. ACL findings 2021. [[paper]](https://aclanthology.org/2021.findings-acl.226/) 

1. Mengzhu Sun, Xi Zhang, Jianqiang Ma, Yazheng Liu. **Inconsistency Matters: A Knowledge-guided Dual-inconsistency Network for Multi-modal Rumor Detection**. ENMLP findings 2021. [[paper]](https://aclanthology.org/2021.findings-emnlp.122/)[[code]](https://github.com/MengzSun/dual-inconsistency-rumor-detection-network)

1. 【Fake News Detection】 Yixuan Chen, Dongsheng Li, Peng Zhang, Jie Sui, Qin Lv, Lu Tun and Li Shang. **Cross-modal Ambiguity Learning for Multimodal Fake News Detection**. WWW 2022. [[paper]](https://dl.acm.org/doi/10.1145/3485447.3511968) 

### 7.2 datasets


## 8. Multimodal-Hate-Detection
### 8.1 paper
1. Xianbing Zhou, Yang Yong, Xiaochao Fan, Ge Ren, Yunfeng Song, Yufeng Diao, Liang Yang, Hongfei Lin. **Hate Speech Detection Based on Sentiment Knowledge Sharing**. ACL 2021. [[paper]](https://aclanthology.org/2021.acl-long.556/) [[code]](https://github.com/1783696285/sks)

1. Austin Botelho, Scott Hale, Bertie Vidgen. **Deciphering Implicit Hate: Evaluating Automated Detection Algorithms for Multimodal Hate**. ACL findings 2021. [[paper]](https://aclanthology.org/2021.findings-acl.166/) [[code]](https://github.com/botelhoa/Dog_Whistle_Hate)



### 8.2 datasets


## 9. Others
### 9.1 paper
1. Pierre Colombo, Emile Chapuis, Matthieu Labeau, Chloé Clavel. **Improving Multimodal fusion via Mutual Dependency Maximisation**. EMNLP 2021. [[paper]](https://aclanthology.org/2021.emnlp-main.21/)

1. Jianing Yang, Yongxin Wang, Ruitao Yi, Yuying Zhu, Azaan Rehman, Amir Zadeh, Soujanya Poria, Louis-Philippe Morency. **MTAG: Modal-Temporal Attention Graph for Unaligned Human Multimodal Language Sequences**. NAACL 2021. [[paper]](https://aclanthology.org/2021.naacl-main.79/) [[paper]](https://github.com/jedyang97/MTAG)

1. 【Stress Detection】Yiqun Yao, Michalis Papakostas, Mihai Burzo, Mohamed Abouelenien, Rada Mihalcea. **MUSER: MUltimodal Stress detection using Emotion Recognition as an Auxiliary Task** NAACL 2021. [[paper]](https://aclanthology.org/2021.naacl-main.216/) [[code]](https://lit.eecs.umich.edu/downloads.html#MUSER)

### 9.2 datasets
1. 【Depression Detection】J Yoon, C Kang, S Kim, J Han. **D-Vlog: Multimodal Vlog Dataset for Depression Detection**. AAAI 2022. [[paper]](https://www.aaai.org/AAAI22Papers/AISI-6612.YoonJ.pdf)

1. 【Enthusiam Detection】 Carla Viegas, Malihe Alikhani. **Entheos: A Multimodal Dataset for Studying Enthusiasm**. ACL findings 2021. [[paper]](https://aclanthology.org/2021.findings-acl.180/) [[code]](https://github.com/clviegas/Entheos-Dataset)

1. Lin Su, Nan Duan, Edward Cui, Lei Ji, Chenfei Wu, Huaishao Luo, Yongfei Liu, Ming Zhong, Taroon Bharti, Arun Sacheti. **GEM: A General Evaluation Benchmark for Multimodal Tasks**. ACL findings 2021. [[paper]](https://aclanthology.org/2021.findings-acl.229/) [[code]](https://github.com/microsoft/GEM)

1. Tulika Saha, Apoorva Upadhyaya, Sriparna Saha, Pushpak Bhattacharyya. **Towards Sentiment and Emotion aided Multi-modal Speech Act Classification in Twitter**. NAACL 2021. [[paper]](https://aclanthology.org/2021.naacl-main.456/)

1. 【Humor Detection】Md Kamrul Hasan, Wasifur Rahman, AmirAli Bagher Zadeh, Jianyuan Zhong, Md Iftekhar Tanveer, Louis-Philippe Morency, Mohammed (Ehsan) Hoque. **UR-FUNNY: A Multimodal Language Dataset for Understanding Humor**. EMNLP 2019. [[paper]](https://aclanthology.org/D19-1211/) [[code]](https://github.com/ROC-HCI/UR-FUNNY)
