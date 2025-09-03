# <p align=center>`Awesome-Promptable-Medical-Image-Segmentation`</p> #

## Contents
- [Investigation of Prompting SAM](#-investigation-of-prompting-sam)
- [Point Prompt](#-point-prompt)
- [BBox Prompt](#-bbox-prompt)
- [Scribble Prompt](#-scribble-prompt)
- [Text Prompt](#-text-prompt)
- [Prompt Fusion](#-prompt-fusion)

## 🔍 Investigation of Prompting SAM
**Medical sam adapter: Adapting segment anything model for medical image segmentation** \
*Junde Wu, Wei Ji, Yuanpei Liu, Huazhu Fu, Min Xu, Yanwu Xu and Yueming Jin* <br>
[MIA 2025] [[Paper](https://www.sciencedirect.com/science/article/pii/S1361841525000945)] [[ArXiv](https://arxiv.org/abs/2304.12620)]

**SAM on Medical Images: A Comprehensive Study on Three Prompt Modes** \
*Dongjie Cheng, Ziyuan Qin, Zekun Jiang, Shaoting Zhang, Qicheng Lao and Kang Li* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2305.00035)]

**Self-Prompting Large Vision Models for Few-Shot Medical Image Segmentation** \
*Qi Wu, Yuyao Zhang and Marawan Elbatel* <br>
[DART 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-45857-6_16)] [[ArXiv](https://arxiv.org/abs/2308.07624)] [[Code](https://github.com/PeterYYZhang/few-shot-self-prompt-SAM)]

**PP-SAM: Perturbed Prompts for Robust Adaptation of Segment Anything Model for Polyp Segmentation** \
*Md Mostafijur Rahman, Mustafa Munir, Debesh Jha, Ulas Bagci and Radu Marculescu* <br>
[CVPR 2024] [[Paper](https://openaccess.thecvf.com/content/CVPR2024W/DEF-AI-MIA/papers/Rahman_PP-SAM_Perturbed_Prompts_for_Robust_Adaption_of_Segment_Anything_Model_CVPRW_2024_paper.pdf)] [[ArXiv](https://arxiv.org/abs/2405.16740)] [[Code](https://github.com/SLDGroup/PP-SAM)]

**Cross Prompting Consistency with Segment Anything Model for Semi-supervised Medical Image Segmentation** \
*Juzheng Miao, Cheng Chen, Keli Zhang, Jie Chuai, Quanzheng Li and Pheng-Ann Heng* <br>
[MICCAI 2024] [[Paper](https://papers.miccai.org/miccai-2024/170-Paper0321.html)] [[ArXiv](https://arxiv.org/abs/2407.05416)] [[Code](https://github.com/JuzhengMiao/CPC-SAM)]

**Beyond Adapting SAM: Towards End-to-End Ultrasound Image Segmentation via Auto Prompting** \
*Xian Lin, Yangyang Xiang, Li Yu and Zengqiang Yan* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_3)] [[ArXiv](https://arxiv.org/abs/2309.06824)] [[Code](https://github.com/xianlin7/SAMUS)]

**Optimizing Efficiency and Effectiveness in Sequential Prompt Strategy for SAM Using Reinforcement Learning** \
*Yifei Huang, Chuyun Shen, Wenhao Li, Xiangfeng Wang, Bo Jin and Haibin Cai* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_45)]

**Prompting Segment Anything Model with Domain-Adaptive Prototype for Generalizable Medical Image Segmentation** \
*Zhikai Wei, Wenhui Dong, Peilin Zhou, Yuliang Gu, Zhou Zhao and Yongchao Xu* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_50)] [[ArXiv](https://arxiv.org/abs/2409.12522)] [[Code](https://github.com/wkklavis/DAPSAM)]

**Automating MedSAM by Learning Prompts with Weak Few-Shot Supervision** \
*Mélanie Gaillochet, Christian Desrosiers and Hervé Lombaert* <br>
[MedAGI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-73471-7_7)] [[ArXiv](https://arxiv.org/abs/2409.20293)] [[Code](https://github.com/Minimel/MedSAMWeakFewShotPromptAutomation)]

**SAM-SP: Self-Prompting Makes SAM Great Again** \
*Chunpeng Zhou, Kangjie Ning, Qianqian Shen, Sheng Zhou, Zhi Yu and Haishuai Wang* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2408.12364)]

**AutoProSAM: Automated Prompting SAM for 3D Multi-Organ Segmentation** \
*Chengyin Li, Prashant Khanduri, Yao Qiang, Rafi Ibn Sultan, Indrin Chetty and Dongxiao Zhu* <br>
[WACV 2025] [[Paper](https://www.computer.org/csdl/proceedings-article/wacv/2025/108300d577/25KlAxa8iZO)] [[ArXiv](https://arxiv.org/abs/2308.14936)] [[Code](https://github.com/ChengyinLee/AutoProSAM_2024)]

**EviPrompt: A Training-Free Evidential Prompt Generation Method for Segment Anything Model in Medical Images** \
*Yinsong Xu, Jiaqi Tang, Aidong Men and Qingchao Chen* <br>
[IEEE Trans. Image Process. 2025] [[Paper](https://ieeexplore.ieee.org/document/10729707)] [[ArXiv](https://arxiv.org/abs/2311.06400)]

## 🎯 Point Prompt
**SAMAUG: POINT PROMPT AUGMENTATION FOR SEGMENT ANYTHING MODEL** \
*Haixing Dai, Chong Ma, Zhiling Yan, Zhengliang Liu, Enze Shi, Yiwei Li, Peng Shu, Xiaozheng Wei, Lin Zhao, Zihao Wu, Fang Zeng, Dajiang Zhu, Wei Liu, Quanzheng Li, Lichao Sun, Shu Zhang, Tianming Liu, and Xiang Li* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2307.01187)]

**ClickSAM: Fine-tuning Segment Anything Model using click prompts for ultrasound image segmentation** \
*Aimee Guoa, Grace Feib, Hemanth Pasupuletic and Jing Wang* <br>
[SPIE Medical Imaging 2024] [[Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12932/3005879/ClickSAM--fine-tuning-Segment-Anything-Model-using-click-prompts/10.1117/12.3005879.full?tab=ArticleLink)] [[ArXiv](https://arxiv.org/pdf/2402.05902)]

**Superpixel-Guided Segment Anything Model for Liver Tumor Segmentation with Couinaud Segment Prompt** \
*Fei Lyu, Jingwen Xu, Ye Zhu, Grace Lai-Hung Wong and Pong C. Yuen* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_64)]

**CycleSAM: Few-Shot Surgical Scene Segmentation with Cycle- and Scene-Consistent Feature Matching** \
*Aditya Murali, Farahdiba Zarin, Adrien Meyer, Pietro Mascagni, Didier Mutter and Nicolas Padoy* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2407.06795)]

**Optimizing prompt strategies for SAM: advancing lesion segmentation across diverse medical imaging modalities** \
*Yuli Wang, Victoria Shi, Wen-Chi Hsu, Yuwei Dai, Sophie Yao, Zhusi Zhong, Zishu Zhang, Jing Wu, Aaron Maxwell, Scott Collins, Zhicheng Jiao and Harrison X. Bai* <br>
[Phys. Med. Biol 2025] [[Paper](https://iopscience.iop.org/article/10.1088/1361-6560/adfc20)] [[ArXiv](https://arxiv.org/abs/2412.17943)]

## 📦 Box Prompt
**Comprehensive Multimodal Segmentation in Medical Imaging: Combining YOLOv8 with SAM and HQ-SAM Models** \
*Sumit Pandey, Kuan-Fu Chen and Erik B. Dam* <br>
[ICCVW 2023] [[Paper](https://www.computer.org/csdl/proceedings-article/iccvw/2023/074400c584/1TanjR1NsL6)] [[ArXiv](https://arxiv.org/abs/2310.12995)]

**SAM-U: Multi-box Prompts Triggered Uncertainty Estimation for Reliable SAM in Medical Image** \
*Guoyao Deng, Ke Zou, Kai Ren, Meng Wang, Xuedong Yuan, Sancong Ying and Huazhu Fu* <br>
[MICCAI 2023 Workshops] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-47425-5_33)] [[ArXiv](https://arxiv.org/abs/2307.04973)]

**Leverage Weakly Annotation to Pixel-wise Annotation via Zero-shot Segment Anything Model for Molecular-empowered Learning** \
*Xueyuan Li, Ruining Deng, Yucheng Tang, Shunxing Bao, Haichun Yang and Yuankai Huo* <br>
[SPIE Medical Imaging 2024] [[Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12933/3006577/Leverage-weekly-annotation-to-pixel-wise-annotation-via-zero-shot/10.1117/12.3006577.short?tab=ArticleLink)] [[ArXiv](https://arxiv.org/abs/2308.05785)]

**Robust Box Prompt Based SAM for Medical Image Segmentation** \
*Yuhao Huang, Xin Yang, Han Zhou, Yan Cao, Haoran Dou, Fajin Dong and Dong Ni* <br>
[MLMI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-73290-4_1)] [[ArXiv](https://arxiv.org/abs/2407.21284)]

**MedLSAM: Localize and Segment Anything Model for 3D CT Images** \
*Wenhui Lei, Xu Wei, Xiaofan Zhang, Kang Li and Shaoting Zhang* <br>
[MIA 2025] [[Paper](https://www.sciencedirect.com/science/article/pii/S1361841524002950)] [[ArXiv](https://arxiv.org/abs/2306.14752)] [[Code](https://github.com/openmedlab/MedLSAM)]

## 🖱️ Scribble Prompt
**ZScribbleSeg: Zen and the Art of Scribble Supervised Medical Image Segmentation** \
*Ke Zhang and Xiahai Zhuang* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2301.04882)]

**ScribblePrompt: Fast and Flexible Interactive Segmentation for Any Biomedical Image** \
*Hallee E. Wong, Marianne Rakic, John Guttag and Adrian V. Dalca* <br>
[ECCV 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-73661-2_12)] [[ArXiv](https://arxiv.org/abs/2312.07381)] [[Code](https://github.com/halleewong/ScribblePrompt)]

## 📖 Text Prompt
**One Model to Rule them All: Towards Universal Segmentation for Medical Images with Text Prompts** \
*Ziheng Zhao, Yao Zhang, Chaoyi Wu, Xiaoman Zhang, Ya Zhang, Yanfeng Wang and Weidi Xie* <br>
[Digit. Med. 2025] [[Paper](https://www.nature.com/articles/s41746-025-01964-w)] [[ArXiv](https://arxiv.org/abs/2312.17183v5)]

**Deep Instruction Tuning for Segment Anything Model** \
*Xiaorui Huang, Gen Luo, Chaoyang Zhu, Bo Tong, Yiyi Zhou, Xiaoshuai Sun and Rongrong Ji* <br>
[ACMMM 2024] [[Paper](https://dl.acm.org/doi/10.1145/3664647.3680571)] [[ArXiv](https://arxiv.org/abs/2404.00650)] [[Code](https://github.com/wysnzzzz/DIT)]

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

**CRISP-SAM2 : SAM2 with Cross-Modal Interaction and Semantic Prompting for Multi-Organ Segmentation** \
*Xinlei Yu, Changmiao Wang, Hui Jin, Ahmed Elazab, Gangyong Jia, Xiang Wan, Changqing Zou and Ruiquan Ge* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2506.23121)] [[Code](https://github.com/YU-deep/CRISP_SAM2)]

## 🎨 Prompt Fusion
**SurgicalPart-SAM: Part-to-Whole Collaborative Prompting for Surgical Instrument Segmentation** \
*Wenxi Yue, Jing Zhang, Kun Hu, Qiuxia Wu, Zongyuan Ge, Yong Xia, Jiebo Luo and Zhiyong Wang* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2312.14481)] [[Code](https://github.com/wenxi-yue/SurgicalPart-SAM)]

**Curriculum Prompting Foundation Models for Medical Image Segmentation** \
*Xiuqi Zheng, Yuhang Zhang, Haoran Zhang, Hongrui Liang, Xueqi Bao, Zhuqing Jiang and Qicheng Lao* <br>
[MICCAI 2024] [[Paper](https://papers.miccai.org/miccai-2024/183-Paper2832.html)] [[ArXiv](https://arxiv.org/abs/2409.00695)] [[Code](https://github.com/AnnaZzz-zxq/Curriculum-Prompting)]