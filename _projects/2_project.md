---
layout: page
title: Path planning for point mass in a constraint Environment using Alternating direction method of multipliers (ADMM) algorithm 
description: This project focused on how to use ADMM method to use path planning within environment having spherical shaped obstacles
img: assets/img/admm.png
importance: 1
category: Modelling/Optimization
---
In this project I have used ADMM algorithm to solve path planning problem in constrained envrionment. I have used python and jax to accelated performance in loop.
Used jax library for faster optimization over a batch <br/>
github library : <a href="https://github.com/prajwalthakur/admm_obstacle_avoidance">github_admm</a> website.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/admm.png" title="admm" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    3d trajectory plot showing initial straight guess trajectory (green) and final trajectory (red) found by ADMM optimizer .
</div>


