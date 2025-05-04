🚗 Robust Optimal Platoon Control Using Model-Free Reinforcement Learning

This project presents a novel robust optimal control strategy for heterogeneous vehicle platoons under unknown dynamics and disturbances.
Traditional reinforcement learning (RL) algorithm often require full knowledge of vehicle dynamics, but this work proposes an adaptive, off-policy, model-free RL algorithm that learns both optimal control inputs and disturbance compensation policies directly from input-output system data, without requiring vehicle dynamic models.



The following video demonstrates the effectiveness of RL-based platooning control on traffic flow stability.
The first part shows a platoon without control, where vehicles decelerate and accelerate alternately, leading to traffic oscillations and stop-and-go phenomena. This instability increases travel time, energy     consumption, and the risk of collisions. 
The second part presents the same platoon under the proposed RL-based cooperative control strategy, where vehicles proactively synchronize their speeds while maintaining a smooth and safe distance. 
Traffic oscillations are significantly attenuated, resulting in smoother traffic flow and enhanced safety and efficiency.

https://github.com/user-attachments/assets/6fdd78e2-16d0-4764-b6d8-9d70b0b982a4
    
Key contributions:

    Distributed Control: Each vehicle uses only local and neighboring information for cooperative decision and control .

    Optimality and Robustness: Solves a distributed Hamilton–Jacobi–Bellman (HJB) equation to minimize tracking errors and attenuate disturbances.

    Model-Free RL: A fully data-driven, online learning method that identifies optimal policies to compensates the effects of unknown dynamics and disturbances.
    
    The virtual testing demonstrates the system’s effectiveness to maintain safe distances and speed tracking among multiple vehicles with parameter uncertainties and external disturbances.

    Keywords: Platooning, Model-Free Reinforcement Learning, Distributed Control, Robust Optimal Control, HJB Equation, Autonomous Vehicles


https://github.com/user-attachments/assets/e4c04bbc-fb1c-4890-acc7-c5a0fc5d9fbf


