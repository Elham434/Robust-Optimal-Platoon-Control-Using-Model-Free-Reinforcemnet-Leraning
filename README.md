🚗 Robust Optimal Platoon Control Using Model-Free Reinforcement Learning

This project presents a novel robust optimal control strategy for multi-vehicle platoons under unknown dynamics and disturbances.
Traditional reinforcement learning (RL) methods often depend on explicit vehicle models, but this work proposes a simplified, adaptive, off-policy, model-free RL algorithm that learns both optimal control an d disturbance compensation policies directly from input-output data, without requiring dynamic models.
The following video demonstrates the impact of reinforcement learning (RL)-based platooning control on traffic flow stability.
The first part shows a platoon without control, where vehicles decelerate and accelerate alternately, leading to traffic oscillations and stop-and-go phenomena. This instability increases travel time, energy     consumption, and the risk of collisions. 
The second part presents the same platoon under a reinforcement learning-based cooperative control strategy, where vehicles proactively adjust their speeds to maintain smooth and safe motion. 
Traffic oscillations are significantly suppressed, resulting in stable inter-vehicle distances, smoother traffic flow, and enhanced safety and efficiency.
https://github.com/user-attachments/assets/6fdd78e2-16d0-4764-b6d8-9d70b0b982a4
    
Key contributions:

    Distributed Control: Each vehicle uses only local and neighboring information for decision-making.

    Optimality and Robustness: Solves a distributed Hamilton–Jacobi–Bellman (HJB) equation to minimize tracking errors and attenuate disturbances.

    Model-Free RL: A fully data-driven, online learning method that identifies control policies and compensates unknown dynamics and disturbances.
    
    The simulation demonstrates the system’s ability to maintain safe distances and velocity synchronization among multiple vehicles even with modeling uncertainties and external disturbances.

    Keywords: Platooning, Model-Free Reinforcement Learning, Distributed Control, Robust Optimal Control, HJB Equation, Autonomous Vehicles
 


   
    
