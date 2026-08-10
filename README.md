# Hi, I'm Siyuan Luo 👋

**Robot Learning · VLA / World-Action Models · MSE @ University of Melbourne**

I build end-to-end embodied AI systems — from robot data collection and
VLA fine-tuning to distributed training, policy serving, and real-robot deployment.

## 🔭 Currently

- 🤖 **Algorithm Intern @ Xiong'an Institute of Artificial Intelligence**  
  Extending FastWAM to whole-body loco-manipulation on Unitree G1.

- 🎓 **Master of Software Engineering @ University of Melbourne**  
  Graduating Dec 2026, supervised by **Dr. Ting Dang**.

- 🔬 **Audio continual learning research**  
  Developing Audio-L3A, an efficient closed-form learner for AudioSet class-incremental learning.

## 🚀 Selected Work

### π₀.₅ on Franka — Flexible Manipulation

`OpenPI` · `JAX / PyTorch` · `Flow Matching` · `LeRobot` · `DROID` · `Franka`

- Adapted π₀.₅ to a Franka manipulation setup for dynamic grasping and flexible
  part sorting under randomized object poses.
- Built the complete pipeline from raw demonstrations, forward-kinematics
  conversion and LeRobot v2 packaging to normalization, full fine-tuning,
  policy serving and real-robot execution.
- Collected and quality-checked 100 demonstrations per task using a
  DROID-style teleoperation and multi-camera setup.
- Fine-tuned on 8×A100 GPUs and deployed inference through a WebSocket policy
  server on an RTX 5090 workstation.
- Used LIBERO evaluation as a regression test before deployment to the real robot.

### Whole-Body WAM on Unitree G1

`FastWAM` · `Video DiT + Action DiT` · `Flow Matching` · `DeepSpeed` · `G1 + Wuji`

- Extending a desktop-manipulation WAM into a whole-body loco-manipulation
  policy for Unitree G1.
- Working on 72-D physical action prediction, multi-source robot data
  normalization, missing-modality masks and distributed pretraining.
- Built data-quality and human-review tooling for multi-source robot datasets:
  [WB-WAM Data Reviewer](https://github.com/LUOSYrrrr/WB_WAM_Data_Viewer).

### Audio-L3A — Efficient Audio Class-Incremental Learning

`PyTorch` · `AudioSet` · `CNN14 / PANNs` · `SLURM`

- Designed a frozen-backbone analytic learner with a weighted closed-form
  classifier and per-class threshold calibration.
- Achieved **45.16% mAP** on five-phase AudioSet-50, outperforming LwF by
  **2.65 points** and finishing only **0.71 points** below the offline upper bound.
- Reduced total training time to approximately **1/9** of offline joint training.
- Evaluated five CIL baselines, two backbones and more than 80 automated experiments.

## 🧠 Technical Focus

| Area | Tools and Topics |
|---|---|
| Robot Learning | VLA · WAM · π₀ / π₀.₅ · Flow Matching · Diffusion Policy |
| Robotics | Franka · Unitree G1 · LeRobot · DROID · LIBERO · VR Teleoperation |
| Model Training | JAX · PyTorch · DDP · DeepSpeed · LoRA · A100 |
| Simulation | Isaac Sim / Isaac Lab · MuJoCo |
| Audio ML | Class-Incremental Learning · AudioSet · CNN14 / PANNs |
| Systems | Linux · CUDA · SLURM · WebSocket Policy Serving |

## 📚 Open-Source Notes and Tools

- [**learn_embodied_papers**](https://github.com/LUOSYrrrr/learn_embodied_papers)  
  Interactive notes on VLA, world models, flow matching and continual learning.

- [**openpi**](https://github.com/LUOSYrrrr/openpi)  
  Annotated fork with π₀ / π₀.₅ architecture, inference and data-pipeline walkthroughs.

- [**WB-WAM Data Reviewer**](https://github.com/LUOSYrrrr/WB_WAM_Data_Viewer)  
  Kubernetes-based remote review workbench for multi-source robot datasets.

## 🔗 Find Me

- Technical blog: [luosyrrrr.github.io](https://luosyrrrr.github.io/)
- GitHub: [@LUOSYrrrr](https://github.com/LUOSYrrrr)

## 📊 GitHub Stats

<!-- Keep your existing GitHub stats cards here -->
