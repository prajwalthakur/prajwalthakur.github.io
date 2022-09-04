---
layout: page
title: PERCEPTION INFORMED BY NAVIGATION FOR SEARCH AND RESCUE
description: A project jointly developed by IIT-ISM and CAIR LAB DRDO
img: assets/img/cair.png
importance: 5
category: misc
---
`Project developed by Indian Institute of Technology ,Dhnabad India and sponsored by Center for Artificial Intelligence and Robotics Lab, A autonoumus lab under Defence Research and Development Organisation India`
<a href="https://www.drdo.gov.in/labs-and-establishments/centre-artificial-intelligence-robotics-cair">CAIR_LAB</a> website. <br/>

This work presents a time dependent metric for object’s confidence  which closely resembles the  behavior inherit by human for detecting an object ,and its inclusion in the pre implemented detection and   tracking algorithm like SORT[],DEEPSORT[].In contrast to other existed tracking algorithm where temporal information is extracted from sequence of frames to enhance tracking this work uses infromation gathered from tracker and generate the the temporal confidence of an object without affecting the fps of existed tracking algorithms.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cair.png" title="admm" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The improved confidence /build up confidence of object is equivalent to the confidence of the tracker .
From frame 0 to 10 the confidence of tracker is falling as the number of losses is increasing this is analogous to the situation where human first think that a object is “X” with confidence of almost 0.5 then next moment is he/she think that object is another object “Y” due to the unabilty to track the object movement in low lighting condition or because of other reason.
From frame 10 to 25 tracker confidence starts rising as hits is increasing this is analogus to the situation where a human starts to identify an object to be “X” continuously but with low confidence may be due to lighting condition or due to any other factors and after continuous gazing he is able to identify the object with almost 100% of confidence.

</div>

Task has been successfully completed by implementing the 
proposed formula in different situations and getting the desired result.

• software prerequisites

• Python 3
• Open CV
For GPU compatibility
• CUDA and CUDNN
• darknet
<br/>
## My Contribution  <br/>
Helping in Developent of Algorithm with Dr Mrinal Sen
studied Kalman filter, Deep sort based tracking Algorithms and modified them as per our needs
Modified the Script to as per the requirements of DRDO and run it on NVIDIA-JETSON-TX2 for further research in real time computation by drones
<br/>
## Project In Charge Professor <br/>
Dr Mrinal Sen of IIT-ISM Dhanbad,India
