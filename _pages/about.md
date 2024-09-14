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
<title>Clickable Dropdown</title>
<style>
/* 初始化样式 */
.dropdown-content {
    display: none;
    overflow: hidden;
    background-color: #f9f9f9;
    padding: 10px;
}
</style>
</head>
<body>

<h2>Clickable Dropdown</h2>
<p>Click the botten to extend the list</p>

<div>
    <button onclick="toggleDropdown('demo')">Click me to extend / fold</button>
    <div id="demo" class="dropdown-content">
        <p>info1</p>
        <p>info2</p>
        <p>info3</p>
    </div>
</div>

<script>
function toggleDropdown(id) {
    var element = document.getElementById(id);
    if (element.style.display === 'block') {
        element.style.display = 'none';
    } else {
        element.style.display = 'block';
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


