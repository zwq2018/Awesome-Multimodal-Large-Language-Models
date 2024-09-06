# Awesome-Multimodal-Large-Language-Models
his is a repository for organizing articles related to Multimodal Large Language Models, Large Language Models, and Diffusion Models; Most papers are linked to **my reading notes**. Feel free to visit my [personal homepage](https://yfzhang114.github.io/) and contact me for collaboration and discussion.


### About Me :high_brightness: 
I'm a third-year Ph.D. student at the State Key Laboratory of Pattern Recognition, the University of Chinese Academy of Sciences, advised by Prof. [Tieniu Tan](http://people.ucas.ac.cn/~tantieniu). I have also spent time at Microsoft, advised by Prof. [Jingdong Wang](https://jingdongwang2017.github.io/), alibaba DAMO Academy, work with Prof. [Rong Jin](https://scholar.google.com/citations?user=CS5uNscAAAAJ&hl=zh-CN).


###  🔥 Updated 2024-09-06
- Recent Modality Bridging papers of Multimodal Large Language Models have been updated.
- Our benchmark  [MME-RealWorld](https://mme-realworld.github.io/) has been released, the most difficult and largest pure manual annotation image perception benchmark so far.  [[Code]](https://github.com/yfzhang114/MME-RealWorld) [[Reading Notes]](https://zhuanlan.zhihu.com/p/717129017)
- Our model  [SliME](https://arxiv.org/abs/2406.08487) has been released, a high-resolution MLLM that can also be extend to video analysis.  [[Code]](https://github.com/yfzhang114/SliME) [[Reading Notes]](https://zhuanlan.zhihu.com/p/703258020)
- Our paper  [Debiasing Multimodal Large Language Models](https://arxiv.org/abs/2403.05262) has been released.  [[Code]](https://github.com/yfzhang114/LLaVA-Align) [[Reading Notes]](https://zhuanlan.zhihu.com/p/686461442)

# Table of Contents (ongoing)
* [Multimodal Large Language Models](#multimodal-large-language-models)
* [BenchMark and Dataset](#benchmark-and-dataset)
* [Diffusion Models](#diffusion-models)
* [MLLM Alignment](#mllm-alignment)
* [Alignment With Human Preference](#alignment-with-human-preference)

# Survey and Outlook
1. [万字长文总结多模态大模型最新进展（Modality Bridging篇）](https://zhuanlan.zhihu.com/p/688215018)
2. [万字长文总结多模态大模型最新进展（Video篇）](https://zhuanlan.zhihu.com/p/704246896)
3. [Aligning Large Language Models with Human](https://zhuanlan.zhihu.com/p/693160839)

   
# Multimodal Large Language Models
1. [MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?](https://zhuanlan.zhihu.com/p/717129017)(最难多模态Benchmark. QwenVL-2第一但未及格！)
2. [VITA: Towards Open-Source Interactive Omni Multimodal LLM](https://zhuanlan.zhihu.com/p/714031459)(VITA : 首个开源支持自然人机交互的全能多模态大语言模型)
3. [Beyond LLaVA-HD: Diving into High-Resolution Large Multimodal Models](https://github.com/yfzhang114/SliME)(高效处理高分辨率图像的多模态大模型)
4. [Matryoshka Multimodal Models](https://zhuanlan.zhihu.com/p/700906592)(如何在正确回答视觉问题的同时使用最少的视觉标记？)
5. [Chameleon: Mixed-Modal Early-Fusion Foundation Models](https://zhuanlan.zhihu.com/p/698911049)(meta: 所有模态都回到token regreesion以达到灵活的理解/生成)
6. [Flamingo: a Visual Language Model for Few-Shot Learning](https://zhuanlan.zhihu.com/p/688215018)(LLM每一层创建额外的block处理视觉信息)
7. [BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(q-former融合视觉-语言信息)
8. [InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(qformer+instruction tuning)
9. [Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(MLP对齐特征，gpt4v生成instruction tuning数据)
10. [Improved Baselines with Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(对于llava数据集以及模型大小的初步scaling)
11. [LLaVA-NeXT: Improved reasoning, OCR, and world knowledge](https://zhuanlan.zhihu.com/p/688215018)(分辨率*4，数据集更大)
12. [Cheap and Quick: Efficient Vision-Language Instruction Tuning for Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(一种端到端的优化方案，通过轻量级适配器连接图像编码器和LLM)
13. [MIMIC-IT: Multi-Modal In-Context Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)( MIMIC-IT包含多个图片或视频的输入数据，并支持多模态上下文信息)
14. [LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image Understanding](https://zhuanlan.zhihu.com/p/688215018)(使用公开可用的OCR工具在LAION数据集的422K个文本丰富的图像上收集结果)
15. [SVIT: Scaling up Visual Instruction Tuning](https://zhuanlan.zhihu.com/p/688215018)(一个包含420万个视觉指导调整数据点的数据集)
16. [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://zhuanlan.zhihu.com/p/688215018)(cross attention对齐特征，更大的第一阶段训练数据)
17. [NExT-GPT: Any-to-Any Multimodal LLM](https://zhuanlan.zhihu.com/p/688215018)(端到端通用的任意对任意MM-LLM（Multimodal-Large Language Model）系统)
18. [InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition](https://zhuanlan.zhihu.com/p/688215018)(视觉信息的压缩采样)
19. [CogVLM: Visual Expert for Pretrained Language Models](https://zhuanlan.zhihu.com/p/688215018)(在LLM的各层添加visual expert，它具有独立的QKV和FFN相关的参数)
20. [OtterHD: A High-Resolution Multi-modality Model](https://zhuanlan.zhihu.com/p/688215018)(专门设计用于以细粒度精度解释高分辨率视觉输入)
21. [Monkey : Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://zhuanlan.zhihu.com/p/688215018)(Monkey模型提出了一种有效地提高输入分辨率的方法，最高可达 896 x 1344 像素)
22. [LLaMA-VID: An Image is Worth 2 Tokens in Large Language Models](https://zhuanlan.zhihu.com/p/688215018)(LLaMA-VID赋予现有框架支持长达一小时的视频，并通过额外的上下文标记推动了它们的上限)
23. [MoE-LLaVA: Mixture of Experts for Large Vision-Language Models](https://zhuanlan.zhihu.com/p/688215018)(解决了多模态稀疏学习中的性能下降问题)
24. [LLaVA-UHD: an LMM Perceiving Any Aspect Ratio and High-Resolution Images](https://zhuanlan.zhihu.com/p/688215018)(高效处理任何纵横比和高分辨率的图像)
25. [Yi-VL](https://zhuanlan.zhihu.com/p/688215018)(Yi-VL采用了LLaVA架构，经过全面的三阶段训练过程，以将视觉信息与Yi LLM的语义空间良好对齐：)
26. [Mini-Gemini](https://zhuanlan.zhihu.com/p/693063778)(双视觉编码器，使用低分辨率的视觉编码器特征作为query，将高分辨率特征作为key 和value进行token mining)
27. [Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding](https://zhuanlan.zhihu.com/p/704246896)(采用了一组动态视觉tokens来统一表示图像和视频。使模型能够高效利用有限数量的视觉tokens，同时捕捉图像所需的空间细节和视频所需的全面时间关系。)
28. [VILA: On Pre-training for Visual Language Models](https://zhuanlan.zhihu.com/p/704246896)(交错的预训练数据是有益的，而单纯的图像-文本对并非最佳选择。)
29. [ST-LLM: Large Language Models Are Effective Temporal Learners](https://zhuanlan.zhihu.com/p/704246896)(ST-LLM提出了一种动态掩码策略，并设计了定制的训练目标。此外，针对特别长的视频，设计了一个全局-局部输入模块，以平衡效率和效果。)
30. [Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://zhuanlan.zhihu.com/p/704246896)(用视频特有的encoder提升视频理解能力而非image encoder)

# BenchMark and Dataset
1. [From Pixels to Prose: A Large Dataset of Dense Image Captions](https://arxiv.org/pdf/2406.10328)(1600万生成的image-text pair，利用尖端的视觉语言模型(Gemini 1.0 Pro Vision)进行详细和准确的描述。)
2. [ShareGPT4Video: Improving Video Understanding and Generation with Better Captions](https://zhuanlan.zhihu.com/p/704246896)(40k from gpt4-v, 4814k生成于自己训练的模型)
3. [OBELICS: An Open Web-Scale Filtered Dataset of Interleaved Image-Text Documents](https://arxiv.org/pdf/2306.16527)(141 million web pages extracted from Common Crawl, 353 million associated images, and 115 billion text tokens)
# Diffusion Models

# MLLM Alignment
1. [Aligning Large Multimodal Models with Factually Augmented RLHF](https://llava-rlhf.github.io/)

# Alignment With Human Preference

1. [ChatGLM-Math：Improving Math Problem-Solving in Large Language Models with a Self-Critique Pipeline](https://zhuanlan.zhihu.com/p/698983475)(ChatGLM-Math: Self-Critique迭代对齐显著提升数学能力)
2. [Beyond One-Preference-Fits-All Alignment: Multi-Objective Direct Preference Optimization](https://zhuanlan.zhihu.com/p/698782623)(大语言模型的多目标对齐)
3. [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://zhuanlan.zhihu.com/p/693163438)(直接偏好优化克服RLHF不稳定的问题)
4. [KTO: Model Alignment as Prospect Theoretic Optimization](https://zhuanlan.zhihu.com/p/693163438)(不需要成对数据的偏好优化)
5. [Direct Preference Optimization with an Offset](https://zhuanlan.zhihu.com/p/693163438)(带偏移的DPO, 要求首选响应和不受欢迎响应之间的可能性差异大于一个偏移值)
6. [Contrastive preference learning: Learning from human feedback without reinforcement learning](https://zhuanlan.zhihu.com/p/693163438)(对比偏好学习（CPL）算法，该算法用于从偏好中学习最优策略而无需学习奖励函数，从而避免了对RL的需求)
7. [Statistical Rejection Sampling Improves Preference Optimization](https://zhuanlan.zhihu.com/p/693163438)(使用拒绝抽样从目标最优策略中获取偏好数据，从而更准确地估计最优策略)
8. [Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study](https://zhuanlan.zhihu.com/p/693163438)(在所有实验中，PPO始终优于DPO。特别是在最具挑战性的代码竞赛任务中，PPO实现了最先进的结果)
9. [Fine-tuning Aligned Language Models Compromises Safety](https://zhuanlan.zhihu.com/p/696707347)(微调对齐的语言模型会损害安全性)
10. [ChatGLM-Math: Improving Math Problem-Solving in Large Language Models with a Self-Critique Pipeline](https://mp.weixin.qq.com/s/lg7ueR9b-om0ecUEoT4x8w)(reward model, Rejective Fine-tuning, then DPO迭代提升模型数学性能)
11. [SimPO: Simple Preference Optimization with a Reference-Free Reward](https://zhuanlan.zhihu.com/p/700438956)(length reg+去掉ref model)
12. [towards analyzing and understanding the limitations of dpo: a theoretical perspective](https://zhuanlan.zhihu.com/p/701213691)(DPO的实际优化过程对SFT后的LLMs对齐能力的初始条件为什么敏感)
