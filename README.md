# Paper: Real-time Workflow Scheduling in Hybrid Clouds with Privacy and Security Constraints: A Deep Reinforcement Learning Approach

This is an implementation code for our paper entitled: Real-time Workflow Scheduling in Hybrid Clouds with Privacy and Security Constraints: A Deep Reinforcement Learning Approach

## Requirements
```
pip install torch==1.12.0
```

## Configuration
- Hyperparameters configuration file: `./Parameter.py`
- Comparison algorithms configuration files : `./Comparison_Algorithms/`

## Quick Start
```
python main.py
```

Directly run the `main.py`, the approach will run with the default settings.

## Data
Workflows data with `.xml` format located in folder [XML_Scientific_Workflow](https://github.com/distsys23/HOPS/tree/main/XML_Scientific_Workflow), including CyberShake, Epigenomics, LIGO, Montage, and SIPHT.
![image](https://github.com/distsys23/img/blob/main/scientific%20workflows.png)


## Code Structure
- `Comparison_Algorithms`: comparison algorithms files.
- `XML_Scientific_Workflow`: data of scientific workflow.
- `preprocess`: functions of processing workflow data.
- `main.py`: main function for HOPS.
- `Q_learning_model.py`: Q-learning model for task prioritization phase.
- `Parameter.py`: hyperparameters configuration.
- `Environment.py`: environment file for workflow scheduling in hybrid clouds.
- `DQN_model.py`: DQN model for task allocation phase.
