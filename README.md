# GhostBusters      
## Introduction
This project implements an AI agent capable of detecting and capturing ghosts in a haunted environment using probabilistic inference techniques.
## Predictive Algorithms
The GhostBusters agent utilizes several predictive algorithms to identify and capture ghosts effectively. The following algorithms are implemented in this project:
- Bayesian Network: A probabilistic graphical model that represents a set of variables and their dependencies using a directed acyclic graph (DAG). The agent uses Bayesian inference to update beliefs about ghost locations based on observed evidence.
- Particle Filter: A Monte Carlo method used for state estimation in dynamic systems. The agent maintains a set of particles representing possible ghost locations and updates them based on sensor measurements and motion models.
- Hidden Markov Model (HMM): A statistical model that assumes the system being modeled is a Markov process with unobserved (hidden) states. The agent uses HMMs to infer ghost movements and make predictions about their future locations.
## Setup
1. Clone the repository: `git clone https://github.com/yourusername/ghostbusters.git`
2. Navigate to the project directory: `cd ghostbusters/`
## Dependencies
- Python 3.x
- NumPy
- matplotlib
## Structure
The project includes the following files and directories:
- ghostbusters.py: Main script to run the GhostBusters agent.
- inference.py: Contains functions for probabilistic inference and Bayesian network operations.
- factorOperations.py: Includes functions for joining factors and variable elimination.
- bustersAgents.py: Defines different types of GhostBusters agents and their behavior.
- util.py: Utility functions used throughout the project.
## Usage 
Run the GhostBusters agent:
- python ghostbusters.py
- Follow the on-screen instructions to interact with the agent and observe its ghost-catching capabilities.
## Installation
Install the required dependencies using pip:
```bash
pip install -r requirements.txt




