# Alibaba Launches Qwen4-Max with 25% Price Cut and Claims of 62% Lower Agent Task Costs

![AI coding and robotics illustration](https://cdn.pixabay.com/photo/2024/08/08/08/46/artificial-intelligence-8953936_640.png)

*Image from Pixabay under the Pixabay Content License. Artist: Mohamed_hassan.*

Alibaba Cloud has moved its flagship Qwen4-Max model from a limited subscription preview to general pay-as-you-go API access, cutting list prices by 25% and reporting substantial efficiency gains for agentic workloads. The announcement, circulating widely on November 16, 2026, underscores intensifying competition in frontier AI pricing, particularly for long-horizon agent tasks that consume large volumes of tokens.

## Key Developments

- **Pricing**: International (Singapore) list prices are now $1.50 per million input tokens and $4.50 per million output tokens, down from $2.00 and $6.00 for the prior Qwen3.8-Max. Implicit cache-hit inputs drop to $0.075 per million, a 70% reduction.
- **Efficiency claims**: On Alibaba’s internal Work360 benchmark (covering professional tasks across many domains), average cost per task fell from $4.43 to $1.67 — a reported 62% reduction. Token usage decreased roughly 24–35% on Work360 and 48–49% on Terminal-Bench 4.0 depending on reasoning effort.
- **Architecture and capabilities**: Sparse Mixture-of-Experts design with approximately 2.4 trillion backbone parameters (71 billion active per token), native vision, and a 1-million-token context window. Available on QwenCloud API, Qwen Studio, QwenWork, and Qoder.
- **Access**: General pay-as-you-go alongside Token Plan subscriptions. A free quota of 1 million tokens is available in Singapore for 90 days under certain conditions. Smaller open-weight Qwen4 models are expected later.

| Metric                  | Qwen4-Max     | Qwen3.8-Max   | Change     |
|-------------------------|---------------|---------------|------------|
| Input price /M tokens  | $1.50        | $2.00        | −25%      |
| Output price /M tokens | $4.50        | $6.00        | −25%      |
| Implicit cache /M      | $0.075       | $0.25        | −70%      |
| Work360 avg cost/task  | $1.67        | $4.43        | −62%      |

These figures come from Alibaba’s own announcements and pricing documentation; independent verification of the token-efficiency and cost claims is still limited.

## Why It Matters for Agents and Developers

Agent systems that loop over tools, search, or long documents are highly sensitive to both per-token price and tokens-per-task. A combination of lower list prices and reduced token consumption can materially change the economics of production agent deployments. Alibaba is positioning Qwen4-Max as a practical “teammate” for coding, research, manufacturing, finance, and scientific workflows rather than solely as a general chatbot.

The move also puts pressure on Western labs. With Anthropic preparing a large IPO and Google shipping successive Gemini 4 variants, aggressive pricing from Chinese providers continues to compress margins across the industry.

## Conclusion of Search

Latest reports from November 15–16, 2026, confirm Qwen4-Max is live on the public API with the stated price cuts and Alibaba-reported efficiency gains. The model exits a Token Plan-only preview (scheduled to retire around November 25). Open-weight smaller siblings are still pending. Primary sources are Alibaba Cloud Model Studio pricing pages and company announcements; secondary coverage appears in Frontier, AlphaSignal, MLQ.ai, and Unite.AI.

## Sources and References

1. Alibaba Cloud Model Studio model pricing documentation (updated around November 16, 2026) — https://www.alibabacloud.com/help/en/model-studio/model-pricing
2. Frontier / The Defiant coverage — https://thedefiant.io/frontier/ai/alibaba-launches-qwen4-max-with-lower-api-prices
3. AlphaSignal summary — https://alphasignal.ai/news/alibaba-s-qwen4-max-slashes-agent-task-costs-62-with-1m-token-context
4. MLQ.ai report — https://mlq.ai/news/alibaba-launches-qwen4-max-saying-it-cuts-task-costs-by-about-60-with-tighter-cyber-guardrails/
5. Unite.AI — https://www.unite.ai/alibaba-cloud-releases-qwen4-max-with-25-lower-singapore-api-prices/
6. AI Tracker — https://ai-tracker.rootstudio.io/news/2026-11-15-qwen4-max-launch

## Helpful Tips

- Check the official Alibaba Cloud Model Studio pricing page for regional variations; Singapore International rates are the most widely cited.
- For agent workloads with repeated prefixes, leverage the cheaper implicit/explicit caching — the 70% cache reduction can be larger than the base list-price cut.
- Work360 and Terminal-Bench numbers are vendor-reported; cross-check with independent evaluations as they appear.
- Free quotas and Token Plan credits may have geographic and usage restrictions — review terms before relying on them for production.
- Monitor for the promised open-weight smaller Qwen4 models if local or fine-tuned deployment is a priority.
