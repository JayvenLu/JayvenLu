<h1 align="center">Hi, I'm Xiaofan Lu</h1>

<p align="center">
  Researcher in vision-based tactile sensing, multimodal robotic perception, and edge AI.
</p>

## About Me

I develop tactile perception systems that recover contact geometry and force
from visual observations. My work spans the full research pipeline, from
sensor data collection and camera calibration to learning-based perception,
physics-informed reconstruction, hardware acceleration, and system
validation.

I am particularly interested in building reliable, high-rate tactile sensing
for contact-rich robotic manipulation.

## Research Interests

- Vision-based tactile sensing and visuotactile perception
- Surface-normal and depth reconstruction
- Three-axis contact-force estimation
- Multimodal perception for robotic manipulation
- Physics-informed learning
- Edge AI, model quantization, and FPGA acceleration

## Selected Research

### Curved Vision-Tactile Perception

I am developing an RGB-NIR curved vision-tactile sensing pipeline that
combines coordinate-aware surface-normal inference, boundary-prior depth
reconstruction, marker-based tangential displacement recovery, and
position-aware three-axis force estimation.

The project addresses practical challenges in curved tactile sensors,
including self-occlusion, near-field illumination, spatially varying
mechanical response, and real-time inference.

### FPGA Edge Deployment

I am building a hardware-oriented workflow for tactile perception that
connects INT8 normal inference, depth reconstruction, and normal-force
estimation. The workflow includes golden-vector generation, RTL replay,
frame-buffer and register-map design, implementation analysis, and board-level
validation procedures.

A full-spatial normal-inference RTL implementation has been validated in
simulation, with a post-route latency estimate of **0.082 ms per 128 x 128
frame at 200 MHz**. This figure is an implementation estimate rather than a
camera-to-force board measurement.

## Publications

- Yuankai Lin, **Xiaofan Lu**, Jiahui Chen, and Hua Yang,
  "3D Vision-tactile Reconstruction from Infrared and Visible Images for
  Robotic Fine-grained Tactile Perception," *IEEE/RSJ International Conference
  on Intelligent Robots and Systems (IROS)*, 2025.
  [DOI](https://doi.org/10.1109/IROS60139.2025.11246893)
- Yuankai Lin, **Xiaofan Lu**, and Hua Yang,
  "High-Precision RGB-NIR Vision-Tactile Sensor via Neural Inverse Rendering
  for Robotic Perception," accepted by *IEEE/ASME Transactions on Mechatronics*.

## Tools

`Python` · `PyTorch` · `NumPy` · `OpenCV` · `Verilog/SystemVerilog` ·
`Vivado` · `XSim` · `Tcl` · `Git`

## Current Focus

- High-fidelity geometry and force perception for curved tactile sensors
- Hardware-software co-design for high-rate tactile inference
- Robust tactile sensing for dexterous and contact-rich manipulation

