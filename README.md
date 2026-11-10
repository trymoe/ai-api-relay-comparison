# AI API 中转站价格对比 · 萌测 TryMoe

Claude、GPT、Gemini、DeepSeek 的 API 中转站怎么比价？这里整理了 7 家服务商的 19 条公开文本报价，输入和输出分开列，每行附采集日期与官方来源。

**首版发布于 2026-11-10。** 价格采集日期见表格，单位为每百万 Token。USD 与 CNY 分开读，API易的人民币数值按该站固定充值兑换比例折算。缓存、工具、多模态和支付费用另计。具体价格以平台当前价表及账单为准。

[查完整站点与在线估价](https://try.moe/stations) · [按模型查价](https://try.moe/models) · [付款、最低充值与退款](guides/topup-and-refunds.md)

## 按模型比较公开报价

### Claude Sonnet 5.5 API 价格

| 站点 | 输入单价 | 输出单价 | 币种 | 计费档位或条件 | 采集日（UTC） | 来源 |
| --- | ---: | ---: | --- | --- | --- | --- |
| [302.AI](https://try.moe/station/302ai) | 2 | 10 | USD | 常规模型 | 2026-11-03 | [官方报价](https://302.ai/) |
| [AIHubMix](https://try.moe/station/aihubmix) | 2 | 10 | USD | 基础文本 | 2026-11-03 | [官方报价](https://aihubmix.com/api/v1/models?type=llm) |
| [CometAPI](https://try.moe/station/cometapi) | 1.6 | 8 | USD | 默认按量，站方倍率已计入 | 2026-11-05 | [官方报价](https://www.cometapi.com/models/anthropic/claude-sonnet-5-5/) |
| [DeepInfra](https://try.moe/station/deepinfra) | 2 | 10 | USD | Serverless Standard | 2026-11-06 | [官方报价](https://api.deepinfra.com/models/anthropic/claude-sonnet-5-5) |
| [OhMyGPT](https://try.moe/station/ohmygpt) | 2.2 | 11 | USD | 公开目录基础文本价 | 2026-11-03 | [官方报价](https://www.ohmygpt.com/models) |
| [OpenRouter](https://try.moe/station/openrouter) | 2 | 10 | USD | 公开目录，具体路由可不同 | 2026-11-03 | [官方报价](https://openrouter.ai/api/v1/models) |
| [API易](https://try.moe/station/apiyi) | 14 | 70 | CNY | Default 分组，按站方 1 美元额度 = 7 元折算 | 2026-11-04 | [官方报价](https://docs.apiyi.com/models) |

[查看 Claude Sonnet 5.5 的完整报价与费用估算](https://try.moe/model/claude-sonnet-55)

### GPT-4.1 Mini API 价格

| 站点 | 输入单价 | 输出单价 | 币种 | 计费档位或条件 | 采集日（UTC） | 来源 |
| --- | ---: | ---: | --- | --- | --- | --- |
| [AIHubMix](https://try.moe/station/aihubmix) | 0.4 | 1.6 | USD | 基础文本，分档见来源 | 2026-11-03 | [官方报价](https://aihubmix.com/api/v1/models?type=llm) |
| [CometAPI](https://try.moe/station/cometapi) | 0.32 | 1.28 | USD | 默认按量，站方倍率已计入 | 2026-11-05 | [官方报价](https://www.cometapi.com/models/openai/gpt-4-1-mini/) |
| [OpenRouter](https://try.moe/station/openrouter) | 0.4 | 1.6 | USD | 公开目录，具体路由可不同 | 2026-11-03 | [官方报价](https://openrouter.ai/api/v1/models) |
| [API易](https://try.moe/station/apiyi) | 2.8 | 11.2 | CNY | Default 分组，按站方 1 美元额度 = 7 元折算 | 2026-11-04 | [官方报价](https://docs.apiyi.com/models) |

[查看 GPT-4.1 Mini 的完整报价与费用估算](https://try.moe/model/gpt-41-mini)

### Gemini 4 Argon API 价格

| 站点 | 输入单价 | 输出单价 | 币种 | 计费档位或条件 | 采集日（UTC） | 来源 |
| --- | ---: | ---: | --- | --- | --- | --- |
| [302.AI](https://try.moe/station/302ai) | 4 | 10 | USD | 常规模型 | 2026-11-03 | [官方报价](https://302.ai/) |
| [AIHubMix](https://try.moe/station/aihubmix) | 2 | 10 | USD | 基础文本 | 2026-11-03 | [官方报价](https://aihubmix.com/api/v1/models?type=llm) |
| [CometAPI](https://try.moe/station/cometapi) | 1.6 | 8 | USD | 默认按量，站方倍率已计入 | 2026-11-05 | [官方报价](https://www.cometapi.com/models/google/gemini-4-argon/) |
| [OpenRouter](https://try.moe/station/openrouter) | 2 | 10 | USD | 公开目录，具体路由可不同 | 2026-11-03 | [官方报价](https://openrouter.ai/api/v1/models) |
| [API易](https://try.moe/station/apiyi) | 14 | 70 | CNY | Default 分组，按站方 1 美元额度 = 7 元折算 | 2026-11-04 | [官方报价](https://docs.apiyi.com/models) |

[查看 Gemini 4 Argon 的完整报价与费用估算](https://try.moe/model/gemini-4-argon)

### DeepSeek V4.1 Flash API 价格

| 站点 | 输入单价 | 输出单价 | 币种 | 计费档位或条件 | 采集日（UTC） | 来源 |
| --- | ---: | ---: | --- | --- | --- | --- |
| [DeepInfra](https://try.moe/station/deepinfra) | 0.14 | 0.42 | USD | Serverless Standard，FP8，含采集时 30% 优惠，截止未公布 | 2026-11-06 | [官方报价](https://api.deepinfra.com/models/deepseek-ai/DeepSeek-V4.1-Flash) |
| [OpenRouter](https://try.moe/station/openrouter) | 0.051 | 0.567 | USD | 公开目录，具体路由可不同 | 2026-11-06 | [官方报价](https://openrouter.ai/api/v1/models) |
| [API易](https://try.moe/station/apiyi) | 2.1 | 8.4 | CNY | Default 分组，按站方 1 美元额度 = 7 元折算 | 2026-11-04 | [官方报价](https://docs.apiyi.com/models) |

[查看 DeepSeek V4.1 Flash 的完整报价与费用估算](https://try.moe/model/deepseek-v41-flash)

## 按自己的用量算

**文本费用 =（输入 Token × 输入单价 + 输出 Token × 输出单价）÷ 1,000,000。**

例如，按表中 USD 2 / 10 的 Claude Sonnet 5.5 报价，累计 100 万输入和 1 万输出 Token，基础文本费是 **USD 2.10**。如果单次请求跨入长上下文价格档，应按每次请求所在档位分别算。输出较多的任务也要单看输出价。以表中 DeepSeek V4.1 Flash 为例，OpenRouter 的目录输入价较低，DeepInfra 采集时的优惠输出价较低。

## 资料与纠错

- [比较口径](methodology.md)解释汇率、价格分档、监控与模型实测的区别。
- [OpenRouter](stations/openrouter.md)与 [API易](stations/apiyi.md)记录各自的目录、路由或分组和充值规则。
- 欢迎推荐中转站、纠正报价和资料、反馈页面问题。[在 GitHub 提交](https://github.com/trymoe/ai-api-relay-comparison/issues/new/choose) · [在萌测报站或纠错](https://try.moe/submit)

这些数字来自公开报价。判断模型身份、工具兼容性和调用稳定性需要单独验证。
