# Warehouse Navigation Agent - Unity ML-Agents

## Project Overview

This project demonstrates the development and training of an intelligent warehouse navigation agent using Unity's ML-Agents Toolkit and reinforcement learning techniques. The agent learns to navigate complex warehouse environments, reach designated targets, and avoid both static and dynamic obstacles through trial-and-error learning.

## 🎯 Objectives
<img width="720" alt="Picture1" src="https://github.com/user-attachments/assets/168be0d0-3cc2-447d-8a7b-48b456bf0178" />

- **Primary Goal**: Develop an AI agent capable of autonomous navigation in a warehouse environment
- **Learning Approach**: Implement reinforcement learning with reward-based training strategies
- **Environment Complexity**: Progress from simple prototypes to complex, dynamic environments with moving obstacles
- **Performance Optimization**: Achieve efficient pathfinding and obstacle avoidance through iterative training

## 🛠️ Technical Stack

- **Game Engine**: Unity 3D
- **ML Framework**: Unity ML-Agents Toolkit
- **Programming Languages**: Python 3.9.13, C#
- **Training Monitoring**: TensorBoard for performance visualization
- **Architecture**: Neural network-based decision making with reinforcement learning

## 🏗️ P.E.A.S Framework Implementation

### Performance Measures
- **Navigation Efficiency**: Time to reach target destinations
- **Obstacle Avoidance**: Collision frequency and penalty reduction
- **Path Optimization**: Route efficiency and decision-making quality
- **Learning Progress**: Reward accumulation and success rate improvement

### Environment
<img width="717" alt="Picture3" src="https://github.com/user-attachments/assets/e384a4f8-3133-4345-b4f9-e8495ec8c4ce" />

- **Warehouse Layout**: Walls, storage containers, and navigational corridors
- **Dynamic Elements**: Moving forklifts creating unpredictable obstacles
- **Complexity Scaling**: Modular environment design using Unity prefabs
- **Training Scenarios**: Multiple environment configurations for robust learning

### Actuators
- **Movement Controls**: Forward, backward, and rotational movement
- **Speed Regulation**: Controllable velocity parameters
- **Decision Execution**: Real-time action selection based on neural network output

### Sensors
- **Reinforcement Learning**: Reward-based environmental feedback
- **Distance Calculation**: Heuristic approach measuring agent-to-target proximity
- **Obstacle Detection**: Environmental awareness for collision avoidance
- **Spatial Reasoning**: 3D environment understanding and navigation

## 📊 Training Results & Analysis

### Learning Progression
The agent demonstrated clear learning capabilities through several key metrics:
<img width="551" alt="Picture5" src="https://github.com/user-attachments/assets/98510322-5b22-4b1c-9f76-3886da19c93a" />

- **Initial Behavior**: Random, aimless movement patterns
- **Progressive Improvement**: Systematic enhancement in navigation efficiency
- **Obstacle Avoidance**: Marked reduction in collision frequency
- **Target Achievement**: Increased success rate in reaching designated goals

### Performance Metrics
<img width="607" alt="Picture6" src="https://github.com/user-attachments/assets/3b22d668-cc3f-492f-9642-01e896cf22aa" />

Over time, the agent's interaction with its environment evolved markedly. It began to understand the space layout better, avoided obstacles with increased consistency, and chose more efficient routes to its goals. This evolution exemplifies the agent's capacity to learn and adapt strategies through interaction. A critical aspect of the agent's learning was the reinforcement learning model applied. This model rewarded positive behaviours, like reaching targets, and penalized negative actions, such as colliding with obstacles or choosing inefficient routes. This reward-penalty system significantly influenced the agent's learning, as shown by its gradual improvement in task completion efficiency.

The above TensorBoard images will provide a visual insight into the agent's learning progress, displaying metrics such as reward accumulation, task completion steps, and success rates at different training stages. This visual data is invaluable for understanding the agent's learning dynamics and making data-driven improvements.
This exploration of machine learning within a simulated environment underscores the potential and challenges of training AI agents. The journey of the ML agent, from its rudimentary beginnings to its current capabilities, highlights the intricacies of AI learning and the necessity for ongoing refinement. The insights gained from this project extend beyond our specific objectives, contributing to the broader understanding of AI and machine learning in virtual settings.

- **Reward Accumulation**: Steady increase over training episodes
- **Episode Length**: Decreased time to complete navigation tasks
- **Penalty Reduction**: Significant drop in negative reinforcement events
- **Mean Reward**: Consistent upward trend indicating successful learning

### Challenges Encountered

- **Hardware Limitations**: Computational constraints affecting training depth
- **Dynamic Elements**: Complexity of integrating moving obstacles
- **Overfitting**: Need for environment variability to ensure generalization
- **Resource Management**: Balancing environment complexity with available processing power

## 🚀 Key Features

### Environment Evolution
1. **Simple Prototype**: Basic walled environment with single obstacle
2. **Intermediate Complexity**: Maze-like structure with multiple static barriers
3. **Advanced Environment**: Dynamic moving obstacles (forklifts) and containers
4. **Modular Design**: Prefab-based environment creation for rapid iteration

### Learning Mechanisms
- **Reward System**: Positive reinforcement for target achievement
- **Penalty Framework**: Negative feedback for collisions and inefficient paths
- **Distance-Based Feedback**: Graduated rewards based on proximity to objectives
- **Adaptive Behavior**: Real-time decision making based on environmental feedback

## 📈 Results Summary

The project successfully demonstrated the effectiveness of reinforcement learning in virtual environments:
<img width="607" alt="Picture6" src="https://github.com/user-attachments/assets/b6bea796-7182-44f4-9248-66ff9e8ded50" />

- **Learning Verification**: Agent evolved from random movement to purposeful navigation
- **Obstacle Navigation**: Successful avoidance of both static and dynamic barriers
- **Performance Optimization**: Measurable improvement in task completion efficiency
- **Scalability**: Framework adaptable to various warehouse configurations

<img width="609" alt="Picture4" src="https://github.com/user-attachments/assets/aeef2faf-c0a2-4551-82fd-a13e2d9aff2f" />

## 🎓 Educational Value

This project serves as a comprehensive introduction to:
- **Reinforcement Learning**: Practical implementation of ML principles
- **Game AI Development**: Unity-based artificial intelligence systems
- **Neural Networks**: Real-world application of deep learning concepts
- **Problem-Solving**: Systematic approach to complex AI challenges

## 📝 Technical Insights

The development process highlighted critical aspects of machine learning implementation:
- **Iterative Development**: Importance of starting simple and adding complexity gradually
- **Environment Design**: Significant impact of training environment on learning outcomes
- **Resource Constraints**: Need to balance ambition with computational limitations
- **Performance Monitoring**: Essential role of metrics in understanding agent behavior

This project demonstrates practical application of machine learning in game development while providing insights into the complexities and rewards of training intelligent agents in virtual environments. The systematic approach from prototype to complex implementation offers valuable lessons for future AI development projects.
