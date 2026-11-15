# Eureka Robotics Launches StereoPick: No-Code Software for 3D Bin-Picking from CAD in Six Steps

**DailyMech Staff** · 15 November 2026

*Photo by PixelLabs on Pixabay — Pixabay Content License*

![Industrial robot concept](https://cdn.pixabay.com/photo/2025/12/26/10/19/ai-generated-10035792_640.png)

**Eureka Robotics has launched StereoPick, software that enables engineers to set up 3D bin-picking systems directly from a CAD file in six guided steps without writing code or possessing specialised vision expertise. The tool builds on more than 30 million production picks logged by Eureka systems worldwide.**

## What StereoPick Delivers

StereoPick is the setup and training interface for Eureka’s AI Vision System, which pairs a stereo 3D camera with an on-premises controller. Users select a robot, upload CAD models for the part and gripper, define pick and place locations, validate the cell in a digital twin, and then train the vision model on synthetic images rendered from the CAD. Once hardware is installed, camera-to-robot calibration completes the workflow.

Simple rigid parts typically train in a few hours. Everything, including model training, runs locally on the plant’s hardware with no cloud dependency required for the core process. A masterless mode also allows immediate picking of many common rigid objects using a pre-trained foundation model with zero additional training.

## Technical Approach

The system uses AI CAD Matching: an AI first detects parts and estimates poses, after which CAD geometry refines the result. This improves reliability on shiny, dark, overlapping, or cluttered parts compared with traditional pure CAD matching. Cycle times for capture and vision processing are typically under two seconds, with overall pick cycles in the 4–8 second range in many applications and success rates of 98–99.9% after tuning.

Eureka reports that the combination of synthetic data generation from CAD and guided no-code workflow reduces the expertise barrier that has historically limited 3D bin-picking adoption.

## Industry Context

Bin-picking remains one of the higher-value but harder automation tasks in manufacturing and logistics. By lowering the setup time from weeks of specialist work to hours of guided configuration, StereoPick aims to expand the addressable market for vision-guided robotics. Eureka positions the solution as customer-owned: models and data stay on-site, with optional edge training available as an add-on.

CEO Cuong Pham stated that with StereoPick, “3D picking becomes accessible to anyone. Either you bring a CAD file and the system trains itself, or you use the base model and start picking right away.”

## Sources and References

1. Robotics Tomorrow: Eureka Robotics launches StereoPick, allowing anyone to set up 3D picking systems — https://www.roboticstomorrow.com/news/2026/11/12/eureka-robotics-launches-stereopick-allowing-anyone-to-set-up-3d-picking-systems/27377/
2. Eureka Robotics official site and StereoPick product pages — https://eurekarobotics.com/
3. Eureka blog: What is bin picking? A field guide for engineers and related training documentation
4. Coverage in The Robotics Media and industry automation outlets

*Images used under the Pixabay Content License. Specifications are based on company announcements; production results vary by application.*
