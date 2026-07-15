<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-16 ~ 2026-07-15
- 运行时间：2026-07-15 14:27:19 UTC
- 运行状态：成功
- 本次总论文数：58
- 精读区：46
- 速读区：12

### 今日简报（AI）
本期精读58篇前沿论文，聚焦扩散策略与流匹配如何让机器人动作更平滑、更连贯。  
最值得关注的是延迟感知异步扩散实现无碰撞操控，以及频率感知流匹配带来的连续一致动作生成。  
想上手可先试试将扩散模型用于避障规划，或在训练中引入频率特征来提升动作连贯性。
- 详情：[/20260616-20260715/README](/20260616-20260715/README)

### 精读区论文标签
1. [LAGO Policy: Latency-Aware Asynchronous Diffusion Policies with Goal-Directed Collision-Free Planning for Smooth Manipulation](/20260616-20260715/2606.17982v1-lago-policy-latency-aware-asynchronous-diffusion-policies-with-goal-directed-collision-free-planning-for-smooth-manipulation)  
   标签：评分：10.0/10、query:rmgp
   evidence：基于扩散的视觉运动策略，结合轨迹优化实现平滑操作
2. [Frequency-Aware Flow Matching for Continuous and Consistent Robotic Action Generation](/20260616-20260715/2606.20135v1-frequency-aware-flow-matching-for-continuous-and-consistent-robotic-action-generation)  
   标签：评分：10.0/10、query:gen-imit
   evidence：提出频率感知流匹配（FAFM），用于连续且时间一致的机器人动作生成，解决异构控制频率问题。
3. [FOCA: Future-Oriented Conditioning for Data-Efficient Vision-Language-Action Adaptation](/20260616-20260715/2606.20867v1-foca-future-oriented-conditioning-for-data-efficient-vision-language-action-adaptation)  
   标签：评分：10.0/10、query:rmgp
   evidence：未来导向的条件化方法实现数据高效的少样本VLA适配
4. [FlowDPG: Deterministic Policy Gradient on Flow Matching Policies for Real-World Manipulation](/20260616-20260715/2606.22303v1-flowdpg-deterministic-policy-gradient-on-flow-matching-policies-for-real-world-manipulation)  
   标签：评分：10.0/10、query:gen-imit
   evidence：面向机器人操作中流匹配策略的确定性策略梯度
5. [RoamFlow: Reinforcement-Aligned One-Step Action MeanFlow Policy for Image-Goal Navigation](/20260616-20260715/2606.29934v1-roamflow-reinforcement-aligned-one-step-action-meanflow-policy-for-image-goal-navigation)  
   标签：评分：10.0/10、query:fewstepgen
   evidence：基于MeanFlow的单步动作生成策略用于图像目标导航
6. [Guided Action Flow: Q-Guided Inference for Flow-Matching Vision-Language-Action Policies](/20260616-20260715/2607.02092v1-guided-action-flow-q-guided-inference-for-flow-matching-vision-language-action-policies)  
   标签：评分：10.0/10、query:gen-imit
   evidence：利用学习到的批评器为流匹配视觉-语言-动作策略提供测试时引导
7. [RynnWorld-Teleop: An Action-Conditioned World Model for Digital Teleoperation](/20260616-20260715/2607.06558v2-rynnworld-teleop-an-action-conditioned-world-model-for-digital-teleoperation)  
   标签：评分：10.0/10、query:world-model
   evidence：动作条件世界模型用于数字遥操作，生成视频作为模仿学习数据。
8. [Invertible Neural Network Adapter for One-Step Flow Matching in Robot Manipulation](/20260616-20260715/2606.19194v1-invertible-neural-network-adapter-for-one-step-flow-matching-in-robot-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：基于可逆神经网络的单步流匹配机器人操作策略
9. [DiffusionVS: A Generative Framework for Robust Visual Servoing Based on Diffusion Policy](/20260616-20260715/2606.19397v1-diffusionvs-a-generative-framework-for-robust-visual-servoing-based-on-diffusion-policy)  
   标签：评分：9.0/10、query:gen-imit
   evidence：基于扩散策略，通过条件去噪生成相机速度，实现鲁棒视觉伺服。
10. [MirrorDuo: Reflection-Consistent Visuomotor Learning from Mirrored Demonstration Pairs](/20260616-20260715/2606.20048v1-mirrorduo-reflection-consistent-visuomotor-learning-from-mirrored-demonstration-pairs)  
   标签：评分：9.0/10、query:gen-imit
   evidence：基于反射的公式，为每个原始演示生成镜像副本，可应用于扩散策略或行为克隆。
11. [BayesFP: Posterior Estimation for Flow-Based Policies via Feynman-Kac Sampling](/20260616-20260715/2606.21014v1-bayesfp-posterior-estimation-for-flow-based-policies-via-feynman-kac-sampling)  
   标签：评分：9.0/10、query:gen-imit
   evidence：通过后验采样实现流匹配策略的约束生成
12. [VQActFlow: Vector-Quantized Action Mode Steering for Multi-Task Robot Manipulation](/20260616-20260715/2606.21600v1-vqactflow-vector-quantized-action-mode-steering-for-multi-task-robot-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：基于变分流匹配的多任务机器人操作策略
13. [CoRDE: Concept-Prior Routed Diffusion Experts for Structural Generalization in Robot Manipulation](/20260616-20260715/2606.21935v1-corde-concept-prior-routed-diffusion-experts-for-structural-generalization-in-robot-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：利用概念先验的扩散专家网络实现长程操作中的结构泛化
14. [Scalable Maximum Entropy Reinforcement Learning for Diffusion Policies via Adjoint Matching](/20260616-20260715/2606.22630v1-scalable-maximum-entropy-reinforcement-learning-for-diffusion-policies-via-adjoint-matching)  
   标签：评分：9.0/10、query:rmgp
   evidence：通过伴随匹配优化扩散策略的强化学习
15. [Temporal Logic Guidance for Action-Only Diffusion Policies with World Models](/20260616-20260715/2606.22729v1-temporal-logic-guidance-for-action-only-diffusion-policies-with-world-models)  
   标签：评分：9.0/10、query:world-model
   evidence：将扩散策略与学习的世界模型结合，实现时序逻辑引导的动作生成
16. [Improving Robotic Imitation Learning via Trajectory Standardization](/20260616-20260715/2606.22907v1-improving-robotic-imitation-learning-via-trajectory-standardization)  
   标签：评分：9.0/10、query:gen-imit
   evidence：轨迹标准化改进机器人模仿学习
17. [Flowing With Purpose: Latent Action Guided Flow Matching Policies For Robotic Manipulation](/20260616-20260715/2606.23420v1-flowing-with-purpose-latent-action-guided-flow-matching-policies-for-robotic-manipulation)  
   标签：评分：9.0/10、query:gen-imit
   evidence：潜在动作引导的流匹配策略用于机器人操作
18. [dVLA-RL: Reinforcement Learning over Denoising Trajectories for Discrete Diffusion Vision-Language-Action Models](/20260616-20260715/2606.23623v1-dvla-rl-reinforcement-learning-over-denoising-trajectories-for-discrete-diffusion-vision-language-action-models)  
   标签：评分：9.0/10、query:gen-imit
   evidence：离散扩散VLA模型通过掩码生成建模（扩散策略）用于机器人操作动作生成。
19. [Learning to See While Learning to Act: Diffusion Models for Active Perception in Robot Imitation](/20260616-20260715/2606.23625v1-learning-to-see-while-learning-to-act-diffusion-models-for-active-perception-in-robot-imitation)  
   标签：评分：9.0/10、query:gen-imit
   evidence：扩散模型用于机器人模仿中的主动感知
20. [Grounding Generative Policies in Physics: Optimization-Guided Diffusion for Robot Control](/20260616-20260715/2606.24208v1-grounding-generative-policies-in-physics-optimization-guided-diffusion-for-robot-control)  
   标签：评分：9.0/10、query:rmgp
   evidence：优化引导扩散模型实现物理可行的机器人控制
21. [World Action Models Enable Continual Imitation Learning with Recurrent Generative Replays](/20260616-20260715/2606.27374v1-world-action-models-enable-continual-imitation-learning-with-recurrent-generative-replays)  
   标签：评分：9.0/10、query:world-model
   evidence：利用世界动作模型生成伪回放以进行持续模仿学习
22. [Learning Transferable Dynamics Priors from Action to World Modeling](/20260616-20260715/2606.29501v1-learning-transferable-dynamics-priors-from-action-to-world-modeling)  
   标签：评分：9.0/10、query:world-model
   evidence：在机器人操作数据上预训练扩散世界模型以获得可迁移动力学先验
23. [CORE: Common Outcome Regularities from Action-Free Visual Demonstrations for Robot Manipulation](/20260616-20260715/2606.29517v1-core-common-outcome-regularities-from-action-free-visual-demonstrations-for-robot-manipulation)  
   标签：评分：9.0/10、query:gen-imit
   evidence：从无动作视觉演示中通过结果规律性进行模仿学习
24. [OpenSPM: An Environment-Transferable Robotic Key Spatial Pose Memory and Closed-Loop High-Frequency Flow-Matching Action Generation Model](/20260616-20260715/2606.29936v1-openspm-an-environment-transferable-robotic-key-spatial-pose-memory-and-closed-loop-high-frequency-flow-matching-action-generation-model)  
   标签：评分：9.0/10、query:rmgp
   evidence：用于闭环机器人操作的流匹配动作生成模型
25. [Efficient Sim-to-Real Transfer of World-Action Models from Synthetic Priors](/20260616-20260715/2606.31101v1-efficient-sim-to-real-transfer-of-world-action-models-from-synthetic-priors)  
   标签：评分：9.0/10、query:world-model
   evidence：世界-动作模型从仿真到真实机器人的迁移
26. [ELASTIC: Efficiently Learning to Adaptively Scale Test-Time Compute for Generative Control Policies](/20260616-20260715/2606.31132v1-elastic-efficiently-learning-to-adaptively-scale-test-time-compute-for-generative-control-policies)  
   标签：评分：9.0/10、query:rmgp
   evidence：为扩散策略和流基VLA自适应分配测试时计算
27. [ABot-M0.5: Unified Mobility-and-Manipulation World Action Model](/20260616-20260715/2607.00678v2-abot-m05-unified-mobility-and-manipulation-world-action-model)  
   标签：评分：9.0/10、query:world-model
   evidence：提出用于移动操作的世界动作模型，预测未来状态与动作
28. [WorldSample: Closed-loop Real-robot RL with World Modelling](/20260616-20260715/2607.02431v1-worldsample-closed-loop-real-robot-rl-with-world-modelling)  
   标签：评分：9.0/10、query:world-model
   evidence：世界模型用于真实机器人强化学习的数据增强
29. [High-Fidelity One-Step Generative Visuomotor Policy via Recursive Correction, Frequency Consistency, and Contrastive Flow Matching](/20260616-20260715/2607.03865v1-high-fidelity-one-step-generative-visuomotor-policy-via-recursive-correction-frequency-consistency-and-contrastive-flow-matching)  
   标签：评分：9.0/10、query:rmgp
   evidence：使用对比流匹配与递归校正的单步生成式视觉运动策略
30. [XS-VLA: Coupling Coarse-grained Spatial Distillation with Latent Flow Matching for Lightweight Robotic Control](/20260616-20260715/2607.04171v1-xs-vla-coupling-coarse-grained-spatial-distillation-with-latent-flow-matching-for-lightweight-robotic-control)  
   标签：评分：9.0/10、query:rmgp
   evidence：结合粗粒度空间蒸馏与潜在流匹配的轻量级VLA机器人控制
31. [Simple-to-Complex Structured Demonstrations for Vision-Language-Action Learning](/20260616-20260715/2607.04591v1-simple-to-complex-structured-demonstrations-for-vision-language-action-learning)  
   标签：评分：9.0/10、query:gen-imit
   evidence：由简到繁的示范组织提升机器人模仿学习
32. [KAM-WM: Kinematic Affordance Maps from Latent World Models for Robot Manipulation](/20260616-20260715/2607.04652v1-kam-wm-kinematic-affordance-maps-from-latent-world-models-for-robot-manipulation)  
   标签：评分：9.0/10、query:world-model
   evidence：利用流匹配潜在世界模型提取运动供给图，条件扩散策略实现少样本操作
33. [Spatial Attention: Adapting Execution Horizons for Diffusion Policies via Observation Sensitivity](/20260616-20260715/2607.04739v1-spatial-attention-adapting-execution-horizons-for-diffusion-policies-via-observation-sensitivity)  
   标签：评分：9.0/10、query:rmgp
   evidence：基于空间注意力与观测敏感性的扩散策略自适应执行时域
34. [DSWAM: A Dual-System World Action Foundation Model for Fine-Grained Robot Manipulation](/20260616-20260715/2607.04927v1-dswam-a-dual-system-world-action-foundation-model-for-fine-grained-robot-manipulation)  
   标签：评分：9.0/10、query:world-model
   evidence：世界动作基础模型用于精细操作
35. [Learning 4D Geometric Priors for Inference-Efficient World Action Models](/20260616-20260715/2607.05468v1-learning-4d-geometric-priors-for-inference-efficient-world-action-models)  
   标签：评分：9.0/10、query:world-model
   evidence：具有4D几何先验的世界动作模型用于高效操作
36. [RynnWorld-4D: 4D Embodied World Models for Robotic Manipulation](/20260616-20260715/2607.06559v1-rynnworld-4d-4d-embodied-world-models-for-robotic-manipulation)  
   标签：评分：9.0/10、query:world-model
   evidence：预测RGB、深度和光流的4D世界模型用于机器人操作
37. [PriGo: Test-Time Primitive Guidance to Diffusion and Flow Policies for Adaptive Robotic Manipulation](/20260616-20260715/2607.07076v1-prigo-test-time-primitive-guidance-to-diffusion-and-flow-policies-for-adaptive-robotic-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：基元引导的扩散与流策略测试时自适应
38. [Expressivity and Statistical Trade-offs in Diffusion Policy Learning](/20260616-20260715/2607.07967v1-expressivity-and-statistical-trade-offs-in-diffusion-policy-learning)  
   标签：评分：9.0/10、query:rmgp
   evidence：通过漂移Lipschitz预算分析扩散策略的表达性
39. [An exact information theory of generalization phase transitions in Bayesian diffusion models](/20260616-20260715/2607.08041v1-an-exact-information-theory-of-generalization-phase-transitions-in-bayesian-diffusion-models)  
   标签：评分：9.0/10、query:gen-models
   evidence：贝叶斯扩散模型泛化相变的精确信息理论
40. [SkillPlug: Unsupervised Skill Mining for Few-Shot Adaptation in Robotic Manipulation](/20260616-20260715/2607.08354v1-skillplug-unsupervised-skill-mining-for-few-shot-adaptation-in-robotic-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：无监督技能挖掘实现少样本视觉运动策略适配
41. [FlowDAgger: Human-in-the-Loop Adaptation of Generative Robot Policies in Latent Space](/20260616-20260715/2607.08877v1-flowdagger-human-in-the-loop-adaptation-of-generative-robot-policies-in-latent-space)  
   标签：评分：9.0/10、query:gen-imit
   evidence：人在回路中利用流匹配和扩散模型适配生成式机器人策略
42. [Source-Lifted Flow Matching for Intervenable Multimodal Imitation](/20260616-20260715/2607.10206v1-source-lifted-flow-matching-for-intervenable-multimodal-imitation)  
   标签：评分：9.0/10、query:rmgp
   evidence：可通过源选择进行干预的流匹配多模态模仿策略
43. [SUREFlow: State-space Uncertainty-aware REsidual Flow Matching for Robust Robot Manipulation](/20260616-20260715/2607.10504v1-sureflow-state-space-uncertainty-aware-residual-flow-matching-for-robust-robot-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：不确定性感知残差流匹配用于鲁棒机器人操作
44. [A Single Diffusion-Policy Controller for Multi-Task Block Pushing with Zero-Shot Sim-to-Real Transfer](/20260616-20260715/2607.10892v1-a-single-diffusion-policy-controller-for-multi-task-block-pushing-with-zero-shot-sim-to-real-transfer)  
   标签：评分：9.0/10、query:rmgp
   evidence：扩散策略用于多任务机器人块推动
45. [SegDiff: Segmented Trajectory Diffusion for Consistent and Adaptive Robot Manipulation](/20260616-20260715/2607.11027v1-segdiff-segmented-trajectory-diffusion-for-consistent-and-adaptive-robot-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：分段轨迹扩散用于机器人操作的闭环视觉运动策略
46. [Mixture of Frames Policy: Multi-Frame Action Denoising for Bimanual Mobile Manipulation](/20260616-20260715/2607.11884v1-mixture-of-frames-policy-multi-frame-action-denoising-for-bimanual-mobile-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：多帧动作去噪的扩散策略用于双臂操作

### 速读区论文标签
1. [Where Should Action Generation Begin? A Learnable Source Prior for Generative Robot Policies](/20260616-20260715/2606.17408v1-where-should-action-generation-begin-a-learnable-source-prior-for-generative-robot-policies)  
   标签：评分：8.0/10、query:rmgp
   evidence：可学习的源先验优化生成式机器人策略
2. [Temporal Self-Imitation Learning](/20260616-20260715/2606.19752v1-temporal-self-imitation-learning)  
   标签：评分：8.0/10、query:rmgp
   evidence：长程机器人操作的时序自模仿学习
3. [Semi-Supervised Vision-Language-Action Model](/20260616-20260715/2606.21493v1-semi-supervised-vision-language-action-model)  
   标签：评分：8.0/10、query:vla-wm
   evidence：利用自蒸馏进行半监督视觉-语言-动作模型适配
4. [Rotation-Aware Point-Cloud Embeddings for Vision-Based In-Hand Reorientation](/20260616-20260715/2606.21788v1-rotation-aware-point-cloud-embeddings-for-vision-based-in-hand-reorientation)  
   标签：评分：8.0/10、query:rmgp
   evidence：点云目标用于手内重定向，策略从三维几何学习。
5. [DREAM-Chunk: Reactive Action Chunking with Latent World Model](/20260616-20260715/2606.18589v1-dream-chunk-reactive-action-chunking-with-latent-world-model)  
   标签：评分：7.0/10、query:vla-wm
   evidence：世界模型增强VLA动作块选择实现反应式执行
6. [SC3-Eval: Evaluating Robot Foundation Models via Self-Consistent Video Generation](/20260616-20260715/2606.18610v2-sc3-eval-evaluating-robot-foundation-models-via-self-consistent-video-generation)  
   标签：评分：7.0/10、query:world-model
   evidence：自洽视频生成，利用动作条件世界模型评估机器人策略
7. [Inductive Generalization for Robotic Manipulation](/20260616-20260715/2606.20999v1-inductive-generalization-for-robotic-manipulation)  
   标签：评分：7.0/10、query:rmgp
   evidence：评估视觉运动策略的归纳泛化能力
8. [Constrained Flow Matching via Lagrangian Dual Flows](/20260616-20260715/2607.04513v1-constrained-flow-matching-via-lagrangian-dual-flows)  
   标签：评分：7.0/10、query:gen-imit
   evidence：用于机器人规划与控制的约束流匹配技术
9. [Scalable Multi-Task Data Generation via Reinforcement Learning for Language-Conditioned Bimanual Dexterous Manipulation](/20260616-20260715/2606.22471v1-scalable-multi-task-data-generation-via-reinforcement-learning-for-language-conditioned-bimanual-dexterous-manipulation)  
   标签：评分：6.0/10、query:gen-imit
   evidence：可扩展的仿真数据生成用于双手灵巧操作策略学习
10. [Learning Action Priors for Cross-embodiment Robot Manipulation](/20260616-20260715/2606.26095v1-learning-action-priors-for-cross-embodiment-robot-manipulation)  
   标签：评分：6.0/10、query:gen-imit
   evidence：为动作模块预训练运动先验，用于跨形态机器人操作策略学习。
11. [Perceptual Flow Matching for Few-Step Generative Modeling](/20260616-20260715/2607.03524v1-perceptual-flow-matching-for-few-step-generative-modeling)  
   标签：评分：6.0/10、query:fewstepgen
   evidence：用于流匹配模型少步生成的感知流匹配方法
12. [GenVid2Robot: From Video Generation to Robot Manipulation via Rigid-Geometric Consistency](/20260616-20260715/2607.09191v1-genvid2robot-from-video-generation-to-robot-manipulation-via-rigid-geometric-consistency)  
   标签：评分：6.0/10、query:rmgp
   evidence：通过刚性几何一致性将生成的视频运动转化为可执行机器人操作。


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
