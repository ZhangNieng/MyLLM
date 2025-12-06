# MyLLM

模型对比: https://artificialanalysis.ai/models


## 大模型的知识
1. token: 自然语言文本的基本单位  (1个英文字符 ≈ 0.3 个 token; 1个中文字符 ≈ 0.6 个 token)
2. 最大输出长度8K: 一次输出最多不超过8000个字
3. 
4. 上下文长度context window: 单次推理过程中可处理的全部token序列的最大长度，包括：输入部分(用户提供的提示词、**历史对话内容**、附加文档等) + 输出部分(模型当前正在生成的响应内容)
5. 上下文截取: 超长文本处理(大模型的失忆性)   [我非常喜欢你, 你喜欢我吗？]     [喜欢你, 你喜欢我吗？你猜呢]
6. 思考think reasoning_content 内容不计入context window的长度
## 大模型的处理逻辑
1. 分词tokenization(一句话切成几个词语)
2. token映射到ID(每个token给定一个ID)
3. 向量嵌入(embedding) 升维 ID → 向量组[- - - - - - -] 低维不能解决的问题, 高维更容易解决

## Transformer
1. 模型介绍
2. 注意力机制: 
