# Huang Jiangzixuan

*"Bridging the gap between bits and atoms."*

Undergraduate in Computer Science at **The University of Hong Kong** and Vision Group member of the **HKU RoboMaster Team**. I work on real-world perception systems, vision-language reasoning, autonomous agents, and embodied AI.

My current interests sit at the intersection of:

- **Vision-language models:** spatial reasoning, visual grounding, and geometry-aware multimodal inference.
- **Computer vision:** detection, segmentation, depth estimation, calibration, and robust state estimation.
- **Autonomous systems:** perception-to-action pipelines, closed-loop control, and real-time deployment.

## Research Interests

<table width="100%">
<tr>
<td width="33%" valign="top">

### Foundation Models & Agents

I am interested in how LLMs and VLMs reason, plan, use tools, and maintain context over long-horizon tasks.

- Tool-augmented reasoning
- Persistent context and memory
- Multimodal planning and evaluation
- Agent reliability under incomplete observations

</td>
<td width="33%" valign="top">

### Geometry-Aware Visual Reasoning

I study whether explicit visual geometry can make VLM reasoning more reliable on real images.

- Object-level spatial representations
- Depth and segmentation assisted reasoning
- Spatial relation and physical-size questions
- Separating perception failures from reasoning failures

</td>
<td width="33%" valign="top">

### Real-World Perception Systems

I build and optimize perception pipelines for dynamic physical environments.

- Object detection and instance segmentation
- Camera calibration and 6-DoF pose estimation
- PnP, Kalman filtering, and state estimation
- CUDA, OpenCV, and real-time CV optimization

</td>
</tr>
</table>

## Projects

<table width="100%">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tr>
<td width="50%" valign="top">

### [GeoVLM-SceneReasoner](https://github.com/Hjjj0918/GeoVLM-SceneReasoner)

Geometry-aware visual reasoning pipeline for evaluating whether object detection, SAM2 segmentation, Depth Anything V2 relative depth, and object-level geometry can improve VLM spatial reasoning.

The project builds a staged benchmark pipeline:

```text
image -> detection -> segmentation -> depth
      -> geometry -> reasoning -> evaluation
```

Current features include YOLO detection, label normalization, SAM2 mask generation, depth estimation, object-level geometry extraction, reasoning prompt generation, a geometry-only rule baseline, and failure analysis that separates upstream perception errors from reasoning errors.

</td>
<td width="50%" valign="top">

### [Sixshot](https://github.com/Hjjj0918/Aimlab-sixshot)

Real-time deep learning aim bot for Aimlab Sixshot. The system uses screen capture, target detection, and hardware mouse control at 100+ FPS.

Built a custom **MiniUNet** with approximately 467K parameters for Gaussian heatmap regression, plus an end-to-end workflow from interactive labeling to real-time inference and adaptive flick control.

</td>
</tr>
</table>

### Ongoing Direction

I am currently building toward a research portfolio around multimodal reasoning and real-world perception:

- VLM spatial reasoning benchmarks
- Geometry-enhanced visual question answering
- Robust perception for robotics and embodied agents
- Evaluation pipelines that expose failure modes instead of hiding them

## Stack

<table width="100%">
<tr>
<td width="50%" valign="top">

### ML & Vision

<p>
  <img src="https://skillicons.dev/icons?i=pytorch,opencv,cuda" />
</p>

PyTorch · OpenCV · CUDA

</td>
<td width="50%" valign="top">

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=py,cpp,cs,java,js" />
</p>

Python · C++ · C# · Java · JavaScript

</td>
</tr>

<tr>
<td width="50%" valign="top">

### Robotics & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=linux,ros,docker,git,mysql,latex" />
</p>

Linux · ROS · Docker · Git · MySQL · LaTeX

</td>
<td width="50%" valign="top">

### Frontend & Tools

<p>
  <img src="https://skillicons.dev/icons?i=react,vue,ts,unity" />
</p>

React · Vue · TypeScript · Unity

</td>
</tr>
</table>

## Contact

<p>
  <a href="https://hjjj.top"><img src="https://img.shields.io/badge/website-hjjj.top-4285F4?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="mailto:u3628929@connect.hku.hk"><img src="https://img.shields.io/badge/email-connect@hku.hk-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/jiangzixuan-huang-b583ab39a/"><img src="https://img.shields.io/badge/linkedin-Huang_Jiangzixuan-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Hjjj0918"><img src="https://img.shields.io/badge/github-Hjjj0918-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>
