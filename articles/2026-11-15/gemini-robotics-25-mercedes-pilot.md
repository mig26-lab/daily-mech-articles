# DeepMind’s Gemini Robotics 2.5 Delivers 96% Success on Live Mercedes-Benz Production Lines

![Robotic hand interacting with technology](https://cdn.pixabay.com/photo/2026/04/20/18/48/18-48-11-393_640.jpg)
*Image: Free for use under Pixabay Content License. Source: Pixabay*

Google DeepMind has introduced Gemini Robotics 2.5, its most advanced vision-language-action (VLA) model to date. Announced on November 10, 2026, the system translates camera input and natural-language instructions directly into precise motor commands for robot arms, hands, and full humanoid bodies. The most striking demonstration occurred outside the laboratory: Apptronik’s Apollo 2 humanoid robots, powered by the new model, achieved a 96% success rate while sorting automotive parts on active Mercedes-Benz production lines.

## The Factory Pilot

The proof-of-concept ran at Mercedes-Benz plants in Kecskemét, Hungary, and Sindelfingen, Germany. Apollo 2 humanoids performed automotive kitting—picking metal brackets from bulk supply bins and placing them into sequencing trays in the exact order required by each vehicle moving down the line. This is repetitive but precision-critical preparatory work that keeps the assembly process flowing.

Two models collaborated. Gemini Robotics ER handled higher-level workflow tracking and planning, while Gemini Robotics 2.5 controlled the hands and arms for the physical manipulations. The tested Apollo 2 configuration used a five-finger SharpaWave hand with 22 degrees of freedom. DeepMind reports that the robots corrected for gaps and maintained reliability in a real industrial environment alongside human workers.

## Performance Gains

Across more than 200 evaluated tasks, Gemini Robotics 2.5 delivered 30–100% higher success rates than previous baselines, depending on the task type, and completed tasks 20–30% faster. Improvements appear in dexterity (handling delicate or flexible objects and using tools), reliability, and physical safety. Inference-time reasoning helps the system avoid hazards in real time. Training was accelerated by Gemini 4 Argon, which generated thousands of simulated practice runs and analyzed failure replays to refine the recipes.

Apptronik CEO Jeff Cardenas noted that the models improved dramatically within weeks of post-training and transferred to the Mercedes-Benz lines with minimal performance drop-off. The model is currently rolling out to DeepMind’s robotics partners rather than being offered as a public API.

## Broader Context

The release arrives as the industry debates the best path to general-purpose robots. While some labs continue specialized robotics stacks, others (including OpenAI’s recent reorganization) are betting that increasingly capable general models can serve as robot brains. Gemini Robotics 2.5 represents DeepMind’s continued investment in purpose-built physical intelligence that can be adapted across embodiments, from dual-arm systems to full humanoids.

Safety remains a focus. The announcement includes ASIMOV-Jailbreak, an open-source benchmark measuring resistance to unsafe commands disguised as benign instructions. Evaluations showed high resistance when using Gemini 4 Argon in the training pipeline.

## Sources and References

- Google DeepMind blog: “Gemini Robotics 2.5: Accelerating Physical Intelligence” (November 10, 2026).
- Reporting from The Decoder, Unite.AI, Humanoids Daily, and Robotics & Automation News on the Mercedes-Benz pilot.
- Apptronik statements regarding the Apollo 2 deployment.

*Images used under the Pixabay Content License.*
