# IndustReal reproduction

This repository contains Rucha Agashe and my work to reproduce NVIDIA's 
IndustReal in NVIDIA Isaac Sim. The goal of this side-project is to gain 
hands-on experience with reinforcement learning for peg-in-hole insertion
in Isaac Sim.

This repo is a part of our wider **startup project** 
[Matrix Lab](https://github.com/Ice-Citron/Matrix-Lab). Matrix Lab is a 
coverage-driven test tool for determining robot policies' reliability. We are
taking on `IndustReal` as a side project, as we believe we will be in a much
better state to continue developing Matrix Lab after gaining more hands-on
experience with Reinforcement Learning in Isaac Sim. Because we never managed
to get RL to properly work in our previous big robotics project 
[Project Automaton: Quantarune](https://github.com/Ice-Citron/Project-Automaton__Quantarune__/tree/main/quantarune).

We will continue improve upon Matrix Lab as our IndustReal reproduction 
continues, and the policies trained in this project will be evaluated with 
Matrix Lab.

## The paper

[IndustReal: Transferring Contact-Rich Assembly Tasks from Simulation to Reality](https://arxiv.org/abs/2305.17110)
(Tang et al., RSS 2023). It trains assembly policies with RL in simulation and runs them on a real Franka arm.

The authors' own release:

- [IndustRealSim](https://github.com/NVIDIA-Omniverse/IsaacGymEnvs/tree/main/isaacgymenvs/tasks/industreal): simulation environments and training code
- [IndustRealLib](https://github.com/NVLabs/industreallib): deployment on a real Franka
- [IndustRealKit](https://github.com/NVlabs/industrealkit): CAD models of the parts
