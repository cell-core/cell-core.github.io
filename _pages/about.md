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

# Research Intreset
My research instreset focus on robotics control, multi-agent and robot detection. 

# Recent Work 
(Update in September 2024)
- **In progress**: Object pose detection in robot grasping in the context of stacked workpieces (Supervised by Dr. Haiyue Zhu). Planned for submission to IROS.
- **Awaiting feedback**: Safe motion planning for multi-vehicle autonomous driving in uncertain environments. Submitted to IEEE Robotics and Automation Letters (RAL) on 15 August 2024 (Supervised by Prof. Shuzhi Sam Ge).

# <a id="Experience"></a> Education & Experience
<head>
<style>
.details {
    overflow: hidden;
    background-color: #f1f1f1;
    padding: 0 10px;
    max-height: 0;
    transition: max-height 0.5s ease-out; /* 使用max-height和过渡效果实现滑动效果 */
}
.summary {
    background-color: #e9e9e9;
    padding: 10px;
    margin-top: 5px;
}
</style>
</head>
<body>

<h2>Education Background</h2>
<div class="summary">
    <strong>M.S. School:</strong> National University of Singapore<br>
    <strong>Major:</strong> Computer Engineering<br>
    <strong>Time:</strong> August 2023 - December 2024 (expected)<br>
    <strong>GPA:</strong> 4.55/5
</div>
<button onclick="toggleDetails('educationDetails')">View More/Less</button>
<div id="educationDetails" class="details">
    <p><strong>Detailed Experience:</strong></p>
    <ul>
        <li>Participated in advanced robotics research projects focusing on AI applications.</li>
        <li>Developed software for autonomous drones as part of a capstone project.</li>
        <li>Contributed to open-source projects relevant to real-time data processing.</li>
    </ul>
</div>

<script>
function toggleDetails(id) {
    var element = document.getElementById(id);
    if (element.style.maxHeight && element.style.maxHeight !== '0px') {
        element.style.maxHeight = '0';
    } else {
        element.style.maxHeight = element.scrollHeight + 'px'; // 设置为实际高度以实现展开
    }
}
</script>

</body>

# <a id="Project"></a> Project
## Highlighted Projects
{% include base_path %}
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
## More Projects

# <a id="Contact"></a> Contact


