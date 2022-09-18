---
layout: page
title: Differentially flat based PID controller for Parrot Anafi Drone 
description: Implementation of PID controller for Parrot Anafi Drone ,Integrated with ROS, Opti Track Cameras Capture and Sphinx Simulator
img: assets/img/anafi_pid_flat.gif
importance: 1
category: Modelling/Optimization
---
`Implemented PID controller for Differentially flat based model of droner, for Parrot Anafi drone . The video shows sphinx simulator,gazebo visualization. As there is no ROS support for Anafi drones ,We built and used custom packages to interact with Opti Track Cameras{demo on real drone coming soon} with Anafi python interface and with Sphinx Simulator.` <br/>


-Higher resolution Video is here:
<a href="https://github.com/prajwalthakur/prajwalthakur.github.io/assets/video/anafi_pid_flat.mp4">anafi_demo_on_simulator</a> github_page.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/anafi_pid_flat.gif" title="anafi_pid" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    demo showing Anafi drone flying towards desired goal position.
</div>
