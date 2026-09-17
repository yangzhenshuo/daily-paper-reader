<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-17
- 运行时间：2026-09-17 23:13:26 UTC
- 运行状态：成功
- 本次总论文数：30
- 精读区：13
- 速读区：17

### 今日简报（AI）
2026-09-17 日报：共筛读30篇机器人策略论文，精读13篇、速读17篇，焦点集中在扩散策略与视觉-语言-动作模型。

最值得看的是满分精读《Attention-DP3》用几何对齐注意力实现空间物体感知的3D扩散策略，以及9分《IMLE-VLA》把VLA动作生成压缩到单步；速读中ObstaDiff、LTLDiff、ActSafeGuard均获8分，分别攻障碍感知泛化、时序逻辑引导多机操作与流匹配策略的安全约束。

普通读者可先读《Attention-DP3》了解3D扩散策略怎么"看懂"物体，再顺《IMLE-VLA》体会单步生成的提速思路。
- 详情：[/202609/17/README](/202609/17/README)

### 精读区论文标签
1. [Attention-DP3: Spatially Object-aware 3D Diffusion Policy via Geometry-aligned Attentional Conditioning](/202609/17/2609.13318v1-attention-dp3-spatially-object-aware-3d-diffusion-policy-via-geometry-aligned-attentional-conditioning)  
   标签：评分：10.0/10、query:rmgp
   evidence：基于点云的物体感知三维扩散策略，扩展DP3主干
2. [IMLE-VLA: Fast Single-Step Action Generation for Vision-Language-Action Policies](/202609/17/2609.10915v1-imle-vla-fast-single-step-action-generation-for-vision-language-action-policies)  
   标签：评分：9.0/10、query:vla-wm
   evidence：面向视觉-语言-动作策略的单步动作生成
3. [Memory as Plans: World-Action Modeling with Memory-Grounded Planning](/202609/17/2609.11561v1-memory-as-plans-world-action-modeling-with-memory-grounded-planning)  
   标签：评分：9.0/10、query:vla-wm
   evidence：面向长时程非马尔可夫操作的内存锚定世界-动作建模
4. [RodForesight: A World Model Enhanced Diffusion Policy for Slender Rod Insertion](/202609/17/2609.12103v2-rodforesight-a-world-model-enhanced-diffusion-policy-for-slender-rod-insertion)  
   标签：评分：9.0/10、query:world-model
   evidence：世界模型增强的扩散策略用于插入操作
5. [DIA: Denoising Intermediate Advantage for Diffusion Policy Optimization](/202609/17/2609.12245v1-dia-denoising-intermediate-advantage-for-diffusion-policy-optimization)  
   标签：评分：9.0/10、query:rmgp
   evidence：扩散机器人策略的强化学习信用分配优化
6. [Dynin-Robotics: Omnimodal Unified Diffusion Vision-Language-Action Model](/202609/17/2609.13053v1-dynin-robotics-omnimodal-unified-diffusion-vision-language-action-model)  
   标签：评分：9.0/10、query:vla-wm
   evidence：统一扩散VLA模型预测动作与未来状态
7. [GeomVLA: Unifying Scene, Motion, and Action in 3D](/202609/17/2609.13812v2-geomvla-unifying-scene-motion-and-action-in-3d)  
   标签：评分：9.0/10、query:vla-wm
   evidence：统一三维场景、运动与流式动作的VLA模型
8. [LieSpline-DP: Lie-Group B-Spline Diffusion Policy for Smooth Robot Manipulation](/202609/17/2609.15162v2-liespline-dp-lie-group-b-spline-diffusion-policy-for-smooth-robot-manipulation)  
   标签：评分：9.0/10、query:rmgp
   evidence：面向平滑机器人操作的李群B样条扩散策略
9. [Convergence rates for generative drifting flows: fixed-scale obstructions and multihead acceleration](/202609/17/2609.15193v1-convergence-rates-for-generative-drifting-flows-fixed-scale-obstructions-and-multihead-acceleration)  
   标签：评分：9.0/10、query:fewstepgen
   evidence：分析训练时传输、推理时单步生成的漂移模型收敛性
10. [DIDO: Distilling Interaction-Centric Dynamics into One-Step Denoising for World Action Models](/202609/17/2609.15570v2-dido-distilling-interaction-centric-dynamics-into-one-step-denoising-for-world-action-models)  
   标签：评分：9.0/10、query:vla-wm
   evidence：将交互动态蒸馏为一步去噪的世界动作模型
11. [World-Action Models for Robot Learning and Control: A Survey](/202609/17/2609.16074v1-world-action-models-for-robot-learning-and-control-a-survey)  
   标签：评分：9.0/10、query:vla-wm
   evidence：综述耦合未来预测与动作生成的世界-动作模型
12. [XPACE: Joint World and Action Modeling from Heterogeneous Experience](/202609/17/2609.17372v1-xpace-joint-world-and-action-modeling-from-heterogeneous-experience)  
   标签：评分：9.0/10、query:vla-wm
   evidence：统一世界-动作模型联合预测动作与未来视频
13. [Modality-Autoregressive World-Action Models](/202609/17/2609.17524v1-modality-autoregressive-world-action-models)  
   标签：评分：9.0/10、query:vla-wm
   evidence：联合预测未来观测与动作的世界-动作模型

### 速读区论文标签
1. [ObstaDiff: Generalizable Diffusion Policy Learning via Obstacle-aware Representations](/202609/17/2609.10918v1-obstadiff-generalizable-diffusion-policy-learning-via-obstacle-aware-representations)  
   标签：评分：8.0/10、query:rmgp
   evidence：面向机器人操作的障碍感知分解式扩散策略框架
2. [LTLDiff: Finite Linear Temporal Logic-Guided Data Generation and Diffusion Policies for Multi-agent Robotic Manipulation](/202609/17/2609.11043v1-ltldiff-finite-linear-temporal-logic-guided-data-generation-and-diffusion-policies-for-multi-agent-robotic-manipulation)  
   标签：评分：8.0/10、query:rmgp
   evidence：结合时序逻辑引导数据生成的扩散策略用于多智能体操作
3. [ActSafeGuard: Differentiable and Training-Aligned Constraint Enforcement for Flow-Matching Policies](/202609/17/2609.11697v1-actsafeguard-differentiable-and-training-aligned-constraint-enforcement-for-flow-matching-policies)  
   标签：评分：8.0/10、query:vla-wm
   evidence：面向流匹配策略的训练对齐约束强制执行
4. [UniMPA: A Unified Memory-Prediction-Action Model via Action-Grounded Transition Modeling](/202609/17/2609.11875v1-unimpa-a-unified-memory-prediction-action-model-via-action-grounded-transition-modeling)  
   标签：评分：8.0/10、query:vla-wm
   evidence：统一记忆-预测-动作模型，预测未来状态与动作
5. [Online Material Estimation for Conditioned Diffusion Policy in Shaping Deformable Linear Objects](/202609/17/2609.12634v1-online-material-estimation-for-conditioned-diffusion-policy-in-shaping-deformable-linear-objects)  
   标签：评分：8.0/10、query:rmgp
   evidence：基于在线材料估计的条件扩散策略模仿学习
6. [Improving Imitation Learning Efficiency for Manipulation through Geometric Prior Pretraining](/202609/17/2609.12721v1-improving-imitation-learning-efficiency-for-manipulation-through-geometric-prior-pretraining)  
   标签：评分：8.0/10、query:rmgp
   evidence：面向操作任务的高效模仿学习
7. [Time-Frequency Geometric Cross-Attention for Chunked Vision-Language-Action Models](/202609/17/2609.09925v1-time-frequency-geometric-cross-attention-for-chunked-vision-language-action-models)  
   标签：评分：7.0/10、query:vla-wm
   evidence：分块VLA模型预测动作块
8. [Show-Harness: Just a VLM Agent Can Play Robots](/202609/17/2609.10522v1-show-harness-just-a-vlm-agent-can-play-robots)  
   标签：评分：7.0/10、query:vla-wm
   evidence：视觉语言模型智能体通过语义动作接口直接控制机器人
9. [Flow Duality and Source Geometry for Categorical Generation](/202609/17/2609.10863v1-flow-duality-and-source-geometry-for-categorical-generation)  
   标签：评分：7.0/10、query:gen-models
   evidence：连续与离散流匹配之间的对偶性
10. [Beyond Noise Steering: Dual-Latent Space Reinforcement Learning for Generative Robot Policy](/202609/17/2609.11270v1-beyond-noise-steering-dual-latent-space-reinforcement-learning-for-generative-robot-policy)  
   标签：评分：7.0/10、query:rmgp
   evidence：对预训练生成式机器人策略进行强化学习微调
11. [2AM: Grounding Agent-Side Memory as Guidance for Steerable Action Models in Long-Horizon Manipulation](/202609/17/2609.11308v1-2am-grounding-agent-side-memory-as-guidance-for-steerable-action-models-in-long-horizon-manipulation)  
   标签：评分：7.0/10、query:vla-wm
   evidence：长时程机器人操作，VLA与智能体侧记忆动作模型
12. [FARM: Reading Failure Signals from the Internal Predictive States of a Frozen Robotic World Model](/202609/17/2609.11445v1-farm-reading-failure-signals-from-the-internal-predictive-states-of-a-frozen-robotic-world-model)  
   标签：评分：7.0/10、query:world-model
   evidence：从冻结机器人世界模型的预测状态中解码失败信号
13. [Arti-JEPA: Adapting Video World Model to Real-Time MRI of the Vocal Tract for Speech-Production Analysis](/202609/17/2609.09757v1-arti-jepa-adapting-video-world-model-to-real-time-mri-of-the-vocal-tract-for-speech-production-analysis)  
   标签：评分：6.0/10、query:world-model
   evidence：联合嵌入预测架构世界模型，自监督目标
14. [RoboDrop: Curating VLA Post-Training Data via Local Gradient Compatibility](/202609/17/2609.10021v1-robodrop-curating-vla-post-training-data-via-local-gradient-compatibility)  
   标签：评分：6.0/10、query:vla-wm
   evidence：面向视觉-语言-动作模型后训练的数据筛选
15. [Model-Aware Schedules Improve Generation via Fiberwise Optimal Transport](/202609/17/2609.11842v1-model-aware-schedules-improve-generation-via-fiberwise-optimal-transport)  
   标签：评分：6.0/10、query:gen-models
   evidence：扩散与流匹配调度的最优传输
16. [Amortized Low-Rank Adaptation for Model-Based Reinforcement Learning](/202609/17/2609.12278v1-amortized-low-rank-adaptation-for-model-based-reinforcement-learning)  
   标签：评分：6.0/10、query:world-model
   evidence：用低秩超网络适配器实现世界模型的测试时自适应
17. [DWMP: Leveraging Dual World Models for Humanoid Obstacle Traversal](/202609/17/2609.12347v1-dwmp-leveraging-dual-world-models-for-humanoid-obstacle-traversal)  
   标签：评分：6.0/10、query:world-model
   evidence：面向机器人策略的双世界模型与潜动态预测


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
