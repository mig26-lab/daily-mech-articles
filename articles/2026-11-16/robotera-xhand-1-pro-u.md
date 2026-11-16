# ROBOTERA Opens Commercial Orders for XHAND 1 Pro-U Dexterous Hand Featured in NVIDIA GR00T 2

![Dexterous robotic hand concept](https://cdn.pixabay.com/photo/2024/02/18/11/11/ai-generated-8581008_1280.jpg)

*Image credit: Pixabay – Free for use under Pixabay Content License. Related search: AI robot hands.*

On November 16, 2026, Chinese robotics company ROBOTERA announced the commercial launch of its XHAND 1 Pro-U, a high-degree-of-freedom five-finger dexterous robotic hand. The initial limited release is capped at 40 units, targeting research teams, developers, and industry partners focused on embodied AI and real-world manipulation.

The hand gained prominence through its starring role in NVIDIA’s GR00T 2 demonstrations, including a DexUMI presentation by Jim Fan, Director and Distinguished Research Scientist at NVIDIA, at the Conference on Robot Learning (CoRL). GR00T 2 is a world-action model that learns dexterous skills from large volumes of first-person human video.

## Design Optimized for Human-to-Robot Transfer

XHAND 1 Pro-U features a human-like configuration with a 16-degree-of-freedom mechanical structure. It is closely aligned with NVIDIA GEAR Lab’s DexUMI exoskeleton, a wearable system that records human demonstrations without requiring a physical robot for data collection.

Corresponding joints map movements directly between the exoskeleton and the robotic hand. This reduces the need for additional motion conversion and preserves fine details of demonstrated actions. Refinements include optimized thumb positioning, enhanced palm-side tactile sensing, and improved articulation for natural grasping postures.

The design supports both high-fidelity human demonstration capture and reliable robot execution. Tactile sensors provide three-dimensional force feedback, enabling adaptive grips during complex interactions.

## Performance in Multi-Step Dexterous Tasks

NVIDIA evaluations tested GR00T 2 with the XHAND on three multi-step bimanual tasks:

| Task                  | Success Rate | Key Skills Demonstrated                  |
|-----------------------|--------------|------------------------------------------|
| Preparing banana yogurt | 60%         | Tool use, object transfer, lid handling |
| Scooping granola      | 80%         | Coordinated grasping, pouring           |
| Fire chemistry (match lighting) | 75%   | Precise tool use, sequential actions    |

Previous models such as GR00T 1.7 and π0.5, trained on the same DexUMI data, completed none of the full tasks. This highlights the value of the hardware-software pairing for physical AI progress.

## Implications for Embodied AI Development

Commercial availability of a hand that matches open research capture hardware accelerates data collection for imitation learning and reinforcement learning. Teams can gather force-aware demonstrations more efficiently. The limited initial run suggests strong demand in the research community.

As general-purpose models increasingly control robots directly, high-DoF hands like XHAND 1 Pro-U become critical interfaces for translating digital intelligence into physical capability. Integration with platforms such as NVIDIA’s GR00T series points toward faster progress in factory, laboratory, and service applications.

**Helpful Tip:** When selecting dexterous hands for research, prioritize designs with one-to-one joint mapping to available exoskeletons. This minimizes retargeting errors and speeds up policy training.

## Sources and References

1. ROBOTERA official announcement and PR Newswire release (November 16, 2026)
2. Unite.AI – “ROBOTERA Opens Orders for XHAND 1 Pro-U Dexterous Robot Hand”
3. NVIDIA GR00T 2 demonstrations at CoRL, including DexUMI evaluations
4. The Robot Daily coverage of the commercial launch
5. ROBOTERA product specifications for XHAND series

*Note: Success rates are from NVIDIA’s reported evaluations.*
