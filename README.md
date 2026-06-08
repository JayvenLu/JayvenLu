<h1 align="center">Xiaofan Lu</h1>

<p align="center">
  M.Eng. Student at Huazhong University of Science and Technology<br>
  Vision-Based Tactile Sensing | Robotic Perception | Edge AI
</p>

<p align="center">
  <a href="https://jayvenlu.github.io/">Academic Website</a> |
  m202470725@hust.edu.cn
</p>

## About Me

I am a master's student in Mechanical Engineering at Huazhong University of
Science and Technology (HUST), advised by Prof. Hua Yang. My research focuses
on vision-based tactile sensing for contact-rich robotic manipulation.

I develop tactile sensing systems across the full research pipeline, including
sensor structure design, fabrication processes, imaging hardware, geometric
and force calibration, 3D reconstruction, force estimation, and FPGA
acceleration. I am particularly interested in high-fidelity, high-speed tactile
perception that connects sensing hardware, learning-based methods, physical
modeling, and real-time deployment.

## Research Interests

- Vision-based tactile sensing
- Contact geometry reconstruction
- Three-axis force estimation
- Neural inverse rendering and synthetic tactile data
- Multimodal perception for robotic manipulation
- Edge AI and FPGA acceleration

## Featured Research

### RGB-NIR Geometry and Force Perception

I lead the development of an RGB-NIR vision-tactile sensing system spanning
sensor design and fabrication, automated calibration, surface-normal
estimation, boundary-prior depth reconstruction, marker displacement recovery,
and position-aware three-axis force estimation.

The system achieves a depth MAE of **0.0415 mm**, a normal-force NMAE of
**2.74%**, and a shear-force NMAE of **2.39%**.

### Neural Inverse Rendering and Synthetic Tactile Data

I co-developed a physics-guided near-field multi-LED illumination model and an
RGB-NIR neural inverse-rendering pipeline for tactile image synthesis. The
pipeline supports transformed contact rendering, automatic OBB annotation, and
few-shot tactile pose estimation.

The rendering method reaches **30.22 dB PSNR**, improving upon the
single-light-source baseline by **6.33 dB**. Models trained with 200 synthetic
samples per class achieve up to **0.995 mAP50-95** in tactile pose estimation.

### High-Speed Tactile Perception

I develop hardware-oriented tactile perception pipelines that connect
surface-normal inference, depth reconstruction, and normal-force estimation on
FPGA platforms.

The computation rates reach **1022 Hz** for image-to-depth
reconstruction and **918 Hz** for image-to-normal-force estimation.

## Publications

1. Yuankai Lin, **Xiaofan Lu**, and Hua Yang,<br>
   **"High-Precision RGB-NIR Vision-Tactile Sensor via Neural Inverse Rendering
   for Robotic Perception."**<br>
   *IEEE/ASME Transactions on Mechatronics*, 2025.<br>
   [Project Page](https://jayvenlu.github.io/smf-psnn-website/) |
   [IEEE Paper](https://doi.org/10.1109/TMECH.2025.3640680)

2. Yuankai Lin, **Xiaofan Lu**, Jiahui Chen, and Hua Yang,<br>
   **"3D Vision-Tactile Reconstruction from Infrared and Visible Images for
   Robotic Fine-Grained Tactile Perception."**<br>
   *IEEE/RSJ International Conference on Intelligent Robots and Systems
   (IROS)*, 2025.<br>
   [Project Page](https://jayvenlu.github.io/gelsplitter3d-website/) |
   [IEEE Paper](https://doi.org/10.1109/IROS60139.2025.11246893)

## Education

- **M.Eng. in Mechanical Engineering**, Huazhong University of Science and
  Technology, 2024-2027
- **B.Eng. in Robotics Engineering**, Huazhong University of Science and
  Technology, 2020-2024

## Skills

- **Sensing:** vision-based tactile sensing, Multispectral imaging, sensor design and
  fabrication, geometric and force calibration
- **Perception:** photometric stereo, surface-normal estimation, 3D
  reconstruction, force estimation, neural inverse rendering, synthetic data
  generation
- **Hardware:** FPGA acceleration, Verilog/SystemVerilog, Vivado, Vitis, XSim
- **Programming:** Python, C/C++, PyTorch, NumPy, OpenCV, Git, Linux
