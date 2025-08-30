
# AI-Driven Orbital Collision Avoidance Using Atmospheric Drag Modulation

## Overview

This project presents a comprehensive analysis and implementation of an artificial intelligence-driven orbital collision avoidance system that utilizes atmospheric drag modulation for satellite trajectory modification. The system employs a neural network to predict optimal ballistic coefficients that maximize miss distances between satellites and Resident Space Objects (RSOs).

## Features

- **AI-Powered Prediction**: Neural network model for optimal ballistic coefficient prediction
- **Physics-Based Simulation**: Accurate orbital mechanics with gravity and atmospheric drag
- **Real-Time Visualization**: 3D orbital trajectory plotting
- **Performance Analysis**: Comprehensive testing and validation framework
- **Collision Avoidance**: Autonomous decision-making for satellite safety

## Technical Highlights

- **Orbital Dynamics**: Two-body problem with atmospheric drag perturbations
- **Machine Learning**: Multi-layer perceptron with ReLU activation
- **Training Data**: 1,000+ orbital encounter scenarios
- **Validation**: Statistical analysis with multiple test scenarios

## Requirements

```
numpy>=1.21.0
scipy>=1.7.0
matplotlib>=3.4.0
torch>=1.9.0
scikit-learn>=0.24.0
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/orbital-collision-avoidance.git
cd orbital-collision-avoidance
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the main simulation:
```bash
python src/orbital_collision_avoidance.py
```

The system will:
1. Generate training data from orbital encounters
2. Train the neural network model
3. Run validation tests with 3D visualizations
4. Display performance metrics and improvement statistics

## Results

- **Average Miss Distance Improvement**: Varies based on scenario parameters
- **Success Rate**: Percentage of encounters with positive improvement
- **Training Convergence**: Model trains effectively within 500 epochs

## Key Components

### 1. Orbital Dynamics Simulator
- Physics-based orbit propagation
- Gravitational and atmospheric drag forces
- High-precision numerical integration

### 2. Neural Network Predictor
- Architecture: 6-128-64-32-1 neurons
- Input: Relative state vector (position and velocity)
- Output: Optimal ballistic coefficient

### 3. Performance Evaluation
- Miss distance calculation
- Statistical analysis
- 3D trajectory visualization

## Technical Analysis

The accompanying technical report identifies several key findings:

- **Temporal Limitations**: 5-hour simulation windows are insufficient for effective drag-based collision avoidance
- **Atmospheric Density Constraints**: Realistic densities at LEO altitudes limit short-term effectiveness
- **Training Data Requirements**: Enhanced dataset diversity needed for improved generalization

## Proposed Solutions

1. **Extended Temporal Analysis**: 24-72 hour prediction windows
2. **Adaptive Atmospheric Modeling**: Realistic density profiles
3. **Enhanced Training**: Augmented dataset with diverse encounter geometries
4. **Hybrid Approach**: Combined propulsion-drag systems

## Future Work

- Implementation of reinforcement learning algorithms
- Multi-satellite coordination and swarm intelligence
- Real-world hardware integration
- Extended validation with flight demonstrations

## Contributing

Contributions are welcome! Please feel free to submit pull requests, report issues, or suggest enhancements.


## Acknowledgments

- National University of Singapore STAR Theme 2 objectives
- Open-source scientific computing community
- Orbital mechanics research community



*This research contributes to sustainable space operations and autonomous satellite systems.*
