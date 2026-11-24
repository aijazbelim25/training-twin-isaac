# From Digital Twin to Training Twin: A USD-Centric Reference Architecture for Closed-Loop Sim-to-Real Robot Development with NVIDIA Isaac Sim and Isaac Lab

**Author:** Aijaz Belim  
**Institution:** Indian Institute of Technology Madras (IIT Madras)  
**Preprint:** [From_Digital_Twin_to_Training_Twin.pdf](From_Digital_Twin_to_Training_Twin.pdf)

---

## Abstract
Digital twins and robot-learning simulators have developed as largely separate literatures. Digital-twin research, rooted in manufacturing and aerospace, is concerned with mirroring a specific physical asset, keeping the virtual and physical states synchronised, and using that correspondence to predict behaviour and support decisions. Robot-learning research, by contrast, treats simulation as a disposable training ground: massively parallel, deliberately varied, and valuable precisely because it does not have to match one particular machine.

This paper argues that the two views are complementary and that modern GPU-accelerated simulation stacks make their convergence practical. Using NVIDIA Isaac Sim and Isaac Lab as the reference platform, we:
1. Map the components of the Isaac stack onto the established Digital Model / Digital Shadow / Digital Twin classification.
2. Synthesise the evidence that policies trained inside such environments can transfer to physical robots (domain randomisation, dynamics randomisation, and deployment-time adaptation).
3. Propose a five-layer, USD-centric reference architecture for a **training twin** — a digital twin whose primary function is to produce, validate, and continuously improve robot policies — together with five validation gates (G1–G5) that must be passed before a twin-trained policy is deployed to hardware.

---

## Paper Link
- **Full Manuscript (PDF):** [View Manuscript](./From_Digital_Twin_to_Training_Twin.pdf)

## Keywords
`digital twin`, `sim-to-real transfer`, `NVIDIA Isaac Sim`, `Isaac Lab`, `NVIDIA Omniverse`, `OpenUSD`, `domain randomisation`, `robot learning`, `reference architecture`, `ROS 2`
