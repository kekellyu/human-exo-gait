# Human–Exoskeleton Gait Synchronization

---

## Repository Structure

This repository contains two core components:

### 🦿 [Human–Exoskeleton Gait Model Integration](https://github.com/kekellyu/human-exo-gait/Leg%20Integration)
- Located in: `./Leg Integration`
- Combines MyoSuite’s `myoleg` musculoskeletal model with a multi-DOF lower-limb exoskeleton
- Uses MuJoCo for biomechanically accurate simulations
- Implements tendon-based coupling and body scaling
- XML and Python scripts for modular generation

### 🤖️ [Human–Exoskeleton Gait Model Control](https://github.com/kekellyu/human-exo-gait/Leg%20Control)
- Located in: `./Leg Control`
- Controls the integrated model using:
  - DEPRL (Differential Extrinsic Plasticity Reinforcement Learning) for the human model
  - DDPC (Data-Driven Predictive Control) for the exoskeleton
- Supports joint synchronization, gait cycle tracking, and natural swing motion generation
- Modified MyoSuite RL environment to accommodate exoskeleton dynamics

---
