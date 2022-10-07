---
layout: page
title: Drone Planning in a map-less Environment
description: Integration of Navigation stack in parrot-bebop drone for 2d planning in a Map - less Environment
img: assets/img/bebop_nav_stack.gif
importance: 1
category: ROS
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bebop_nav_stack.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Parrot-bebop Planning using Navigation Stack in  a Gazebo World .
</div>

I Developed the ROS package for the Course and Drone Competition ( DeltaX) which will be happening at the University of Tartu, Estonia. 
In this Competition, Students are required to program a Parrot Bebop to autonomously navigate and  find a particular Augmented Reality Tag placed in an Arena. 
Students are required to either already Existing Motion Planning Algorithm from Navigation Stack or developed a Motion Planner from their own .

This simulation is replicating the actual Arena equipped with <a href="https://optitrack.com/">OptiTrack </a> . We used OptiTrack System to get the very accurate  drone position and center position of the obstacle .
As it is Easier to use Navigation Stack with Laser data ,  we have to converted the obstacle position to laser datas .
We approximated the shape of the obstacle as a circle , created a circualr point-cloud  of it  and then finally coverted the point cloud data to laser data in a  drone frame . 

Above video shows the final result of drone , planning in 2d plane without pre existing map .

We uses the drone foot frint to plan in 2d , thats why it is also avoiding the objects which are below the drone's  current altitude .
<!-- A detailed tutorial  of how to setup the teb planner in ROS , what parameters usually need to be tuned, and other useful information will be posted at <a href="https://www.skillsmove.eu/">skills.move.eu</a> website. Tutorial link:
`to be posted later , once tutorial gets published at skillsmove.eu` -->