---
title: "The 21st China University Robot Competition (Robocon), First Prize (5th)"
excerpt: "Robot Control - Computer Vision - Leader of Visual Group <br/><img src='/images/21stRobocon/21stRobocon.png'>"
collection: portfolio
---
## About the 21st Robocon Competition
The China University Robot Competition (Robocon), launched in 2002, is an annual event where the winning team represents China in the Asia-Pacific Robot Contest (ABU ROBOCON). It is considered the most technically challenging and influential university robot competition in China.

In the 21st competition (held in July 2022), teams were given ten months (Sep 2021 - July 2022) to design and build two robots. The challenge required the robots to knock down and then rebuild two block towers within a specified time. The team that rebuilt the towers more perfectly (with the centers of the blocks fully aligned) and in the shortest time was declared the winner.

The following video shows our competition. If the video on the webpage doesn't play properly, please try [this link](https://www.bilibili.com/video/BV13r4y1L77y?p=3&vd_source=870fbef53255ad18abea405aa3264d46). (Highlighted key moments in the video: 00:10 - competition starts; 01:00 - building the first tower; 01:45 - building the second tower; 02:25 - game finishs).
<style>
    .responsive-iframe-container {
        position: relative;
        width: 100%;        /* 容器宽度为100% */
        height: 0;
        padding-bottom: 56.25%; /* 保持16:9的宽高比 */
    }
    .responsive-iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>

<div class="responsive-iframe-container">
    <iframe class="responsive-iframe" src="//player.bilibili.com/player.html?isOutside=true&aid=813863581&bvid=BV1XG4y1i7oG&cid=783836404&p=1" frameborder="0" scrolling="no" allowfullscreen="true"></iframe>
</div>

<div align="center">

<img src="/images/21stRobocon/ShooterRobot.png" alt="The "shooter" robot" width="80%"/>

<img src="/images/21stRobocon/BuilderRobot.png" alt="The "builder" robot" width="80%"/>

# <p>图1. 图片说明文字</p>

</div>

## My Role and Contributions in the Team
### Leader of Robot Vision Group
I was the leader of the robot's vision group, primarily responsible for designing the robot's vision system and implementing vision-assisted object recognition functionality. The recognition algorithm utilized the target's color and shape as features, and Support Vector Machine (SVM) was employed for classification to achieve detection. The final tests showed that both the accuracy and real-time performance met the design requirements. Unfortunately, although the object recognition tasks were completed, the vision-based recognition solution was not used in the final robot due to weight constraints, as the competition imposed strict limits on the robot's weight.

### Participated in Robot Function Design
During the robot design phase, our team focused on developing specific functionalities tailored to the robot's tasks. Many great design ideas were proposed and implemented during this process. My suggestions primarily focused on components related to the robot's vision system, such as the requirements for camera installation and positioning. I also contributed my thoughts during discussions on other functionalities.

### Helped with Robot Debugging
In the early stages of preparation, I participated in the debugging of the robot's vision-related systems, such as serial communication between the host computer and the robot, and the adjustment of the automatic pan-tilt for the fixed camera. Although my vision solution was not implemented in the final robot due to weight constraints, I remained actively involved in the testing of other control systems, including the robot's launching mechanism. Our final success was a result of the collaboration and hard work of all team members.