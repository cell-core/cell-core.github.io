---
title: "Safe Motion Planning for Multi-Vehicle Autonomous Driving in Uncertain Environment"
excerpt: "First Author; Paper submitted to RAL on 15 August <br/><img src='/images/ACL/ACL.png'>"
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
<span>Sep 2023 - Jul 2024</span>
</div>
<p>Publication: IEEE Robotics and Automation Letters [(Paper)](https://ieeexplore.ieee.org/document/10838711)</p>
<p>Authors: <strong>Zhezhi Lei</strong>, Wenxin Wang, Zicheng Zhu, Jun Ma and Shuzhi Ge</p>
<p><strong>Key words:</strong> Autonomous Driving; Multi-Agent Navigation; Motion Planning</p>

## Problem to Solve
This research focuses on motion planning for multi-agent systems, considering uncertainty in position. This uncertainty can arise from sensor noise and inaccuracies in data transmission. In addition to the uncertainty, computational burden is a significant challenge, particularly in large-scale problems, and the presence of uncertainty further increases the computational load.


## Brief Introduction & Contribution
To reduce the computational load in multi-agent motion planning, we focus on the Alternating Direction Method of Multipliers (ADMM) method, which is commonly used to speed up processes in computer vision. We develop a motion planning framework for multi-vehicle systems, considering noise in vehicle dynamics and uncertainty in the positions of nearby vehicles. Using the ADMM framework and Iterative Linear Quadratic Gaussian algorithm, we solve optimization problems with nonlinear dynamic constraints and improve how collision constraints are handled. Additionally, we introduce the ADMM-based Linearized Chance Constraint (ALCC) method to overcome non-convexity issues in chance constraints, which helps reduce the computation required, especially in large-scale problems.

Key contribution:
- We introduce a new framework that improves multi-agent motion planning by considering noise and uncertainty, making the planner more robust in real-world situations.
- The ALCC method we propose solves the challenges iLQG faces with collision constraints and reduces computation, particularly for large problems.
- Through Carla simulation experiments, our method ensures vehicle safety in noisy and uncertain environments, while being more efficient than other methods.

## Experiments
The experiments were simulated in Carla, where all vehicles used the ALCC algorithm for motion planning. As shown in Figure 1, the vehicles successfully navigate through the intersection without interfering with each other. Figure 2 shows the changes in vehicle trajectories with ADMM iterations.

<div align="center">
    <img src="/images/ACL/result.gif" alt="Result gif" width="80%">
    <p>Fig.1. Carla simulation results for 8 vehicles</p>
</div>

<div align="center">
    <img src="/images/ACL/s2plot_final.eps" alt="traj" width="80%">
    <p>Fig.2. Vehicle trajectories vs. ADMM iterations</p>
</div>

Figure 3 shows the changes in control inputs during vehicle driving, indicating that input constraints are met. Figure 4 shows the changes in algorithm residuals with ADMM iterations. The decreasing residuals indicate that the ADMM algorithm tends to converge.

<div align="center">
    <img src="/images/ACL/result.gif" alt="Result gif" width="80%">
    <p>Fig.3. Variations in steering angle $\delta$ and acceleration $a$</p>
</div>

<div align="center">
    <img src="/images/ACL/s2plot_final.eps" alt="traj" width="80%">
    <p>Fig.4. ADMM prime residuals vs. iteration count</p>
</div>