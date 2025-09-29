# Collection of the latest spatial, 3D, and video reasoning papers


## Datasets

|Name|Modalities|Description|Train|Test|HF|
|-|-|-|-|-|-|
|[Zebra-CoT](https://arxiv.org/abs/2507.16746)|Multi-Image, Text|Interleaved Vision Language Reasoning|Yes|-|[Link](https://huggingface.co/datasets/multimodal-reasoning-lab/Zebra-CoT)|
|[Video-R1](https://arxiv.org/abs/2503.21776)|Video, Text|Video and text-based reasoning|Yes|-|[Code](https://github.com/tulerfeng/Video-R1)|
|[VSI-Bench](https://huggingface.co/datasets/nyu-visionx/VSI-Bench)|Video, Text|Video walk through of apartment, questions about spatial orientations and planning|No  |Yes| No|
|[CV-Bench](https://huggingface.co/datasets/nyu-visionx/CV-Bench)|Image, Text|Spatial relationship QA on images|No|Yes| [link](https://huggingface.co/collections/nyu-visionx/cambrian-1-models-666fa7116d5420e514b0f23c)|
|[SAT](https://huggingface.co/datasets/array/SAT)|Multi-image, Text|Complex spatial QAs that require reasoning about action/motion causality on synthetic images|Yes|Yes|[link](https://huggingface.co/datasets/array/SAT)|
|[BLINK](https://huggingface.co/datasets/BLINK-Benchmark/BLINK)|Multi-image, Text|Complex visual QA with spatial perception splits|No|Yes|No|
|[ProVision](https://huggingface.co/datasets/Salesforce/ProVision-10M)|Image, Text|Pseudo-annotated spatial relationship QAs on images|Yes|Yes|No|
|[SpatialRGPT](https://www.anjiecheng.me/SpatialRGPT)|Image, Text|Pseudo-annotated spatial relationship QAs on images|Yes|Yes|No|
|[RoboPoint](https://huggingface.co/datasets/wentao-yuan/robopoint-data)|Image, Text|spatial affordance prediction|Yes|Yes|[link](https://huggingface.co/wentao-yuan/robopoint-v1-vicuna-v1.5-13b)|
|[RoboSpatial](https://arxiv.org/abs/2411.16537)|Image, Text|spatial task QAs|Yes|Yes|No|
|[PhysBench](https://huggingface.co/datasets/USC-GVL/PhysBench)|Multi-image, Text|physical object properties, relationships, physics-driven dynamics|Yes|Yes|No|
|[Cambrian-10M](https://huggingface.co/datasets/nyu-visionx/Cambrian-10M)|Image, Text|MLM pretraining QA on images|Yes|No|[link](https://huggingface.co/collections/nyu-visionx/cambrian-1-models-666fa7116d5420e514b0f23)|
|[PixMO](https://huggingface.co/collections/allenai/pixmo-674746ea613028006285687b)|Image, Text|MLM pretraining QA on images|Yes|Yes|[link](https://huggingface.co/allenai/Molmo-7B-D-0924)|
|[MegaBench](https://tiger-ai-lab.github.io/MEGA-Bench/)|Image, Text|MLM benchmark with splits on spatial reasoning|No|Yes|No|
|[MultiSpatialLLM](https://github.com/facebookresearch/Multi-SpatialMLLM)| Image/multi-image, Text | Dynamic spatial QAs|Yes|Yes|-|
|[PEVideo](https://ai.meta.com/datasets/pe-video/)| Video, Text | dense action video annotations| Yes | Yes| -|
|[SPaRC](https://huggingface.co/datasets/lkaesberg/SPaRC/)| Text | 2D pathfinding dataset, requiring multi-step spatial and rule-based reasoning| Yes | Yes|-|



## Topics

### Vision-langauge Models
#### Image/video question-answering

|Paper|Venue/Date|
|-|-|
|[Thinking in Space](https://arxiv.org/abs/2412.14171)|Preprint 2025|
|[SAT: Spatial Aptitude Training for Multimodal Language Models](https://arijitray1993.github.io/SAT/)|Preprint 2024|
|[RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics](https://huggingface.co/datasets/wentao-yuan/robopoint-data)|CoRL 2024|
|[RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics](https://arxiv.org/abs/2411.16537)|Preprint 2024|
|[Cambrian-1: Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs](https://cambrian-mllm.github.io/)|Neurips 2024|
|[SpatialRGPT: Grounded Spatial Reasoning in Vision Language Models](https://www.anjiecheng.me/SpatialRGPT)|Neurips 2024|
|[SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities](https://spatial-vlm.github.io/)|CVPR 2024|
|[ProVision: Programmatically Scaling Vision-centric Instruction Data for Multimodal Language Models](https://arxiv.org/pdf/2412.07012)|Preprint 2024|


#### Robotics and action
|Paper|Venue/Date|Code|
|-|-|-|
|[Gemini Robotics](https://storage.googleapis.com/deepmind-media/gemini-robotics/gemini_robotics_report.pdf)|2025|-|
|[NVIDIA Gr00T N1](https://d1qx31qr3h6wln.cloudfront.net/publications/GR00T_1_Whitepaper.pdf)|2025|[link](https://github.com/NVIDIA/Isaac-GR00T/)|
|[Open X-Embodiment: Robotic Learning Datasets and RT-X Models](https://arxiv.org/abs/2310.08864)|2023|[link](https://robotics-transformer-x.github.io/)|
|[Pi-0: A Vision-Language-Action Flow Model for General Robot Control](https://www.physicalintelligence.company/download/pi0.pdf)|2024||
|[Poliformer: Scaling On-Policy RL with Transformers Results in Masterful Navigators](https://arxiv.org/abs/2406.20083)|CoRL 2024|[link](https://github.com/allenai/PoliFormer)|
|[SPOC: Imitating Shortest Paths in Simulation Enables Effective Navigation and Manipulation in the Real World](https://spoc-robot.github.io/)|CVPR 2024|[link](https://github.com/allenai/spoc-robot-training)|
|[RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics](https://huggingface.co/datasets/wentao-yuan/robopoint-data)|CoRL 2024|[link](https://github.com/wentaoyuan/RoboPoint)|
|[3D-VLA: A 3D Vision-Language-Action Generative World Model](https://arxiv.org/abs/2403.09631)|ICML 2024|[link](https://github.com/UMass-Foundation-Model/3D-VLA)|
|[OpenVLA: An Open-Source Vision-Language-Action Model](https://openvla.github.io/)|2024|[link](https://github.com/openvla/openvla)|
|[Latent Action Pretraining](https://arxiv.org/pdf/2410.11758)|2024|[link](https://latentactionpretraining.github.io/)|
|[GraspMolmo](https://arxiv.org/abs/2505.13441)|2025|[link](https://abhaybd.github.io/GraspMolmo/)|




#### Reasoning, chain-of-thought, RL
|Paper|Venue/Date|Code|
|-|-|-|
|[Machine Mental Imagery: Empower Multimodal Reasoning with Latent Visual Tokens](https://www.arxiv.org/abs/2506.17218)|2025|-|
|[COT-VLA](https://arxiv.org/abs/2503.22020)|2025|-|
|[SpatialCOT: Advancing Spatial Reasoning through Coordinate Alignment and Chain-of-Thought for Embodied Task Planning](https://arxiv.org/abs/2501.10074)|2025|-|
|[Perception Tokens Enhance Visual Reasoning in Multimodal Language Models](https://arxiv.org/abs/2412.03548)|2025|-|
|[Improving Transformer World Models for Data-Efficient RL](https://arxiv.org/abs/2502.01591)|2025|-|
|[Video-R1: Reinforcing Video Reasoning in MLLMs](https://arxiv.org/abs/2503.21776)|2025|[Code](https://github.com/tulerfeng/Video-R1)|
|[SIFThinker: Spatially-Aware Image Focus for Visual Reasoning](https://arxiv.org/abs/2508.06259)|2025|[Code](https://github.com/zhangquanchen/SIFThinker)|
|[VisRL: Intention-Driven Visual Perception via Reinforced Reasoning](https://arxiv.org/abs/2503.07523)|2025|[Code](https://github.com/zhangquanchen/VisRL)|
|[Dream to Control: Learning Behaviors by Latent Imagination](https://arxiv.org/abs/1912.01603)|2019|-|


#### Image-text representations

|Paper|Venue/Date|Code|
|-|-|-|
|[Perception Encoder](https://arxiv.org/abs/2504.13181)|2025||
|[TIPS: Text-Image Pretraining with Spatial Awareness](https://arxiv.org/abs/2410.16512)|ICLR 2025||

----

### Multi-view 2D to 3D

|Paper|Venue/Date|Code|
|-|-|-|
|[DUSt3R: Geometric 3D Vision Made Easy](https://arxiv.org/abs/2312.14132)|2023||
|[Grounding Image Matching in 3D with MASt3R](https://arxiv.org/abs/2406.09756)|2024||
|[Fast3r: Towards 3D Reconstruction of 1000+ Images in One Forward Pass](https://arxiv.org/abs/2501.13928)|2025||
|[Light3R-SfM: Towards Feed-forward Structure-from-Motion](https://arxiv.org/abs/2501.14914)|2025||
|[Stereo 4D](https://stereo4d.github.io/)|2025|[link](https://stereo4d.github.io/)|

----


### Spatial Scene Generation
- [Holodeck- Language Guided Generation of 3D Embodied AI Environments](https://yueyang1996.github.io/holodeck/)
- [Scenecraft- Layout-Guided 3D Scene Generation](https://orangesodahub.github.io/SceneCraft/)
- [Scenescript- Reconstructing Scenes With An Autoregressive Structured Language Model](https://arxiv.org/abs/2403.13064)
- [R2D3-Imparting Spatial Reasoning by Reconstructing 3D Scenes from 2D Images](https://openreview.net/attachment?id=Ku4lylDpjq&name=pdf)




## Related repos/surveys
- https://github.com/ActiveVisionLab/Awesome-LLM-3D
  
----


