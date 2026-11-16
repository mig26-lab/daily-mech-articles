# SMART and NUS Pioneer Neural-Inspired Controller for Adaptive Soft Robots

![Futuristic soft robotics concept](https://cdn.pixabay.com/photo/2024/02/06/10/13/ai-generated-8556594_1280.jpg)

*Image credit: Pixabay – Free for use under Pixabay Content License. Related: soft robots, AI control.*

Researchers from the Singapore-MIT Alliance for Research and Technology (SMART), National University of Singapore (NUS), MIT, and Nanyang Technological University (NTU Singapore) have developed a general AI control system that brings human-like adaptability to soft robotic arms. The work, published in *Science Advances* under the title “A general soft robotic controller inspired by neuronal structural and plastic synapses that adapts to diverse arms, tasks, and perturbations,” addresses a long-standing barrier in soft robotics.

Soft robots, constructed from flexible materials such as soft rubber and driven by artificial-muscle-like actuators, excel at safe interaction with humans and irregular objects. However, their continuum bodies change shape unpredictably under disturbances, making reliable control difficult in real environments.

## Structural and Plastic Synapses for Learning and Adaptation

The controller draws inspiration from neuronal structural and plastic synapses in the human brain. It uses two complementary mechanisms:

- **Structural synapses**: Trained offline on foundational motions such as bending and extending. These provide a stable base of learned skills that transfer across tasks.
- **Plastic synapses**: Update online in real time to fine-tune behavior in response to new conditions, disturbances, or hardware variations.

A built-in stability measure acts as a safeguard, ensuring movements remain smooth and controlled even while the system adapts. This combination enables the robot to learn a broad repertoire of motions once, then adjust instantly to changing scenarios without full retraining.

## Key Capabilities Achieved

The system is among the first general soft-robot controllers to deliver all three critical capabilities simultaneously:

1. Transfer of offline-learned skills to diverse tasks.
2. Instant online adaptation to perturbations (weight shifts, wind, faults, or new environments).
3. Maintained stability and safety throughout adaptation.

Previous approaches typically handled only one or two of these requirements, limiting practical deployment. Associate Professor Zhiqiang Tang, first and co-corresponding author (formerly at SMART M3S and NUS, now at Southeast University), noted: “This new AI control system is one of the first general soft-robot controllers that can achieve all three key aspects needed for soft robots to be used in society and various industries.”

## Applications and Future Outlook

The advance brings soft robotics closer to reliable use in assistive devices, rehabilitation robots, wearable medical systems, and industrial settings where gentle interaction is essential. Soft robots can now handle a wider range of real-world variability while remaining safe around people.

Broader implications include reduced reliance on extensive per-task data collection and faster deployment of compliant robots in unstructured environments. As the field moves toward more intelligent physical systems, biologically inspired controllers like this one offer a promising path for combining flexibility with reliability.

**Helpful Tip:** For soft robot projects, evaluate controllers on the full triad of skill transfer, online adaptation, and stability rather than isolated accuracy metrics. Real-world robustness depends on all three.

## Sources and References

1. SMART / NUS / MIT / NTU collaborative research published in Science Advances (November 2026)
2. MedTech Spectrum – “SMART and NUS Pioneer Neural Blueprint for Human-like Intelligence in Soft Robots” (November 16, 2026)
3. Statements from Associate Professor Zhiqiang Tang and the research team
4. Coverage of soft robotics challenges and solutions in recent robotics literature

*Note: Results are based on the published scientific study.*
