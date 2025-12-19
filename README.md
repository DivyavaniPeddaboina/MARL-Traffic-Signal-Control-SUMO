# MARL Traffic Signal Control using SUMO

This project implements a Multi-Agent Reinforcement Learning (MARL) framework for adaptive urban traffic signal control using the SUMO (Simulation of Urban Mobility) simulator. Each traffic signal is modeled as an autonomous learning agent that dynamically adjusts signal phases based on real-time traffic conditions such as queue lengths, waiting times, and vehicle flow.

The system replaces traditional fixed-time or rule-based signal control with a decentralized learning-based approach. Through continuous interaction with the simulated traffic environment, agents learn optimal control policies that minimize vehicle waiting time, reduce congestion, and improve overall traffic flow efficiency.

The MARL framework is integrated with SUMO via the SUMO-RL library, enabling realistic microscopic traffic simulation and scalable multi-intersection coordination. The decentralized nature of the approach allows agents to cooperate implicitly, adapting to changing traffic demand without centralized control.

### Key Features
- Multi-Agent Reinforcement Learning–based traffic signal control
- Autonomous decision-making at each intersection
- Integration with SUMO for realistic traffic simulation
- Reduction in vehicle waiting time and congestion
- Improved traffic flow efficiency and adaptability

### Technologies Used
- Python
- Multi-Agent Reinforcement Learning (MARL)
- SUMO (Simulation of Urban Mobility)
- SUMO-RL Framework

### Project Structure
MARL-Traffic-Signal-Control-SUMO/
- sumo-rl/ : SUMO-RL framework containing environments, agents, and training logic
- README.md : Project documentation

### Application Areas
- Smart city traffic management
- Intelligent transportation systems
- Adaptive traffic signal control
- Urban mobility optimization

### Conclusion
This project demonstrates that Multi-Agent Reinforcement Learning is an effective and scalable solution for intelligent traffic signal control in urban environments. By learning directly from traffic dynamics and adapting in real time, the proposed system improves transportation efficiency and supports future smart city infrastructure.

