# My Isaac Lab Workspace

This is an external Isaac Lab workspace that depends on the main Isaac Lab repository: https://github.com/isaac-sim/IsaacLab.git

It was created to develop and train a locomotion controller using Reinforcement Learning with RSL-RL. The project follows the manager-based workflow from Isaac Lab to organize tasks, configurations, and training pipelines.

The final goal is to deploy the trained policy in Isaac Sim and integrate it with ROS 2 for real-time testing and control.

![Spot robot in underground environment](images/spot_robot.jpg)

## 🚀 Installation

1. **Install Isaac Lab** by following the official instructions here:  
   👉 [Isaac Lab Installation (PIP)](https://isaac-sim.github.io/IsaacLab/main/source/setup/installation/pip_installation.html)

2. **Clone this repository** and navigate into the project directory:

   ```bash
   git clone https://github.com/YousefSamm/my_isaaclab_ws.git
   cd my_isaaclab_ws/spot_locomotion
3. **install the custom module**
    ```bash
    python -m pip install -e spot_locomotion/source
