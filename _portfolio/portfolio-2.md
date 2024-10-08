---
title: "The 20th China University Robot Competition (Robocon), Second Prize"
excerpt: "The 20th China University Robot Competition (Robocon), Second Prize <br/><img src='/images/20thRobocon/20thRobocon.png'>"
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
<span>Sep 2020 - Jul 2021</span>
</div>
<p><strong>Key words:</strong> Robot design & control; computer vision</p>

## About the 20th Robocon Competition
The China University Robot Competition (Robocon), launched in 2002, is an annual event where the winning team represents China in the Asia-Pacific Robot Contest (ABU ROBOCON). It is considered the most technically challenging and influential university robot competition in China.

In the 20th competition (held in July 2021), teams were given ten months (Sep 2020 - July 2021) to design and build two robots. The competition required teams to designate one robot to shoot arrows into target barrels to score points, while the other robot could interfere with the opponent's scoring. The team with the highest score at the end of the time was declared the winner.
<div align="center">
    <img src="/images/20thRobocon/20thRobocon.png" alt="The shooter robot" width="60%">
    <p>The shooter robot</p>
</div>

<div align="center">
    <img src="/images/20thRobocon/DefenderRobot.png" alt="The defender robot" width="60%">
    <p>The defender robot</p>
</div>


## My Role and Contributions in the Team
### Designed Robot Vision Algorithm
Since the competition required robots to shoot arrows into target barrels, the robot's vision task was to identify these target barrels on the field. Due to the limited computational power of the host computer, I decided to design a fast recognition algorithm based on simple features. The algorithm extracted the color and shape of the target barrels as features and used a rule-based method for classification to achieve recognition. To handle occlusion, I utilized the known field map and location data collected from the robot’s chassis, combined with camera parameters, to estimate the target position. I also designed a memory bank to leverage temporal information of target positions to further improve accuracy. Additionally, I employed the HSV color space instead of the RGB space to reduce the impact of ambient light variations. The final experimental results showed that this simple recognition algorithm achieved high accuracy without the need for complex AI models, and it provided better real-time performance.


### Robot Control with Microcontroller
Before joining the vision group to design the robot's vision algorithm, I was involved in the debugging of the robot's chassis, more specifically, controling  the four DJI 3508 motors on the robot's chassis. This work used data collected from encoders to determine the robot's position on the field. Based on the positional information, I also worked on controlling the robot to move along the planned trajectory.

<div align="center">
    <img src="/images/20thRobocon/20thTeam.png" alt="The shooter robot" width="80%">
    <p>Photo of all our Robocon team members<br> (I'm in the second row, first from the left)</p>
</div>


