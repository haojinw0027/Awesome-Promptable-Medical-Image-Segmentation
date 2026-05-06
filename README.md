<h1 align="center">A Decade of Deep Learning-based Biomedical Image Segmentation</h1>
<p align="center">
  <i>Suhao Yu<sup>*1</sup>, Haojin Wang<sup>*2</sup>, Ningsen Wang<sup>*3</sup>, Sicheng Chen<sup>*5</sup>, Juncheng Wu<sup>3</sup>, Zhenlong Yuan<sup>3</sup>, Tianhao Qi<sup>†3</sup>,<br>Zongwei Zhou<sup>4</sup>, Fei Xia<sup>†5,6</sup>, Jun Ma<sup>7</sup> and Yuyin Zhou<sup>†3</sup></i><br>
  <sup>1</sup>University of Pennsylvania, <sup>2</sup>University of Illinois Urbana-Champaign, <sup>3</sup>University of California, Santa Cruz, <sup>4</sup>Johns Hopkins University, <sup>5</sup>University of California, Irvine, <sup>6</sup>Beckman Laser Institute and Medical Clinic, UC Irvine, <sup>7</sup>University Health Network<br>
  [bioRxiv 2026] [<a href="https://www.biorxiv.org/content/early/2026/04/30/2026.04.27.721127">Paper</a>]
</p>

## 📢 News

- **[2026-05-06]** 🎉 We release the first version of our survey on a decade of deep learning-based biomedical image segmentation!

## Contents<!-- omit in toc -->
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

**De-LightSAM: Modality-Decoupled Lightweight SAM for Generalizable Medical Segmentation** \
*Qing Xu, Jiaxuan Li, Xiangjian He, Chenxin Li, Fiseha B. Tesem, Wenting Duan, Zhen Chen, Rong Qu, Jonathan M. Garibaldi and Chang Wen Chen* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2407.14153v5)] [[Code](https://github.com/xq141839/De-LightSAM)]

**Diffusion-empowered AutoPrompt MedSAM** \
*Peng Huang, Shu Hu, Bo Peng, Xun Gong, Penghang Yin, Hongtu Zhu, Xi Wu and Xin Wang* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2502.06817)] [[Code](https://github.com/HP-ML/AutoPromptMedSAM)]

## 🎯 Point Prompt
**SAMAUG: POINT PROMPT AUGMENTATION FOR SEGMENT ANYTHING MODEL** \
*Haixing Dai, Chong Ma, Zhiling Yan, Zhengliang Liu, Enze Shi, Yiwei Li, Peng Shu, Xiaozheng Wei, Lin Zhao, Zihao Wu, Fang Zeng, Dajiang Zhu, Wei Liu, Quanzheng Li, Lichao Sun, Shu Zhang, Tianming Liu and Xiang Li* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2307.01187)]

**Self-Prompting Large Vision Models for Few-Shot Medical Image Segmentation** \
*Qi Wu, Yuyao Zhang and Marawan Elbatel* <br>
[DART 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-45857-6_16)] [[ArXiv](https://arxiv.org/abs/2308.07624)] [[Code](https://github.com/PeterYYZhang/few-shot-self-prompt-SAM)]

**HAL-IA: A Hybrid Active Learning framework using Interactive Annotation for medical image segmentation** \
*Xiaokang Li, Menghua Xia, Jing Jiao, Shichong Zhou, Cai Chang, Yuanyuan Wang, Yi Guo* <br>
[MedIA 2023] [[Paper](https://www.sciencedirect.com/science/article/pii/S1361841523001226)]

**EviPrompt: A training-free evidential prompt generation method for adapting segment anything model in medical images** \
*Yinsong Xu, Jiaqi Tang, Aidong Men and Qingchao Chen* <br>
[IEEE Trans. Image Process 2024] [[Paper](https://ieeexplore.ieee.org/document/10729707)] [[ArXiv](https://arxiv.org/abs/2311.06400)] [[Code](https://github.com/SPIresearch/EviPrompt)]

**SemiSAM: Enhancing Semi-Supervised Medical Image Segmentation via SAM-Assisted Consistency Regularization** \
*Yichi Zhang, Jin Yang, Yuchen Liu, Yuan Cheng and Yuan Qi* <br>
[BIBM 2024] [[Paper](https://ieeexplore.ieee.org/abstract/document/10821951)] [[ArXiv](https://arxiv.org/abs/2312.06316)]

**Adapting Segment Anything Model to Melanoma Segmentation in Microscopy Slide Images** \
*Qingyuan Liu and Avideh Zakhor * <br>
[ECCV 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-91721-9_10)] [[ArXiv](https://arxiv.org/abs/2410.02207)] 

**Dr-SAM: An End-to-End Framework for Vascular Segmentation Diameter Estimation and Anomaly Detection on Angiography Images** \
*Vazgen Zohranyan, Vagner Navasardyan, Hayk Navasardyan, Jan Borggrefe and Shant Navasardyan* <br>
[CVPR 2024] [[Paper](https://openaccess.thecvf.com/content/CVPR2024W/DEF-AI-MIA/html/Zohranyan_Dr-SAM_An_End-to-End_Framework_for_Vascular_Segmentation_Diameter_Estimation_and_CVPRW_2024_paper.html)] [[ArViv](https://arxiv.org/abs/2404.17029)] [[Code](https://github.com/vazgenzohranyan/Dr.SAM)]

**Cross Prompting Consistency with Segment Anything Model for Semi-supervised Medical Image Segmentation** \
*Juzheng Miao, Cheng Chen, Keli Zhang, Jie Chuai, Quanzheng Li and Pheng-Ann Heng* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72120-5_16)] [[ArXiv](https://arxiv.org/abs/2407.05416)]

**PRISM: A Promptable and Robust Interactive Segmentation Model with Visual Prompts** \
*Hao Li, Han Liu, Dewei Hu, Jiacheng Wang and Ipek Oguz* <br>
[MICCAI 2024] [[ArXiv](https://arxiv.org/abs/2404.15028)] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72384-1_37)] [[Code](https://github.com/MedICL-VU/PRISM)]

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

**Segment anything in medical images** \
*Jun Ma, Yuting He, Feifei Li, Lin Han, Chenyu You and Bo Wang* <br>
[Nat. Communications 2024] [[ArXiv](https://arxiv.org/abs/2304.12306)] [[Paper](https://www.nature.com/articles/s41467-024-44824-z)] [[Code](https://github.com/bowang-lab/MedSAM)]

**Evaluating segment anything model (SAM) on MRI scans of brain tumors** \
*Luqman Ali, Fady Alnajjar, Muhammad Swavaf, Omar Elharrouss, Alaa Abd-alrazaq and Rafat Damseh* <br>
[Nat. Scientific Reports 2024] [[Paper](https://www.nature.com/articles/s41598-024-72342-x)]

**An efficient segment anything model for the segmentation of medical images** \
*Guanliang Dong, Zhangquan Wang, Yourong Chen, Yuliang Sun, Hongbo Song, Liyuan Liu and Haidong Cui* <br>
[Nat. Scientific Reports 2024] [[Paper](https://www.nature.com/articles/s41598-024-70288-8)]

**An effective and open source interactive 3D medical image segmentation solution** \
*Yi Gao, Xiaohui Chen, Qinzhu Yang, Andras Lasso, Ivan Kolesov, Steve Pieper, Ron Kikinis, Allen Tannenbaum and Liangjia Zhu* <br>
[Nat. Scientific Reports 2024] [[Paper](https://www.nature.com/articles/s41598-024-80206-7)]

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
*Xueyu Liu, Guangze Shi, Rui Wang, Yexin Lai, Jianan Zhang, Weixia Han, Min Lei, Ming Li, Xiaoshuang Zhou, Yongfei Wu, Chen Wang and Wen Zheng* <br>
[MIA 2025] [[Paper](https://www.sciencedirect.com/science/article/pii/S1361841525000970)] [[Code](https://github.com/XueyuLiu/Segment-Any-Tissue)]

**Biosam: Generating sam prompts from superpixel graph for biological instance segmentation** \
*Miaomiao Cai, Xiaoyu Liu, Zhiwei Xiong, Xuejin Chen* <br>
[IEEE J. Biomed. Health Inform. 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10705688)]

**Using Foundation Models as Pseudo-label Generators for Pre-clinical 4D Cardiac CT Segmentation** \
*Anne-Marie Rickmann, Stephanie L. Thorn, Shawn S. Ahn, Supum Lee, Selen Uman, Taras Lysyy, Rachel Burns, Nicole Guerrera, Francis G. Spinale, Jason A. Burdick, Albert J. Sinusas and James S. Duncan* <br>
[FIMH 2025] [[Paper](http://link.springer.com/chapter/10.1007/978-3-031-94562-5_23)] [[ArXiv](https://www.arxiv.org/abs/2505.09564)] 

**Integrating SAM priors with U-Net for enhanced multiclass cell detection in digital pathology** \
*Zheng Wu, Ji-Yun Yang, Chang-Bao Yan, Cheng-Gui Zhang and Hai-Chao Yang* <br>
[Nat. Scientific Reports 2025] [[Paper](https://www.nature.com/articles/s41598-025-99278-0)]

## 📦 Box Prompt
**Self-Prompting Large Vision Models for Few-Shot Medical Image Segmentation** \
*Qi Wu, Yuyao Zhang and Marawan Elbatel* <br>
[DART 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-45857-6_16)] [[ArXiv](https://arxiv.org/abs/2308.07624)] [[Code](https://github.com/PeterYYZhang/few-shot-self-prompt-SAM)]

**Guided Prompting in SAM for Weakly Supervised Cell Segmentation in Histopathological Images** \
*Aayush Kumar Tyagi, Vaibhav Mishra and Prathosh A.P., Mausam* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2311.17960)]

**Segment anything model-guided collaborative learning network for scribble-supervised polyp segmentation** \
*Yiming Zhao, Tao Zhou, Yunqi Gu, Yi Zhou, Yizhe Zhang, Ye Wu and Huazhu Fu* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2312.00312)]

**SAM-MPA: Applying SAM to Few-shot Medical Image Segmentation using Mask Propagation and Auto-prompting** \
*Jie Xu, Xiaokang Li, Chengyu Yue, Yuanyuan Wang and Yi Guo* <br>
[Neurips Workshop 2024] [[Paper](https://neurips.cc/virtual/2024/109352)] [[ArXiv](https://arxiv.org/abs/2411.17363)]

**Curriculum Prompting Foundation Models for Medical Image Segmentation** \
*Xiuqi Zheng, Yuhang Zhang, Haoran Zhang, Hongrui Liang, Xueqi Bao, Zhuqing Jiang and Qicheng Lao* <br>
[MICCAI 2024] [[Paper](https://papers.miccai.org/miccai-2024/183-Paper2832.html)] [[ArXiv](https://arxiv.org/abs/2409.00695)] [[Code](https://github.com/AnnaZzz-zxq/Curriculum-Prompting)]

**AM-SAM: Automated Prompting and Mask Calibration for Segment Anything Model** \
*Yuchen Li, Li Zhang, Youwei Liang and Pengtao Xie* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2410.09714)]

**Leveraging SAM for Single-Source Domain Generalization in Medical Image Segmentation** \
*Hanhui Wang, Huaize Ye, Yi Xia and Xueyan Zhang* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2401.02076)] [[Code](https://github.com/SARIHUST/SAMMed)]

## 🎭 Mask Prompt
**Sam2Rad: A Segmentation Model for Medical Images with Learnable Prompts** \
*Assefa Seyoum Wahd, Banafshe Felfeliyan, Yuyue Zhou, Shrimanti Ghosh, Adam McArthur, Jiechen Zhang, Jacob L. Jaremko and Abhilash Hareendranathan* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2409.06821)] [[Code](https://github.com/aswahd/SamRadiology)]

**MaskSAM: Towards Auto-prompt SAM with Mask Classification for Volumetric Medical Image Segmentation** \
*Bin Xie, Hao Tang, Bin Duan, Dawen Cai, Yan Yan and Gady Agam* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2403.14103)]

**DeSAM: Decoupled Segment Anything Model for Generalizable Medical Image Segmentation** \
*Yifan Gao, Wei Xia, Dingdu Hu, Wenkui Wang and Xin Gao* <br>
[MICCAI 2024] [[ArXiv](https://arxiv.org/abs/2306.00499)] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_48)] [[Code](https://github.com/yifangao112/DeSAM)]

**Mixture-of-Shape-Experts (MoSE): End-to-End Shape Dictionary Framework to Prompt SAM for Generalizable Medical Segmentation** \
*Jia Wei, Xiaoqi Zhao, Jonghye Woo, Jinsong Ouyang, Georges El Fakhri, Qingyu Chen and Xiaofeng Liu* <br>
[CVPR 2025] [[Paper](https://openaccess.thecvf.com/content/CVPR2025W/DG-EBF/papers/Wei_Mixture-of-Shape-Experts_MoSE_End-to-End_Shape_Dictionary_Framework_to_Prompt_SAM_for_CVPRW_2025_paper.pdf)] [[ArXiv](https://arxiv.org/abs/2504.09601)] 

**MA-SAM: A Multi-Atlas Guided SAM Using Pseudo Mask Prompts Without Manual Annotation for Spine Image Segmentation** \
*Dingwei Fan, Junyong Zhao, Chunlin Li, Xinlong Wang, Ronghan Zhang and Qi Zhu* <br>
[IEEE Trans. Medical Imaging 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10819446)]

**SAM-I-Am: Semantic boosting for zero-shot atomic-scale electron micrograph segmentation** \
*Waqwoya Abebe, Jan Strube, Luanzheng Guo, Nathan R. Tallent, Oceane Bel, Steven Spurgeon, Christina Doty, Ali Jannesari* <br>
[CMS 2025] [[ArXiv](https://arxiv.org/abs/2404.06638)] [[Paper](https://www.sciencedirect.com/science/article/pii/S0927025624006219)] 

## 📖 Text Prompt
**Ariadne’s Thread: Using Text Prompts to Improve Segmentation of Infected Areas from Chest X-ray Images** \
*Yi Zhong, Mengqiu Xu, Kongming Liang, Kaixin Chen and Ming Wu* <br>
[MICCAI 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_69)] [[ArXiv](https://arxiv.org/abs/2307.03942)] [[Code](https://github.com/Junelin2333/LanGuideMedSeg-MICCAI2023)]

**Polyp-SAM++: Can A Text Guided SAM Perform Better for Polyp Segmentation?** \
*Risab Biswas* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2308.06623)]

**TP-DRSeg: Improving Diabetic Retinopathy Lesion Segmentation with Explicit Text-Prompts Assisted SAM** \
*Wenxue Li, Xinyu Xiong, Peng Xia, Lie Ju and Zongyuan Ge* <br>
[MICCAI 2024] [[Paper](https://papers.miccai.org/miccai-2024/794-Paper0014.html)] [[ArXiv](https://arxiv.org/abs/2406.15764)]

**LGA: A Language Guide Adapter for Advancing the SAM Model’s Capabilities in Medical Image Segmentation** \
*Jihong Hu, Yinhao Li, Hao Sun, Yu Song, Chujie Zhang, Lanfen Lin and Yen-Wei Chen* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_57)]

**SimTxtSeg: Weakly-Supervised Medical Image Segmentation with Simple Text Cues** \
*Yuxin Xie, Tao Zhou, Yi Zhou and Geng Chen* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_60)] [[ArXiv](https://arxiv.org/abs/2406.19364)] [[Code](https://github.com/xyx1024/SimTxtSeg)]

**ZePT: Zero-Shot Pan-Tumor Segmentation via Query-Disentangling and Self-Prompting** \
*Yankai Jiang, Zhongzhen Huang, Rongzhao Zhang, Xiaofan Zhang and Shaoting Zhang* <br>
[CVPR 2024] [[Paper](https://ieeexplore.ieee.org/document/10656766)] [[ArXiv](https://arxiv.org/abs/2312.04964)] [[Code](https://github.com/Yankai96/ZePT)]

**CAT: Coordinating Anatomical-Textual Prompts for Multi-Organ and Tumor Segmentation** \
*Zhongzhen Huang, Yankai Jiang, Rongzhao Zhang, Shaoting Zhang and Xiaofan Zhang* <br>
[NeurIPS 2024] [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/06a52a54c8ee03cd86771136bc91eb1f-Paper-Conference.pdf)] [[ArXiv](https://arxiv.org/abs/2406.07085)] [[Code](https://github.com/zongzi3zz/CAT)]

**AdaptiveSAM: Towards Efficient Tuning of SAM for Surgical Scene Segmentation** \
*Jay N. Paranjape, Nithin Gopalakrishnan Nair, Shameema Sikder, S. Swaroop Vedula and Vishal M. Patel * <br>
[MIUA 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-66958-3_14)] [[ArXiv](https://arxiv.org/abs/2308.03726)] [[Code](https://github.com/JayParanjape/biastuning)]

**BiomedParse: a biomedical foundation model for image parsing of everything everywhere all at once** \
*Theodore Zhao, Yu Gu, Jianwei Yang, Naoto Usuyama, Ho Hin Lee, Sid Kiblawi, Tristan Naumann, Jianfeng Gao, Angela Crabtree, Jacob Abel, Christine Moung-Wen, Brian Piening, Carlo Bifulco, Mu Wei, Hoifung Poon and Sheng Wang* <br>
[Nat. Methods 2024] [[Paper](https://www.nature.com/articles/s41592-024-02499-w)] [[ArXiv](https://arxiv.org/abs/2405.12971)] [[Project](https://microsoft.github.io/BiomedParse/)]

**Leveraging Task-Specific Knowledge from LLM for Semi-Supervised 3D Medical Image Segmentation** \
*Suruchi Kumari, Aryan Das, Swalpa Kumar Roy, Indu Joshi and Pravendra Singh* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2407.05088)]

**SEG-SAM: Semantic-Guided SAM for Unified Medical Image Segmentation** \
*Shuangping Huang, Hao Liang, Qingfeng Wang, Chulong Zhong, Zijian Zhou and Miaojing Shi* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2412.12660)] 

**RefSAM3D: Adapting SAM with Cross-modal Reference for 3D Medical Image Segmentation** \
*Xiang Gao and Kai Lu* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2412.05605)]

**Advancing Generalizable Tumor Segmentation with Anomaly-Aware Open-Vocabulary Attention Maps and Frozen Foundation Diffusion Models** \
*Yankai Jiang, Peng Zhang, Donglin Yang, Yuan Tian, Hai Lin and Xiaosong Wang* <br>
[CVPR 2025] [[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Jiang_Advancing_Generalizable_Tumor_Segmentation_with_Anomaly-Aware_Open-Vocabulary_Attention_Maps_and_CVPR_2025_paper.html)] [[ArXiv](https://arxiv.org/abs/2505.02753)] [[Code](https://github.com/Yankai96/DiffuGTS)]

**MedCLIP-SAMv2: Towards Universal Text-Driven Medical Image Segmentation** \
*Taha Koleilat, Hojat Asgariandehkordi, Hassan Rivaz and Yiming Xiao* <br>
[MedIA 2025] [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1361841525002968)] [[ArXiv](https://arxiv.org/abs/2409.19483)] [[Code](https://github.com/HealthX-Lab/MedCLIP-SAMv2)]

**TP-SA3M: text prompts-assisted SAM for myopic maculopathy segmentation** \
*Tingyao Li, Zehua Jiang, Yixiao Jin, Chunxing Liu, Xiangning Wang and Tingli Chen* <br>
[Vis Comput 2025] [[Paper](https://link.springer.com/article/10.1007/s00371-025-03892-y)]

**LuGSAM: a novel framework for integrating text prompts to Segment Anything Model (SAM) for segmentation tasks of ICU chest x-rays** \
*Dhanush Babu Ramesh, Rishika Iytha Sridhar, Pulakesh Upadhyaya and Rishikesan Kamaleswaran* <br>
[MTA 2025] [[Paper](https://link.springer.com/article/10.1007/s11042-025-21094-5)] 

**One Model to Rule them All: Towards Universal Segmentation for Medical Images with Text Prompts** \
*Ziheng Zhao, Yao Zhang, Chaoyi Wu, Xiaoman Zhang, Ya Zhang, Yanfeng Wang and Weidi Xie* <br>
[npj Digit. Med. 2025] [[Paper](https://www.nature.com/articles/s41746-025-01964-w)] [[ArXiv](https://arxiv.org/abs/2312.17183v5)]

**Large-vocabulary segmentation for medical images with text prompts** \
*Ziheng Zhao, Yao Zhang, Chaoyi Wu, Xiaoman Zhang, Xiao Zhou, Ya Zhang, Yanfeng Wang and Weidi Xie* <br>
[npj Digit. Med. 2025] [[ArXiv](https://arxiv.org/abs/2312.17183)] [[Paper](https://www.nature.com/articles/s41746-025-01964-w)] [[Code](https://github.com/zhaoziheng/SAT)]

**Vision-language foundation model for 3D medical imaging** \
*Jing Wu, Yuli Wang, Zhusi Zhong, Weihua Liao, Natalia Trayanova, Zhicheng Jiao and Harrison X. Bai* <br>
[npj Artificial Intelligence 2025] [[Paper](https://www.nature.com/articles/s44387-025-00015-9)]

**Modality-projection universal model for comprehensive full-body medical imaging segmentation** \
*Yixin Chen, Lin Gao, Yajuan Gao, Rui Wang, Jingge Lian, Xiangxi Meng, Yanhua Duan, Leiying Chai, Hongbin Han, Zhaoping Cheng and Zhaoheng Xie* <br>
[Nature Communications 2025] [[ArXiv](https://arxiv.org/abs/2412.19026)] [[Paper](https://www.nature.com/articles/s41467-025-64469-w)] [[Code](https://github.com/YixinChen-AI/MPUM)]

**PG-SAM: Prior-Guided SAM with Medical for Multi-organ Segmentation** \
*Yiheng Zhong, Zihong Luo, Chengzhi Liu, Feilong Tang, Zelin Peng, Ming Hu, Yingzhen Hu, Jionglong Su, Zongyuan Ge and Imran Razzak* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2503.18227)] [[Code](https://github.com/logan-0623/PG-SAM)]

**MedSeg-R: Reasoning Segmentation in Medical Images with Multimodal Large Language Models** \
*Yu Huang, Zelin Peng, Yichen Zhao, Piao Yang, Xiaokang Yang and Wei Shen* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2506.10465)]

**Diffusion-empowered AutoPrompt MedSAM** \
*Peng Huang, Shu Hu, Bo Peng, Xun Gong, Penghang Yin, Hongtu Zhu, Xi Wu and Xin Wang* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2502.06817)] [[Code](https://github.com/HP-ML/AutoPromptMedSAM)]

**Causal-SAM-LLM: Large Language Models as Causal Reasoners for Robust Medical Segmentation** \
*Tao Tang, Shijie Xu, Yiting Wu and Zhixiang Lu* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2507.03585)]

## 🎨 Multimodal Prompt Fusion
**SurgicalPart-SAM: Part-to-Whole Collaborative Prompting for Surgical Instrument Segmentation** \
*Wenxi Yue, Jing Zhang, Kun Hu, Qiuxia Wu, Zongyuan Ge, Yong Xia, Jiebo Luo and Zhiyong Wang* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2312.14481)] [[Code](https://github.com/wenxi-yue/SurgicalPart-SAM)]

**False Negative/Positive Control for SAM on Noisy Medical Images** \
*Xing Yao, Han Liu, Dewei Hu, Daiwei Lu, Ange Lou, Hao Li, Ruining Deng, Gabriel Arenas, Baris Oguz, Nadav Schwartz, Brett C Byram and Ipek Oguz* <br>
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2308.10382)] 

**Optimizing Efficiency and Effectiveness in Sequential Prompt Strategy for SAM Using Reinforcement Learning** \
*Yifei Huang, Chuyun Shen, Wenhao Li, Xiangfeng Wang, Bo Jin and Haibin Cai* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_45)]

**TV-SAM: increasing Zero-Shot segmentation performance on multimodal medical images using GPT-4 generated descriptive prompts without human annotation** \
*Zekun Jiang, Dongjie Cheng, Ziyuan Qin, Jun Gao, Qicheng Lao, Abdullaev Bakhrom Ismoilovich* <br>
[BDMA 2024] [[Paper](https://ieeexplore.ieee.org/abstract/document/10778143)] [[ArXiv](https://arxiv.org/abs/2402.15759)]

**SurgicalPart-SAM: Part-to-Whole Collaborative Prompting for Surgical Instrument Segmentation** \
*Wenxi Yue, Jing Zhang, Kun Hu, Qiuxia Wu, Zongyuan Ge, Yong Xia, Jiebo Luo and Zhiyong Wang* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2312.14481)] [[Code](https://github.com/wenxi-yue/SurgicalPart-SAM)]

**CC-SAM: SAM with Cross-Feature Attention and Context for Ultrasound Image Segmentation** \
*Shreyank N. Gowda and David A. Clifton * <br>
[ECCV 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72995-9_7)] [[ArXiv](https://arxiv.org/abs/2408.00181)]

**MIT-SAM: Medical Image-Text SAM With Mutually Enhanced Heterogeneous Features Fusion for Medical Image Segmentation** \
*Xichuan Zhou, Lingfeng Yan, Rui Ding, Chukwuemeka Clinton Atabansi, Jing Nie and Lihui Chen* <br>
[IEEE J. Biomed. Health Inform. 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10966035)] [[Code](https://github.com/jojodan514/MIT-SAM)]

**CLISC: Bridging clip and sam by enhanced cam for unsupervised brain tumor segmentation** \
*Xiaochuan Ma, Jia Fu, Wenjun Liao, Shichuan Zhang and Guotai Wang* <br>
[ISBI 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10980784)] [[ArXiv](https://arxiv.org/abs/2501.16246)]

**Integrating multi-scale information and diverse prompts in large model SAM-Med2D for accurate left ventricular ejection fraction estimation** \
*Yagang Wu, Tianli Zhao, Shijun Hu, Qin Wu, Yingxu Chen, Xin Huang and Zhoushun Zheng* <br>
[Med. Biol. Eng. Comput. 2025] [[Paper](https://link.springer.com/article/10.1007/s11517-025-03310-4)] 

**AMVLM: Alignment-Multiplicity Aware Vision-Language Model for Semi-Supervised Medical Image Segmentation** \
*Qingtao Pan, Zhengrong Li, Wenhao Qiao, Jingjiao Lou, Qing Yang and Guang Yang* <br>
[IEEE Trans. Medical Imaging 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/11014494)] [[Code](https://github.com/QingtaoPan/AMVLM)]

**Zero-Shot Pseudo Labels Generation Using SAM and CLIP for Semi-Supervised Semantic Segmentation** \
*Nagito Saito, Shintaro Ito, Koichi Ito and Takafumi Aoki* <br>
[ICIP 2025] [[ArXiv](https://arxiv.org/abs/2505.19846)] [[Project](https://arxiv.org/abs/2505.19846)]

**Generalist medical foundation model improves prostate cancer segmentation from multimodal MRI images** \
*Yuhan Zhang, Xiao Ma, Mingchao Li, Kun Huang, Jie Zhu, Miao Wang, Xi Wang, Menglin Wu and Pheng-Ann Heng* <br>
[npj Digital Medicine 2025] [[Paper](https://www.nature.com/articles/s41746-025-01756-2)] [[Code](https://github.com/ZhangYH0502/PCaSAM)]

**A promptable CT foundation model for solid tumor evaluation** \
*Léo Machado, Léo Alberge, Hélène Philippe, Elodie Ferreres, Julien Khlaut, Julie Dupuis, Korentin Le Floch, Denis Habip Gatenyo, Pascal Roux, Jules Grégory, Maxime Ronot, Corentin Dancette, Tom Boeken, Daniel Tordjman, Pierre Manceron and Paul Hérent* <br>
[npj Precision Oncology 2025] [[ArXiv](https://arxiv.org/abs/2410.07908)] [[Paper](https://www.nature.com/articles/s41698-025-00903-y)]

**CRISP-SAM2 : SAM2 with Cross-Modal Interaction and Semantic Prompting for Multi-Organ Segmentation** \
*Xinlei Yu, Changmiao Wang, Hui Jin, Ahmed Elazab, Gangyong Jia, Xiang Wan, Changqing Zou and Ruiquan Ge* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2506.23121)] [[Code](https://github.com/YU-deep/CRISP_SAM2)]

**BiPrompt-SAM: Enhancing Image Segmentation via Explicit Selection between Point and Text Prompts** \
*Suzhe Xu, Jialin Peng and Chengyuan Zhang* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2503.19769)]

**MedPrompt: LLM-CNN Fusion with Weight Routing for Medical Image Segmentation and Classification** \
*Shadman Sobhan, Kazi Abrar Mahmud and Abduz Zami* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2506.21199)]

**SAMSA 2.0: Prompting Segment Anything with Spectral Angles for Hyperspectral Interactive Medical Image Segmentation** \
*Alfie Roddan, Tobias Czempiel, Chi Xu, Daniel S. Elson and Stamatia Giannarou* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2508.00493)]

## 🔔 Prompt Generation and Optimization
**Temporally-Extended Prompts Optimization for SAM in Interactive Medical Image Segmentation** \
*Chuyun Shen, Wenhao Li, Ya Zhang, Yanfeng Wang and Xiangfeng Wang* <br>
[BIBM 2023] [[Paper](https://ieeexplore.ieee.org/abstract/document/10385291)] [[ArXiv](https://arxiv.org/abs/2306.08958)]

**Comprehensive Multimodal Segmentation in Medical Imaging: Combining YOLOv8 with SAM and HQ-SAM Models** \
*Sumit Pandey, Kuan-Fu Chen and Erik B. Dam* <br>
[ICCV 2023] [[Paper](https://openaccess.thecvf.com/content/ICCV2023W/CVAMD/html/Pandey_Comprehensive_Multimodal_Segmentation_in_Medical_Imaging_Combining_YOLOv8_with_SAM_ICCVW_2023_paper.html)] [[ArXiv](https://arxiv.org/abs/2310.12995)]

**Evaluation and Improvement of Segment Anything Model for Interactive Histopathology Image Segmentation** \
*SeungKyu Kim, Hyun-Jic Oh, Seonghui Min and Won-Ki Jeong* <br>
[MICCAI 2023] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-47401-9_24)] [[ArXiv](https://arxiv.org/abs/2310.10493)]

**Exploring SAM Ablations for Enhancing Medical Segmentation in Radiology and Pathology** \
*Amin Ranem, Niklas Babendererde, Moritz Fuchs and Anirban Mukhopadhyay* <br>\
[ArXiv 2023] [[ArXiv](https://arxiv.org/abs/2310.00504)] 

**Optimizing Efficiency and Effectiveness in Sequential Prompt Strategy for SAM Using Reinforcement Learning** \
*Yifei Huang, Chuyun Shen, Wenhao Li, Xiangfeng Wang, Bo Jin and Haibin Cai* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_45)]

**Feature-Prompting GBMSeg: One-Shot Reference Guided Training-Free Prompt Engineering for Glomerular Basement Membrane Segmentation** \
*Xueyu Liu, Guangze Shi, Rui Wang, Yexin Lai, Jianan Zhang, Lele Sun, Quan Yang, Yongfei Wu, Ming Li, Weixia Han and Wen Zheng* <br>
[MICCAI 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72114-4_27)] [[ArXiv](https://arxiv.org/abs/2406.16271)] [[Code](https://github.com/XueyuLiu/GBMSeg)]

**SAM Carries the Burden: A Semi-Supervised Approach Refining Pseudo Labels for Medical Segmentation** \
*Ron Keuth, Lasse Hansen, Maren Balks, Ronja Jäger, Anne-Nele Schröder, Ludger Tüshaus and Mattias Heinrich* <br>
[MICCAI 2024] [[ArXiv](https://arxiv.org/abs/2411.12602)] [[Code](https://github.com/multimodallearning/SamCarriesTheBurden)]

**Prompting Segment Anything Model with Domain-Adaptive Prototype for Generalizable Medical Image Segmentation** \
*Zhikai Wei, Wenhui Dong, Peilin Zhou, Yuliang Gu, Zhou Zhao and Yongchao Xu* <br>
[MICCAI 2024] [[ArXiv](https://arxiv.org/abs/2409.12522)] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-72111-3_50)] [[Code](https://github.com/wkklavis/DAPSAM)]

**Benchmarking Human and Automated Prompting in the Segment Anything Model** \
*Jorge Quesada, Zoe Fowler, Mohammad Alotaibi, Mohit Prabhushankar and Ghassan AlRegib* <br>
[IEEE Int. Conf. Big Data 2024] [[Paper](https://ieeexplore.ieee.org/abstract/document/10825731)] [[ArXiv](https://arxiv.org/abs/2410.22048)] [[Code](https://github.com/olivesgatech/PointPrompt)]

**Segmentation by Registration-Enabled SAM Prompt Engineering Using Five Reference Images** \
*Yaxi Chen, Aleksandra Ivanova, Shaheer U. Saeed, Rikin Hargunani, Jie Huang, Chaozong Liu and Yipeng Hu* <br>
[WBIR 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-73480-9_19)] [[ArXiv](https://arxiv.org/abs/2407.17933)] [[Code](https://github.com/chrissyinreallife/KneeSegmentWithSAM)]

**ScribblePrompt: Fast and Flexible Interactive Segmentation for Any Biomedical Image** \
*Hallee E. Wong, Marianne Rakic, John Guttag and Adrian V. Dalca* <br>
[ECCV 2024] [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-73661-2_12)] [[ArXiv](https://arxiv.org/abs/2312.07381)] [[Project](https://scribbleprompt.csail.mit.edu/)]

**SimSAM: Zero-Shot Medical Image Segmentation via Simulated Interaction** \
*Benjamin Towle, Xin Chen and Ke Zhou* <br>
[ISBI 2024] [[Paper](https://ieeexplore.ieee.org/abstract/document/10635227)] [[ArXiv](https://arxiv.org/abs/2406.00663)] [[Code](https://github.com/BenjaminTowle/SimSAM)]

**Surgical-DeSAM: decoupling SAM for instrument segmentation in robotic surgery** \
*Yuyang Sheng, Sophia Bano, Matthew J. Clarkson and Mobarakol Islam* <br>
[IJCARS 2024] [[Paper](https://link.springer.com/article/10.1007/s11548-024-03163-6)] [[ArXiv](https://arxiv.org/abs/2404.14040)]

**SAMIC: Segment Anything with In-Context Spatial Prompt Engineering** \
*Savinay Nagendra, Kashif Rashid, Chaopeng Shen and Daniel Kifer* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2412.11998)]

**Adaptive Prompt Learning with SAM for Few-shot Scanning Probe Microscope Image Segmentation** \
*Yao Shen, Ziwei Wei, Chunmeng Liu, Shuming Wei, Qi Zhao, Kaiyang Zeng and Guangyao Li* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2410.12562)]

**TAVP: Task-Adaptive Visual Prompt for Cross-domain Few-shot Segmentation** \
*qi Yang, Yaning Zhang, Jingxi Hu, Xiangjian He, Linlin Shen and Guoping Qiu* <br>
[ArXiv 2024] [[ArXiv](https://arxiv.org/abs/2409.05393)]

**Optimizing prompt strategies for SAM: advancing lesion segmentation across diverse medical imaging modalities** \
*Yuli Wang, Victoria Shi, Wen-Chi Hsu, Yuwei Dai, Sophie Yao, Zhusi Zhong, Zishu Zhang, Jing Wu, Aaron Maxwell, Scott Collins, Zhicheng Jiao and Harrison X Bai* <br>
[Phys. Med. Biol 2025] [[Paper](https://iopscience.iop.org/article/10.1088/1361-6560/adfc20/meta)] [[ArXiv](https://arxiv.org/abs/2412.17943)]

**Self-Prompting Polyp Segmentation in Colonoscopy Using Hybrid YOLO-SAM2 Model** \
*Mobina Mansoori, Sajjad Shahabodini, Jamshid Abouei, Konstantinos N. Plataniotis and Arash Mohammadi* <br>
[ICASSP 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10887638)] [[ArXiv](https://arxiv.org/abs/2409.09484)] [[Code](https://github.com/sajjad-sh33/YOLO_SAM2)]

**PGP-SAM: Prototype-Guided Prompt Learning for Efficient Few-Shot Medical Image Segmentation** \
*Zhonghao Yan, Zijin Yin, Tianyu Lin, Xiangzhu Zeng, Kongming Liang and Zhanyu Ma* <br>
[ISBI 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10980911)] [[ArXiv](https://arxiv.org/abs/2501.06692)]

**Learnable Prompting SAM-Induced Knowledge Distillation for Semi-Supervised Medical Image Segmentation** \
*Kaiwen Huang, Tao Zhou, Huazhu Fu, Yizhe Zhang, Yi Zhou and Chen Gong* <br>
[IEEE Trans. Medical Imaging 2025] [[Paper](https://ieeexplore.ieee.org/abstract/document/10843257)] [[ArXiv](https://arxiv.org/abs/2412.13742)] [[Code](https://github.com/taozh2017/KnowSAM)]

**Steady Progress Beats Stagnation: Mutual Aid of Foundation and Conventional Models in Mixed Domain Semi-Supervised Medical Image Segmentation** \
*Qinghe Ma, Jian Zhang, Zekun Li, Lei Qi, Qian Yu and Yinghuan Shi* <br>
[CVPR 2025] [[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Ma_Steady_Progress_Beats_Stagnation_Mutual_Aid_of_Foundation_and_Conventional_CVPR_2025_paper.html)] [[ArXiv](https://arxiv.org/abs/2503.16997)] [[Code](https://github.com/MQinghe/SynFoC)]

**ICA-SAMv7: Internal carotid artery segmentation with coarse to fine network** \
*Xiaotian Yan, Yuting Guo, Ziyi Pei, Xinyu Zhang, Jinghao Li, Zitao Zhou, Lifang Liang, Shuai Li, Peng Lun and Aimin Hao* <br>
[CMIG 2025] [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0895611125000643)] [[Code](https://github.com/BessiePei/ICA-SAMv7)]

**Prompt2SegCXR:Prompt to Segment All Organs and Diseases in Chest X-rays** \
*Abduz Zami, Shadman Sobhan, Rounaq Hossain, Md. Sawran Sorker, Mohiuddin Ahmed and Md. Redwan Hossain* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2507.00673)]

**SemiSAM+: Rethinking Semi-Supervised Medical Image Segmentation in the Era of Foundation Models** \
*Yichi Zhang, Bohao Lv, Le Xue, Wenbo Zhang, Yuchen Liu, Yu Fu, Yuan Cheng and Yuan Qi* <br>
[ArXiv 2025] [[ArXiv](https://arxiv.org/abs/2502.20749)]

## 📚 Citation

If you find this repository useful, please consider citing our work:

```bibtex
@article {Yu2026.04.27.721127,
	author = {Yu, Suhao and Wang, Haojin and Wang, Ningsen and Chen, Sicheng and Wu, Juncheng and Yuan, Zhenlong and Qi, Tianhao and Zhou, Zongwei and Xia, Fei and Ma, Jun and Zhou, Yuyin},
	title = {A Decade of Deep Learning-based Biomedical Image Segmentation},
	elocation-id = {2026.04.27.721127},
	year = {2026},
	doi = {10.64898/2026.04.27.721127},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/early/2026/04/30/2026.04.27.721127},
	eprint = {https://www.biorxiv.org/content/early/2026/04/30/2026.04.27.721127.full.pdf},
	journal = {bioRxiv}
}

```

If you have any questions or suggestions, please feel free to open an issue or contact us.
