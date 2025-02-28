---
title: Calendar
layout: page
---

Week 1 Jan 23
: **Lecture**{: .label .label-green }[Introduction](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lectures/week01_intro.pdf)
  **Tutorial**{: .label .label-purple }[HPC tutorial](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lab/lab1_hpc.pdf)
: - History of self-driving cars
  - Embodied learning
  - Suggested readings
    - Turing (1950) [Computing Machinery and Intelligence](https://www.cs.ox.ac.uk/activities/ieg/e-library/sources/t_article.pdf)
	- Pomerleau (1988) [ALVINN: An Autonomous Land Vehicle in a Neural Network](https://proceedings.neurips.cc/paper/1988/file/812b4ba287f5ee0bc9d43bbf5bbe87fb-Paper.pdf)
	- [Video] [History Channel 1998 : Driverless Car Technology Overview at Carnegie Mellon University](https://www.youtube.com/watch?v=2KMAAmkz9go)
	- Smith & Gasser (2005) [The Development of Embodied Cognition: Six Lessons from Babies](https://cogdev.sitehost.iu.edu/labwork/6_lessons.pdf)

Week 2 Jan 30
: **Lecture**{: .label .label-green }[Deep Learning for Structured Outputs](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lectures/week02_structured_learning.pdf)
  **Tutorial**{: .label .label-purple }[Simulator Tutorial](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lab/lab2_simulator.pdf)
: - Object detection and segmentation
  - Graphical models
  - Energy-based models
  - Autoregressive models
  - Suggested readings
    - LeCun (2006) [A Tutorial on Energy-Based Learning](https://www.cs.toronto.edu/~vnair/ciar/lecun1.pdf)
    - Girshick et al. (2013) [Rich feature hierarchies for accurate object detection and semantic segmentation](https://arxiv.org/abs/1311.2524)
    - Long et al. (2014) [Fully Convolutional Networks for Semantic Segmentation](https://arxiv.org/abs/1411.4038)
    - Zheng et al. (2015) [Conditional Random Fields as Recurrent Neural Networks](https://arxiv.org/abs/1502.03240)
    - Chen et al. (2016) [DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs](https://arxiv.org/abs/1606.00915)
    - Kingma & Dhariwal (2018) [Glow: Generative Flow with Invertible 1x1 Convolutions](https://arxiv.org/abs/1807.03039)
    - Ho et al. (2020) [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
  - Additional readings
    - Carion et al. (2020) [End-to-End Object Detection with Transformers](https://arxiv.org/pdf/2005.12872)
    - Kamath et al. (2021) [MDETR -- Modulated Detection for End-to-End Multi-Modal Understanding](https://arxiv.org/abs/2104.12763)
    - Cheng et al. (2021) [Per-Pixel Classification is Not All You Need for Semantic Segmentation](https://arxiv.org/abs/2107.06278)
    - Rombach et al. (2022) [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)
    - Kirillov et al. (2023) [Segment Anything](https://arxiv.org/abs/2304.02643)
    - Bai et al. (2023) [Sequential Modeling Enables Scalable Learning for Large Vision Models](https://arxiv.org/abs/2312.00785)
    - Chi et al. (2023) [Diffusion Policy: Visuomotor Policy Learning via Action Diffusion](https://arxiv.org/abs/2303.04137)

Week 3 Feb 6
: **Lecture**{: .label .label-green }[3D Vision, Mapping](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lectures/week03_3d_mapping.pdf)
  **Tutorial**{: .label .label-purple }[Video Learning Tutorial](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lab/lab3_video_learning.pdf)
: - Diffusion models
    - Probabilistic foundation
    - Applications in embodied learning
  - 3D network designs
    - Bird's eye view networks
    - Point cloud networks
  - Suggested readings:
    - Fischer et al. (2015) [FlowNet: Learning Optical Flow with Convolutional Networks](https://arxiv.org/abs/1504.06852)
    - Godard et al. (2016) [Unsupervised Monocular Depth Estimation with Left-Right Consistency](https://arxiv.org/abs/1609.03677)
    - Qi et al. (2016) [PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/abs/1612.00593)
    - Tamar et al. (2016) [Value Iteration Networks](https://arxiv.org/abs/1602.02867)
    - Parisotto et al. (2017) [Neural Map: Structured Memory for Deep Reinforcement Learning](https://arxiv.org/abs/1702.08360)
    - Gupta et al. (2017) [Cognitive Mapping and Planning for Visual Navigation](https://arxiv.org/abs/1702.03920)
  - Additional readings: 
    - Chaplot et al. (2020) [Neural Topological SLAM for Visual Navigation](https://arxiv.org/abs/2005.12256)
    - Huang et al. (2022) [FlowFormer: A Transformer Architecture for Optical Flow](https://arxiv.org/abs/2203.16194)
    - Wu et al. (2023) [Policy Pre-training for Autonomous Driving via Self-supervised Geometric Modeling](https://arxiv.org/abs/2301.01006)
    - Sun et al. (2023) [Dynamo-Depth: Fixing Unsupervised Depth Estimation for Dynamical Scenes](https://arxiv.org/abs/2310.18887)
    - Yang et al. (2024) [Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data](https://arxiv.org/abs/2401.10891)
    - Wang et al. (2025) [Continuous 3D Perception Model with Persistent State](https://arxiv.org/abs/2501.12387)

Week 4 Feb 13
: **Lecture**{: .label .label-green }[Self-Supervised Representation Learning and Object Discovery](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lectures/week04_ssl.pdf)
  **Tutorial**{: .label .label-purple }[Egocentric Video Tutorial](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lab/lab4_ego4d.pdf)
: - 3D vision
    - Sensor fusion
    - Multi-task architecture
  - Physical grounding
    - Stereo, self-supervised depth
    - Optical flow
    - Unsupervised flow, depth and pose
  - Mapping
    - Soft mapping
    - Registration
  - Representation learning
    - DAE, MAE
    - Energy-based models
  - Suggested readings:
    - Sermanet et al. (2017) [Time-Contrastive Networks: Self-Supervised Learning from Video](https://arxiv.org/abs/1704.06888)
    - Van den Oord et al. (2018) [Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748)
    - Wu et al. (2018) [Unsupervised Feature Learning via Non-Parametric Instance-level Discrimination](https://arxiv.org/abs/1805.01978)
    - Chen et al. (2020) [A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709)
    - Grill et al. (2020) [Bootstrap Your Own Latent: A New Approach to Self-Supervised Learning](https://arxiv.org/abs/2006.07733)
    - He et al. (2021) [Masked Autoencoders Are Scalable Vision Learners](https://arxiv.org/abs/2111.06377)
  - Additional readings:
    - Weinzaepfel et al. (2022) [CroCo v2: Improved Cross-view Completion Pre-training for Stereo Matching and Optical Flow](https://arxiv.org/abs/2211.10408)
    - Wang et al. (2022) [Self-Supervised Transformers for Unsupervised Object Discovery using Normalized Cut](https://arxiv.org/abs/2202.11539)
    - Seo et al. (2022) [Masked World Models for Visual Control](https://arxiv.org/abs/2206.14244)
    - Venkataramanan et al. (2023) [Is ImageNet Worth 1 Video? Learning Strong Image Encoders from 1 Long Unlabelled Video](https://arxiv.org/abs/2310.08584)
    - van Steenkiste et al. (2024) [Moving Off-the-Grid: Scene-Grounded Video Representations](https://arxiv.org/abs/2411.05927)
    - Cui et al. (2024) [DynaMo: In-Domain Dynamics Pretraining for Visuo-Motor Control](https://arxiv.org/abs/2409.12192)
    - Wang et al. (2024) [PooDLe: Pooled and Dense Self-Supervised Learning from Naturalistic Videos](https://arxiv.org/abs/2408.11208)

Week 5 Feb 20
: **Lecture**{: .label .label-green }[World Models and Forecasting](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lectures/week05_world_models.pdf)
  **Tutorial**{: .label .label-purple }Motion Learning Tutorial
: - Representation learning
    - Energy-based models
    - Joint embedding models
  - Object discovery
    - Pseudo-labels
    - Slot-based models
    - Complex-valued autoencoders
  - World models
    - Trajectory prediction
    - Latent sequence models
    - Occupancy volume prediction
  - Suggested readings:
    - Kalchbrenner et al. (2016) [Video Pixel Networks](https://arxiv.org/abs/1610.00527)
    - Ha and Schmidhuber (2018) [World Models](https://arxiv.org/abs/1803.10122)
    - Hafner et al. (2019) [Dream to Control: Learning Behaviors by Latent Imagination](https://arxiv.org/abs/1912.01603)
  - Additional readings:
    - Liang et al. (2020) [Learning Lane Graph Representations for Motion Forecasting](https://arxiv.org/abs/2007.13732)
    - Wu et al. (2022) [DayDreamer: World Models for Physical Robot Learning](https://arxiv.org/abs/2206.14176)
    - Yu et al. (2022) [MAGVIT: Masked Generative Video Transformer](https://arxiv.org/abs/2212.05199)
    - Hafner et al. (2023) [Mastering Diverse Domains through World Models](https://arxiv.org/abs/2301.04104)
    - Hansen et al. (2023) [TD-MPC2: Scalable, Robust World Models for Continuous Control](https://arxiv.org/abs/2310.16828)
    - Hu et al. (2023) [GAIA-1: A Generative World Model for Autonomous Driving](https://arxiv.org/abs/2309.17080)
    - Zhang et al. (2024) [Copilot4D: Learning Unsupervised World Models for Autonomous Driving via Discrete Diffusion](https://arxiv.org/abs/2311.01017)
    - Casas et al. (2024) [DeTra: A Unified Model for Object Detection and Trajectory Forecasting](https://arxiv.org/abs/2406.04426)
    - Bruce et al. (2024) [Genie: Generative Interactive Environments](https://arxiv.org/abs/2402.15391)

Week 6 Feb 27
: **Lecture**{: .label .label-green }[End-to-End Planning](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lectures/week06_planning.pdf)
  **Tutorial**{: .label .label-purple }[LLM Agent Tutorial](https://embodied-learning-vision-course.github.io/course-public/2025-spring/lab/lab6_LLMAgent.pdf)
: - Suggested readings:
    - Ross et al. (2011) [A Reduction of Imitation Learning and Structured Prediction to No-Regret Online Learning](https://arxiv.org/abs/1011.0686)
    - Haarnoja et al. (2018) [Soft Actor-Critic: Off-Policy Maximum Entropy Deep Reinforcement Learning with a Stochastic Actor](https://arxiv.org/abs/1801.01290)
    - Srinivas et al. (2018) [Universal Planning Networks](https://arxiv.org/abs/1804.00645)
    - Sukhbaatar et al. (2018) [Intrinsic Motivation and Automatic Curricula via Asymmetric Self-Play](https://arxiv.org/abs/1703.05407)
    - Amos et al. (2018) [Differentiable MPC for End-to-end Planning and Control](https://arxiv.org/abs/1810.13400)
    - Zeng et al. (2019) [End-to-end Interpretable Neural Motion Planner](https://arxiv.org/abs/2101.06679)
  - Additional readings:
    - Casas et al. (2021) [MP3: A Unified Model to Map, Perceive, Predict and Plan](https://arxiv.org/abs/2101.06806)
    - Hu et al. (2022) [Planning-oriented Autonomous Driving](https://arxiv.org/abs/2212.10156)
    - Chaplot et al. (2021) [Differentiable Spatial Planning using Transformers](https://arxiv.org/abs/2112.01010)
    - Dinev et al. (2022) [Differentiable Optimal Control via Differential Dynamic Programming](https://arxiv.org/abs/2209.01117)
    - Chi et al. (2023) [Diffusion Policy: Visuomotor Policy Learning via Action Diffusion](https://arxiv.org/abs/2303.04137)
    - Psenka et al. (2024) [Learning a Diffusion Model Policy from Rewards via Q-Score Matching](https://arxiv.org/abs/2312.11752)


Week 7 Mar 6
: **Lecture**{: .label .label-green }Continual Learning, Few-Shot Learning and Meta-Learning
  **Seminar**{: .label .label-purple }Structure Prediction
: - Suggested readings:
    - Marsland (2002) [A Self-Organising Network that Grows when Required](https://www.sciencedirect.com/science/article/pii/S0893608002000783)
    - Kirkpatrick et al. (2016) [Overcoming catastrophic forgetting in neural networks](https://arxiv.org/abs/1612.00796)
    - Rebuffi et al. (2016) [iCaRL: Incremental Classifier and Representation Learning](https://arxiv.org/abs/1611.07725)
    - Yoon et al. (2017) [Lifelong Learning with Dynamically Expandable Networks](https://arxiv.org/abs/1708.01547)
    - Nguyen et al. (2017) [Variational Continual Learning](https://arxiv.org/abs/1710.10628)
    - Van de Ven et al. (2020) [Brain-Inspired Replay for Continual Learning with Artificial Neural Networks](https://www.nature.com/articles/s41467-020-17866-2)
  - Additional readings:
    - Dohare et al. (2021) [Continual Backprop: Stochastic Gradient Descent with Persistent Randomness](https://arxiv.org/abs/2108.06325)
    - Wang et al. (2021) [Learning to Prompt for Continual Learning](https://arxiv.org/abs/2112.08654)
    - Powers et al. (2023) [Evaluating Continual Learning on a Home Robot](https://arxiv.org/abs/2306.02413)
    - Zhang et al. (2023) [A Novel Visual Question Answering Continual Learning Setting](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_VQACL_A_Novel_Visual_Question_Answering_Continual_Learning_Setting_CVPR_2023_paper.pdf)
    - Lee et al. (2023) [STELLA: Continual Audio-Video Pre-training with Spatio-Temporal Localized Alignment](https://arxiv.org/abs/2310.08204)
    - Majumder et al. (2023) [CLIN: A Continually Learning Language Agent for Rapid Task Adaptation and Generalization](https://arxiv.org/abs/2310.10134)


Week 8 Mar 13
: **Lecture**{: .label .label-green } Guest Lecture (Prof. Wei-Chiu Ma)
  **Seminar**{: .label .label-red } 3D Vision
: - Suggested readings (on Few-Shot Learning):
    - Fei-Fei & Fergus (2006) [One-Shot Learning of Object Categories](http://vision.stanford.edu/documents/Fei-FeiFergusPerona2006.pdf)
    - Lake et al. (2011) [One-Shot Learning of Simple Visual Concepts](https://cims.nyu.edu/~brenden/papers/LakeEtAl2011CogSci.pdf)
    - Snell et al. (2017) [Prototypical Networks for Few-shot Learning](https://arxiv.org/abs/1703.05175)
    - Finn et al. (2017) [Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks](https://arxiv.org/abs/1703.03400)
    - James et al. (2018) [Task-Embedded Control Networks for Few-Shot Imitation Learning](https://arxiv.org/abs/1810.03237)
    - Brown et al. (2020) [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)
    - Chen et al. (2021) [Exploring Simple Meta-Learning for Few-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Chen_Meta-Baseline_Exploring_Simple_Meta-Learning_for_Few-Shot_Learning_ICCV_2021_paper.pdf)
  - Additional readings:
    - Javed & White (2019) [Meta-Learning Representations for Continual Learning](https://arxiv.org/abs/1905.12588)
    - Lake (2019) [Compositional Generalization through Meta Sequence-to-Sequence Learning](https://arxiv.org/abs/1906.05381)
    - Ren et al. (2021) [Wandering Within a World: Online Contextualized Few-Shot Learning](https://arxiv.org/abs/2007.04546)
    - Alayrac et al. (2022) [Flamingo: a Visual Language Model for Few-Shot Learning](https://arxiv.org/abs/2204.14198)
    - Song et al. (2022) [LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models](https://arxiv.org/abs/2212.04088)

Week 9 Mar 20
: **Seminar**{: .label .label-red } Self-Supervised Learning
  **Seminar**{: .label .label-red } World Models
: - Suggested readings (on LLM Agents):
    - Langley et al. (2009) [Cognitive architectures: Research issues and challenges](https://www.sciencedirect.com/science/article/abs/pii/S1389041708000557)
    - Misra et al. (2017) [Mapping Instructions and Visual Observations to Actions with Reinforcement Learning](https://arxiv.org/abs/1704.08795)
    - Andreson et al. (2018) [Vision-and-Language Navigation: Interpreting Visually-Grounded Navigation Instructions in Real Environments](https://arxiv.org/abs/1711.07280)
    - Andreas (2022) [Language Models as Agent Models](https://arxiv.org/abs/2212.01681)
    - Sridhar et al. (2023) [Cognitive Neuroscience Perspective on Memory: Overview and Summary](https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2023.1217093/full)
  - Additional readings:
    - Anh et al. (2022) [Do As I Can, Not As I Say: Grounding Language in Robotic Affordances](https://arxiv.org/abs/2204.01691)
    - Sumers et al. (2023) [Cognitive Architectures for Language Agents](https://arxiv.org/abs/2309.02427)
    - Schick et al. (2023) [Language Models Can Teach Themselves to Use Tools](https://arxiv.org/pdf/2302.04761)
    - Rana et al. (2023) [SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning](https://arxiv.org/abs/2307.06135)
    - Kim et al. (2024) [ReALFRED: An Embodied Instruction Following Benchmark in Photo-Realistic Environments](https://arxiv.org/abs/2407.18550)
    - Li et al. (2024) [Embodied Agent Interface: Benchmarking LLMs for Embodied Decision Making](https://arxiv.org/abs/2410.07166)
