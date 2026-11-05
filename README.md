<!-- Profile README: alyssaserrano -->

<div align="center">

# Alyssa Serrano

### PhD Computational Science · UCI & SDSU

**Resource-aware autonomous systems · Real-time scheduling · Embedded GPU optimization**

<p>
  <a href="https://github.com/alyssaserrano"><img src="https://img.shields.io/badge/GitHub-alyssaserrano-181717?style=flat&logo=github&logoColor=white" alt="GitHub profile" /></a>
  <a href="mailto:alyssaserrano@acm.org"><img src="https://img.shields.io/badge/Email-alyssaserrano%40acm.org-BD351A?style=flat&logo=gmail&logoColor=white" alt="Email Alyssa" /></a>
  <a href="https://www.acm.org/"><img src="https://img.shields.io/badge/Member-ACM-0085CA?style=flat" alt="Association for Computing Machinery member" /></a>
  <a href="https://www.siam.org/"><img src="https://img.shields.io/badge/Member-SIAM-6B2D5C?style=flat" alt="Society for Industrial and Applied Mathematics member" /></a>
  <a href="https://brdsdsu.github.io/"><img src="https://img.shields.io/badge/Lab-Computer%20Systems%20Intelligence-5C2D91?style=flat" alt="Computer Systems Intelligence Lab" /></a>
</p>

</div>

## About me

I am a joint PhD student in Computational Science at the **University of California, Irvine** and **San Diego State University**, working as a Graduate Research Assistant in the [Computer Systems Intelligence Lab](https://brdsdsu.github.io/). I am also a proud member of the **Association for Computing Machinery (ACM)** and the **Society for Industrial and Applied Mathematics (SIAM)**.

My work focuses on making autonomous and robotics workloads more **predictable, efficient, and reproducible** on embedded platforms. I enjoy finding the performance trade-offs that matter—from GPU memory pressure and kernel concurrency to latency variance and storage throughput—and turning those findings into practical systems improvements.

## Research focus

- **Predictable GPU inference:** SM-aware scheduling, isolation, CUDA Green Contexts, and concurrent CNN execution
- **Embedded autonomy:** profiling and optimization for transformer-based navigation and real-time computer vision
- **Systems benchmarking:** reproducible experiments with containers, cgroup-v2, fio, ROS, and performance profilers
- **Edge computing:** resource-aware scheduling and reliable data handling for autonomous systems

## Highlights

<table>
  <tr>
    <td align="center"><strong>49.7%</strong><br />lower maximum reserved GPU memory</td>
    <td align="center"><strong>34%</strong><br />average camera-input-utilization improvement</td>
    <td align="center"><strong>355.35</strong><br />mean score on Atari Breakout</td>
  </tr>
</table>

## Selected work

### NVIDIA SM-Aware Edge GPU Scheduling

Designing offline scheduling models and implementing SM-partitioning approaches for concurrent neural-network inference workloads using **C/C++, CUDA, libsmctrl, CUDA Green Contexts, TensorRT, ONNX, and Nsight**.

### Transformer-Based Navigation on Embedded Devices

Optimized a transformer-based computer-vision reinforcement-learning agent for edge devices, reducing maximum reserved GPU memory by **49.7%** and maximum allocated GPU memory by **11.6%** while validating behavior in ROS Noetic and Gazebo.

### SPEED: Predictable Data Handling for Autonomous Systems

Benchmarked a scalable data-handling approach against MCAP using cgroup-v2 and fio, achieving a **34% average camera-input-utilization improvement** in the experimental environment. Experiments were containerized with Docker and ROS 2 Humble rosbag.

### [CARLA Lane Detection Scenarios](https://github.com/alyssaserrano/carla_api)

Created obstruction scenarios and camera-input manipulations in the CARLA simulator to support more realistic evaluation of autonomous-vehicle vision systems.

### [Double DQN — Atari Breakout](https://github.com/alyssaserrano/DQN-Atari-Breakout)

Built a PyTorch Double DQN agent with experience replay, target networks, frame stacking, Huber loss, and epsilon-greedy exploration. The final model achieved a **355.35 mean score** after approximately 200 million frames.

## Personal homelab

Outside of research, my personal hobby is **self-hosted infrastructure**. I build and maintain a Linux-based homelab with **Proxmox virtualization, virtual machines, containers, Docker, networking, storage, backups, and smart-home automation**. It is my hands-on playground for Linux administration, reliable service management, systems troubleshooting, and integrating hardware with software.

## Teaching

I support computer science students through teaching, office hours, code reviews, debugging, and project planning in:

- **Operating systems:** processes, threads, synchronization, memory management, scheduling, and file systems
- **Intermediate Java programming:** object-oriented programming, software practices, and debugging
- **Capstone development:** workflows, industry standards, code quality, and team project execution

## Toolkit

<p align="center">
  <img src="https://img.shields.io/badge/C-C0A000?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" alt="Proxmox" />
</p>

**Also:** PyTorch · TensorRT · ONNX · Hugging Face · ROS 2 · Gazebo · CARLA · Bash · Make · GitHub Actions · Nsight Compute/Systems · fio · cgroup-v2 · AWS

## Education

- **Joint PhD in Computational Science**, University of California, Irvine × San Diego State University — *2026–present*
- **B.S. in Computer Science**, San Diego State University — *2025, Summa Cum Laude*
- **A.S. in Computer Science**, Grossmont Community College — *2023, Honors*
- **A.S. in University Studies: Mathematics, Natural Sciences, and Computer Science**, Grossmont Community College — *Honors*

## Posters & funding

- **PRINCE: Predictable Inference Latency using CUDA Green Contexts** — SDSU S3 Student Symposium, 2026
- **Transformer-Based Navigation on Embedded Devices** — SDSU S3 Student Symposium, 2025
- SDSU Graduate Research Funding
- SDSU Undergraduate Research Program Fellowship

<div align="center">

### Building systems that are fast, predictable, and reproducible.

</div>
