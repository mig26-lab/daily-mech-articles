# Gemini Robotics 2.5 Delivers Factory-Ready Dexterity and Open Safety Benchmarks

![Robotic arm in industrial setting](https://cdn.pixabay.com/photo/2024/09/21/07/41/ai-generated-9063230_640.jpg)

*Image credit: Pixabay – Free for use under Pixabay Content License*

Google DeepMind introduced Gemini Robotics 2.5 in mid-November 2026 as its most capable vision-language-action (VLA) model to date. The release emphasizes greater skill breadth, faster learning, improved reliability, and safety features for real-world industrial and everyday environments.

## Performance Gains

Evaluations across more than 200 tasks showed success rates 30% to 100% higher than previous baselines, with tasks completed 20% to 30% faster. The model improves dexterity for everyday tools and delicate or flexible objects while enhancing robustness.

In a proof-of-concept on Mercedes-Benz production lines (Kecskemét, Hungary and Sindelfingen, Germany), Apptronik’s Apollo 2 humanoid robots using Gemini Robotics 2.5 for arm and hand control, paired with Gemini Robotics ER for planning, achieved a 96% success rate on automotive kitting — selecting parts from bulk containers and arranging them into sequencing trays.

Safety reasoning raised safe task completion by 33% around obstacles and 43% near people. The system can stop or wait when conditions become unsafe.

## ASIMOV-Jailbreak Open Benchmark

Alongside the model, DeepMind released ASIMOV-Jailbreak, an open-source dataset of hundreds (reports vary up to ~1,500) of adversarial prompts designed to disguise unsafe requests across diverse scenes. It is available on Hugging Face under a permissive license.

Gemini 4 Argon achieved approximately 99.5% resistance (or 98.8% in some reporting) versus roughly 82% or 73.5% for earlier baselines when used in the safety loop. Note that the highest scores apply primarily to the reasoning model rather than the pure action VLA.

## Broader Context

The model is rolling out to robotics partners. This continues DeepMind’s push into physical intelligence, complementing work on world models and agentic systems. Real factory results, even in limited pilots, mark a step beyond pure lab demos toward production relevance.

**Helpful Tip:** For industrial deployments, prioritize systems with explicit obstacle and human-proximity safety behaviors plus independent safety evaluations.

## Sources and References

1. Google DeepMind blog – “Gemini Robotics 2.5: Accelerating Physical Intelligence” (Nov 10, 2026)
2. Ars Technica – coverage of ASIMOV-Jailbreak and factory results
3. Robotics & Automation News and other industry reports
4. Hugging Face: google/asimov_agentic dataset
5. Partner demonstrations with Apptronik Apollo 2 at Mercedes-Benz

*Figures are primarily from DeepMind announcements and pilot reports.*
