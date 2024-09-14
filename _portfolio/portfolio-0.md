---
title: "Safe motion planning for multi-vehicle autonomous driving in uncertain environments"
excerpt: "First Author; Paper submitted to RAL on 15 August <br/><img src='/images/21stRobocon.png'>"
collection: portfolio
---
## Problem to Solve
This academic research was conducted during my master's studies (August 2023 - August 2024) under the supervision of Professor Shuzhi Sam Ge. The focus of the research is on motion planning for multi-agent systems, considering uncertainty in position. This uncertainty can arise from sensor noise and inaccuracies in data transmission. In addition to the uncertainty, computational burden is a significant challenge, particularly in large-scale problems, and the presence of uncertainty further increases the computational load.


## Brief Introduction & Contribution
To reduce the computational load in multi-agent motion planning, we focus on the ADMM method, which is commonly used to speed up processes in computer vision. We develop a motion planning framework for multi-vehicle systems, considering noise in vehicle dynamics and uncertainty in the positions of nearby vehicles. Using the ADMM framework and iLQG algorithm, we solve optimization problems with nonlinear dynamic constraints and improve how collision constraints are handled. Additionally, we introduce the ADMM-based Linearized Chance Constraint (ALCC) method to overcome non-convexity issues in chance constraints, which helps reduce the computation required, especially in large-scale problems.

Key contribution:
- We introduce a new framework that improves multi-agent motion planning by considering noise and uncertainty, making the planner more robust in real-world situations.
- The ALCC method we propose solves the challenges iLQG faces with collision constraints and reduces computation, particularly for large problems.
- Through Carla simulation experiments, our method ensures vehicle safety in noisy and uncertain environments, while being more efficient than other methods.

## Experience
Here we present some experimental results. The experiments were simulated in Carla, where all vehicles used the ALCC algorithm for motion planning. As shown, the vehicles successfully navigate through the intersection without interfering with each other.



More details about the methods and experiments will be updated when the paper is published ...
