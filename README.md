# 3DGS-Unity-URP-Integration
3D Gaussian Splatting rendering pipeline integrated into Unity URP via Compute Shaders for real-time spatial visualization
# 3D Gaussian Splatting (3DGS) Pipeline in Unity URP

[![Unity](https://img.shields.io/badge/Unity-2022.3_LTS-black?style=flat-square&logo=unity)](https://unity.com/)
[![C++ / Compute Shaders](https://img.shields.io/badge/Architecture-C++_%2F_HLSL-blue?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-PC_VR_Deployed-success?style=flat-square)](#)

## Real-time Rendering Demo
![Demo](demo.gif)

## Project Overview
This repository demonstrates the architectural integration of a cutting-edge **Neural Rendering pipeline (3D Gaussian Splatting)** into an industry-standard game engine environment. 

Moving beyond traditional polygon meshes, this project successfully deploys hardware-accelerated Compute Shaders within Unity's Universal Render Pipeline (URP) to achieve **photorealistic digital twin visualization** in real-time.

## Core Engineering Contributions
* **Pipeline Integration:** Seamlessly integrated an open-source 3DGS C++/HLSL backend into Unity 2022.3 LTS.
* **Spatial Computing:** Configured high-performance Radix Sort algorithms via Compute Shaders to handle real-time depth sorting of millions of Gaussian splats.
* **Hardware Utilization:** Bypassed traditional CPU bottlenecks, maximizing GPU memory bandwidth for real-time 3D spatial rendering.

## Next Steps (Ongoing R&D)
Currently exploring the optimization of the underlying C++ rendering logic to deploy this pipeline onto standalone mobile VR headsets (Meta Quest architecture), aiming to overcome severe mobile GPU bandwidth limitations.

Attribution & Acknowledgments
Core 3DGS Implementation: This project integrates the highly optimized open-source Unity 3DGS implementation by Aras Pranckevičius (aras-p).

Datasets: Point cloud datasets used for visualization are sourced from the original 3D Gaussian Splatting research publications.

My Focus: My work in this repository centers on environment configuration, pipeline integration within Unity 2022 URP, and exploring deployment strategies for VR hardware.

---
*Developed by Yiheng C. | Computer Science Undergrad @ constructor university
