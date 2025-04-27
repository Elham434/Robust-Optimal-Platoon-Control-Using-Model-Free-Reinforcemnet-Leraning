🚗 Robust Optimal Platoon Control Using Model-Free Reinforcement Learning

This project presents a novel robust optimal control strategy for multi-vehicle platoons under unknown dynamics and disturbances.
Traditional reinforcement learning (RL) methods often depend on explicit vehicle models, but this work proposes a simplified, adaptive, off-policy, model-free RL algorithm that learns both optimal control and disturbance compensation policies directly from input-output data, without requiring dynamic models.

Key contributions:

    Distributed Control: Each vehicle uses only local and neighboring information for decision-making.

    Optimality and Robustness: Solves a distributed Hamilton–Jacobi–Bellman (HJB) equation to minimize tracking errors and attenuate disturbances.

    Model-Free RL: A fully data-driven, online learning method that identifies control policies and compensates unknown dynamics and disturbances.

    The simulation demonstrates the system’s ability to maintain safe distances and velocity synchronization among multiple vehicles even with modeling uncertainties and external disturbances.

    Keywords: Platooning, Model-Free Reinforcement Learning, Distributed Control, Robust Optimal Control, HJB Equation, Autonomous Vehicles
