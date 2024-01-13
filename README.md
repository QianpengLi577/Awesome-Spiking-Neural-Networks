# Awesome Spiking Neural Networks [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repo collects papers, docs, codes about spiking neural networks for anyone who wants to do research on it. We are continuously improving the project. Welcome to PR the works (papers, repositories) that are missed by the repo. Special thanks to [Dayong Ren](https://github.com/DayongRen), [Qianpeng Li](https://github.com/QianpengLi577), and all researchers who have contributed to this project!

## Table of Contents

- [Survey Papers](#Survey_Papers)
  - [Survey_of_Direct_Training_Method](#Survey_of_Direct_Training_Method)
  - [Survey_of_ANN-SNN](#Survey_of_ANN-SNN)
- [Papers](#Papers)
  - [2024](#2024)
  - [2023](#2023)
  - [2022](#2022)
  - [2021](#2021)
  - [2020](#2020)
  - [2019](#2019)
  - [2018](#2018)
  - [2017](#2017)
  - [2016](#2016)
  - [2015](#2015)
- [Codes and Docs](#Codes_and_Docs)
- [Our Team](#Our_Team)

## Survey_Papers

### Survey_of_Direct_Training_Method

Our survey paper **Direct Learning-Based Deep Spiking Neural Networks: A Review** (_Frontiers in Neuroscience_) is a comprehensive survey of recent progress in directly training spiking neural networks. For details, please refer to:

**Direct Learning-Based Deep Spiking Neural Networks: A Review** [[Paper](https://arxiv.org/abs/2305.19725)]

[**Yufei Guo**](https://yfguo91.github.io/), Xuhui Huang, and Zhe Ma.

<details><summary>Bibtex</summary><pre><code>@article{guo2023direct,
  title={Direct learning-based deep spiking neural networks: a review},
  author={Guo, Yufei and Huang, Xuhui and Ma, Zhe},
  journal={Frontiers in Neuroscience},
  volume={17},
  pages={1209795},
  year={2023},
  publisher={Frontiers}
}</code></pre></details>


### Survey_of_ANN-SNN

The survey paper 

## Papers

### 2024

- [[AAAI](https://arxiv.org/pdf/2312.06372.pdf)] Ternary Spike: Learning Ternary Spikes for Spiking Neural Networks [[code](https://github.com/yfguo91/Ternary-Spike)]
- [[AAAI](https://arxiv.org/pdf/2312.07922.pdf)] Memory-Efficient Reversible Spiking Neural Networks [[code](https://github.com/mi804/RevSNN)]
- [[AAAI](https://arxiv.org/pdf/2308.06582.pdf)] Gated Attention Coding for Training High-performance and Efficient Spiking Neural Networks [[code](https://github.com/bollossom/GAC)]
- [[AAAI](https://arxiv.org/pdf/2308.10873.pdf)] SpikingBERT: Distilling BERT to Train Spiking Language Models Using Implicit Differentiation [[code](https://github.com/NeuroCompLab-psu/SpikingBERT)]
- [[AAAI](https://arxiv.org/pdf/2308.13250.pdf)] TC-LIF: A Two-Compartment Spiking Neuron Model for Long-term Sequential Modelling [[code](https://github.com/zhangshimin1/tc-lif)]
- [[AAAI](https://arxiv.org/pdf/2311.09077.pdf)] Spiking NeRF: Representing the Real-World Geometry by a Discontinuous Representation [[code](https://github.com/liaozhanfeng/Spiking-NeRF)]
- [[AAAI](https://arxiv.org/abs/2303.13077)] An Efficient Knowledge Transfer Strategy for Spiking Neural Networks from Static to Event Domain [[code](https://github.com/BrainCog-X/Brain-Cog/tree/main/examples/Perception_and_Learning/img_cls/transfer_for_dvs)]
- [[AAAI](https://arxiv.org/pdf/2401.01912.pdf)] Shrinking Your TimeStep: Towards Low-Latency Neuromorphic Object Recognition with Spiking Neural Networks
- [[AAAI](https://arxiv.org/pdf/2401.05373.pdf)] Dynamic Spiking Graph Neural Networks
- [[AAAI - no paper link]()] Dynamic Reactive Spiking Graph Neural Network
- [[AAAI - no paper link]()] Enhancing Representation of Spiking Neural Networks via Similarity-Sensitive Contrastive Learning
- [[AAAI - no paper link]()] Efficient Spiking Neural Networks with Sparse Selective Activation for Continual Learning
- [[AAAI - no paper link]()] Enhancing Training of Spiking Neural Network with Stochastic Latency
- [[AAAI - no paper link]()] Enhancing the robustness of spiking neural networks with stochastic gating mechanisms


### 2023

- [[NeurIPS](https://arxiv.org/pdf/2310.06232.pdf)] Spiking PointNet: Spiking Neural Networks for Point Clouds [[code](https://github.com/DayongRen/Spiking-PointNet)]
- [[NeurIPS](https://arxiv.org/pdf/2307.01694.pdf)] Spike-driven Transformer [[code](https://github.com/BICLab/Spike-Driven-Transformer)]
- [[NeurIPS](https://arxiv.org/pdf/2305.17650.pdf)] Evolving Connectivity for Recurrent Spiking Neural Networks [[code](https://github.com/imoneoi/EvolvingConnectivity)]
- [[NeurIPS](https://openreview.net/pdf?id=8IvW2k5VeA)] Exploring Loss Functions for Time-based Training Strategy in Spiking Neural Networks [[code](https://github.com/zhuyaoyu/SNN-temporal-training-losses)]
- [[NeurIPS](https://openreview.net/pdf?id=OMDgOjdqoZ)] EICIL: Joint Excitatory Inhibitory Cycle Iteration Learning for Deep Spiking Neural Networks
- [[NeurIPS](https://openreview.net/forum?id=Ht79ZTVMsn)] Addressing the speed-accuracy simulation trade-off for adaptive spiking neurons [[code](https://github.com/webstorms/blocks)]
- [[NeurIPS](https://arxiv.org/pdf/2304.12760.pdf)] Parallel Spiking Neurons with High Efficiency and Ability to Learn Long-term Dependencies [[code](https://github.com/fangwei123456/Parallel-Spiking-Neuron)]
- [[NeurIPS](https://arxiv.org/pdf/2307.06003.pdf)] Unsupervised Optical Flow Estimation with Dynamic Timing Representation for Spike Camera [[code](https://github.com/Bosserhead/USFlow)]
- [[NeurIPS](https://openreview.net/pdf?id=FLFasCFJNo)] Meta-learning families of plasticity rules in recurrent spiking networks using simulation-based inference
- [[NeurIPS](https://arxiv.org/pdf/2306.12045.pdf)] Temporal Conditioning Spiking Latent Variable Models of the Neural Response to Natural Visual Scenes
- [[NeurIPS](https://openreview.net/pdf?id=aGZp61S9Lj)] Enhancing Adaptive History Reserving by Spiking Convolutional Block Attention Module in Recurrent Neural Networks
- [[NeurIPS](https://arxiv.org/pdf/2306.03603.pdf)] Trial matching: capturing variability with data-constrained spiking neural networks [[code](https://github.com/EPFL-LCN/pub-sourmpis2023-neurips)]
- [[NeurIPS](https://openreview.net/pdf?id=yzZbwQPkmP)] SparseProp: Efficient Event-Based Simulation and Training of Sparse Recurrent Spiking Neural Networks
- [[NeurIPS](https://arxiv.org/pdf/2306.03603.pdf)] SEENN: Towards Temporal Spiking Early-Exit Neural Networks [[code](https://github.com/Intelligent-Computing-Lab-Yale/SEENN)]
- [[ACMMM](https://arxiv.org/pdf/2308.04672.pdf)] Resource Constrained Model Compression via Minimax Optimization for Spiking Neural Networks [[code](https://github.com/chenjallen/Resource-Constrained-Compression-on-SNN)]
- [[ICCV](https://arxiv.org/pdf/2302.14311.pdf)] Towards Memory- and Time-Efficient Backpropagation for Training Spiking Neural Networks [[code](https://github.com/qymeng94/SLTT)]
- [[ICCV](https://arxiv.org/pdf/2307.11411.pdf)] Deep Directly-Trained Spiking Neural Networks for Object Detection [[code](https://github.com/BICLab/EMS-YOLO)]
- [[ICCV](https://arxiv.org/pdf/2308.08227.pdf)] Inherent Redundancy in Spiking Neural Networks [[code](https://github.com/BICLab/ASA-SNN)]
- [[ICCV](https://arxiv.org/pdf/2308.06787.pdf)] RMP-Loss: Regularizing Membrane Potential Distribution for Spiking Neural Networks
- [[ICCV](https://arxiv.org/pdf/2308.08359.pdf)] Membrane Potential Batch Normalization for Spiking Neural Networks [[code](https://github.com/yfguo91/MPBN)]
- [[ICCV](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Masked_Spiking_Transformer_ICCV_2023_paper.html)] Masked Spiking Transformer [[code](https://github.com/bic-L/Masked-Spiking-Transformer)]
- [[ICML](https://openreview.net/pdf?id=GdkwSGTpbC)] Adaptive Smoothing Gradient Learning for Spiking Neural Networks [[code](https://github.com/Windere/ASGL-SNN)]
- [[ICML](https://openreview.net/pdf?id=zRkz4duLKp)] Surrogate Module Learning: Reduce the Gradient Error Accumulation in Training Spiking Neural Networks [[code](https://github.com/brain-intelligence-lab/surrogate_module_learning)]
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Bu_Rate_Gradient_Approximation_Attack_Threats_Deep_Spiking_Neural_Networks_CVPR_2023_paper.pdf)] Rate Gradient Approximation Attack Threats Deep Spiking Neural Networks [[code](https://github.com/putshua/SNN_attack_RGA)]
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2023/papers/Chang_1000_FPS_HDR_Video_With_a_Spike-RGB_Hybrid_Camera_CVPR_2023_paper.pdf)] 1000 FPS HDR Video with a Spike-RGB Hybrid Camera
- [[CVPR](https://arxiv.org/pdf/2304.05627.pdf)] Constructing Deep Spiking Neural Networks from Artificial Neural Networks with Knowledge Distillation
- [[ICLR](https://arxiv.org/pdf/2302.10685.pdf)] Bridging the Gap between ANNs and SNNs by Calibrating Offset Spikes [[code](https://github.com/hzc1208/ANN2SNN_COS)]
- [[ICLR](https://arxiv.org/pdf/2302.13019.pdf)] A Unified Framework for Soft Threshold Pruning [[code](https://github.com/Yanqi-Chen/LATS)]
- [[ICLR](https://openreview.net/pdf?id=QIRtAqoXwj)] Heterogeneous Neuronal and Synaptic Dynamics for Spike-Efficient Unsupervised Learning: Theory and Design Principles
- [[ICLR](https://openreview.net/pdf?id=pgU3k7QXuz0)] Spiking Convolutional Neural Networks for Text Classification [[code](https://github.com/Lvchangze/snn)]
- [[ICLR](https://openreview.net/pdf?id=frE4fUwz_h)] Spikformer: When Spiking Neural Network Meets Transformer [[code](https://github.com/ZK-Zhou/spikformer)]
- [[PR](https://arxiv.org/pdf/2305.02099.pdf)] Joint A-SNN: Joint Training of Artificial and Spiking Neural Networks via Self-Distillation and Weight Factorization [[code](https://github.com/yfguo91/Joint-A-SNN)]
- [[AAAI](https://arxiv.org/pdf/2302.02091.pdf)] Reducing ANN-SNN Conversion Error through Residual Membrane Potential [[code](https://github.com/hzc1208/ANN2SNN_SRP)]
- [[AAAI](https://arxiv.org/pdf/2211.14406.pdf)] Exploring Temporal Information Dynamics in Spiking Neural Networks [[code](https://github.com/Intelligent-Computing-Lab-Yale/Exploring-Temporal-Information-Dynamics-in-Spiking-Neural-Networks)]
- [[AAAI](https://arxiv.org/pdf/2303.06060.pdf)] Deep Spiking Neural Networks with High Representation Similarity Model Visual Pathways of Macaque and Mouse [[code](https://github.com/Grasshlw/SNN-Neural-Similarity-Static)]
- [[IJCAI](https://arxiv.org/pdf/2211.11760.pdf)] A Low Latency Adaptive Coding Spiking Framework for Deep Reinforcement Learning
- [[IJCAI](https://arxiv.org/pdf/2308.04749.pdf)] Enhancing Efficient Continual Learning with Dynamic Structure Development of Spiking Neural Networks [[code](https://github.com/BrainCog-X/Brain-Cog/tree/main/examples/Structural_Development/DSD-SNN)]
- [[ICASSP](https://arxiv.org/pdf/2302.08607.pdf)] Adaptive Axonal Delays in feedforward spiking neural networks for accurate spoken word recognition
- [[ICASSP](https://arxiv.org/pdf/2303.12738.pdf)] Joint ANN-SNN Co-training for Object Localization and Image Segmentation
- [[ICASSP](https://ieeexplore.ieee.org/document/10097174)] Leveraging Sparsity with Spiking Recurrent Neural Networks for Energy-Efficient Keyword Spotting
- [[ICASSP](https://ieeexplore.ieee.org/document/10096951)] Training Robust Spiking Neural Networks on Neuromorphic Data with Spatiotemporal Fragments
- [[ICASSP](https://ieeexplore.ieee.org/document/10096958)] Training Stronger Spiking Neural Networks with Biomimetic Adaptive Internal Association Neurons
- [[ICASSP](https://ieeexplore.ieee.org/document/10094902)] In-Sensor & Neuromorphic Computing Are all You Need for Energy Efficient Computer Vision




### 2022

- [[NeurIPS](https://arxiv.org/pdf/2210.13768.pdf)] GLIF: A Unified Gated Leaky Integrate-and-Fire Neuron for Spiking Neural Networks [[code](https://github.com/Ikarosy/Gated-LIF)]
- [[NeurIPS](https://arxiv.org/pdf/2206.04426.pdf)] Biologically Inspired Dynamic Thresholds for Spiking Neural Networks
- [[NeurIPS](https://arxiv.org/pdf/2210.04195.pdf)] Online Training Through Time for Spiking Neural Networks [[code](https://github.com/pkuxmq/OTTT-SNN)]
- [[NeurIPS](https://arxiv.org/pdf/2205.13493.pdf)] Mesoscopic modeling of hidden spiking neurons
- [[NeurIPS](https://openreview.net/pdf?id=fLIgyyQiJqz)] Temporal Effective Batch Normalization in Spiking Neural Networks [[code](https://openreview.net/attachment?id=fLIgyyQiJqz&name=supplementary_material)]
- [[NeurIPS](https://openreview.net/pdf?id=Lr2Z85cdvB)] Differentiable hierarchical and surrogate gradient search for spiking neural networks [[code](https://github.com/Huawei-BIC/SpikeDHS)]
- [[NeurIPS](https://openreview.net/pdf?id=BbaSRgUHW3)] LTMD: Learning Improvement of Spiking Neural Networks with Learnable Thresholding Neurons and Moderate Dropout [[code](https://github.com/sq117/LTMD)]
- [[NeurIPS](https://openreview.net/pdf?id=I0CiI7Oyp1E)] Theoretically Provable Spiking Neural Networks
- [[NeurIPS](https://openreview.net/pdf?id=Yopob26XjmL)] Natural gradient enables fast sampling in spiking neural networks
- [[NeurIPS](https://openreview.net/pdf?id=zdmYnIRXvKS)] Biologically plausible solutions for spiking networks with efficient coding
- [[NeurIPS](https://openreview.net/pdf?id=Ncyc0JS7Q16)] Toward Robust Spiking Neural Network Against Adversarial Perturbation
- [[NeurIPS](https://openreview.net/pdf?id=xwBdjfKt7_W)] SNN-RAT: Robustness-enhanced Spiking Neural Network through Regularized Adversarial Training
- [[NeurIPS](https://openreview.net/pdf?id=xwBdjfKt7_W)] Emergence of Hierarchical Layers in a Single Sheet of Self-Organizing Spiking Neurons
- [[NeurIPS](https://openreview.net/pdf?id=d4JmP1T45WE)] Training Spiking Neural Networks with Event-driven Backpropagation
- [[NeurIPS](https://openreview.net/pdf?id=Jw34v_84m2b)] IM-Loss: Information Maximization Loss for Spiking Neural Networks
- [[NeurIPS](https://openreview.net/pdf?id=ckQvYXizgd1)] The computational and learning benefits of Daleian neural networks
- [[NeurIPS](https://openreview.net/pdf?id=-yiZR4_Xhh)] Dance of SNN and ANN: Solving binding problem by combining spike timing and reconstructive attention
- [[NeurIPS](https://openreview.net/pdf?id=3vYkhJIty7E)] Learning Optical Flow from Continuous Spike Streams [[code](https://github.com/ruizhao26/Spike2Flow)]
- [[NeurIPS](https://openreview.net/pdf?id=iUOUnyS6uTf)] STNDT: Modeling Neural Population Activity with Spatiotemporal Transformers
- [[AAAI](https://arxiv.org/pdf/2202.01440.pdf)] Optimized Potential Initialization for Low-latency Spiking Neural Networks
- [[AAAI](https://arxiv.org/pdf/2104.03414.pdf)] PrivateSNN: Privacy-Preserving Spiking Neural Networks
- [[AAAI](https://aaai.org/AAAI22Papers/AAAI-364.LiuF.pdf)] SpikeConverter: An Efficient Conversion Framework Zipping the Gap between Artificial Neural Networks and Spiking Neural Networks
- [[AAAI](https://aaai.org/AAAI22Papers/AAAI-884.ZhangD.pdf)] Multi-sacle Dynamic Coding improved Spiking Actor Network for Reinforcement Learning
- [[AAAI](https://arxiv.org/pdf/2110.00375.pdf)] Fully Spiking Variational Autoencoder [[code](https://github.com/kamata1729/FullySpikingVAE)]
- [[AAAI](https://arxiv.org/pdf/2109.01905.pdf)] Spiking Neural Networks with Improved Inherent Recurrence Dynamics for Sequential Learning
- [[AAAI](https://arxiv.org/pdf/2109.04871.pdf)] Spatio-Temporal Recurrent Networks for Event-Based Optical Flow Estimation [[code](https://github.com/ruizhao26/STE-FlowNet)]
- [[IJCAI](https://arxiv.org/pdf/2204.13271.pdf)] Efficient and Accurate Conversion of Spiking Neural Network with Burst Spikes [[code](https://github.com/Brain-Cog-Lab/Conversion_Burst)]
- [[IJCAI](https://arxiv.org/pdf/2205.02767.pdf)] Spiking Graph Convolutional Networks [[code](https://github.com/ZulunZhu/SpikingGCN)]
- [[IJCAI](https://www.ijcai.org/proceedings/2022/0347.pdf)] Signed Neuron with Memory: Towards Simple, Accurate and High-Effcient ANN-SNN Conversion [[code](https://github.com/ppppps/ANN2SNNConversion_SNM_NeuronNorm)]
- [[IJCAI](https://www.ijcai.org/proceedings/2022/0396.pdf)] Self-Supervised Mutual Learning for Dynamic Scene Reconstruction of Spiking Camera
- [[IJCAI](https://www.ijcai.org/proceedings/2022/0343.pdf)] Multi-Level Firing with Spiking DS-ResNet: Enabling Better and Deeper Directly-Trained Spiking Neural Networks [[code](https://github.com/langfengQ/MLF-DSResNet)]
- [[ICML](https://proceedings.mlr.press/v162/chen22ac/chen22ac.pdf)] State Transition of Dendritic Spines Improves Learning of Sparse Spiking Neural Networks
- [[ICML](https://arxiv.org/pdf/2201.12738.pdf)] AutoSNN: Towards Energy-Efficient Spiking Neural Networks
- [[ICML](https://arxiv.org/pdf/2204.01668.pdf)] Scalable Spike-and-Slab
- [[ICML](https://proceedings.mlr.press/v162/khajehnejad22a/khajehnejad22a.pdf)] Neural Network Poisson Models for Behavioural and Neural Spike Train Data
- [[CVPR](https://arxiv.org/pdf/2203.14679.pdf)] Brain-inspired Multilayer Perceptron with Spiking Neurons [[code](https://github.com/huawei-noah/Efficient-AI-Backbones/tree/master/snnmlp_pytorch)]
- [[CVPR](https://arxiv.org/pdf/2205.00459.pdf)] Training High-Performance Low-Latency Spiking Neural Networks by Differentiation on Spike Representation [[code](https://github.com/qymeng94/DSR)]  
- [[CVPR](https://arxiv.org/pdf/2201.10943.pdf)] Event-based Video Reconstruction via Potential-assisted Spiking Neural Network [[code](https://github.com/LinZhu111/EVSNN)]  
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_RecDis-SNN_Rectifying_Membrane_Potential_Distribution_for_Directly_Training_Spiking_Neural_CVPR_2022_paper.pdf)] RecDis-SNN: Rectifying Membrane Potential Distribution for Directly Training Spiking Neural Networks
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Spiking_Transformers_for_Event-Based_Single_Object_Tracking_CVPR_2022_paper.pdf)] Spiking Transformers for Event-Based Single Object Tracking [[code](https://github.com/Jee-King/CVPR2022_STNet)]  
- [[CVPR](https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_Optical_Flow_Estimation_for_Spiking_Camera_CVPR_2022_paper.pdf)] Optical Flow Estimation for Spiking Camera [[code](https://github.com/Acnext/Optical-Flow-For-Spiking-Camera)]
- [[ECCV](https://arxiv.org/pdf/2207.01382.pdf)] Exploring Lottery Ticket Hypothesis in Spiking Neural Networks [[code](https://github.com/Intelligent-Computing-Lab-Yale/Exploring-Lottery-Ticket-Hypothesis-in-SNNs)]
- [[ECCV](https://arxiv.org/pdf/2203.06145.pdf)] Neuromorphic Data Augmentation for Training Spiking Neural Networks [[code](https://github.com/Intelligent-Computing-Lab-Yale/NDA_SNN)]
- [[ECCV](https://arxiv.org/pdf/2201.10355.pdf)] Neural Architecture Search for Spiking Neural Networks [[code](https://github.com/Intelligent-Computing-Lab-Yale/Neural-Architecture-Search-for-Spiking-Neural-Networks)]
- [[ECCV](https://arxiv.org/pdf/2210.06686.pdf)] Real Spike: Learning Real-valued Spikes for Spiking Neural Networks [[code](https://github.com/yfguo91/Real-Spike)]
- [[ECCV](https://arxiv.org/pdf/2307.04356.pdf)] Reducing Information Loss for Spiking Neural Networks [[code](https://github.com/yfguo91/Re-Loss)]
- [[ICLR](https://openreview.net/pdf?id=7B3IJMM1k_M)] Optimal ANN-SNN Conversion for High-accuracy and Ultra-low-latency Spiking Neural Networks [[code](https://github.com/putshua/SNN_conversion_QCFS)]  
- [[ICLR](https://openreview.net/pdf?id=iMH1e5k7n3L)] Spike-inspired rank coding for fast and accurate recurrent neural networks
- [[ICLR](https://openreview.net/pdf?id=bp-LJ4y_XC)] Sequence Approximation using Feedforward Spiking Neural Network for Spatiotemporal Learning: Theory and Optimization Methods
- [[ICLR](https://openreview.net/pdf?id=_XNtisL32jv)] Temporal Efficient Training of Spiking Neural Network via Gradient Re-weighting [[code](https://github.com/brain-intelligence-lab/temporal_efficient_training)]  


### 2021

- [[NeurIPS](https://openreview.net/pdf?id=f2Llmm_z5Sm)] Training Feedback Spiking Neural Networks by Implicit Differentiation on the Equilibrium State
- [[NeurIPS](https://openreview.net/pdf?id=9DEAT9pDiN)] Fitting summary statistics of neural data with a differentiable spiking network simulator
- [[NeurIPS](https://openreview.net/pdf?id=aLE2sEtMNXv)] Sparse Spiking Gradient Descent
- [[NeurIPS](https://openreview.net/pdf?id=H4e7mBnC9f0)] Differentiable Spike: Rethinking Gradient-Descent for Training Spiking Neural Networks
- [[NeurIPS](https://openreview.net/pdf?id=MySjw6CHPa4)] Self-Supervised Learning of Event-Based Optical Flow with Spiking Neural Networks
- [[NeurIPS](https://openreview.net/pdf?id=6OoCDvFV4m)] Deep Residual Learning in Spiking Neural Networks
- [[NeurIPS](https://openreview.net/pdf?id=Fw0IQgaGlhh)] Learning to Time-Decode in Spiking Neural Networks Through the Information Bottleneck
- [[ICLR](https://openreview.net/pdf?id=FZ1oTwcXchK)] Optimal Conversion of Conventional Artificial Neural Networks to Spiking Neural Networks
- [[ICLR](https://openreview.net/pdf?id=aGfU_xziEX8)] Efficient Inference of Flexible Interaction in Spiking-neuron Networks

## Codes_and_Docs

- [[中文](https://blog.csdn.net/qq_43622216/article/details/128918566)] 2023年顶会、顶刊SNN相关论文
- [[中文](https://blog.csdn.net/qq_43622216/article/details/124163883)] 2022年顶会、顶刊SNN相关论文

## Our_Team

Our team .


### Publications



