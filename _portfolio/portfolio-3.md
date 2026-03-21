---
title: "Dual-Quadruped Collaborative Transportation in Narrow Environments via Safe Reinforcement Learning"
excerpt: "First Author; <img src='/images/dual-quad/illustration3.jpg'>"
collection: portfolio
---
<head>
    <style>
        .logo-container {
          display: inline-flex; /* 使用flex布局，使logo和文字保持在同一行 */
          align-items: center; /* 确保logo与文字垂直居中对齐 */
        }
        .logo {
          width: 20px; /* 控制 logo 的宽度，根据需要调整大小 */
          height: auto;
          margin-right: 8px; /* 控制 logo 和文字之间的间距 */
          vertical-align: middle;
        }
    </style>
</head>

<div class="logo-container">
<img src="/images/calendar.png" alt="Date Icon" class="logo">
<span>Jan 2025 - Nov 2025</span>
</div>
<p>Publication: Under review at a journal in robotics [(Arxiv preprint link)](https://arxiv.org/abs/2602.16353)</p>
<p>Authors: <strong>Zhezhi Lei</strong>, Zhihai Bi, Wenxin Wang and Jun Ma</p>
<p><strong>Key words:</strong> Multi-Robot Systems; Legged Robots; Reinforcement Learning</p>

## Problem to Solve
This work focuses on collaborative transportation with dual quadruped robots in narrow environments, where robots must coordinate tightly while avoiding collisions. The task is challenging due to strong coupling between agents, shared safety constraints, and instability in decentralized multi-agent learning, making it difficult to achieve both safety and efficient cooperation.

## Brief Introduction & Contribution
To tackle these challenges, we propose a safe reinforcement learning framework that formulates the task as a fully cooperative constrained Markov game, aiming to maximize team reward while satisfying a global safety constraint. The key idea is to transform the difficult problem of shared constraints into tractable individual learning problems. The method introduces a cost–advantage decomposition to stabilize learning under shared constraints, and a constraint allocation mechanism to distribute safety budgets among robots, enabling adaptive and implicit role coordination. Combined with trust-region optimization and Lagrangian methods, the framework ensures both safe and high-performance collaboration.

Key contribution:
- We propose a novel decentralized framework for dual-quadruped collaborative transportation in narrow environments, enabling robots to safely and efficiently transport a payload while improving inter-robot coordination.
- We introduce a trust-region-based cost–advantage decomposition method that incorporates safety constraints directly into the learning process, ensuring stable policy updates and consistent safety guarantees during training.
- We develop a constraint allocation mechanism that distributes shared constraint budgets among robots, encouraging autonomous task assignment and improving collaborative performance through implicit coordination.
- We validate the proposed approach through both real-world experiments, demonstrating superior task performance and safety compared to existing methods.

## Experiments
Experiments demonstrate that our approach achieves higher success rates, lower collision rates, and more efficient trajectories compared to existing methods. The robot team can adaptively adjust formation and maintain stable coordination in complex, constrained environments.

<div align="center">
    <img src="/images/dual-quad/gate.gif" alt="gate" width="80%">
    <p>Fig.1. Gate Scenario</p>
</div>
