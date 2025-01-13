# RL Holiday Assignment 165

## Overview
This repository contains three Python programs developed by **G. Madhav** as part of the RL Holiday Assignment 165. Each program showcases a unique application of Reinforcement Learning (RL) or optimization techniques. Below is an overview of each program:

### 1. Multi-Armed Bandit Simulation
**File:** MultiArmBanditGame
- **Description:** A simulation of the Multi-Armed Bandit problem using the Upper Confidence Bound (UCB) algorithm.
- **Highlights:**
  - Implements UCB to balance exploration and exploitation.
  - Simulates reward probabilities for actions.
  - Provides step-by-step action selection and cumulative rewards.
- **Use Case:** Optimizing action selection in uncertain environments.

### 2. IoT Device Energy Optimization
**File:** IoTDeviceManager
- **Description:** A program to optimize energy efficiency in IoT devices using UCB.
- **Highlights:**
  - Manages multiple devices with different operational modes.
  - Adapts to dynamic environmental factors such as temperature and occupancy.
  - Simulates real-time decision-making to maximize overall efficiency.
- **Use Case:** Enhancing energy efficiency in smart homes and IoT ecosystems.

### 3. Simplified Chess Decision Tree
**File:** SimplifiedChess
- **Description:** A simplified chess game environment using Decision Trees for move prediction.
- **Highlights:**
  - Uses a dataset to train a Decision Tree Classifier for optimal move prediction.
  - Provides an interactive game environment where the player competes against the model.
  - Includes win/loss conditions based on game rules.
- **Use Case:** Demonstrating AI's ability to make decisions in strategic board games.

## How to Run
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/RL-Holiday-Assignment-165.git
   cd RL-Holiday-Assignment-165
   ```

2. **Dependencies:**
   Install the required libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Execute Programs:**
   Each program can be executed individually:
   - Run `MultiArmBanditGame`:
     ```bash
     python multi_arm_bandit.py
     ```
   - Run `IoTDeviceManager`:
     ```bash
     python iot_device_manager.py
     ```
   - Run `SimplifiedChess`:
     ```bash
     python simplified_chess.py
     ```

## Acknowledgments
This project was developed as part of the **RL Holiday Assignment** to explore and implement RL concepts. Special thanks to instructors and peers for guidance and support.

## Author
**G. Madhav**

