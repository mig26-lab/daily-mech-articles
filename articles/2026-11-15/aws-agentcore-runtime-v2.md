# AWS Makes Next-Generation AgentCore Runtime the Default for Faster, More Efficient AI Agents

**Published: November 15, 2026**  
**Category: AI / Cloud / Technology**

![Abstract neural network and technology](https://cdn.pixabay.com/photo/2024/01/29/22/47/ai-generated-8540914_1280.jpg)

*Image: AI neural network visualization from Pixabay (Pixabay Content License – free for commercial and non-commercial use)*

On November 12, 2026, Amazon Web Services announced that the next-generation AgentCore runtime is now the default for new Amazon Bedrock AgentCore deployments across roughly 19–20 AWS Regions. The update restores sessions from snapshots of initialized agents, scales compute and memory dynamically, and reduces cold-start times dramatically while preserving strong isolation.

Each session continues to run inside its own hardware-isolated Firecracker microVM. Sessions can now scale to 8 vCPUs and 32 GB of memory (up from earlier limits around 2 vCPUs and 8 GB) and support container images up to 10 GB. On a 2 GB image, P75 startup time drops from 29.7 seconds to under 2 seconds. Idle agents scale to zero, and multi-turn agents can see up to 68% less billed memory per session.

## Why This Matters for Production Agents

AI agents that browse the web, compile code, call tools, or maintain multi-step reasoning often suffer from slow cold starts and inefficient resource use. Traditional serverless approaches can force developers to maintain warm pools or accept latency spikes. AgentCore’s snapshot-based restore addresses the initialization bottleneck while Firecracker microVMs provide stronger isolation than containers alone.

AWS states that agents can now handle heavier workloads inside a single session—such as compiling a large codebase, driving a browser, or loading a local model—without sacrificing the one-session-one-microVM security model. Memory is reclaimed within minutes after release. Existing runtimes remain on the previous version until explicitly migrated by setting `platformVersion` to V2.

## Technical Details and Availability

The runtime is available by default in regions including US East (N. Virginia), US East (Ohio), US West (Oregon), Europe (Frankfurt, Ireland, London, and others), and Asia Pacific (Tokyo, Singapore, Sydney, Mumbai, and more). Developers can still pin to V1 if needed. Pricing remains consumption-based, with reported rates around $0.1276 per vCPU-hour and $0.0169 per GB-hour in some documentation, plus options for committed baselines on always-on workloads.

Firecracker, originally developed for Lambda, provides lightweight virtualization that combines container-like speed with VM-level isolation. AgentCore applies this model to stateful agent sessions that may last hours and involve multiple tool calls and model invocations.

## Broader Context in the Agent Stack

As frontier models improve at tool use and long-horizon tasks, the infrastructure layer becomes a bottleneck. Faster, more efficient runtimes lower the cost and latency of deploying agents at scale. This benefits both custom agents built on frameworks such as LangGraph or Strands and managed Bedrock experiences. Competitors in the cloud and AI platform space are also investing in specialized agent hosting; AWS’s move strengthens its position for enterprises already using Bedrock.

## Looking Forward

Developers evaluating AgentCore will want to test migration paths, measure real-world cold-start and cost improvements on their workloads, and monitor any additional features such as filesystem mounting options. The update is an incremental but practical step toward making production AI agents more responsive and economical.

## Sources and References

1. AWS What’s New: “The next generation AgentCore runtime is now the default” (November 12, 2026).
2. AWS Machine Learning Blog: “Run agents securely and efficiently with the next generation AgentCore runtime.”
3. Amazon Bedrock AgentCore documentation on session isolation and Firecracker microVMs.
4. Secondary reporting from AWSInsider, Data Phoenix, and developer communities summarizing the performance claims.

*This article synthesizes publicly available information as of November 15, 2026. Images used under the Pixabay Content License. Consult primary sources for the latest updates.*