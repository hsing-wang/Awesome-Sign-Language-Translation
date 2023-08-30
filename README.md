# Awesome-Neural-Sign-Language-Translation


This is a neural sign language translation reading list maintained by [Xing Wang](http://xingwang4nlp.com/) and [Jinhui Ye](https://jhuiye.com/) 


* [Survey.](#survey)
* [Sign Language Gloss Translation.](#gloss)
* [Two-stage Sign Language Translation.](#Two-stage)
* [End-to-end Sign Translation.](#end2end)
* [Gloss-free Sign Translation .](#gloss-free)
* [Dataset.](#data)
* [WMT shared task on sign language translation.](#wmt)



<h2 id="survey">Survey</h2>

* [Sign Language Processing](https://research.sign.mt/). Moryossef, Amit and Goldberg, Yoav. (2021)
* [A survey on Sign Language machine translation](https://arxiv.org/abs/2301.07069). Adrián Núñez-Marcos, Olatz Perez-de-Viñaspre, Gorka Labaka. (Expert Systems with Applications 2022)
* [Machine translation from signed to spoken languages: state of the art and challenges](https://arxiv.org/abs/2202.03086). Mathieu De Coster, Dimitar Shterionov, Mieke Van Herreweghe and Joni Dambre. (Universal Access in the Information Society 2023)
* [Sign Language Translation: A Survey of Approaches and Techniques](https://www.mdpi.com/2079-9292/12/12/2678). Zeyu Liang, Huailing Li and Jianping Chai. (Electronics 2023)



<h2 id="gloss">Sign Language Gloss Translation</h2>

* [Data Augmentation for Sign Language Gloss Translation](https://aclanthology.org/2021.mtsummit-at4ssl.1.pdf). Amit Moryossef, Kayo Yin, Graham Neubig, Yoav Goldberg. (AT4SSL 2021)
* [Frozen Pretrained Transformers for Neural Sign Language Translation](https://aclanthology.org/2021.mtsummit-at4ssl.10.pdf). Mathieu De Coster, Karel D’Oosterlinck, Marija Pizurica, Paloma Rabaey, Severine Verlinden, Mieke Van Herreweghe and Joni Dambre. (AT4SSL 2021) {[code](https://github.com/m-decoster/fpt4slt)}
* [Approaching Sign Language Gloss Translation as a Low-Resource Machine Translation Task](https://aclanthology.org/2021.mtsummit-at4ssl.7.pdf). Xuan Zhang and Kevin Duh. (AT4SSL 2021)
* [Using Neural Machine Translation Methods for Sign Language Translation](https://aclanthology.org/2022.acl-srw.21). Galina Angelova, Eleftherios Avramidis, Sebastian Möller. (ACL SRW 2022) {[code](https://github.com/DFKI-SignLanguage/gloss-to-text-sign-language-translation)}
* [Scaling Back-Translation with Domain Text Generation for Sign Language Gloss Translation](https://aclanthology.org/2023.eacl-main.34/). Jinhui Ye, Wenxiang Jiao, Xing Wang, Zhaopeng Tu. (EACL 2023) {[code](https://github.com/Atrewin/PGen)}


<h2 id="Two-stage"> Two-stage Sign Language Translation </h2>

* [TSPNet: Hierarchical Feature Learning via Temporal Semantic Pyramid for Sign Language Translation](https://proceedings.neurips.cc/paper/2020/file/8c00dee24c9878fea090ed070b44f1ab-Paper.pdf)  Dongxu Li, Chenchen Xu, Xin Yu, Kaihao Zhang, Benjamin Swift, Hanna Suominen, Hongdong Li. (NeurIPS 2020)
* [Better Sign Language Translation with STMC-Transformer](https://aclanthology.org/2022.loresmt-1.pdf)  Kayo Yin, Jesse Read. (COLING 2020)
* [Improving Sign Language Translation with Monolingual Data by Sign Back-Translation](http://openaccess.thecvf.com/content/CVPR2021/papers/Zhou_Improving_Sign_Language_Translation_With_Monolingual_Data_by_Sign_Back-Translation_CVPR_2021_paper.pdf)  Hao Zhou, Wengang Zhou, Weizhen Qi, Junfu Pu, Houqiang Li. (CVPR 2021)
* [Including Signed Languages in Natural Language Processing](https://arxiv.org/pdf/2105.05222)  Kayo Yin, Amit Moryossef, Julie Hochgesang, Yoav Goldberg, Malihe Alikhani. (arXiv preprint 2021)
* [Skeleton-Aware Neural Sign Language Translation](https://dl.acm.org/doi/pdf/10.1145/3474085.3475577?casa_token=AswxspbNYzgAAAAA:iJJ8tDNZuu8r0VCiDfHSV70A5vOgDk-ngKgm2X0chMcGuSBDxRW9TpSrvFjpwVH-dDtbf2VxDcMAUu29)  Shiwei Gan, Yafeng Yin, Zhiwei Jiang, Lei Xie, Sanglu Lu. (ACM MM 2021)
* [WearSign: Pushing the Limit of Sign Language Translation Using Inertial and EMG Wearables](https://dl.acm.org/doi/pdf/10.1145/3517257?casa_token=RFZGeppaecQAAAAA:qTKlWJXlUKMrVVxVX0O1MAqPGkLRu_OzT9z2R_XzUWmCs55jT9o8Q-eghh9-p52L8qU1z5IHGF6BCP8R) Qian Zhang, JiaZhen Jing, Dong Wang, Run Zhao. (ACM Interact. Mob. Wearable Ubiquitous Technol. 2022) 


<h2 id="end2end"> End-to-end Sign Translation </h2>

* [Sign Language Transformers: Joint End-to-End Sign Language Recognition and Translation](http://openaccess.thecvf.com/content_CVPR_2020/papers/Camgoz_Sign_Language_Transformers_Joint_End-to-End_Sign_Language_Recognition_and_Translation_CVPR_2020_paper.pdf).  Necati Cihan Camgoz, Oscar Koller, Simon Hadfield, Richard Bowden. (CVPR 2020) {[code](https://github.com/neccam/slt)}
* [SimulSLT: End-to-End Simultaneous Sign Language Translation](https://arxiv.org/abs/2112.04228).  Aoxiong Yin, Zhou Zhao, Jinglin Liu, Weike Jin, Meng Zhang, Xingshan Zeng, Xiaofei He. (ACM MM 2021)
* [Contrastive Disentangled Meta-Learning for Signer-Independent Sign Language Translation](https://dl.acm.org/doi/pdf/10.1145/3474085.3475456?casa_token=wDqujzOY8qoAAAAA:KFwcBI5nlgpabQPV0fLvQ34PovxsydAyge6xPn1KrTMe5G_lkktvkAL4ZQ9XRa-cFSbRTaFMYcXaiK9C). Tao Jin, Zhou Zhao. (ACM MM 2021)
* [Prior Knowledge and Memory Enriched Transformer for Sign Language Translation](https://aclanthology.org/2022.findings-acl.297/). Tao Jin, Zhou Zhao, Meng Zhang, Xingshan Zeng. (Findings of ACL 2022)
* [Two-Stream Network for Sign Language Recognition and Translation](https://proceedings.neurips.cc/paper_files/paper/2022/file/6cd3ac24cdb789beeaa9f7145670fcae-Paper-Conference.pdf). Yutong Chen, Ronglai Zuo, Fangyun Wei, Yu Wu, Shujie Liu, Brian Mak. (NeurIPS 2022) {[code](https://github.com/FangyunWei/SLRT/tree/main/TwoStreamNetwork)}
* [Mc-slt: Towards Low-Resource Signer-Adaptive Sign Language Translation](https://dl.acm.org/doi/pdf/10.1145/3474085.3475456) Tao Jin, Zhou Zhao, Meng Zhang, Xingshan Zeng. (ACM MM 2022)
* [A Simple Multi-Modality Transfer Learning Baseline for Sign Language Translation](http://openaccess.thecvf.com/content/CVPR2022/papers/Chen_A_Simple_Multi-Modality_Transfer_Learning_Baseline_for_Sign_Language_Translation_CVPR_2022_paper.pdf). Yutong Chen, Fangyun Wei, Xiao Sun, Zhirong Wu, Stephen Lin. (CVPR 2022) {[code](https://github.com/FangyunWei/SLRT/tree/main/TwoStreamNetwork)}
* [MLSLT: Towards Multilingual Sign Language Translation](https://openaccess.thecvf.com/content/CVPR2022/papers/Yin_MLSLT_Towards_Multilingual_Sign_Language_Translation_CVPR_2022_paper.pdf). Aoxiong Yin, Zhou Zhao, Weike Jin, Meng Zhang, Xingshan Zeng, Xiaofei He. (CVPR 2022) {[code](https://github.com/MLSLT/SP-10)}
* [Sign Language Translation with Hierarchical Spatio-Temporal Graph Neural Network](https://openaccess.thecvf.com/content/WACV2022/papers/Kan_Sign_Language_Translation_With_Hierarchical_Spatio-Temporal_Graph_Neural_Network_WACV_2022_paper.pdf). Jichao Kan, Kun Hu, Markus Hagenbuchner, Ah Chung Tsoi, Mohammed Bennamounm, Zhiyong Wang. (CVPR 2022)
* [Addressing Resource Scarcity across Sign Languages with Multilingual Pretraining and Unified-Vocabulary Datasets](https://openreview.net/forum?id=zBBmV-i84Go). NC Gokul, Manideep Ladi, Sumit Negi, Prem Selvaraj, Pratyush Kumar, Mitesh M Khapra. (NeurIPS 2022 Track Datasets and Benchmarks) {[code](https://openhands.ai4bharat.org/en/latest/)}
* [SLTUNET: A Simple Unified Model for Sign Language Translation](https://arxiv.org/abs/2305.01778). Biao Zhang, Mathias Müller, Rico Sennrich. (ICLR 2023) {[code](https://github.com/bzhangGo/sltunet)}
* [Cross-modality Data Augmentation for End-to-End Sign Language Translation](https://arxiv.org/abs/2305.11096). Jinhui Ye, Wenxiang Jiao, Xing Wang, Zhaopeng Tu, Hui Xion. (arxiv 2023) {[code](https://github.com/Atrewin/SignXmDA)}




<h2 id="gloss-free"> Gloss-free Sign Translation </h2>

* [Gloss-free Sign Language Translation: Improving from Visual-Language Pretraining](https://arxiv.org/pdf/2307.14768) Benjia Zhou, Zhigang Chen, Albert Clapés, Jun Wan, Yanyan Liang, Sergio Escalera, Zhen Lei, Du Zhang. (ICCV 2023) {[code](https://github.com/zhoubenjia/GFSLT-VLP)}
* [Gloss-Free End-to-End Sign Language Translation](https://arxiv.org/pdf/2305.12876) Lin, Kezhou and Wang, Xiaohan and Zhu, Linchao and Sun, Ke and Zhang, Bang and Yang, Yi (ACL 2023) {[code](https://github.com/HenryLittle/GloFE)}
* [Gloss Attention for Gloss-free Sign Language Translation](http://openaccess.thecvf.com/content/CVPR2023/papers/Yin_Gloss_Attention_for_Gloss-Free_Sign_Language_Translation_CVPR_2023_paper.pdf)  Aoxiong Yin, Tianyun Zhong, Li Tang, Weike Jin, Tao Jin, Zhou Zhao. (CVPR 2023) {[code](https://github.com/YinAoXiong/GASLT)}



<h2 id="data">Dataset</h2>

* [RWTH-PHOENIX-Weather 2014 T](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/). Human Language Technology and Pattern Recognition Group at the RWTH Aachen University
* [CSL-Daily Dataset](https://ustc-slr.github.io/datasets/2021_csl_daily/). Visual Sign Language Research Group at the University of Science and Technology of China
* [How2Sign](https://how2sign.github.io/) Universitat Politecnica de Catalunya / Barcelona Supercomputing Center /Institut de Robotica i Informatica Industrial, CSIC-UPC / Carnegie Mellon University / Facebook AI / Gallaudet University
* [BOBSL: BBC-Oxford British Sign Language Dataset](https://www.robots.ox.ac.uk/~vgg/data/bobsl/#data). Visual Geometry Group at the University of Oxford
* [YouTube-ASL](https://github.com/google-research/google-research/tree/master/youtube_asl). Google 


<h2 id="wmt">WMT shared task on sign language translation</h2>

* [Findings of the First WMT Shared Task on Sign Language Translation (WMT-SLT22)](https://www.statmt.org/wmt22/pdf/2022.wmt-1.71.pdf). Mathias Müller, Sarah Ebling, Eleftherios Avramidis, Alessia Battisti, Michèle Berger, Richard Bowden, Annelies Braffort, Necati Cihan Camgöz, Cristina España-Bonet, Roman Grundkiewicz, Zifan Jiang, Oscar Koller, Amit Moryossef, Regula Perrollaz, Sabine Reinhard, Annette Rios, Dimitar Shterionov, Sandra Sidler-Miserez, Katja Tissi and Davy Van Landuyt. (WMT 2023)




