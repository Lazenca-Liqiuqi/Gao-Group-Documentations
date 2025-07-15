# LLM价格一览

包含：OpenAI（GPT系列）、Google（Gemini系列）、Anthropic（Claude系列）、X（Grok系列）、幻方量化（Deepseek系列），国外模型价格均为美元。国产平台大多是可以免费使用的，由于Deepseek的服务器很垃圾，大部分人都会选择使用API。

包含最新网页版与会员所提供的模型，不包含只提供API不提供网页版会员的模型，价格均为每百万Tokens价格（M Toks）。

可以和中间商API平台校对价格，中间商平台一般不提供缓存价格，多轮聊天全计算输入价格，这也是他们盈利的主要方式之一。

## OpenAI

| 模型         | 提示 | 输出 | 缓存  | 备注 |
| ------------ | ---- | ---- | ----- | ---- |
| GPT-4o       | 2.5  | 10   | 1.25  |      |
| GPT-4.1 mini | 0.4  | 1.6  | 0.1   |      |
| GPT-4.1      | 2    | 8    | 0.5   |      |
| o3           | 2    | 8    | 0.5   |      |
| o4-mini      | 1.1  | 4.4  | 0.275 |      |
| o4-mini-high | /    | /    | /     |      |
| o3-pro       | 20   | 80   | /     |      |
| o1           | 15   | 60   | 7.5   |      |
| o1-pro       | 150  | 600  | /     |      |

信源：https://openai.com/zh-Hans-CN/chatgpt/pricing/, https://platform.openai.com/docs/pricing

时间：25.7.14

## Google

| 模型                  | 提示     | 输出  | 缓存        | 备注        |
| --------------------- | -------- | ----- | ----------- | ----------- |
| Gemini 2.5 Pro        | 1.25/2.5 | 10/15 | 0.31/0.625  | 20w提示为界 |
| Gemini 2.5 Flash      | 0.3/1    | 2.5   | 0.075/0.25  | 音频更贵    |
| Gemini 2.5 Flash-Lite | 0.1/0.5  | 0.4   | 0.025/0.125 | 音频更贵    |

信源：https://ai.google.dev/gemini-api/docs/pricing?hl=zh-cn

时间：25.7.14

## Anthropic

W/R分别是Write和Read的价格，所有价格批处理可以便宜50%。


| 模型             | 提示 | 输出 | 缓存      | 备注 |
| ---------------- | ---- | ---- | --------- | ---- |
| Claude Opus 4    | 15   | 75   | 18.75/1.5 | W/R  |
| Claude Sonnet 4  | 3    | 15   | 3.75/0.3  | W/R  |
| Claude Haiku 3.5 | 0.8  | 4    | 1/0.08    | W/R  |

信源：https://www.anthropic.com/pricing#api

时间：25.7.14

## X

| 模型             | 提示 | 输出 | 缓存 | 备注 |
| ---------------- | ---- | ---- | ---- | ---- |
| Grok-4           | 3    | 15   | /    |      |
| Grok-3           | 3    | 15   | /    |      |
| Grok-3-mini      | 0.3  | 0.5  | /    |      |
| Grok-3-fast      | 5    | 25   | /    |      |
| Grok-3-mini-fast | 0.6  | 4    | /    |      |

信源：https://docs.x.ai/docs/models

时间：25.7.14

## 幻方量化

Deepseek的价格在优惠时间段打折，Chat模型打5折，Reasoner打25折。同时，Deepseek对于命中缓存的输入提供更低的价格，价格单位都是人民币。

| 模型              | 提示  | 输出 | 缓存 | 备注     |
| ----------------- | ----- | ---- | ---- | -------- |
| Deepseek-chat     | 0.5/2 | 8    | /    | 标准时段 |
| Deepseek-reasoner | 1/4   | 16   | /    | 标准时段 |

信源：https://api-docs.deepseek.com/zh-cn/quick_start/pricing#%E6%89%A3%E8%B4%B9%E8%A7%84%E5%88%99

时间：25.7.14