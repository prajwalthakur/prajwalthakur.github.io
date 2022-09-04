---
layout: page
title: Learning based model predictive Controller (LB MPC) for Altitude Control of VTOL aircraft
description: Proposed a DDPG based LBMPC controller to learn the weights in a mpc cost formulation
img: assets/img/lbmpc_cover.png
importance: 1
category: RL/ML
---
`Bachelors final year project ` <br/>


A detailed description can be found in my bachelor's final year project pdf (chapter4) <br/> 
pdf link:<br/>
<a href="/assets/pdf/Bachelor_Thesis.pdf">Bachelor_thesis</a> <br/>





<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lbmpc_thesis.png" title="vtol_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Naive ddpg based lbmpc controller 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lbmpc_avg_reward.png" title="vtol_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    avg reward per episode vs iteration 
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lbmpc_first.png" title="vtol_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Aircraft was able to reach 103m  ,-2m less than desired height
</div>

After 1000 iteration we can see increase in the avg reward per episode  from 0.48 to 0.62 , and thus algorithm was able to learn some better weights 
for mpc . We can see in below fig the aircraft can now reach to 104.5m ,1m less than the desired height
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lbmpc_learned.png" title="vtol_model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Aircraft was able to reach 104.5m  ,0.5m less than desired height
</div>
