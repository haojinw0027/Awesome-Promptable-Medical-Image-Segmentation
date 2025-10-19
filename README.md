# <p align=center>`Awesome-Promptable-Medical-Image-Segmentation`</p> # 


## Contents<!-- omit in toc -->
- [`Awesome-Promptable-Medical-Image-Segmentation`](#awesome-promptable-medical-image-segmentation)
  - [🛏️ Embedding Prompt](#️-embedding-prompt)
  - [🎯 Point Prompt](#-point-prompt)
  - [📦 Box Prompt](#-box-prompt)
  - [🎭 Mask Prompt](#-mask-prompt)
  - [📖 Text Prompt](#-text-prompt)
  - [🎨 Multimodal Prompt Fusion](#-multimodal-prompt-fusion)
  - [🔔 Prompt Generation and Optimization](#-prompt-generation-and-optimization)

## 🛏️ Embedding Prompt
**CEmb-SAM: Segment Anything Model with Condition Embedding for Joint Learning from Heterogeneous Datasets** \
*Dongik Shin, Beomsuk Kim, M.D. and Seungjun Baek* <br>
[MICCAI 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-47401-9_27)] [[ArXiv](https://arxiv.org/abs/2308.06957)] [[Code](https://github.com/i-dongik/CEmb-SAM)]

**Automating MedSAM by Learning Prompts with Weak Few-Shot Supervision** \
*Mélanie Gaillochet, Christian Desrosiers and Hervé Lombaert* <br>
[MedAGI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-73471-7_7)] [[ArXiv](https://arxiv.org/abs/2409.20293)] [[Code](https://github.com/Minimel/MedSAMWeakFewShotPromptAutomation)]

**AutoProSAM: Automated Prompting SAM for 3D Multi-Organ Segmentation** \
*Chengyin Li, Prashant Khanduri, Yao Qiang, Rafi Ibn Sultan, Indrin Chetty and Dongxiao Zhu* <br>
[WACV 2025] [[Paper](https://www.computer.org/csdl/proceedings-article/wacv/2025/108300d577/25KlAxa8iZO)] [[ArXiv](https://arxiv.org/abs/2308.14936)] [[Code](https://github.com/ChengyinLee/AutoProSAM_2024)]

**Diffusion-empowered AutoPrompt MedSAM** \
*Peng Huang, Shu Hu, Bo Peng, Xun Gong, Penghang Yin, Hongtu Zhu, Xi Wu, Xin Wang* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2502.06817)] [[Code](https://github.com/HP-ML/AutoPromptMedSAM)]

**De-LightSAM: Modality-Decoupled Lightweight SAM for Generalizable Medical Segmentation** \
*Qing Xu, Jiaxuan Li, Xiangjian He, Chenxin Li, Fiseha B. Tesem, Wenting Duan, Zhen Chen, Rong Qu, Jonathan M. Garibaldi, Chang Wen Chen* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2407.14153v5)] [[Code](https://github.com/xq141839/De-LightSAM)]

## 🎯 Point Prompt
**SAMAUG: POINT PROMPT AUGMENTATION FOR SEGMENT ANYTHING MODEL** \
*Haixing Dai, Chong Ma, Zhiling Yan, Zhengliang Liu, Enze Shi, Yiwei Li, Peng Shu, Xiaozheng Wei, Lin Zhao, Zihao Wu, Fang Zeng, Dajiang Zhu, Wei Liu, Quanzheng Li, Lichao Sun, Shu Zhang, Tianming Liu, and Xiang Li* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2307.01187)]

**Self-Prompting Large Vision Models for Few-Shot Medical Image Segmentation** \
*Qi Wu, Yuyao Zhang and Marawan Elbatel* <br>
[DART 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-45857-6_16)] [[ArXiv](https://arxiv.org/abs/2308.07624)] [[Code](https://github.com/PeterYYZhang/few-shot-self-prompt-SAM)]

**EviPrompt: A training-free evidential prompt generation method for adapting segment anything model in medical images** \
*Yinsong Xu, Jiaqi Tang, Aidong Men and Qingchao Chen* <br>
[IEEE Trans. Image Process 2024] [[Paper](https://ieeexplore.ieee.org/document/10729707)] [[ArXiv](https://arxiv.org/abs/2311.06400)] [[Code](https://github.com/SPIresearch/EviPrompt)]

**SemiSAM: Enhancing Semi-Supervised Medical Image Segmentation via SAM-Assisted Consistency Regularization** \
[BIBM 2024] [[Paper](https://ieeexplore.ieee.org/abstract/document/10821951)] [[ArXiv](https://arxiv.org/abs/2312.06316)]

**Adapting Segment Anything Model to Melanoma Segmentation in Microscopy Slide Images** \
*Qingyuan Liu and Avideh Zakhor * <br>
[ECCV 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-91721-9_10)] [[ArXiv](https://arxiv.org/abs/2410.02207)] 

**Dr-SAM: An End-to-End Framework for Vascular Segmentation Diameter Estimation and Anomaly Detection on Angiography Images** \
*Vazgen Zohranyan, Vagner Navasardyan, Hayk Navasardyan, Jan Borggrefe and Shant Navasardyan* <br>
[CVPR 2024] [[Paper](https://openaccess.thecvf.com/content/CVPR2024W/DEF-AI-MIA/html/Zohranyan_Dr-SAM_An_End-to-End_Framework_for_Vascular_Segmentation_Diameter_Estimation_and_CVPRW_2024_paper.html)] [[ArViv](https://arxiv.org/abs/2404.17029)] [[Code](https://github.com/vazgenzohranyan/Dr.SAM)]

**Cross Prompting Consistency with Segment Anything Model for Semi-supervised Medical Image Segmentation** \
*Juzheng Miao, Cheng Chen, Keli Zhang, Jie Chuai, Quanzheng Li, Pheng-Ann Heng* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72120-5_16)] [[ArXiv](https://arxiv.org/abs/2407.05416)]

**From generalization to precision: Exploring sam for tool segmentation in surgical environments** \
*Kanyifeechukwu J. Oguine, Roger D. Soberanis-Mukul, Nathan Drenkow and Mathias Unberath* <br>
[SPIE Medical Imaging 2024] [[Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12926/1292603/From-generalization-to-precision--exploring-SAM-for-tool-segmentation/10.1117/12.3006981.short)] [[ArXiv](https://arxiv.org/abs/2402.17972)]

**Med-PerSAM: One-Shot Visual Prompt Tuning for Personalized Segment Anything Model in Medical Domain** \
*Hangyul Yoon, Doohyuk Jang, Jungeun Kim and Eunho Yang* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2411.16123)]

**EP-SAM: Weakly Supervised Histopathology Segmentation via Enhanced Prompt with Segment Anything** \
*Joonhyeon Song, Seohwan Yun, Seongho Yoon, Joohyeok Kim and Sangmin Lee* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2410.13621)] [[Code](https://github.com/QI-NemoSong/EP-SAM)]

**Segment Any Cell: A SAM-based Auto-prompting Fine-tuning Framework for Nuclei Segmentation** \
*Saiyang Na, Yuzhi Guo, Feng Jiang, Hehuan Ma and Junzhou Huang* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2401.13220)]

**Part-aware Prompted Segment Anything Model for Adaptive Segmentation** \
*Chenhui Zhao and Liyue Shen* <br>
[ArXiv 2024] [[ArXiv](http://arxiv.org/abs/2403.05433)] [[Code](https://github.com/Zch0414/p2sam)]

**CycleSAM: Few-Shot Surgical Scene Segmentation with Cycle- and Scene-Consistent Feature Matching** \
*Aditya Murali, Farahdiba Zarin, Adrien Meyer, Pietro Mascagni, Didier Mutter and Nicolas Padoy* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2407.06795)]

**MIAS-SAM: Medical Image Anomaly Segmentation without thresholding** \
*Marco Colussi, Dragan Ahmetovic and Sergio Mascetti* <br>
[ArXiv 2025] [[ArXiv](http://arxiv.org/abs/2505.22762)]

**Optimizing prompt strategies for SAM: advancing lesion segmentation across diverse medical imaging modalities** \
*Yuli Wang, Victoria Shi, Wen-Chi Hsu, Yuwei Dai, Sophie Yao, Zhusi Zhong, Zishu Zhang, Jing Wu, Aaron Maxwell, Scott Collins, Zhicheng Jiao and Harrison X. Bai* <br>
[Phys. Med. Biol 2025] [[Paper](https://iopscience.iop.org/article/10.1088/1361-6560/adfc20)] [[ArXiv](https://arxiv.org/abs/2412.17943)]

**Segment Any Tissue: One-shot reference guided training-free automatic point prompting for medical image segmentation** \
*Xueyu Liu, Guangze Shi, Rui Wang, Yexin Lai, Jianan Zhang, Weixia Han, Min Lei, Ming Li, Xiaoshuang Zhou, Yongfei Wu, Chen Wang, Wen Zheng* <br>
[MIA 2025] [[Paper](https://www.sciencedirect.com/science/article/pii/S1361841525000970)] [[Code](https://github.com/XueyuLiu/Segment-Any-Tissue)]

**Biosam: Generating sam prompts from superpixel graph for biological instance segmentation** \
*Miaomiao Cai, Xiaoyu Liu, Zhiwei Xiong, Xuejin Chen* <br>
[IEEE J. Biomed. Health Inform. 2025][[Paper](https://ieeexplore.ieee.org/abstract/document/10705688)]

**Using Foundation Models as Pseudo-label Generators for Pre-clinical 4D Cardiac CT Segmentation** \
*Anne-Marie Rickmann, Stephanie L. Thorn, Shawn S. Ahn, Supum Lee, Selen Uman, Taras Lysyy, Rachel Burns, Nicole Guerrera, Francis G. Spinale, Jason A. Burdick, Albert J. Sinusas and James S. Duncan* <br>
[FIMH 2025] [[Paper](http://link.springer.com/chapter/10.1007/978-3-031-94562-5_23)] [[ArXiv](https://www.arxiv.org/abs/2505.09564)] 

## 📦 Box Prompt
**Self-Prompting Large Vision Models for Few-Shot Medical Image Segmentation** \
*Qi Wu, Yuyao Zhang and Marawan Elbatel* <br>
[DART 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-45857-6_16)] [[ArXiv](https://arxiv.org/abs/2308.07624)] [[Code](https://github.com/PeterYYZhang/few-shot-self-prompt-SAM)]

**SAM-MPA: Applying SAM to Few-shot Medical Image Segmentation using Mask Propagation and Auto-prompting** \
*Jie Xu, Xiaokang Li, Chengyu Yue, Yuanyuan Wang and Yi Guo* <br>
[Neurips Workshop 2024] [[Paper](https://neurips.cc/virtual/2024/109352)] [[ArXiv](https://arxiv.org/abs/2411.17363)]

**Curriculum Prompting Foundation Models for Medical Image Segmentation** \
*Xiuqi Zheng, Yuhang Zhang, Haoran Zhang, Hongrui Liang, Xueqi Bao, Zhuqing Jiang and Qicheng Lao* <br>
[MICCAI 2024] [[Paper](https://papers.miccai.org/miccai-2024/183-Paper2832.html)] [[ArXiv](https://arxiv.org/abs/2409.00695)] [[Code](https://github.com/AnnaZzz-zxq/Curriculum-Prompting)]

**AM-SAM: Automated Prompting and Mask Calibration for Segment Anything Model** \
*Yuchen Li, Li Zhang, Youwei Liang, Pengtao Xie* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2410.09714)]

## 🎭 Mask Prompt
**Sam2Rad: A Segmentation Model for Medical Images with Learnable Prompts** \
*Assefa Seyoum Wahd, Banafshe Felfeliyan, Yuyue Zhou, Shrimanti Ghosh, Adam McArthur, Jiechen Zhang, Jacob L. Jaremko, Abhilash Hareendranathan* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2409.06821)] [[Code](https://github.com/aswahd/SamRadiology)]

## 📖 Text Prompt
**One Model to Rule them All: Towards Universal Segmentation for Medical Images with Text Prompts** \
*Ziheng Zhao, Yao Zhang, Chaoyi Wu, Xiaoman Zhang, Ya Zhang, Yanfeng Wang and Weidi Xie* <br>
[Digit. Med. 2025] [[Paper](https://www.nature.com/articles/s41746-025-01964-w)] [[ArXiv](https://arxiv.org/abs/2312.17183v5)]

**TP-DRSeg: Improving Diabetic Retinopathy Lesion Segmentation with Explicit Text-Prompts Assisted SAM** \
*Wenxue Li, Xinyu Xiong, Peng Xia, Lie Ju and Zongyuan Ge* <br>
[MICCAI 2024] [[Paper](https://papers.miccai.org/miccai-2024/794-Paper0014.html)] [[ArXiv](https://arxiv.org/abs/2406.15764)]

**LGA: A Language Guide Adapter for Advancing the SAM Model’s Capabilities in Medical Image Segmentation** \
*Jihong Hu, Yinhao Li, Hao Sun, Yu Song, Chujie Zhang, Lanfen Lin and Yen-Wei Chen* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_57)]

**ZePT: Zero-Shot Pan-Tumor Segmentation via Query-Disentangling and Self-Prompting** \
*Yankai Jiang, Zhongzhen Huang, Rongzhao Zhang, Xiaofan Zhang and Shaoting Zhang* <br>
[CVPR 2024] [[Paper](https://ieeexplore.ieee.org/document/10656766)] [[ArXiv](https://arxiv.org/abs/2312.04964)] [[Code](https://github.com/Yankai96/ZePT)]

**CAT: Coordinating Anatomical-Textual Prompts for Multi-Organ and Tumor Segmentation** \
*Zhongzhen Huang, Yankai Jiang, Rongzhao Zhang, Shaoting Zhang and Xiaofan Zhang* <br>
[Neurips 2024] [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/06a52a54c8ee03cd86771136bc91eb1f-Paper-Conference.pdf)] [[ArXiv](https://arxiv.org/abs/2406.07085)] [[Code](https://github.com/zongzi3zz/CAT)]

**TP-SA3M: text prompts-assisted SAM for myopic maculopathy segmentation** \
*Tingyao Li, Zehua Jiang, Yixiao Jin, Chunxing Liu, Xiangning Wang and Tingli Chen* <br>
[Vis Comput 2025] [[Paper](https://link.springer.com/article/10.1007/s00371-025-03892-y)]

## 🎨 Multimodal Prompt Fusion
**SurgicalPart-SAM: Part-to-Whole Collaborative Prompting for Surgical Instrument Segmentation** \
*Wenxi Yue, Jing Zhang, Kun Hu, Qiuxia Wu, Zongyuan Ge, Yong Xia, Jiebo Luo and Zhiyong Wang* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2312.14481)] [[Code](https://github.com/wenxi-yue/SurgicalPart-SAM)]

**Optimizing Efficiency and Effectiveness in Sequential Prompt Strategy for SAM Using Reinforcement Learning** \
*Yifei Huang, Chuyun Shen, Wenhao Li, Xiangfeng Wang, Bo Jin and Haibin Cai* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_45)]

**TV-SAM: increasing Zero-Shot segmentation performance on multimodal medical images using GPT-4 generated descriptive prompts without human annotation** \
*Zekun Jiang, Dongjie Cheng, Ziyuan Qin, Jun Gao, Qicheng Lao, Abdullaev Bakhrom Ismoilovich* <br>
[BDMA 2024] [[Paper](https://ieeexplore.ieee.org/abstract/document/10778143)] [[ArXiv](https://arxiv.org/abs/2402.15759)]

**CRISP-SAM2 : SAM2 with Cross-Modal Interaction and Semantic Prompting for Multi-Organ Segmentation** \
*Xinlei Yu, Changmiao Wang, Hui Jin, Ahmed Elazab, Gangyong Jia, Xiang Wan, Changqing Zou and Ruiquan Ge* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2506.23121)] [[Code](https://github.com/YU-deep/CRISP_SAM2)]

**BiPrompt-SAM: Enhancing Image Segmentation via Explicit Selection between Point and Text Prompts** \
*Suzhe Xu, Jialin Peng and Chengyuan Zhang* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2503.19769)]

**CLISC: Bridging clip and sam by enhanced cam for unsupervised brain tumor segmentation** \
*Xiaochuan Ma, Jia Fu, Wenjun Liao, Shichuan Zhang, Guotai Wang* <br>
[ISBI 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10980784)] [[ArXiv](https://arxiv.org/abs/2501.16246)]

## 🔔 Prompt Generation and Optimization
**Temporally-Extended Prompts Optimization for SAM in Interactive Medical Image Segmentation** \
*Chuyun Shen, Wenhao Li, Ya Zhang, Yanfeng Wang, Xiangfeng Wang* <br>
[BIBM 2023] [[Paper](https://ieeexplore.ieee.org/abstract/document/10385291)] [[ArXiv](https://arxiv.org/abs/2306.08958)]

**Benchmarking Human and Automated Prompting in the Segment Anything Model** \
*Jorge Quesada, Zoe Fowler, Mohammad Alotaibi, Mohit Prabhushankar, Ghassan AlRegib* <br>
[IEEE Int. Conf. Big Data 2024] [[Paper](https://ieeexplore.ieee.org/abstract/document/10825731)] [[ArXiv](https://arxiv.org/abs/2410.22048)] [[Code](https://github.com/olivesgatech/PointPrompt)]

**SAMIC: Segment Anything with In-Context Spatial Prompt Engineering** \
*Savinay Nagendra, Kashif Rashid, Chaopeng Shen, Daniel Kifer* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2412.11998)]

**Adaptive Prompt Learning with SAM for Few-shot Scanning Probe Microscope Image Segmentation** \
*Yao Shen, Ziwei Wei, Chunmeng Liu, Shuming Wei, Qi Zhao, Kaiyang Zeng, Guangyao Li* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2410.12562)]

**TAVP: Task-Adaptive Visual Prompt for Cross-domain Few-shot Segmentation** \
*qi Yang, Yaning Zhang, Jingxi Hu, Xiangjian He, Linlin Shen, Guoping Qiu* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2409.05393)]

**Optimizing Efficiency and Effectiveness in Sequential Prompt Strategy for SAM Using Reinforcement Learning** \
*Yifei Huang, Chuyun Shen, Wenhao Li, Xiangfeng Wang, Bo Jin, Haibin Cai* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_45)]

**Feature-Prompting GBMSeg: One-Shot Reference Guided Training-Free Prompt Engineering for Glomerular Basement Membrane Segmentation** \
*Xueyu Liu, Guangze Shi, Rui Wang, Yexin Lai, Jianan Zhang, Lele Sun, Quan Yang, Yongfei Wu, Ming Li, Weixia Han, Wen Zheng* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72114-4_27)] [[ArXiv](https://arxiv.org/abs/2406.16271)] [[Code](https://github.com/XueyuLiu/GBMSeg)]

**Segmentation by Registration-Enabled SAM Prompt Engineering Using Five Reference Images** \
*Yaxi Chen, Aleksandra Ivanova, Shaheer U. Saeed, Rikin Hargunani, Jie Huang, Chaozong Liu, Yipeng Hu* <br>
[WBIR 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-73480-9_19)] [[ArXiv](https://arxiv.org/abs/2407.17933)] [[Code](https://github.com/chrissyinreallife/KneeSegmentWithSAM)]

**Optimizing prompt strategies for SAM: advancing lesion segmentation across diverse medical imaging modalities** \
*Yuli Wang, Victoria Shi, Wen-Chi Hsu, Yuwei Dai, Sophie Yao, Zhusi Zhong, Zishu Zhang, Jing Wu, Aaron Maxwell, Scott Collins, Zhicheng Jiao, Harrison X Bai* <br>
[Phys. Med. Biol 2025] [[Paper](https://iopscience.iop.org/article/10.1088/1361-6560/adfc20/meta)] [[ArXiv](https://arxiv.org/abs/2412.17943)]

**Self-Prompting Polyp Segmentation in Colonoscopy Using Hybrid YOLO-SAM2 Model** \
*Mobina Mansoori, Sajjad Shahabodini, Jamshid Abouei, Konstantinos N. Plataniotis, Arash Mohammadi* <br>
[ICASSP 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10887638)] [[ArXiv](https://arxiv.org/abs/2409.09484)] [[Code](https://github.com/sajjad-sh33/YOLO_SAM2)]

**PGP-SAM: Prototype-Guided Prompt Learning for Efficient Few-Shot Medical Image Segmentation** \
*Zhonghao Yan, Zijin Yin, Tianyu Lin, Xiangzhu Zeng, Kongming Liang, Zhanyu Ma* <br>
[ISBI 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10980911)] [[ArXiv](https://arxiv.org/abs/2501.06692)]


