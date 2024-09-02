# Advanced-Neuron-Structures-and-Learning-Mechanisms-in-Spiking-Neural-Networks
This project investigates the impact of neuron structures on learning in Spiking Neural Networks (SNNs).

It explores various mechanisms such as Lateral Inhibition, K Winners Take All (KWTA), and Homeostasis, and their effects on learning efficiency, pattern recognition, and network stability.

## Project Objectives
1. **Neuron Structure and Learning**: Analyze how different neuron structures and network configurations impact learning in SNNs.
2. **Lateral Inhibition**: Understand the role of lateral inhibition in enhancing pattern differentiation and network sensitivity.
3. **K Winners Take All (KWTA)**: Evaluate the influence of KWTA on learning efficiency and pattern classification in SNNs.
4. **Homeostasis**: Explore the effects of homeostasis on network stability, learning speed, and pattern recognition.
5. **Parameter Exploration**: Study the effects of various parameters on the learning behavior of the network.

## Implemented Features
### 1. Spiking Neural Network Design
- **Network Structure**: The network consists of an input layer with 6 neurons and an output layer with 2 neurons. The network is fully connected, and synaptic weights are adjusted using the Spike-Timing-Dependent Plasticity (STDP) rule.

### 2. Lateral Inhibition
- **Objective**: Enhance pattern differentiation and neuron sensitivity by introducing lateral inhibition in the output layer.
- **Outcome**: Neurons in the output layer exhibit improved sensitivity to input patterns, although differentiation between patterns can be challenging with intersecting inputs.

### 3. K Winners Take All (KWTA)
- **Objective**: Implement KWTA to promote competition among neurons in the output layer, improving learning efficiency and pattern recognition.
- **Outcome**: KWTA significantly enhances the network's ability to classify and differentiate between input patterns, with faster convergence and reduced overfitting.

### 4. Homeostasis
- **Objective**: Introduce homeostasis to maintain balanced activity levels across the network, preventing neurons from becoming overly excited or inhibited.
- **Outcome**: Homeostasis improves network dynamics, stabilizes learning, reduces overfitting, and enhances pattern recognition.

### 5. Parameter Exploration
- **Parameters Explored**:
  - **Voltage-Based Homeostasis**: Target voltage, maximum and minimum thresholds, and learning rate.
  - **KWTA**: Number of active winners (K).
  - **Lateral Dendritic Input**: Current coefficient and inhibitory setting.
- **Outcome**: The network's performance and learning behavior vary significantly with different parameter settings, affecting stability, learning speed, and pattern recognition accuracy.

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `scipy`, `conex`, `PymoNNtorch`
