## Ansys Sweep Model, Pybullet Simulation Environment, and Reinforcement Learning Controller for HEMS Magnetic Levitation
This repository contains files with Ansys Parametric Sweep data, polynomial interpolation of this data, PyBullet simulation
interfacing with this data and drawing from physical constraints on the actual chassis, and trial reinforcement learning models
that learn from the environment based on a defined cost function.

#### Upcoming objectives
1. Verify again that sweep interpolation data provides reasonable estimates of real-world forces and torques using load cell
2. Implement PID controller that interfaces with the simulation environment present in ```lev_pod_env.py```
3. Implement other forms of reinforcement learning control, look into designing a reward structure that is conducive to learning, and
overall dive into more research on reinforcement learning algorithms for very sensitive tasks that are intrinsically highly unstable.
