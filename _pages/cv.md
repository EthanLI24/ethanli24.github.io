---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. Candidate in Artificial Intelligence, The Hong Kong Polytechnic University, Jan. 2025 - Jan. 2028 (Expected)
  * Supervisors: Prof. Hongxia Yang and Prof. Wenguang Chen
* MEng in Artificial Intelligence, University of Science and Technology of China, Sep. 2021 - Jun. 2024
  * Supervisor: Prof. Yong Wang
* B.S. in Mechanical Engineering, Jiangnan University, Sep. 2017 - Jun. 2021
  * Supervisor: Prof. Jun Zhang

Research interests
======
* AI infrastructure and machine learning systems for large-scale LLM training, including distributed training, memory optimization and system-algorithm co-design.
* Efficient LLM training and inference, including FP8/FP4/NVFP4 training, INT4 rollout, quantization-aware training, compression and reasoning under efficiency constraints.

Research experience
======
* Ultra-Low-Bit LLM Pretraining in NVFP4 with System-Level Optimization, PolyU
  * Designed end-to-end ultra-low-bit NVFP4 LLM training pipelines with framework-level optimization on GB200/B300, covering pretraining, post-training and RL.
  * Developed system-algorithm co-design strategies for distributed training and investigated per-token scaling, block-level scaling and module-sensitive precision allocation.
* End-to-End FP8 Training for Reasoning-Capable LLMs at Scale, PolyU / InfiX.ai
  * Developed FP8 training recipes for reasoning-enhanced LLMs, covering continual pretraining, SFT, evaluation and deployment-oriented precision consistency.
  * Worked on thousand-GPU training with NVIDIA H- and B-series GPUs, including numerical stability monitoring, throughput profiling and memory analysis.
* INT4 RL with Real W4A16 Rollout for Train-Inference Alignment, with SGLang and LMSys
  * Built an INT4 QAT-RL pipeline that combines fake-quantized training with real W4A16 serving-side rollout.
  * Integrated SGLang and Marlin-based INT4 rollout kernels for MoE reasoning models.

Work experience
======
* Nov. 2024 - Present: Research Intern / Member of Technical Staff (Intern), InfiX.ai, HKSAR
  * Built LLM pretraining infrastructure deployed on a 2K+ GPU H800 cluster with correctness validation and training-pipeline integration.
  * Led research on ultra-low-bit LLM training and distributed optimization on GB200 GPUs.
  * Developed inference acceleration and low-bit deployment pipelines for edge devices.
* Jul. 2024 - Nov. 2024: Algorithm Engineer, Tencent Interactive Entertainment Group, Shenzhen
  * Accelerated Stable Diffusion inference on consumer GPUs via distributed parallelism.
  * Built automated web-agent pipelines for data collection.
* Jul. 2023 - Apr. 2024: AI Infra Engineer Intern, Ant Group NextEVO Research Center, Hangzhou
  * Contributed to ATorch, a distributed training framework built on Megatron-LM and DeepSpeed.
  * Developed RLHF system components and improved reward-model training efficiency.
* Oct. 2022 - May. 2023: Research Intern, AMD Xilinx DeePhi, Beijing
  * Worked on LLM compression and quantization methods including SmoothQuant and AWQ.
  * Deployed quantized models on AMD edge devices and contributed evaluation pipelines for Vitis-AI Model Zoo 3.0.
* Mar. 2022 - Jun. 2022: Research Intern, iFlytek Technology Research Institute
  
Skills
======
* Programming: Python, C++, CUDA, Golang
* Systems and frameworks: Megatron-LM, DeepSpeed, vLLM, Ray, Triton
* Research expertise: ultra-low-bit LLM training, FP8/FP4/NVFP4, quantization-aware training, distributed training systems, inference optimization
* Additional: profiling, memory optimization, large-scale training infrastructure

Publications
======
* Zhen Li, et al. Quantization Meets Reasoning: Exploring and Mitigating Degradation of Low-Bit LLMs in Mathematical Reasoning. Under review.
* Zhen Li, Yupeng Su, Songmiao Wang, et al. InfiJanice: Joint Analysis and In-situ Correction Engine for Quantization-Induced Math Degradation in Large Language Models. Under review.
* Wenjun Wang, Shuo Cai, Congkai Xie, Mingfa Feng, Yiming Zhang, Zhen Li, et al. InfiR2: A Comprehensive FP8 Training Recipe for Reasoning-Enhanced Language Models. arXiv.
* Congkai Xie, Shuo Cai, Wenjun Wang, et al. InfiR: Crafting Effective Small Language Models and Multimodal Small Language Models in Reasoning. arXiv.
* Qi Zhou, Yiming Zhang, Yanggan Gu, et al. Democratizing AI Through Model Fusion: A Comprehensive Review and Future Directions. Nexus, 2025.
* Zeyu Liu, Yuhang Liu, Guanghao Zhu, et al. Infi-MMR: Curriculum-based Unlocking Multimodal Reasoning via Phased Reinforcement Learning in Multimodal Small Language Models. Under review.
* Aofan Liu, Yuguo Yin, Hongjian Xing, Zhen Li, Yiyan Qi. MD3R: Minimizing Data Distribution Discrepancies to Tackle Inconsistencies in Multilingual Query-Code Retrieval. ACL@KnowFM, 2025.

Patents
======
* Zhen Li, et al. InfiDeck: An AI Operating System with Integrated Hardware Extensions. China Patent.
* Xiaotian Han, Zhen Li, et al. Reinforcement Learning Model Training Method and Device. U.S., China and Singapore Patent.
  
Teaching
======
* COMP6713 - Advanced Large Language Model and Beyond, Teaching Assistant, PolyU, 2026 Spring
* COMP2021 - Object-oriented Programming, Teaching Assistant, PolyU, 2025 Fall
* ML4432 - Machine Learning, Teaching Assistant, PolyU, 2025 Spring
* CONT010177 - Modern Control Theory, Teaching Assistant, USTC, 2022 Fall
  
Selected honors and awards
======
* PolyU Research Postgraduate Scholarship, 2025
* Outstanding Postgraduate Student of USTC, 2024
* First Class Academic Scholarship of USTC, 2021-2024
* Merit Student Award of the Province, 2021
* Annual Outstanding Student of the Province, 2019
* Merit Student Award, 2019
* Outstanding Student Leader Award, 2021

Service and leadership
======
* President of the University Student Union
