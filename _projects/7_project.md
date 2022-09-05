---
layout: page
title: LINEAR MODEL PREDICTIVE ALTITUDE CONTROLLER FOR HYBRID Vertical Takeoff and Landing Aircraft
description: This project focused on designing non linear mpc control for altitude control of VTOL aircraft in python
img: assets/img/vtol_python.gif
importance: 3
category: Modelling/Optimization
---
` THIS PROJECT IS A SMALL PART OF A RESEARCH PROJECT THAT I HAVE WORKED AT IIIT HYDERABAD,INDIA`
<a href="https://www.iiit.ac.in/">IIIT_HYD</a> website. <br/>

In this project I have desinged an linear mpc controller for altitude controller for hybrid vtol ,using an optimization library known as CASADi in python .<br/>
A detailed description can be found in my bachelor's final year project pdf (chapter3 ) <br/> 
pdf link:<br/>
<a href="/assets/pdf/Bachelor_Thesis.pdf">Bachelor_thesis</a> <br/>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vtol_python.gif" title="vtol_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    demo showing vtol model flying to get to a desired height
</div>



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mpc_vtol_state.png" title="vtol_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Linear state space model of vtol in a fixed wing mode
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/casadi_mpc.png" title="vtol_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   formulating minimization problem in CASADI that has been used in this project with quadratic cost
</div>
