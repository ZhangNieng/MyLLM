# MyLLM
## 链接
1. 模型测评: https://artificialanalysis.ai/models

## 名词解释
1. AGI：Artificial General Intelligence  人工通用智能



## 大模型的知识
1. token: 自然语言文本的基本单位  (1个英文字符 ≈ 0.3 个 token; 1个中文字符 ≈ 0.6 个 token)
2. 最大输出长度8K: 一次输出最多不超过8000个字
3. 参数的个数8B, billion十亿  Trillion万亿
4. 上下文长度context window: 单次推理过程中可处理的全部token序列的最大长度，包括：输入部分(用户提供的提示词、**历史对话内容**、附加文档等) + 输出部分(模型当前正在生成的响应内容)
5. 上下文截取: 超长文本处理(大模型的失忆性)   [我非常喜欢你, 你喜欢我吗？]     [喜欢你, 你喜欢我吗？你猜呢]
6. 思考think reasoning_content 内容不计入context window的长度
## 大模型的处理逻辑
1. 分词tokenization(一句话切成几个词语)
2. token映射到ID(每个token给定一个ID)
3. 向量嵌入(embedding) 升维 ID → 向量组[- - - - - - -] 低维不能解决的问题, 高维更容易解决

## Transformer
1. 模型介绍
2. 注意力机制Attention: 关键词
3. 温度(Temperature): 调节大模型生成内容的策略, 从而决定生成内容的风格
4. RLHF GRPO: 决策方法  用于智能体通过感知外界环境来决策学习方向
5. 混合专家MoE(Mixture of Expert): 通过动态选择不同子模块来处理输入数据的不同部分, MoE能够有效地增加模型容量而不显著增加推理成本
6. 蒸馏(Distillation): 生成数据来微调其他模型的技术
7. 数据标注(Data Annotation):  机器学习的前提和基础, 目标是为模型提供清晰/结构化的输入, 帮助其学习特定任务或改进生成质量
8. 预训练(Pre-Training):  正式训练之前, 先在一个大规模的、通用的数据集上对模型进行初步训练的过程, 帮助模型学习到广泛的知识和特征表示, 从而在后续的任务中更好地泛化和迁移这些知识





##  AI Code | LLM Code
1. GPT-5.1-Codex-Max
2. Google Antigravity  gemini
3. Claude Code
4. Trae
5. Cursor
6. Vibe Coding
7. Claude Opus 4.5





##  命令行
1. cd cd /d D:\MyChat\MyTraeChat  跨盘路径
2. 
