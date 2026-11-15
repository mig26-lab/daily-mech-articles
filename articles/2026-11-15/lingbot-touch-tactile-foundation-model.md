# LingBot-Touch: Open-Source Tactile Foundation Model Gives Robots a Shared Sense of Touch

**Published: November 15, 2026**  
**Category: Robotics / AI / Hardware**

![Humanoid robot working at a workbench](https://cdn.pixabay.com/photo/2023/07/22/03/37/ai-generated-8142626_1280.jpg)

*Image: AI-generated humanoid robot in industrial setting from Pixabay (Pixabay Content License – free for commercial use with attribution preferred)*

Robbyant, the embodied AI unit within Ant Group, has open-sourced LingBot-Touch, a tactile foundation model designed to unify signals from heterogeneous touch sensors and improve dexterous robotic manipulation. Released around November 9–10, 2026, the model addresses one of the longest-standing gaps in robotics: the ability to reliably interpret and act on physical contact information across different hardware.

## The Challenge of Touch in Robotics

Vision has advanced rapidly for robots, but touch remains fragmented. Different sensor technologies—piezoresistive, magnetic, and visuotactile—produce incompatible raw signals. Data collected on one hand or glove rarely transfers to another. LingBot-Touch tackles this by learning a shared latent representation that can be plugged into existing action models.

The model was pretrained on nearly 5,000 hours (4,983 hours reported) of real tactile recordings from human-worn gloves and teleoperated robot hands, totaling hundreds of thousands of episodes and over a billion frames. A lightweight variant (HaT-Tiny / LingBot-Touch-Tiny) contains only about 5.3–5.5 million parameters.

## Reported Performance Gains

In evaluations across 26 real-world dexterous tasks on hands such as Sharpa Wave and XHand, adding LingBot-Touch improved average success rates by roughly 14 to 26 percentage points compared with no-touch baselines. Gains held across multiple policies including Diffusion Policy, π₀.5, LingBot-VLA, and T-Rex.

A striking example: unscrewing a bottle cap. Success rose from around 56% with no touch to 90% when using LingBot-Touch processed features. Raw sensor input produced only modest improvement, demonstrating that the learned representation, not just the presence of sensors, drives the benefit.

The code and weights are available under Apache 2.0 on GitHub and Hugging Face, enabling the community to experiment and extend the work.

## Broader Context in Tactile and Dexterity Advances

LingBot-Touch arrives amid a wave of related progress:
- Microchip announced high-channel tactile digitizers capable of reading dozens of sensor channels at high frequency for robotic hands.
- Demonstrations at Swiss Robotics Day 2026 highlighted thin robot skin and high-DOF hands with force modulation.
- Other groups are releasing tactile world models and simulation tools.

These developments complement vision-language-action models and support the shift toward humanoid and industrial robots that can handle unstructured, contact-rich tasks such as assembly, packing, and inspection.

## Key Takeaways

- Open-source tactile model unifying three major sensor types.
- Pretrained on ~5,000 hours of real data; tiny variant under 6M parameters.
- 14–26 point success rate gains on 26 real robot tasks.
- Plug-and-play with existing control policies.

## Helpful Tips

- Developers can start with the Tiny checkpoint for low-overhead integration into existing VLA or diffusion policies.
- When evaluating tactile systems, compare against both no-touch and raw-signal baselines to isolate representation quality.
- Combine with simulation-to-real pipelines and force-controlled hardware for best results on contact-heavy industrial tasks.

## Sources and References

1. Robbyant official LingBot-Touch project page and technical materials (November 2026).
2. Coverage from Humanoids Daily, The Robotics Media, Interesting Engineering, and Pandaily (November 10–15, 2026).
3. Related announcements on Microchip tactile digitizers and Swiss Robotics Day dexterity demonstrations.

*This article synthesizes publicly available information as of November 15, 2026. Images used under the Pixabay Content License. Consult primary sources and the official repository for implementation details.*