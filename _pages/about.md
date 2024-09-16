---
permalink: /
title: "Hi there, welcome to my homepage!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# <a id="Home"></a> About Me
My name is Zhezhi Lei. I am currently persuing my M.S. degree in Computer Engineering at National University of Singapore (NUS), with an expected graduation in December 2024. During my master's studies, I am a member of Control & Simulation Lab, supervised by [Professor Shuzhi Sam Ge](https://cde.nus.edu.sg/ece/staff/ge-shuzhi-sam/), where I conducted research on motion planning with uncertainty in multi-agent systems. Before coming to NUS, I received my B.E. degree in Robotics Engineering from Harbin Engineering University, China.

Currently, I am working on an NUS student research project at Singapore Institute of Manufacturing Technology (SimTech) at the Agency for Science, Technology and Research ([A*STAR](https://www.a-star.edu.sg/)), where I collaborate with [Dr. Haiyue Zhu](https://scholar.google.com/citations?hl=en&user=uO_R9wQAAAAJ) on projects focusing on object detection in robot grasping.

My research instreset focus on robotics control, multi-agent and computer vision. 

# Recent Work 
(Update in September 2024)
- **In progress**: Object pose detection in robot grasping in the context of stacked workpieces (Supervised by Dr. Haiyue Zhu). Planned for submission to IROS.
- **Under review**: Safe motion planning for multi-vehicle autonomous driving in uncertain environments. Submitted to IEEE Robotics and Automation Letters (RAL) on 15 August 2024 (Supervised by Prof. Shuzhi Sam Ge).

# <a id="Experience"></a> Education & Experience

<head>
    <style>
        .education-block {
            margin-top: 20px; /* 上边距 */
            margin-bottom: 25px; /* 下边距 */
        }
        .extra-space {
            margin-top: 30px; /* 根据需要调整这个数值来增加间距 */
        }
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
        details {
            margin-top: -17px; /* 控制details元素上方的间距 */
            margin-bottom: 16px; /* 控制details元素下方的间距 */
            margin-left: 20px;
        }
        details details { /* 为嵌套的details设置样式，以区别于一级details */
            margin-left: 20px;
            /*margin-top: 10px;*/
        }
    </style>
</head>

<div class="education-block">
  <div class="logo-container">
      <img src="/images/favicon.png" alt="NUS Logo" class="logo">
      <span><strong>National University of Singapore, 2023 - Present</strong></span>
  </div>
  <p>M.S. in Computer Engineering | GPA: 4.56/5 | <a href="/files/NUS_Transcript.pdf">View Transcript</a></p>


  <details>
    <summary>Experience details </summary>
    <p><strong>Experience during master's studies:</strong></p>
    <details>
      <summary>2024 - Present. Visitor at Singapore Institute of Manufacturing Technology (SimTech), supervised by Dr. Haiyue Zhu</summary>
      <ul>
        <li>Conducted research on robot grasping, with a focus on object detection in complex environments.</li>
        <li>Currently in the experimental phase, with ongoing work to refine detection models and techniques.</li>
      </ul>
    </details>
    <details>
      <summary>2023 - Present. Member of Control & Simulation Lab, supervised by Prof. Shuzhi Sam Ge</summary>
      <ul>
        <li>Researched multi-agent motion planning problems under uncertainty.</li>
        <li>Developed a novel ADMM-based method, which demonstrated higher computational efficiency compared to existing methods.</li>
        <li>Submitted related work to IEEE Robotics and Automation Letters (RAL) as the first author.</li>
      </ul>
    </details>
  </details>


  <div class="logo-container">
      <img src="/images/favicon.png" alt="Harbin Engineering University Logo" class="logo">
      <span><strong>Harbin Engineering University, 2019 - 2023</strong></span>
  </div>
  <p>B.E. in Robotics Engineering | GPA: 89/100 | <a href="/files/HEU_Transcript.pdf">View Transcript</a></p>

  <details>
    <summary>Experience details </summary>
    <p><strong>Experience during undergraduate studies:</strong></p>
    <details>
      <summary>2021 - 2022. Lead of the Robot Vision Group, Harbin Engineering University Robotics Club</summary>
      <ul>
        <li>Led the development of the robot vision strategy and coordinated team efforts in implementing the design.</li>
        <li>Spearheaded robot perception systems, focusing on target recognition and inspection tasks.</li>
        <li>Awarded First Prize (5th overall) at the 21st China University Robot Competition (ROBOCON).</li>
      </ul>
    </details>
    <details>
      <summary>2020 - 2021. Member of Harbin Engineering University Robotics Club</summary>
      <ul>
        <li>Developed algorithms for robot target detection and tracking.</li>
        <li>Assisted in robot control implementation using microcontroller-based systems.</li>
        <li>Awarded Second Prize at the 20th China University Robot Competition (ROBOCON).</li>
      </ul>
    </details>
  </details>
</div>



# <a id="Project"></a> Highlighted Projects
{% include base_path %}
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

# More Projects

# <a id="Contact"></a> Contact
Email: lei_zhezhi@u.nus.edu

