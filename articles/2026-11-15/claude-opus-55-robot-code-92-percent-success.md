# Claude Opus 5.5 Generates Robot Control Programs Achieving 92.1% Success in Physical Trials Without Live AI

**DailyMech Staff** · 15 November 2026

*Photo by Waqas420 on Pixabay — Pixabay Content License*

![Robotics and artificial intelligence concept](https://cdn.pixabay.com/photo/2026/04/20/18/48/18-48-11-393_640.jpg)

**A November 12 preprint details how robot-control programs written with Anthropic’s Claude Opus 5.5 achieved a 92.1% success rate across 240 physical trials. Crucially, the model was absent during evaluation: each program was frozen after development and executed without further AI or human intervention in the control loop.**

## The ACE-CaP-0 Method

Researchers with the ACE-CaP Team used a method called ACE-CaP-0 in which the coding agent writes, runs, inspects, and revises code while receiving physical feedback during the development phase. Once a program for a given task is finalised, it is locked. Evaluation then consists of 30 independent trials per task with the code remaining unchanged.

The experimental setup employed two Agilex PIPERX dual-arm robots equipped with three Orbbec DaBai DC1 cameras. Tasks included packing bread and shoes, inserting a charger and a flower, uncapping a bottle, nesting cups, plating chicken, and reorienting a parcel.

## Results Breakdown

Across eight tasks and 240 trials total, 221 succeeded (92.1%). Performance varied:

- Charger insertion: 30/30 (100%)
- Chicken plating: 29/30
- Parcel reorientation and cup nesting: 28/30 each
- Shoe packing, flower insertion, bottle uncapping: 27/30 each
- Bread packing: 25/30 (lowest)

Average physical execution times ranged from under one minute to roughly 2.3 minutes. On-demand simulation during development improved outcomes for some tasks; for charger insertion, simulation-assisted development reached 100% evaluation success versus 86.7% without it, while also reducing development time.

## Significance for Embodied AI

The results demonstrate that frontier language models can produce durable, task-specific robot control code that continues to function after the generative agent is removed. This contrasts with approaches that keep a large model in the live control loop. It also complements other recent work, such as Apple research showing frontier models with appropriate harnesses outperforming specialist vision-language-action models on certain manipulation benchmarks.

While still limited to structured laboratory tasks, the high success rate on frozen code points toward practical pathways for deploying AI-generated robot skills in manufacturing and logistics without continuous high-cost inference.

## Sources and References

1. EconoTimes: Claude Opus 5.5 Robot Programs Succeed in 221 of 240 Trials — https://econotimes.com/Claude-Opus-5-5-Robot-Programs-Succeed-in-221-of-240-Trials-1777308
2. The Currency Analytics coverage of the ACE-CaP-0 preprint results
3. Related reporting on Anthropic Claude models and robotics benchmarks (RoboDojo, etc.)
4. Preprint details as summarised in multiple technology outlets on 15 November 2026

*Images used under the Pixabay Content License. The study is a preprint and results should be interpreted in that context.*
