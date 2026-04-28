

---
# Infra
## 移动端
- [ ] [[HF-0422#30-`2604.19642`-`Micro Language Models Enable Instant Responses`]]

# Data Selection
- [ ] [[HF-0422#16-`2604.15706`-`Target-Oriented Pretraining Data Selection via Neuron-Activated Graph`]]
# 解释/改进 Transformer/attn机制

## 解释
## attn sink
- [ ] [[HF-0414#3-AttentionSinkSurvey-Attention Sink in Transformers A Survey on Utilization, Interpretation, and Mitigation]]
## 任务算术 task arithmetic
- [ ] [[HF-0422#11-`2604.17078`-`Understanding and Enforcing Weight Disentanglement in Task Arithmetic`]]
## 改进
### 改进 PEFT
- [ ] [[HF-0422#7-`2604.19254`-`ShadowPEFT Shadow Network for Parameter-Efficient Fine-Tuning`]]
- [ ] [[HF-0422#18-`2604.19321`-`RDP LoRA Geometry-Driven Identification for Parameter-Efficient Adaptation in Large Language Models`]]

---

# 统一模型/Omni
## Unified Multimodal Model
- [ ] happyhorse
- [ ] [[HF-0414#9-PseudoUnification-Pseudo-Unification Entropy Probing Reveals Divergent Information Patterns in Unified Multimodal Models]]
## Omni
- [ ] [[HF-0420#4-`2604.15804`-`Qwen3.5-Omni Technical Report`]]
### 设计 Omni Reasoning 范式
- [ ] [[HF-0424#10-`2604.21921`-`Context Unrolling in Omni Models`]]

---

# 生成方向
## Diff/FlowMatching

### REPA 等
- [ ] [[HF-0327#15-Representation Alignment for Just Image Transformers is not Easier than You Think]]
- [ ] 【固定特征空间未必最适合生成目标，可能限制收敛和质量】[[HF-0424#17-`2604.17492`-`Coevolving Representations in Joint Image-Feature Diffusion`]]
### 做小
- [ ] [[HF-0420#8-`2604.16503`-`Motif-Video 2B Technical Report`]]

### 做好：生成质量
- [ ] MixFlow: Mixed Source Distributions Improve Rectified Flows [[HF-0413#25-MixFlow-MixFlow Mixed Source Distributions Improve Rectified Flows]]
- [ ] [[HF-0420#1-`2604.16044`-`Elucidating the SNR-t Bias of Diffusion Probabilistic Models`]]
- [ ] [[HF-0327#3-Calibri-Enhancing Diffusion Transformers via Parameter-Efficient Calibration]]
#### 用self-play的手段
- [ ] [[HF-0424#13-`2604.21904`-`UniGenDet A Unified Generative-Discriminative Framework for Co-Evolutionary Image Generation and Generated Image Detection`]]
### 做长

### 做更多Cond
#### MultiReference
- [ ] 【dataset】[[HF-0327#7-MACRO-Advancing Multi-Reference Image Generation with Structured Long-Context Data]]

### Editing
##### Image Editing
- [ ] [[HF-0327#15-Representation Alignment for Just Image Transformers is not Easier than You Think]]
###### with reward model
- [ ] 【使用了NFT做后训练，基于VLM进行Heuristic RM设计】[[HF-0422#10-`2604.19587`-`SmartPhotoCrafter Unified Reasoning, Generation and Optimization for Automatic Photographic Image Editing`]]
- [ ] 【训练个HPscore打分器，并且以其作为数据引擎】[[HF-0422#20-`2604.19406`-`HP-Edit A Human-Preference Post-Training Framework for Image Editing`]]
- [ ] 【显式reasoning的RM, 相当于用LLM给人类偏好对扩写了理由】[[HF-0416#3-RationalRewards-RationalRewards Reasoning Rewards Scale Visual Generation Both Training and Test Time]]
- [ ] 【经典Reward fn配置：一大堆RM做的大杂烩】
- [ ] 【任意长宽比编辑，或许能从中获得捕捉object位置的灵感】[[HF-0424#11-`2604.10268`-`EditCrafter Tuning-free High-Resolution Image Editing via Pretrained Diffusion Model`]]

## AR Video/Image Gen

- [ ] Elastic Looped Transformers for Visual Generation[[HF-0413#7-ELT-ELT Elastic Looped Transformers for Visual Generation]]
- [ ] [[HF-0413#29-QuantizationBasin-Initialisation Determines the Basin Efficient Codebook Optimisation for Extreme LLM Quantization]]
### 做好：
#### 物理性
- [ ] 【运动频率合理性】[[HF-0326#9-`2603.14375`-`The Pulse of Motion Measuring Physical Frame Rate from Visual Dynamics`]]

### 做小/快
- [ ] [[HF-0326#16-`2603.18742`-`6Bit-Diffusion Inference-Time Mixed-Precision Quantization for Video Diffusion Models`]]
- [ ] 【一步生成；支持更复杂的文本】[[HF-0421#1-`2604.18168`-`Extending One-Step Image Generation from Class Labels to Text via Discriminative Text Representation`]]
#### 利用推测解码的思想
- [ ] [[HF-0422#15-`2604.17397`-`Speculative Decoding for Autoregressive Video Generation`]]

### 做长：
#### Forcing系
- [ ] [[HF-0330#3-`2603.25730`-`PackForcing Short Video Training Suffices for Long Video Sampling and Long Context Inference`]]
## WM Reward Model


## WM
- [ ] WildDet3D: Scaling Promptable 3D Detection in the Wild[[HF-0413#1-WildDet3D-WildDet3D Scaling Promptable 3D Detection in the Wild]]
- [ ] Matrix-Game 3.0: Real-Time and Streaming Interactive World Model with Long-Horizon Memory[[HF-0413#4-MatrixGame3.0-Matrix-Game 3.0 Real-Time and Streaming Interactive World Model with Long-Horizon Memory]]
- [ ] [[HF-0331#10-Video Generation Models as World Models-Efficient Paradigms, Architectures and Algorithms]]

### WM memory
- [ ] [[HF-0330#1-`2603.25716`-`Out of Sight but Not Out of Mind Hybrid Memory for Dynamic Video World Models`]]
- [ ] 【现实地理坐标做个rag】[[HF-0422#14-`2604.19741`-`CityRAG Stepping Into a City via Spatially-Grounded Video Generation`]]

### Multi-Agent
- [ ] [[HF-0421#5-`2604.18564`-`MultiWorld Scalable Multi-Agent Multi-View Video World Models`]]

## Action Cond
### Omni
- [ ] [[HF-0414#4-OmniShow-OmniShow Unifying Multimodal Conditions for Human-Object Interaction Video Generation]](像worldcanvas的升级版)

## Action Modeling
### CamTraj Gen
- [ ] [[HF-0413#28-CT1-CT-1 Vision-Language-Camera Models Transfer Spatial Reasoning Knowledge to Camera-Controllable Video Generation]]

### Latent Action Model

### 显式的 Action Modeling
#### dynamics modeling（显式地建模轨迹）
- [ ] [[HF-0413#11-EnvisioningFuture-One Step at a Time-Envisioning the Future, One Step at a Time]]



---
# 理解方向
## LLM/VLM

### 与传统CV
#### Pointing
- [ ] [[HF-0331#26-MolmoPoint-Better Pointing for VLMs with Grounding Tokens]]
#### OCR
- [ ] [[HF-0421#36-`2604.16943`-`MNAFT modality neuron-aware fine-tuning of multimodal large language models for image translation`]]

### OOD能力增强
- [ ] [[HF-0413#14-VisionFoundry-VisionFoundry Teaching VLMs Visual Perception with Synthetic Images]]

### Reasoning
- [ ] [[HF-0413#24-RobustReasoningBenchmark-Robust Reasoning Benchmark]]
- [ ] 【解释Reasoning】[[HF-0326#21-`2603.23539`-`PLDR-LLMs Reason At Self-Organized Criticality`]]
- [ ] 【解释CoT为什么会损害多模态理解能力】[[HF-0422#35-`2604.16060`-`Chain-of-Thought Degrades Visual Spatial Reasoning Capabilities of Multimodal LLMs`]]
### Speculative Decoding
- [ ] [[HF-0413#27-Cactus-Cactus Accelerating Auto-Regressive Decoding with Constrained Acceptance Speculative Sampling]]
- [ ] [[HF-0331#1-TAPS-Task Aware Proposal Distributions for Speculative Sampling]]

### MoE
- [ ] [[HF-0331#7-On Token's Dilemma-Dynamic MoE with Drift-Aware Token Assignment for Continual Learning of Large Vision Language Models]]

### 并行推理
- [ ] [[HF-0420#6-`2604.16029`-`Cut Your Losses! Learning to Prune Paths Early for Efficient Parallel Reasoning`]]

## RL/OPD/Distillation

### In WM

### In LLM/VLM
#### Reward Model / Reward fn
#### OPD(on policy distillation)
- [ ] [[HF-0414#12-SCOPE-SCOPE Signal-Calibrated On-Policy Distillation Enhancement with Dual-Path Adaptive Weighting]]（有点像大杂烩）
- [ ] [[HF-0327#14-Revisiting On-Policy Distillation-Empirical Failure Modes and Simple Fixes]]

#### Self-Distillation/Self-Play
- [ ] [[HF-0326#2-`2603.24472`-`Why Does Self-Distillation (Sometimes) Degrade the Reasoning Capability of LLMs?`]]
- [ ] [[HF-0421#21-`2604.18131`-`Training LLM Agents for Spontaneous, Reward-Free Self-Evolution via World Knowledge Exploration`]]
- [ ] [[HF-0421#22-`2604.17696`-`Stratagem Learning Transferable Reasoning via Trajectory-Modulated Game Self-Play`]]
- [ ] 【防止未授权蒸馏】[[HF-0421#48-`2602.15143`-`Protecting Language Models Against Unauthorized Distillation through Trace Rewriting`]]
##### 更稠密的信号
- [ ] [[HF-0416#20-SelfDistillationZero-Self-Distillation Zero Self-Revision Turns Binary Rewards into Dense Supervision]]
##### 基于熵
- [ ] [[HF-0414#1-ThePastIsNotPast-The Past Is Not Past Memory-Enhanced Dynamic Reward Shaping]]
##### 过程RM/R-Fn
- 合理性
- [ ] [[HF-0413#18-ProcessRewardAgents-Process Reward Agents for Steering Knowledge-Intensive Reasoning]] 
- 多样性
- [ ] [[HF-0327#17-Reaching Beyond the Mode-RL for Distributional Reasoning in Language Models]]
- [ ] [[HF-0327#25-Can MLLMs Read Students' Minds?-Unpacking Multimodal Error Analysis in Handwritten Math]]
##### 正负样本
- [ ] [[HF-0330#4-`2603.25158`-`Trace2Skill Distill Trajectory-Local Lessons into Transferable Agent Skills`]]

#### Replay-buffer
- [ ] [[HF-0414#15-ExperienceReplayLLMRL-Efficient RL Training for LLMs with Experience Replay]]


## Diffusion Language Model
- [ ] ECHO: Efficient Chest X-ray Report Generation with One-step Block Diffusion [[HF-0413#8-ECHO-ECHO Efficient Chest X-ray Report Generation with One-step Block Diffusion]]
- [ ] [[HF-0414#13-IntrospectiveDLM-Introspective Diffusion Language Models]]
- [ ] [[HF-0327#21-S2D2-Fast Decoding for Diffusion LLMs via Training-Free Self-Speculation]]

## Agent

## CPU/Schedular
- [ ] 【分任务的bench】[[HF-0421#46-`2604.15760`-`KWBench Measuring Unprompted Problem Recognition in Knowledge Work`]]

### Prompt Engineering
- [ ] [[HF-0413#15-p1-p1 Better Prompt Optimization with Fewer Prompts]]

### LongVideoUnderstanding

- [ ] Structured Causal Video Reasoning via Multi-Objective Alignment [[HF-0413#12-StructuredCausalVideoReasoning-Structured Causal Video Reasoning via Multi-Objective Alignment]]
- [ ] [[HF-0331#31-AdaptToken-Entropy-based Adaptive Token Selection for MLLM Long Video Understanding]]
- [ ] [[HF-0326#4-`2603.22918`-`EVA Efficient Reinforcement Learning for End-to-End Video Agent`]]
- [ ] [[HF-0421#6-`2604.16893`-`EasyVideoR1 Easier RL for Video Understanding`]]
- [ ] [[HF-0421#19-`2604.11102`-`OmniScript Towards Audio-Visual Script Generation for Long-Form Cinematic Video`]]
#### 流式
- [ ] [[HF-0331#22-STRIDE-When to Speak Meets Sequence Denoising for Streaming Video Understanding]]

### Mem/RAG
- [ ] AgentSwing: Adaptive Parallel Context Management Routing for Long-Horizon Web Agents[[HF-0413#9-AgentSwing-AgentSwing Adaptive Parallel Context Management Routing for Long-Horizon Web Agents]]
- [ ] 【试图克服外挂式Mem，核实下是不是在扯淡】[[HF-0327#6-MSA-Memory Sparse Attention for Efficient End-to-End Memory Model Scaling to 100M Tokens]]
- [ ] [[HF-0327#19-MemMA-Coordinating the Memory Cycle through Multi-Agent Reasoning and In-Situ Self-Evolution]]
- [ ] [[HF-0331#17-MuSEAgent-A Multimodal Reasoning Agent with Stateful Experiences]]
- [ ] [[HF-0420#5-`2604.04936`-`Web Retrieval-Aware Chunking (W-RAC) for Efficient and Cost-Effective Retrieval-Augmented Generation Systems`]]
#### 上下文压缩
- [ ] [[HF-0331#28-Density-aware Soft Context Compression with Semi-Dynamic Compression Ratio]]
- [ ] [[HF-0421#17-`2604.17091`-`GenericAgent A Token-Efficient Self-Evolving LLM Agent via Contextual Information Density Maximization (V1.0)`]]
- [ ] 
### Agent
#### Sub-Agent
- [ ] [[HF-0414#17-AgenticAggregation-Agentic Aggregation for Parallel Scaling of Long-Horizon Agentic Tasks]]
- [ ] [[HF-0331#4-Emergent Social Intelligence Risks in Generative Multi-Agent Systems]]
- [ ] 【大系统，适合作为Codebase】[[HF-0421#3-`2604.18292`-`Agent-World Scaling Real-World Environment Synthesis for Evolving General Agent Intelligence`]]

### 解释层
- [ ] 【解释为什么LLM agent很脆弱不鲁棒】[[HF-0326#8-`2603.23994`-`Understanding the Challenges in Iterative Generative Optimization with LLMs`]]
- [ ] 【解释为啥agent没好奇心】[[HF-0421#20-`2604.17609`-`Agents Explore but Agents Ignore LLMs Lack Environmental Curiosity`]]
- [ ] 【系统性研究LLM/MLLM hacking问题】[[HF-0421#41-`2604.17596`-`Terminal Wrench A Dataset of 331 Reward-Hackable Environments and 3,632 Exploit Trajectories`]]
### 应用层
- [ ] 【Raster Img to SVG】[[HF-0327#10-VFIG-Vectorizing Complex Figures in SVG with Vision-Language Models]]
- [ ] 【harness coding】[[HF-0330#7-`2603.25723`-`Natural-Language Agent Harnesses`]]
- [ ] 【technich report】[[HF-0330#10-`2603.24477`-`Composer 2 Technical Report`]]
- [ ] [[HF-0330#12-`2603.26664`-`Learning to Commit Generating Organic Pull Requests via Online Repository Memory`]]
- [ ] 【加速Deep Research】[[HF-0331#16-Marco DeepResearch-Unlocking Efficient Deep Research Agents via Verification-Centric Design]]
- [ ] 【结构化Deep Research】[[HF-0420#7-`2604.14518`-`Mind DeepResearch Technical Report`]]
- [ ] 【technich report】[[HF-0331#24-KAT-Coder-V2 Technical Report]]
- [ ] 【如何给每个工具一个SOP】[[HF-0421#31-`2604.17886`-`Latent Preference Modeling for Cross-Session Personalized Tool Calling`]]
- [ ] 【Agent as a judge】[[HF-0422#9-`2604.18240`-`AJ-Bench Benchmarking Agent-as-a-Judge for Environment-Aware Evaluation`]]
- [ ] 【通义出品，写多页web agent的】[[HF-0424#14-`2604.20398`-`WebGen-R1 Incentivizing Large Language Models to Generate Functional and Aesthetic Websites with Reinforcement Learning`]]
#### 进化(有点像bad case analysis)
- [ ] [[HF-0422#29-`2604.19341`-`Evaluation-driven Scaling for Scientific Discovery`]]
- [ ] [[HF-0422#24-`2604.19440`-`What Makes an LLM a Good Optimizer? A Trajectory Analysis of LLM-Guided Evolutionary Search`]]
#### Bench
- [ ] [[HF-0326#1-`2603.24440`-`CUA-Suite Massive Human-annotated Video Demonstrations for Computer-Use Agents`]]

---

# 生成与理解方向的交叉

## Modal Fusion
### VLM fused in GEN model
- [ ] 【类似PAN】[[HF-0330#9-`2603.22782`-`Know3D Prompting 3D Generation with Knowledge from Vision-Language Models`]]
### Gen model fused in VLM
#### Gen Model as Tools
- [ ] [[HF-0331#3-Gen-Searcher-Reinforcing Agentic Search for Image Generation]]  
- [ ] [[HF-0326#18-`2603.24458`-`OmniWeaving Towards Unified Video Generation with Free-form Composition and Reasoning`]]

---
# 传统CV

## 分割
- [ ] [[HF-0327#28-PMT-Plain Mask Transformer for Image and Video Segmentation with Frozen Vision Encoders]]
- [ ] [[HF-0330#11-`2603.23906`-`GenMask Adapting DiT for Segmentation via Direct Mask`]]
- [ ] 【免训适配DINOv3到seg】[[HF-0331#33-INSID3-Training-Free In-Context Segmentation with DINOv3]]

# 3D
## 重建
### reshooting
- [ ] [[HF-0424#12-`2604.21915`-`Vista4D Video Reshooting with 4D Point Clouds`]]
- [ ] 