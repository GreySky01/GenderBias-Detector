# GenderBias-Detector

## Introduction
This project is built on the HuggingFace pre-trained model `unitary/toxic-bert`,
and provides a basic tool for detecting sexist or offensive speech.  
Current features:
- Detect whether a given text is toxic (offensive/sexist) or non-toxic
- Provide simple coping strategies or supportive responses

## Usage
1. Install dependencies:
   pip install transformers torch
2. Run the function detect_and_respond(text)
3. Input any sentence to get a classification result and a suggested response

## Applications
- Online conversation monitoring
- Prototype for self-help / psychological support tools
- Data analysis in gender equality research

## Future Work
- Collect and annotate more Chinese and English data for fine-tuning
- Expand from binary classification to “explicit / implicit / non-sexist”
- Add richer coping strategies and psychological support modules


# 性别歧视言论检测器

## 简介
本项目基于 HuggingFace 提供的预训练模型 `unitary/toxic-bert`，
实现了一个基础的性别歧视/攻击性言论检测工具。  
目前功能：
- 检测输入文本是否包含攻击性/歧视性内容（toxic / non-toxic）
- 提供对应的心理支持/应对建议

## 使用方法
1. 安装依赖
   pip install transformers torch
2. 运行 detect_and_respond(text) 函数
3. 输入任意句子，得到检测结果和建议

## 适用范围
- 在线对话监测
- 心理支持工具的原型验证
- 性别平等研究中的数据分析

## 后续扩展
- 收集并标注更多中英文语料，进一步微调模型
- 增加“显性 / 隐性 / 无歧视”三分类
- 在检测结果中引入更丰富的心理应对策略
