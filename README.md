<h1 align="center"> Awesome Parametric Knowledge in LLMs</h1>


<div align="center">

[![LICENSE](https://img.shields.io/github/license/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)](https://github.com/Trae1ounG/Awesome-parametric-Knowledge-in-LLMs/blob/main/LICENSE)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![commit](https://img.shields.io/github/last-commit/Trae1ounG/Awesome-parametric-Knowledge-in-LLMs?color=blue)](https://github.com/Xnhyacinth/Long_Text_Modeling_Papers/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/Trae1ounG/Awesome-parametric-Knowledge-in-LLMs/pulls)
[![GitHub Repo stars](https://img.shields.io/github/stars/Trae1ounG/Awesome-parametric-Knowledge-in-LLMs)](https://github.com/Trae1ounG/Awesome-parametric-Knowledge-in-LLMs)
<!-- ![license](https://img.shields.io/bower/l/bootstrap?style=plastic) -->

</div>
This repo includes papers about parametric knowledge in LLMs, now we have parametric knowledge detection and parametric knowledge application these two main categories!👻

We believe that the parametric knowledge in LLMs is still a largely unexplored area, and we hope this repository will provide you with some valuable insights!😶‍🌫️

# Prametric Knowledge Detection
## Knowledge in Transformer-based Model——Analysis🧠
### 2025
1. **[Decoding specialised feature neurons in LLMs with the final projection layer](http://arxiv.org/abs/2501.02688)**

    [Logits Lens, Analysis of Query Neuron]
### 2024
1. **[What does the knowledge neuron thesis  have to do with knowledge? ](https://arxiv.org/abs/2405.02421)**

    *Jingcheng Niu, Andrew Liu, Zining Zhu, Gerald Penn.*   ICLR'24(Spotlight)

2. **[Knowledge Mechanisms in Large Language Models: A Survey and Perspective](https://arxiv.org/abs/2407.15017)**

    *Mengru Wang, Yunzhi Yao, Ziwen Xu, Shuofei Qiao, Shumin Deng, Peng Wang, Xiang Chen, Jia-Chen Gu, Yong Jiang, Pengjun Xie, Fei Huang, Huajun Chen, Ningyu Zhang.* EMNLP'24 Findings

3. **[Disentangling Memory and Reasoning Ability in Large Language Models](https://arxiv.org/abs/2411.13504v2)** [![github repo stars](https://img.shields.io/github/stars/MingyuJ666/Disentangling-Memory-and-Reasoning)](https://github.com/MingyuJ666/Disentangling-Memory-and-Reasoning)

    *Mingyu Jin, Weidi Luo, Sitao Cheng, Xinyi Wang, Wenyue Hua, Ruixiang Tang, William Yang Wang, Yongfeng Zhang.* preprint'24

4. **[Linguistic collapse: Neural collapse in (large) language models](https://arxiv.org/abs/2405.17767)**[![github repo stars](https://img.shields.io/github/stars/rhubarbwu/linguistic-collapse)]( https://github.com/rhubarbwu/linguistic-collapse)

    *Robert Wu, Vardan Papyan.* NIPS'24

5. **[Understanding the Interplay between Parametric and Contextual Knowledge for Large Language Models](https://arxiv.org/abs/2410.08414)**[![github repo stars](https://img.shields.io/github/stars/sitaocheng/Knowledge_Interplay)](https://github.com/sitaocheng/Knowledge_Interplay)

    *Sitao Cheng, Liangming Pan, Xunjian Yin, Xinyi Wang, William Yang Wang.* Preprint'24

6. **[Evaluating the External and Parametric Knowledge Fusion of Large Language Models](https://arxiv.org/abs/2405.19010)**

    *Hao Zhang, Yuyang Zhang, Xiaoguang Li, Wenxuan Shi, Haonan Xu, Huanshuo Liu, Yasheng Wang, Lifeng Shang, Qun Liu, Yong Liu, Ruiming Tang.* Preprint'24 

7. **[Adaptive Chameleon or Stubborn Sloth: Revealing the Behavior of Large Language Models in Knowledge Conflicts](https://arxiv.org/abs/2305.13300)**[![github repo stars](https://img.shields.io/github/stars/OSU-NLP-Group/LLM-Knowledge-Conflict)](https://github.com/OSU-NLP-Group/LLM-Knowledge-Conflict)

    *Jian Xie, Kai Zhang, Jiangjie Chen, Renze Lou, Yu Su.* ICLR'24 Spotlight

8. **[Knowledge entropy decay during language model pretraining hinders new knowledge acquisition](https://arxiv.org/abs/2410.01380)**

    *Jiyeon Kim, Hyunji Lee, Hyowon Cho, Joel Jang, Hyeonbin Hwang, Seungpil Won, Youbin Ahn, Dohaeng Lee, Minjoon Seo.* Preprint'24

9. **[When Context Leads but Parametric Memory Follows in Large Language Models](https://arxiv.org/abs/2409.08435)**[![github repo stars](https://img.shields.io/github/stars/PortNLP/WikiAtomic)](https://github.com/PortNLP/WikiAtomic)

    *Yufei Tao, Adam Hiatt, Erik Haake, Antonie J. Jetter, Ameeta Agrawal.* EMNLP'24

10. **[Neuron-level knowledge attribution in large language models](https://arxiv.org/abs/2312.12141)**[![github repo stars](https://img.shields.io/github/stars/zepingyu0512/neuron-attribution)](https://github.com/zepingyu0512/neuron-attribution)

    *Zeping Yu, Sophia Ananiadou.* EMNLP'24

11. **[Dissecting recall of factual associations in auto-regressive language models](http://arxiv.org/abs/2304.14767)**[[code](https://github.com/google-research/google-research/tree/master/dissecting_factual_predictions)]

    *Mor Geva, Jasmijn Bastings, Katja Filippova, Amir Globerson.* EMNLP'23

### 2021
1. **[Transformer Feed-Forward Layers Are Key-Value Memories](https://arxiv.org/abs/2012.14913)** 

    *Mor Geva, Roei Schuster, Jonathan Berant, Omer Levy.* EMNLP'21
## Knowledge in Transformer-based Model——Causal Tracing🦾
1. **[Does knowledge localization hold true? Surprising differences between entity and relation perspectives in language models](https://arxiv.org/pdf/2409.00617)**

    *Yifan Wei, Xiaoyan Yu, Yixuan Weng, Huanhuan Ma, Yuanzhe Zhang, Jun Zhao, Kang Liu.* CIKM'24

### 2022
1. **[Locating and Editing Factual Associations in GPT](https://arxiv.org/abs/2202.05262)**

    *Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov.* NIPS'22
### 2024
## Knowledge in Transformer-based Model——Gradient Attribution👀

1. **[Identifying query-relevant neurons in large language models for long-form texts](https://arxiv.org/abs/2406.10868)**

    *Lihu Chen, Adam Dejl, Francesca Toni.* Preprint'24

2. **[Revealing the parametric knowledge of language models: A unified framework for attribution methods](https://arxiv.org/abs/2404.18655)**

    *Haeun Yu, Pepa Atanasova, Isabelle Augenstein.* ACL'24
3. **[Does Large Language Model contain Task-Specific Neurons.](https://aclanthology.org/2024.emnlp-main.403/)**

    *Ran Song, Shizhu He, Shuting Jiang, Yantuan Xian, Shengxiang Gao, Kang Liu, and Zhengtao Yu.* EMNLP'24

4. **[Journey to the center of the knowledge neurons: Discoveries of language-independent knowledge neurons and degenerate knowledge neurons](http://arxiv.org/abs/2308.13198)**[![github repo stars](https://img.shields.io/github/stars/heng840/AMIG)](https://github.com/heng840/AMIG)

    *Yuheng Chen, Pengfei Cao, Yubo Chen, Kang Liu, Jun Zhao.* AAAI'24
### 2022
1. **[Knowledge Neurons in Pretrained Transformers](https://arxiv.org/abs/2104.08696)**[![github repo stars](https://img.shields.io/github/stars/Hunter-DDM/knowledge-neurons)](https://github.com/Hunter-DDM/knowledge-neurons)

    *Damai Dai, Li Dong, Yaru Hao, Zhifang Sui, Baobao Chang, Furu Wei.* ACL'22

## Knowledge in Transformer-based Model——Activation🫀
### 2024
1. **[Separating tongue from thought: Activation patching reveals language-agnostic concept representations in transformers](https://arxiv.org/abs/2411.08745)** [![github repo stars](https://img.shields.io/github/stars/Butanium/llm-lang-agnostic)](https://github.com/Butanium/llm-lang-agnostic)

    *Clément Dumas, Chris Wendler, Veniamin Veselovsky, Giovanni Monea, Robert West.* ICLR'24 Spotlight

2. **[From yes-men to truth-tellers Addressing sycophancy in large language models with pinpoint tuning](https://arxiv.org/pdf/2409.01658v2)**

    *Wei Chen, Zhen Huang, Liang Xie, Binbin Lin, Houqiang Li, Le Lu, Xinmei Tian, Deng Cai, Yonggang Zhang, Wenxiao Wang, Xu Shen, Jieping Ye.* ICML'24

3. **[Language-specific neurons: The key to multilingual capabilities in large language models.](https://arxiv.org/abs/2402.16438)**

    *Tianyi Tang, Wenyang Luo, Haoyang Huang, Dongdong Zhang, Xiaolei Wang, Xin Zhao, Furu Wei, Ji-Rong Wen.* ACL'24

4. **[Multi-property Steering of Large Language Models with Dynamic Activation Composition](https://arxiv.org/abs/2406.17563)** [![github repo stars](https://img.shields.io/github/stars/DanielSc4/Dynamic-Activation-Composition)](https://github.com/DanielSc4/Dynamic-Activation-Composition)

    *Daniel Scalena, Gabriele Sarti, Malvina Nissim.* ACL'24 BlackboxNLP Workshop

5. **[Exploring the benefit of activation sparsity in pre-training](http://arxiv.org/abs/2410.03440)**[![github repo stars](https://img.shields.io/github/stars/thunlp/moefication)](https://github.com/thunlp/moefication)

    [MoE, Activation Sparsity, Activation Pattern, Inference Speedup]
    *Zhengyan Zhang, Chaojun Xiao, Qiujieli Qin, Yankai Lin, Zhiyuan Zeng, Xu Han, Zhiyuan Liu, Ruobing Xie, Maosong Sun, Jie Zhou.* ICML'24


## 2023
1. **[Activation Addition: Steering Language Models Without Optimization](https://arxiv.org/abs/2308.10248v4)**

    *Alexander Matt Turner, Lisa Thiergart, Gavin Leech, David Udell, Juan J. Vazquez, Ulisse Mini, Monte MacDiarmid.* Preprint'23

2. **[Deja vu: Contextual sparsity for efficient LLMs at inference time](http://arxiv.org/abs/2310.17157)**

    [Sparsity, Inference Speedup]
    *Zichang Liu, Jue Wang, Tri Dao, Tianyi Zhou, Binhang Yuan, Zhao Song, Anshumali Shrivastava, Ce Zhang, Yuandong Tian, Christopher Re, Beidi Chen.* ICML'23




# Parametric Knowledge Application
## Knowledge Editing 🧑‍⚕️
### 2024
1. **[A Comprehensive Study of Knowledge Editing for Large Language Models](https://arxiv.org/abs/2401.01286)**

    *Ningyu Zhang, Yunzhi Yao, Bozhong Tian, Peng Wang, Shumin Deng, Mengru Wang, Zekun Xi, Shengyu Mao, Jintian Zhang, Yuansheng Ni, Siyuan Cheng, Ziwen Xu, Xin Xu, Jia-Chen Gu, Yong Jiang, Pengjun Xie, Fei Huang, Lei Liang, Zhiqiang Zhang, Xiaowei Zhu, Jun Zhou, Huajun Chen.* Preprint'24

2. **[FAME: Towards Factual Multi-Task Model Editing](https://arxiv.org/abs/2410.10859)**[![GitHub Repo stars](https://img.shields.io/github/stars/BITHLP/FAME)](https://github.com/BITHLP/FAME)
    *Li Zeng, Yingyu Shan, Zeming Liu, Jiashu Yao, Yuhang Guo.* EMNLP'24

3. **[To Forget or Not? Towards Practical Knowledge Unlearning for Large Language Models](https://arxiv.org/abs/2407.01920)**[![github repo stars](https://img.shields.io/github/stars/zjunlp/KnowUnDo)](https://github.com/zjunlp/KnowUnDo)

    *Bozhong Tian, Xiaozhuan Liang, Siyuan Cheng, Qingbin Liu, Mengru Wang, Dianbo Sui, Xi Chen, Huajun Chen, Ningyu Zhang.* EMNLP'24 findings

4. **[Understanding the Collapse of LLMs in Model Editing](https://arxiv.org/abs/2406.11263)**

    *Wanli Yang, Fei Sun, Jiajun Tan, Xinyu Ma, Du Su, Dawei Yin, Huawei Shen.* EMNLP'24 findings

5. **[Is it possible to edit large language models robustly?](https://arxiv.org/pdf/2402.05827)**[![github repo stars](https://img.shields.io/github/stars/xbmxb/edit_analysis)](https://github.com/xbmxb/edit_analysis)

    *Xinbei Ma, Tianjie Ju, Jiyang Qiu, Zhuosheng Zhang, Hai Zhao, Lifeng Liu, Yulong Wang.* Preprint'24

6. **[Retrieval-enhanced Knowledge Editing in Language Models for Multi-Hop Question Answering](https://arxiv.org/pdf/2403.19631)**[![github repo stars](https://img.shields.io/github/stars/sycny/RAE)](https://github.com/sycny/RAE)

    *Yucheng Shi, Qiaoyu Tan, Xuansheng Wu, Shaochen Zhong, Kaixiong Zhou, Ninghao Liu.* CIKM'24

7. **[Latent paraphrasing: Perturbation on layers improves knowledge injection in language models](https://arxiv.org/abs/2411.00686)**

    *Minki Kang, Sung Ju Hwang, Gibbeum Lee, Jaewoong Cho.* NIPS'24

8. **[Learning to edit: Aligning LLMs with knowledge editing](https://arxiv.org/abs/2402.11905)**[![github repo stars](https://img.shields.io/github/stars/YJiangcm/LTE)](https://github.com/YJiangcm/LTE)

    *Yuxin Jiang, Yufei Wang, Chuhan Wu, Wanjun Zhong, Xingshan Zeng, Jiahui Gao, Liangyou Li, Xin Jiang, Lifeng Shang, Ruiming Tang, Qun Liu, Wei Wang.* ACL'24

9. **[Inspecting and Editing Knowledge Representations in Language Models](https://arxiv.org/abs/2304.00740)**[![github repo stars](https://img.shields.io/github/stars/evandez/REMEDI)](https://github.com/evandez/REMEDI)

    *Evan Hernandez, Belinda Z. Li, Jacob Andreas.* COLM'24

10. **[Forgetting before learning: Utilizing parametric arithmetic for knowledge updating in large language models](https://arxiv.org/abs/2311.08011)**

    *Shiwen Ni, Dingwei Chen, Chengming Li, Xiping Hu, Ruifeng Xu, Min Yang.* ACL'24

11. **[Ethos: Rectifying language models in orthogonal parameter space](http://arxiv.org/abs/2403.08994)**

    [Toxic/Bias Unlearning, SVD, Analysis of Parametric Knowledge, Task Vector]

    NAACL'24 findings

### 2023
1. **[Editing Large Language Models: Problems, Methods, and Opportunities](https://arxiv.org/abs/2305.13172)**

    *Yunzhi Yao, Peng Wang, Bozhong Tian, Siyuan Cheng, Zhoubo Li, Shumin Deng, Huajun Chen, Ningyu Zhang.* EMNLP'23
### 2022
1. **[Locating and Editing Factual Associations in GPT](https://arxiv.org/abs/2202.05262)**

    *Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov.* NIPS'22
2. **[Memory-Based Model Editing at Scale](https://arxiv.org/abs/2206.06520)**

    *Eric Mitchell, Charles Lin, Antoine Bosselut, Christopher D. Manning, Chelsea Finn.* ICLR'22
### 2021
1. **[Editing Factual Knowledge in Language Models](https://arxiv.org/abs/2104.08164)**

    *Nicola De Cao, Wilker Aziz, Ivan Titov.* EMNLP'21
### 2020
1. **[Editable neural networks.](https://arxiv.org/abs/2004.00345)**

    *Anton Sinitsin, Vsevolod Plokhotnyuk, Dmitriy Pyrkin, Sergei Popov, Artem Babenko.* ICLR'20
## Knowledge Transfer🧚‍♀️
### 2024
1. **[Seeking Neural Nuggets: Knowledge Transfer in Large Language Models from a Parametric Perspective](https://arxiv.org/abs/2310.11451)**

 *Ming Zhong, Chenxin An, Weizhu Chen, Jiawei Han, Pengcheng He.* ICLR'24

2. **[Initializing models with larger ones](https://arxiv.org/abs/2311.18823)**[![github repo stars](https://img.shields.io/github/stars/OscarXZQ/weight-selection)](https://github.com/OscarXZQ/weight-selection)

    *Zhiqiu Xu, Yanjie Chen, Kirill Vishniakov, Yida Yin, Zhiqiang Shen, Trevor Darrell, Lingjie Liu, Zhuang Liu.* ICLR'24 **Spotlight**

3. **[Cross-model Control: Improving Multiple Large Language Models in One-time Training](https://www.arxiv.org/abs/2410.17599)**[![github repo stars](https://img.shields.io/github/stars/wujwyi/CMC)](https://github.com/wujwyi/CMC)

    *Jiayi Wu, Hao Sun, Hengyi Cai, Lixin Su, Shuaiqiang Wang, Dawei Yin, Xiang Li, Ming Gao.* NIPS'24

4. **[Knowledge fusion of large language models](https://arxiv.org/abs/2401.10491)**[![github repo stars](https://img.shields.io/github/stars/fanqiwan/FuseLLM)](https://github.com/fanqiwan/FuseLLM)

    *Fanqi Wan, Xinting Huang, Deng Cai, Xiaojun Quan, Wei Bi, Shuming Shi.* ICLR'24

5. **[Tuning language models by proxy](https://arxiv.org/abs/2401.08565)**[![github repo stars](https://img.shields.io/github/stars/alisawuffles/proxy-tuning)](https://github.com/alisawuffles/proxy-tuning)

    *Alisa Liu, Xiaochuang Han, Yizhong Wang, Yulia Tsvetkov, Yejin Choi, Noah A. Smith.* COLM'24

6. **[Chat vector: A simple approach to equip LLMs with instruction following and model alignment in new languages](http://arxiv.org/abs/2310.04799)**[![github repo stars](https://img.shields.io/github/stars/aqweteddy/ChatVector)](https://github.com/aqweteddy/ChatVector)
    
    [Task Vector, Parametric Knowledge, Knowledge Transfer]

    ACL'24

7. **[FedMKT: Federated Mutual Knowledge Transfer for Large and Small Language Models](https://arxiv.org/abs/2406.02224)**

    [Federated Learning, Knowledge Transfer, Heterogeneous Token Alignment]

    Coling'25

8. **[Function vectors in large language models](http://arxiv.org/abs/2310.15213)**

    [Function Vector, Causal Mediation, Mechanism Interpretation]

    ICLR'24

9. **[Refine large language model fine-tuning via instruction vector](http://arxiv.org/abs/2406.12227)**

    [Catastrophic Forgetting, Function Vector, Causal Mediation]

    Preprint'24

10. **[KlF: Knowledge localization and fusion for language model continual learning](http://arxiv.org/abs/2408.05200)**

    [Catastrophic Forgetting, Continual Learning, Sensetity-based Location]

    ACL'24

11. **[Language models are super mario: Absorbing abilities from homologous models as a free lunch](http://arxiv.org/abs/2311.03099)**

    [Knowledge Transfer, Model Merging, Efficient Skill] ICML'24

12. **[Beyond task vectors: Selective task arithmetic based on importance metrics](http://arxiv.org/abs/2411.16139)**
 
    [Task Vector, Sensetivity-based Importance Score, Model Merging] Preprint'24

### 2023   
1. **[Mutual enhancement of large and small language models with cross-silo knowledge transfer](https://arxiv.org/abs/2312.05842)**

    *Yongheng Deng, Ziqing Qiao, Ju Ren, Yang Liu, Yaoxue Zhang.* Preprint'23

2. **[Learning to grow pretrained models for efficient transformer training](https://arxiv.org/abs/2303.00980)**[![github repo stars](https://img.shields.io/github/stars/VITA-Group/LiGO)](https://github.com/VITA-Group/LiGO)

    *Peihao Wang, Rameswar Panda, Lucas Torroba Hennigen, Philip Greengard, Leonid Karlinsky, Rogerio Feris, David D. Cox, Zhangyang Wang, Yoon Kim.* ICLR'23 

3. **[Retrieval-based knowledge transfer: An effective approach for extreme large language model compression](https://arxiv.org/abs/2310.15594)**

    *Jiduan Liu, Jiahao Liu, Qifan Wang, Jingang Wang, Xunliang Cai, Dongyan Zhao, Ran Lucien Wang, Rui Yan.* EMNLP'23 Findings

4. **[Editing models with task arithmetic](http://arxiv.org/abs/2212.04089)**[![github repo stars](https://img.shields.io/github/stars/mlfoundations/task_vectors)](https://github.com/mlfoundations/task_vectors)

    [Task Vecotr, Parametric Knowledge, Knowledge Transfer, Multi-task Learning]

    ICLR'23

5. **[Task-Specific Skill Localization in Fine-tuned Language Models](http://arxiv.org/abs/2302.06600)**

    [Knowledge Transfer, Model Graft, Skill Parameter Localization]

    ICML'23

6. **[Composing parameter-efficient modules with arithmetic operations](http://arxiv.org/abs/2306.14870)**

    [PEFT, Task Vector, Model Merge]

    NIPS'23

7. **[Dataless knowledge fusion by merging weights of language models](http://arxiv.org/abs/2212.09849)**

    [Model Merge]

    ICLR'23
### 2021
1. **[Weight distillation: Transferring the knowledge in neural network parameters](https://arxiv.org/abs/2009.09152)**[![github repo stars](https://img.shields.io/github/stars/Lollipop321/weight-distillation)](https://github.com/Lollipop321/weight-distillation)

    *Ye Lin, Yanyang Li, Ziyang Wang, Bei Li, Quan Du, Tong Xiao, Jingbo Zhu.* ACL'21

## Activation Steering
## 2024
1. **[Multi-property Steering of Large Language Models with Dynamic Activation Composition](https://arxiv.org/abs/2406.17563)** [![github repo stars](https://img.shields.io/github/stars/DanielSc4/Dynamic-Activation-Composition)](https://github.com/DanielSc4/Dynamic-Activation-Composition)

    *Daniel Scalena, Gabriele Sarti, Malvina Nissim.* ACL'24 BlackboxNLP Workshop

2. **[Word embeddings are steers for language models](http://arxiv.org/abs/2305.12798)**

    [Word Embedding Steering, Generation Control] ACL'24

## 2023
1. **[Activation Addition: Steering Language Models Without Optimization](https://arxiv.org/abs/2308.10248v4)**

*Alexander Matt Turner, Lisa Thiergart, Gavin Leech, David Udell, Juan J. Vazquez, Ulisse Mini, Monte MacDiarmid.* Preprint'23
## Knowledge Distillation 
### 2024
1. **[PromptKD: Distilling Student-Friendly Knowledge for Generative Language Models via Prompt Tuning](https://arxiv.org/abs/2402.12842)**[![github repo stars](https://img.shields.io/github/stars/gmkim-ai/PromptKD)](https://github.com/gmkim-ai/PromptKD)(Note: not parametric)

    *Gyeongman Kim, Doohyuk Jang, Eunho Yang.* EMNLP'24 findings

2. **[From Instance Training to Instruction Learning: Task Adapters Generation from Instructions](https://arxiv.org/abs/2406.12382)**[![github repo stars](https://img.shields.io/github/stars/Xnhyacinth/TAGI)](https://github.com/Xnhyacinth/TAGI/)

    *Huanxuan Liao, Yao Xu, Shizhu He, Yuanzhe Zhang, Yanchao Hao, Shengping Liu, Kang Liu, Jun Zhao.* NIPS'24

3. **[When babies teach babies: Can student knowledge sharing outperform teacher-guided distillation on small datasets?](https://arxiv.org/abs/2411.16487v1)**

    *Srikrishna Iyer.* EMNLP'24  CoNLL Workshop

## Pramatric Quantization

### 2024

1. **[OneBit: Towards extremely low-bit large language models](https://arxiv.org/abs/2402.11295)** [![github repo stars](https://img.shields.io/github/stars/xuyuzhuang11/OneBit)]( https://github.com/xuyuzhuang11/OneBit)


    *Yuzhuang Xu, Xu Han, Zonghan Yang, Shuo Wang, Qingfu Zhu, Zhiyuan Liu, Weidong Liu, Wanxiang Che.* NIPS'24

### 2023

1. **[The cost of compression: Investigating the impact of compression on parametric knowledge in language models](https://arxiv.org/abs/2312.00960)** [![github repo stars](https://img.shields.io/github/stars/NamburiSrinath/LLMCompression)](https://github.com/NamburiSrinath/LLMCompression)

    *Satya Sai Srinath Namburi, Makesh Sreedhar, Srinath Srinivasan, Frederic Sala.* EMNLP'23 findings

## Knowledge Injection
### 2024
1. **[Awakening augmented generation: Learning to awaken internal knowledge of large language models for question answering](http://arxiv.org/abs/2403.15268)**[![github repo stars](https://img.shields.io/github/stars/Xnhyacinth/IAG)](https://github.com/Xnhyacinth/IAG)

    [HyperNet, RAG, Context Compression]

    *Huanxuan Liao, Shizhu He, Yao Xu, Yuanzhe Zhang, Kang Liu, Shengping Liu, Jun Zhao.* AAAI'25


### 2023
1. **[Memory injections: Correcting multi-hop reasoning failures during inference in transformer-based language models](http://arxiv.org/abs/2309.05605)**[![github repo stars](https://img.shields.io/github/stars/msakarvadia/memory_injections)](https://github.com/msakarvadia/memory_injections)

    *Mansi Sakarvadia, Aswathy Ajith, Arham Khan, Daniel Grzenda, Nathaniel Hudson, André Bauer, Kyle Chard, Ian Foster.*	Oral Presentation at BlackboxNLP Workshop at EMNLP'23

2. **[Decouple knowledge from parameters for plug-and-play language modeling](http://arxiv.org/abs/2305.11564)**[![github repo stars](https://img.shields.io/github/stars/Hannibal046/PlugLM)](https://github.com/Hannibal046/PlugLM)

    *Xin Cheng, Yankai Lin, Xiuying Chen, Dongyan Zhao, Rui Yan.* ACL'23 findings

3. **[IN-PARAMETER KNOWLEDGE INJECTION: INTEGRATING TEMPORARY CONTEXTUAL INFORMATION INTO  MODEL PARAMETERS](https://openreview.net/forum?id=sl4hOq9wm9)**

    submitted to ICLR'25
### 2022
1. **[Kformer: Knowledge injection in transformer feed-forward layers](http://arxiv.org/abs/2201.05742)**[![github repo stars](https://img.shields.io/github/stars/zjunlp/Kformer)](https://github.com/zjunlp/Kformer)

    *Yunzhi Yao, Shaohan Huang, Li Dong, Furu Wei, Huajun Chen, Ningyu Zhang.* NLPCC'22

## Parameter-Effecient Fine-tuning(PEFT)
### 2024
1. **[KaSA: Knowledge-aware singular-value adaptation of large language models](http://arxiv.org/abs/2412.06071)**[![github repo stars](https://img.shields.io/github/stars/juyongjiang/KaSA)](https://github.com/juyongjiang/KaSA)

    [Knowledge-aware LoRA, SVD]

    *Fan Wang, Juyong Jiang, Chansung Park, Sunghun Kim, Jing Tang.* Preprint'24

2. **[CorDA: Context-Oriented Decomposition Adaptation of Large Language Models for Task-Aware Parameter-Efficient Fine-tuning](https://arxiv.org/abs/2406.05223)**[![github repo stars](https://img.shields.io/github/stars/iboing/CorDA)](https://github.com/iboing/CorDA)

    [Knowledge-aware LoRA, SVD]

    *Yibo Yang, Xiaojie Li, Zhongzhu Zhou, Shuaiwen Leon Song, Jianlong Wu, Liqiang Nie, Bernard Ghanem.* NIPS'24

3. **[DoRA: Weight-Decomposed Low-Rank Adaptation](https://arxiv.org/abs/2402.09353)**[![github repo stars](https://img.shields.io/github/stars/NVlabs/DoRA)](https://github.com/NVlabs/DoRA)

    [Weight-Decomposed LoRA, SVD, Analysis of FT and LoRA]
    *Shih-Yang Liu, Chien-Yi Wang, Hongxu Yin, Pavlo Molchanov, Yu-Chiang Frank Wang, Kwang-Ting Cheng, Min-Hung Chen.* ICML'24 Oral

4. **[Low-rank adaptation with task-relevant feature enhancement for fine-tuning language models](http://arxiv.org/abs/2412.09827)**

    [Task-aware LoRA, Hidden Representation Enhancement] AAAI'25 CoLoRAI Workshop

5 **[Train small, infer large: Memory-efficient LoRA training for large language models](http://arxiv.org/abs/2502.13533)**

    [Memory-efficient LoRA Training, Pruning Methods, High memory efficiency]
## Continual Learning
### 2024
1. **[Learn more, but bother less: Parameter efficient continual learning](https://neurips.cc/virtual/2024/poster/94599)**

    [Continual Learning, Parameter Efficient, Knowledge Transfer] NIPS'24

2. **[What will my model forget? Forecasting forgotten examples in language model refinement](http://arxiv.org/abs/2402.01865)**

    [Catastrophic Forgetting, Forecasting Forgetting, Analysis] ICML'24 Spotlight
## RAG  
### 2024
1. **[xRAG: Extreme context compression for retrieval-augmented generation with one token](http://arxiv.org/abs/2405.13792)**

    [Context Compression, RAG, Multimodal Fusion] NIPS'24

2. **[Parametric retrieval augmented generation](http://arxiv.org/abs/2501.15915)**

    [Parametric RAG, Document Parameterization, Offline Method]

## Long Context Extend
### 2024

1. **[LongEmbed: Extending embedding models for long context retrieval](http://arxiv.org/abs/2404.12096)**

    [Long Context, Embedding Model, Benchmark] EMNLP'24

2. **[LLM maybe LongLM: Self-extend LLM context window without tuning](http://arxiv.org/abs/2401.01325)**

    [Long Context Extend, Plug-and-Play Method] ICML'24 Spotlight

3. **[Two stones hit one bird: Bilevel positional encoding for better length extrapolation](http://arxiv.org/abs/2401.16421)**

    [Long Context Extend, Absolute PE + Relative PE, Plug-and-Play but Training-based Method] ICML'24
### 2023
1. **YaRN: Efficient context window extension of large language models[http://arxiv.org/abs/2309.00071]**

    [Long Context Extend, Variation of RoPE] ICLR'24
### 2022
1. **[Train short, test long: Attention with linear biases enables input length extrapolation](http://arxiv.org/abs/2108.12409)**

    [Alibi, Long Context Extrapolate, Training-based Method] ICLR'22

### 2021
1. **[RoFormer: Enhanced Transformer with Rotary Position Embedding.](https://arxiv.org/abs/2104.09864)**

    [Rotary Position Embedding, Classic]


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Trae1ounG/Awesome-parametric-Knowledge-in-LLMs&type=Date)](https://star-history.com/#Trae1ounG/Awesome-parametric-Knowledge-in-LLMs&Date)