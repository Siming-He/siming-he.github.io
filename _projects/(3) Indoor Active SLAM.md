---
name: Active Simultaneous Localization and Mapping in Unstructured Environment with a Quadrotor 
tools: [Robotics, SLAM]
description: This paper proposes an active SLAM system that allows an agent to explore its surroundings efficiently based on information theoretic criterion.
# external_url: https://repository.upenn.edu/spur/41/
---

# Active Simultaneous Localization and Mapping in Unstructured Environment with a Quadrotor 

{% include elements/button.html link=" https://repository.upenn.edu/handle/20.500.14332/47436" text="Paper" %}

<b>Abstract: </b> An agent performing Simultaneous Localization and Mapping (SLAM) constructs a map of the environment while estimating its location at the same time. SLAM algorithms primarily focus on finding the best estimate of the location of the agent, and by extension, that of the landmarks in the environment, given observations from sensors. These algorithms do not typically address how an agent should explore an unknown environment to build a map efficiently. This ability for active exploration is important for autonomous robots to work in unknown, unstructured environments such as forests or caves. This paper proposes an active SLAM system that allows an agent to explore its surroundings, using visual-inertial data from an RGBD camera. We formalize this problem as taking actions that maximize the amount of information obtained from the scene. At each time step, a utility function that computes the incremental information gain is used to take actions. We conduct experiments using an Intel RealSense camera mounted on a custom-built quadrotor and show that we can explore indoor environments (while restricting the actions to choosing new viewpoints in SO(3) for practical reasons).<br>

<iframe width="640" height="360" src="https://youtube.com/embed/M68yx2p-jQo" frameborder="0" allowfullscreen></iframe>
