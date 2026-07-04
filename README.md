# Hi, I'm Akash Deshapathi 👋

I build intelligent machines at the intersection of **Robotics**, **AI**, and **Control Systems** — bridging the gap between simulation-first development and deterministic, real-world deployment.

---

### 🚀 Core Focus Areas

*   🤖 **Robotics & Autonomy**: ROS 2 (Jazzy/Humble), Nav2 navigation tuning, MoveIt 2 manipulation, and photorealistic simulation (NVIDIA Isaac Sim, Gazebo).
*   🧠 **Deep RL & Foundation Models**: GPU-parallel reinforcement learning gaits (Isaac Lab, PPO), Vision-Language-Action (VLA) manipulation, and LLM-based agentic planners (LangGraph).
*   🎛️ **Optimal Control & Estimation**: Nonlinear Model Predictive Control (acados, do-mpc, CasADi), dynamic vehicle/process modeling, and high-frequency sensor fusion (Error-State EKF in C++17 Eigen).

---

### 🛠️ Featured Projects

#### [Isaac Lab Quadruped RL](https://github.com/dark-syndrome/isaac-lab-quadruped-rl)
*Massively parallel locomotion learning with sim-to-real export*
*   Trained velocity-tracking locomotion policies over **4096 parallel environments** on a single RTX GPU using PPO.
*   Implemented curriculum-driven terrain generation, domain randomization, and ONNX export for 50 Hz embedded control loops.
*   **Tech**: Isaac Lab 2.x, rsl_rl, PyTorch, ONNX, Python

#### [Nonlinear MPC Racing Controller](https://github.com/dark-syndrome/ros2-mpc-racing)
*Real-time model predictive contouring control at the grip limit*
*   Formulated Model Predictive Contouring Control (MPCC) using a dynamic bicycle model with Pacejka lateral tire forces.
*   Achieved sub-millisecond solves (N=40 horizon) using **acados SQP-RTI solver** with ROS 2 diagnostic reporting.
*   **Tech**: acados, CasADi, ROS 2 Jazzy, F1TENTH, Python/C

#### [Agentic Robot Orchestrator](https://github.com/dark-syndrome/agentic-robot-orchestrator)
*LLM mission planning compiled to verified behavior trees*
*   Built a **LangGraph agent pipeline** to decompose high-level user missions into typed, Pydantic-validated skill sequences.
*   Incorporated an adversarial safety critic agent to review plans against site rules before compiling them into deterministic `py_trees` behavior trees.
*   **Tech**: LangGraph, py_trees, ROS 2 Actions, Pydantic, Python

#### [VLA Manipulation Pipeline](https://github.com/dark-syndrome/vla-manipulation-pipeline)
*Language-conditioned pick-and-place with foundation models*
*   Implemented a target resolution pipeline using Grounding DINO + SAM 2, feeding into an OpenVLA-7B model for end-effector delta generation.
*   Gated action execution with confidence metrics, routing low-certainty commands to a deterministic MoveIt 2 sampler and safety envelope.
*   **Tech**: OpenVLA, SAM 2, Grounding DINO, MoveIt 2, ROS 2

#### [Multi-Sensor Fusion ES-EKF](https://github.com/dark-syndrome/multi-sensor-fusion-esekf)
*Error-state Kalman filtering for GNSS + IMU + odometry in C++*
*   Designed a 15-state indirect EKF (position, velocity, orientation, sensor biases) running on manifold representation at 200 Hz.
*   Utilized $\chi^2$ innovation gating for multipath rejection, zero-velocity updates (ZUPT), and Joseph-form covariance updates.
*   **Tech**: C++17, Eigen, GoogleTest, ROS 2

---

### 💻 Technologies & Tools

*   **Languages**: Python, C++17, MATLAB/Simulink
*   **Libraries**: PyTorch, NumPy, SciPy, Eigen, CasADi
*   **Robotics/Sim**: ROS 2 (Jazzy/Humble), Nav2, MoveIt 2, Isaac Sim/Lab, Gazebo
*   **Control/Opt**: acados, do-mpc, IPOPT
*   **DevOps/Infra**: Docker, Git, CI/CD (GitHub Actions), Linux (Ubuntu)

---

### 📫 Connect with Me
*   📧 Email: [akdeshapathi@gmail.com](mailto:akdeshapathi@gmail.com)
*   💻 Portfolio: [akashdeshapathi.com](https://github.com/dark-syndrome/akash-portfolio)
*   👔 LinkedIn: [LinkedIn Profile](#)
