---
title: "Deictic Image Maps: An Abstraction For Learning Pose Invariant Manipulation Policies"
date: 2020-07-20
---
**Abstract:**  In applications of deep reinforcement learning to robotics, it is often the case that we want 
to learn pose invariant policies: policies that are invariant to changes in the position and orientation of 
objects in the world. For example, consider a peg-in-hole insertion task. If the agent learns to insert a peg
into one hole, we would like that policy to generalize to holes presented in different poses. Unfortunately, 
this is a challenge using conventional methods. This paper proposes a novel state and action abstraction that 
is invariant to pose shifts called *deictic image maps* that can be used with deep reinforcement learning. 
We provide broad conditions under which optimal abstract policies are optimal for the underlying system. 
Finally, we show that the method can help solve challenging robotic manipulation problems. 