# Awesome Robotics Libraries with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of robotics libraries and simulators.

## Contents

* [Libraries](#libraries)
  * [Dynamics Simulation](#dynamics-simulation)
  * [Inverse Kinematics](#inverse-kinematics)
  * [Machine Learning](#machine-learning)
  * [Motion Planning and Control](#motion-planning-and-control)
  * [Optimization](#optimization)
  * [Robot Modeling](#robot-modeling)
  * [Robot Platform](#robot-platform)
  * [Reinforcement Learning for Robotics](#reinforcement-learning-for-robotics)
  * [SLAM](#slam)
  * [Vision](#vision)
  * [Fluid](#fluid)
  * [Grasping](#grasping)
  * [Humanoid Robotics](#humanoid-robotics)
  * [Multiphysics](#multiphysics)
  * [Math](#math)
  * [ETC](#etc)
* [Simulators](#simulators)
* [Other Awesome Lists](#other-awesome-lists)

> **Legend**: 🟢 Active (<1yr) · 🟡 Slow (1-2yr) · 🔴 Stale (>2yr) · 💀 Archived

## [Libraries](#contents)

### [Dynamics Simulation](#contents)

*Physics engines and rigid/soft body dynamics libraries. See also [Comparisons](COMPARISONS.md).*

* 🟢 [Genesis](https://genesis-world.readthedocs.io) - Generative and universal physics platform for robotics with GPU-accelerated parallel simulation. [⭐ 29.4k](https://github.com/Genesis-Embodied-AI/Genesis) ⭐ 29,770 | 🐛 125 | 🌐 Python | 📅 2026-08-19
* 🟢 [Bullet](https://pybullet.org/) - Real-time physics simulation for games, visual effects, and robotics. [⭐ 14.6k](https://github.com/bulletphysics/bullet3) ⭐ 14,683 | 🐛 423 | 🌐 C++ | 📅 2025-10-22
* 🟢 [MuJoCo](https://mujoco.org/) - Multi-joint dynamics with contact for physics-based simulation and control. [⭐ 14k](https://github.com/google-deepmind/mujoco) ⭐ 14,591 | 🐛 350 | 🌐 C++ | 📅 2026-08-19
* 🟢 [Newton](https://newton-physics.github.io/newton/) - GPU-accelerated differentiable physics engine built on NVIDIA Warp for robotics simulation. [⭐ 5.1k](https://github.com/newton-physics/newton) ⭐ 5,484 | 🐛 390 | 🌐 Python | 📅 2026-08-19
* 🟢 [PhysX](https://nvidia-omniverse.github.io/PhysX/physx/5.5.0/index.html) - NVIDIA physics engine for real-time rigid body and vehicle simulation. [⭐ 4.6k](https://github.com/NVIDIA-Omniverse/PhysX) ⭐ 4,729 | 🐛 74 | 🌐 C++ | 📅 2026-08-07
* 🟢 [Drake](https://drake.mit.edu/) - Planning, control, and analysis toolbox for nonlinear dynamical systems. [⭐ 4.1k](https://github.com/RobotLocomotion/drake) ⭐ 4,155 | 🐛 656 | 🌐 C++ | 📅 2026-08-19
* 🟢 [pinocchio](https://stack-of-tasks.github.io/pinocchio/) - Fast and flexible algorithms for rigid-body dynamics with analytical derivatives. [⭐ 3.5k](https://github.com/stack-of-tasks/pinocchio) ⭐ 3,660 | 🐛 107 | 🌐 C++ | 📅 2026-08-11
* 🟢 [Brax](https://github.com/google/brax) ⭐ 3,220 | 🐛 113 | 🌐 Jupyter Notebook | 📅 2026-08-06 - Massively parallel differentiable rigid body physics engine in JAX for robotics and RL. [⭐ 3.2k](https://github.com/google/brax) ⭐ 3,220 | 🐛 113 | 🌐 Jupyter Notebook | 📅 2026-08-06
* 🟢 [CHRONO::ENGINE](https://projectchrono.org/) - Multi-physics simulation of rigid and flexible bodies, granular, and fluid systems. [⭐ 2.9k](https://github.com/projectchrono/chrono) ⭐ 2,984 | 🐛 19 | 🌐 C++ | 📅 2026-08-18
* 🟢 [Simbody](https://simtk.org/home/simbody/) - Multibody dynamics library for biomechanical and mechanical systems. [⭐ 2.5k](https://github.com/simbody/simbody) ⭐ 2,543 | 🐛 161 | 🌐 C++ | 📅 2026-08-12
* 🟢 PositionBasedDynamics - Position-based methods for simulating deformable objects and fluids. [⭐ 2.2k](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics) ⭐ 2,261 | 🐛 11 | 🌐 C++ | 📅 2026-08-14
* 🟢 [mrpt](https://www.mrpt.org/) - Mobile Robot Programming Toolkit for SLAM, navigation, and computer vision. [⭐ 2.1k](https://github.com/MRPT/mrpt) ⭐ 2,155 | 🐛 29 | 🌐 C++ | 📅 2026-08-11
* 🟡 [ReactPhysics3d](https://www.reactphysics3d.com/) - Open-source 3D physics engine for rigid body simulation and collision detection. [⭐ 1.8k](https://github.com/DanielChappuis/reactphysics3d) ⭐ 1,771 | 🐛 91 | 🌐 C++ | 📅 2025-03-28
* 🔴 [nphysics](https://nphysics.org/) - 2D and 3D rigid body physics engine written in Rust. [⭐ 1.6k](https://github.com/dimforge/nphysics) ⭐ 1,649 | 🐛 44 | 🌐 Rust | 📅 2021-07-27
* 🔴 Tiny Differentiable Simulator - Header-only differentiable physics engine for robotics. [⭐ 1.4k](https://github.com/erwincoumans/tiny-differentiable-simulator) ⭐ 1,368 | 🐛 12 | 🌐 C++ | 📅 2024-10-18
* 🟢 [SOFA](https://www.sofa-framework.org/) - Simulation Open Framework Architecture for medical and physics simulation. [⭐ 1.2k](https://github.com/sofa-framework/sofa) ⭐ 1,245 | 🐛 446 | 🌐 C++ | 📅 2026-08-18
* 🟢 [Rigs of Rods](https://www.rigsofrods.org/) - Soft-body vehicle simulator using beam physics. [⭐ 1.2k](https://github.com/RigsOfRods/rigs-of-rods) ⭐ 1,227 | 🐛 236 | 🌐 C++ | 📅 2026-08-11
* 🟡 [Robotics Library](https://www.roboticslibrary.org/) - Self-contained C++ library for robot kinematics, planning, and control. [⭐ 1.2k](https://github.com/roboticslibrary/rl) ⭐ 1,196 | 🐛 53 | 🌐 C++ | 📅 2025-04-15
* 🟢 [DART](http://dartsim.github.io/) - Dynamic Animation and Robotics Toolkit for multibody simulation and planning. [⭐ 1.1k](https://github.com/dartsim/dart) ⭐ 1,195 | 🐛 9 | 🌐 C++ | 📅 2026-08-19
* 🟢 [Newton Dynamics](https://newtondynamics.com/) - Real-time physics engine for rigid body simulation. [⭐ 1k](https://github.com/MADEAPPS/newton-dynamics) ⭐ 1,024 | 🐛 0 | 🌐 HTML | 📅 2026-01-17
* 💀 qu3e - Lightweight 3D physics engine for rigid body dynamics. [⭐ 997](https://github.com/RandyGaul/qu3e) ⚠️ Archived
* 🟢 [KDL](https://www.orocos.org/kdl.html) - Orocos Kinematics and Dynamics Library for kinematic chains. [⭐ 884](https://github.com/orocos/orocos_kinematics_dynamics) ⭐ 898 | 🐛 60 | 🌐 C++ | 📅 2026-07-22
* 🟡 [OpenRAVE](https://www.openrave.org/) - Open Robotics Automation Virtual Environment for planning and simulation. [⭐ 807](https://github.com/rdiankov/openrave) ⭐ 815 | 🐛 349 | 🌐 C++ | 📅 2026-08-12
* 💀 [Flex](https://developer.nvidia.com/flex) - GPU-based particle simulation for rigid bodies, fluids, and deformables. [⭐ 797](https://github.com/NVIDIAGameWorks/FleX) ⭐ 809 | 🐛 96 | 🌐 C++ | 📅 2021-04-15
* 🟡 [RBDL](https://rbdl.github.io/) - Rigid Body Dynamics Library based on Featherstone algorithms. [⭐ 700](https://github.com/rbdl/rbdl) ⭐ 703 | 🐛 33 | 🌐 C++ | 📅 2025-06-09
* 🟡 kindr - Kinematics and dynamics library for rigid body transformations. [⭐ 613](https://github.com/ANYbotics/kindr) ⭐ 615 | 🐛 29 | 🌐 C++ | 📅 2025-02-15
* 🟢 [Klampt](https://klampt.org/) - Robot planning, control, and simulation with visualization support. [⭐ 433](https://github.com/krishauser/Klampt) ⭐ 434 | 🐛 27 | 🌐 C++ | 📅 2026-01-10
* 🟢 [PyDy](https://www.pydy.org/) - Multibody dynamics analysis with symbolic Python using SymPy. [⭐ 413](https://github.com/pydy/pydy) ⭐ 416 | 🐛 88 | 🌐 Python | 📅 2026-07-28
* 🟢 [mvsim](http://wiki.ros.org/mvsim) - Lightweight multi-vehicle 2D simulator with ROS integration. [⭐ 404](https://github.com/MRPT/mvsim) ⭐ 410 | 🐛 6 | 🌐 C++ | 📅 2026-07-17
* 🔴 [LibrePilot](http://www.librepilot.org/site/index.html) - Open-source autopilot for UAVs and other autonomous vehicles. [⭐ 356](https://github.com/librepilot/LibrePilot) ⭐ 357 | 🐛 18 | 🌐 C | 📅 2023-12-14
* 💀 [RaiSim](https://slides.com/jeminhwangbo/raisim-manual) - Cross-platform physics engine for robotics and reinforcement learning. [⭐ 328](https://github.com/leggedrobotics/raisimLib) ⚠️ Archived
* 🟡 RigidBodyDynamics.jl - Julia library for rigid body dynamics algorithms. [⭐ 309](https://github.com/JuliaRobotics/RigidBodyDynamics.jl) ⭐ 309 | 🐛 40 | 🌐 Julia | 📅 2024-11-08
* 🟢 idyntree - Library for estimation and whole-body dynamics of floating-base robots. [⭐ 231](https://github.com/gbionics/idyntree) ⭐ 235 | 🐛 197 | 🌐 C++ | 📅 2026-07-27
* 🔴 [Robopy](https://adityadua24.github.io/robopy/) - Python robotics toolbox inspired by Peter Corke's Robotics Toolbox. [⭐ 229](https://github.com/adityadua24/robopy) ⭐ 229 | 🐛 6 | 🌐 Python | 📅 2021-02-10
* 🟢 RBDyn - Rigid body dynamics algorithms using spatial algebra with Eigen. [⭐ 222](https://github.com/jrl-umi3218/RBDyn) ⭐ 223 | 🐛 16 | 🌐 C++ | 📅 2026-07-25
* 🟢 [siconos](https://nonsmooth.gricad-pages.univ-grenoble-alpes.fr/siconos/) - Nonsmooth dynamical systems modeling and simulation platform. [⭐ 187](https://github.com/siconos/siconos) ⭐ 187 | 🐛 11 | 🌐 C | 📅 2026-08-12
* 🔴 [FROST](https://ayonga.github.io/frost-dev/index.html) - Fast Robot Optimization and Simulation Toolkit for hybrid dynamical systems in MATLAB. [⭐ 169](https://github.com/ayonga/frost-dev) ⭐ 169 | 🐛 11 | 🌐 MATLAB | 📅 2023-11-29
* 🟢 [MARS](http://rock-simulation.github.io/mars/) - Machina Arte Robotum Simulans — a cross-platform simulation environment. [⭐ 68](https://github.com/rock-simulation/mars) ⭐ 68 | 🐛 30 | 🌐 C++ | 📅 2025-09-01
* 🟢 [MBSim](https://www.mbsim-env.de/) - Multi-body simulation environment for flexible and rigid systems. [⭐ 53](https://github.com/mbsim-env/mbsim) ⭐ 53 | 🐛 3 | 🌐 C++ | 📅 2026-08-16
* 🔴 [Moby](http://physsim.sourceforge.net/index.html) - Multi-body dynamics simulation for rigid bodies with contact. [⭐ 37](https://github.com/PositronicsLab/Moby) ⭐ 37 | 🐛 2 | 🌐 C++ | 📅 2021-11-26
* 🔴 [trep](http://murpheylab.github.io/trep/) - Simulation and optimal control using variational integrators. [⭐ 20](https://github.com/MurpheyLab/trep) ⭐ 20 | 🐛 4 | 🌐 C | 📅 2023-09-03
* 💀 metapod - Template-based robot dynamics library using spatial algebra. [⭐ 14](https://github.com/laas/metapod) ⚠️ Archived
* 🔴 [MBSlib](http://www.sim.informatik.tu-darmstadt.de/res/sw/mbslib) - Lightweight multibody system dynamics library. [⭐ 11](https://github.com/SIM-TU-Darmstadt/mbslib) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2016-08-17
* [ARCSim](http://graphics.berkeley.edu/resources/ARCSim/index.html) - Adaptive remeshing cloth and shell simulator for thin deformable objects.
* [IBDS](http://www.interactive-graphics.de/index.php/downloads/12-ibds) - Impulse-based dynamics simulation for rigid bodies and particle systems.
* [MBDyn](https://www.mbdyn.org/) - General-purpose multibody dynamics analysis software. \[[code](https://www.mbdyn.org/?Software_Download)]
* [ODE](https://ode.org/) - Open Dynamics Engine for simulating rigid body dynamics. \[[bitbucket](https://bitbucket.org/odedevs/ode)]
* [RobWork](https://robwork.dk/) - Framework for simulation and control of robot systems. \[[gitlab](https://gitlab.com/sdurobotics/RobWork)]

### [Inverse Kinematics](#contents)

*Libraries for computing joint configurations from end-effector poses.*

* 🔴 RelaxedIK - Real-time Synthesis of Accurate and Feasible Robot Arm Motion. [⭐ 249](https://github.com/uwgraphics/relaxed_ik) ⭐ 252 | 🐛 20 | 🌐 Python | 📅 2023-04-13
* 🟢 IKBT - A python package to solve robot arm inverse kinematics in symbolic form. [⭐ 217](https://github.com/uw-biorobotics/IKBT) ⭐ 218 | 🐛 4 | 🌐 Python | 📅 2026-08-14
* 🟢 Kinpy - A simple pure python package to solve inverse kinematics. [⭐ 181](https://github.com/neka-nat/kinpy) ⭐ 180 | 🐛 4 | 🌐 Python | 📅 2026-05-21
* 🟢 ssik - Analytical inverse kinematics for 6R and 7R revolute robot arms, returning every IK branch. [⭐ 113](https://github.com/personalrobotics/ssik) ⭐ 180 | 🐛 31 | 🌐 Python | 📅 2026-08-10
* 🔴 [Trip](https://trip-kinematics.readthedocs.io/en/main/index.html) - A python package that solves inverse kinematics of parallel-, serial- or hybrid-robots. [⭐ 43](https://github.com/TriPed-Robot/trip_kinematics) ⭐ 43 | 🐛 21 | 🌐 Python | 📅 2022-05-06
* 🔴 Lively - A highly configurable toolkit for commanding robots in mixed modalities. [⭐ 8](https://github.com/Wisc-HCI/lively) ⭐ 8 | 🐛 2 | 🌐 Rust | 📅 2023-08-15

### [Machine Learning](#contents)

*Machine learning frameworks and tools applied to robotics.*

* 🟢 LeRobot - Pretrained models, datasets, and simulation environments for real-world robotics in PyTorch. [⭐ 25.4k](https://github.com/huggingface/lerobot) ⭐ 26,747 | 🐛 804 | 🌐 Python | 📅 2026-08-19
* 🟢 [Ivy](https://lets-unify.ai/) - Unified Machine Learning Framework. [⭐ 14.2k](https://github.com/ivy-llc/ivy) ⭐ 14,170 | 🐛 985 | 🌐 Python | 📅 2026-08-11
* 🟢 [Gymnasium](https://gymnasium.farama.org/) - Developing and comparing reinforcement learning algorithms. [⭐ 12.1k](https://github.com/Farama-Foundation/Gymnasium) ⭐ 12,349 | 🐛 77 | 🌐 Python | 📅 2026-08-18
  * 💀 gym-gazebo - OpenAI Gym environments for the Gazebo simulator. [⭐ 846](https://github.com/erlerobot/gym-gazebo) ⚠️ Archived
  * 🔴 gym-dart - OpenAI Gym environments using the DART physics engine. [⭐ 140](https://github.com/DartEnv/dart-env) ⭐ 140 | 🐛 0 | 🌐 Python | 📅 2020-10-20
* 🔴 [tiny-dnn](http://tiny-dnn.readthedocs.io/en/latest/) - Header only, dependency-free deep learning framework in C++14. [⭐ 6k](https://github.com/tiny-dnn/tiny-dnn) ⭐ 6,028 | 🐛 297 | 🌐 C++ | 📅 2022-04-17
* 🟢 [mlpack](https://www.mlpack.org/) - Scalable C++ machine learning library. [⭐ 5.7k](https://github.com/mlpack/mlpack) ⭐ 5,701 | 🐛 15 | 🌐 C++ | 📅 2026-08-09
* 🔴 [DyNet](https://dynet.readthedocs.io/en/latest/) - The Dynamic Neural Network Toolkit. [⭐ 3.4k](https://github.com/clab/dynet) ⭐ 3,436 | 🐛 233 | 🌐 C++ | 📅 2023-12-01
* 🟢 [robosuite](https://robosuite.ai/docs/) - A modular simulation framework and benchmark for robot learning. [⭐ 2.5k](https://github.com/ARISE-Initiative/robosuite) ⭐ 2,559 | 🐛 110 | 🌐 Python | 📅 2026-07-11
* 🟢 Any4LeRobot - A collection of utilities and tools for LeRobot. [⭐ 1.1k](https://github.com/Tavish9/any4lerobot) ⭐ 1,133 | 🐛 4 | 🌐 Python | 📅 2026-08-17
* 🟡 DLL - Deep Learning Library (DLL) for C++. [⭐ 687](https://github.com/wichtounet/dll) ⭐ 687 | 🐛 1 | 🌐 C++ | 📅 2025-05-27
* 🔴 [Fido](http://fidoproject.github.io/) - Lightweight C++ machine learning library for embedded electronics and robotics. [⭐ 462](https://github.com/FidoProject/Fido) ⭐ 463 | 🐛 15 | 🌐 C++ | 📅 2020-01-05
* 🔴 MiniDNN - A header-only C++ library for deep neural networks. [⭐ 435](https://github.com/yixuan/MiniDNN) ⭐ 434 | 🐛 12 | 🌐 C++ | 📅 2021-04-16
* 🟡 [AllenAct](https://allenact.org/) - Python/PyTorch-based Research Framework for Embodied AI. [⭐ 383](https://github.com/allenai/allenact) ⭐ 382 | 🐛 58 | 🌐 Python | 📅 2026-05-19
* 🔴 RLLib - Temporal-difference learning algorithms in reinforcement learning. [⭐ 211](https://github.com/samindaa/RLLib) ⭐ 212 | 🐛 13 | 🌐 C++ | 📅 2016-08-15
* 🟢 [LeRobot Episode Scoring Toolkit](https://github.com/RoboticsData/score_lerobot_episodes) ⭐ 72 | 🐛 5 | 🌐 Python | 📅 2026-03-13 - One-click tool to score, filter, and export higher-quality LeRobot datasets. [⭐ 69](https://github.com/RoboticsData/score_lerobot_episodes) ⭐ 72 | 🐛 5 | 🌐 Python | 📅 2026-03-13

### [Motion Planning and Control](#contents)

*Libraries for robot motion planning, trajectory optimization, and control.*

* 🟢 [OMPL](https://ompl.kavrakilab.org/) - Open motion planning library. [⭐ 2.1k](https://github.com/ompl/ompl) ⭐ 2,126 | 🐛 99 | 🌐 C++ | 📅 2026-08-14
* 🟢 [MoveIt!](https://moveit.ai/) - Motion planning framework. [⭐ 2.1k](https://github.com/moveit/moveit) ⭐ 2,077 | 🐛 621 | 🌐 C++ | 📅 2026-07-20
* 🟢 [cuRobo](https://curobo.org) - A CUDA accelerated library containing a suite of robotics algorithms that run significantly faster. [⭐ 1.7k](https://github.com/nvlabs/curobo) ⭐ 1,778 | 🐛 15 | 🌐 Python | 📅 2026-07-23
* 🔴 [Control Toolbox](https://ethz-adrl.github.io/ct/) - Open-Source C++ Library for Robotics, Optimal and Model Predictive Control. [⭐ 1.7k](https://github.com/ethz-adrl/control-toolbox) ⭐ 1,704 | 🐛 64 | 🌐 C++ | 📅 2022-11-09
* 🟢 OCS2 - Efficient continuous and discrete time optimal control implementation. [⭐ 1.5k](https://github.com/leggedrobotics/ocs2) ⭐ 1,496 | 🐛 54 | 🌐 C++ | 📅 2026-07-20
* 🟢 Crocoddyl - Optimal control library for robot control under contact sequence. [⭐ 1.2k](https://github.com/loco-3d/crocoddyl) ⭐ 1,279 | 🐛 19 | 🌐 C++ | 📅 2026-08-18
* 🟢 Fields2Cover - Robust and efficient coverage paths for autonomous agricultural vehicles. [⭐ 829](https://github.com/fields2cover/fields2cover) ⭐ 867 | 🐛 31 | 🌐 C++ | 📅 2026-08-18
* 🔴 GPMP2 - Gaussian Process Motion Planner 2. [⭐ 357](https://github.com/gtrll/gpmp2) ⭐ 357 | 🐛 13 | 🌐 C++ | 📅 2022-08-28
* 🔴 [AIKIDO](https://github.com/personalrobotics/aikido) ⭐ 233 | 🐛 100 | 🌐 C++ | 📅 2023-03-10 - Solving robotic motion planning and decision making problems. [⭐ 233](https://github.com/personalrobotics/aikido) ⭐ 233 | 🐛 100 | 🌐 C++ | 📅 2023-03-10
* 🟢 Bioptim - Bioptim, a Python Framework for Musculoskeletal Optimal Control in Biomechanics. [⭐ 119](https://github.com/pyomeca/bioptim) ⭐ 120 | 🐛 94 | 🌐 Python | 📅 2026-08-18
* [CuiKSuite](http://www.iri.upc.edu/people/porta/Soft/CuikSuite2-Doc/html) - Applications to solve position analysis and path planning problems.
* [HPP](https://humanoid-path-planner.github.io/hpp-doc/) - Path planning for kinematic chains in environments cluttered with obstacles.
* 🟢 [Optimization Engine (OpEn)](https://alphaville.github.io/optimization-engine/) - Optimization Engine (OpEn) is a numerical optimization library written in Rust and a code generator in Python that facilitates the design of optimizers, suitable for embedded applications and robotics. Typical applications include model predictive control (MPC) and moving horizon estimation (MHE), which are popular in robotics. OpEn has been used on ground and aerial vehicles.

Some examples of applications where OpEn has been used are [autonomous racing cars](https://giuseppesilano.net/publications/SMC22.pdf), navigation of a [Husky robot](https://alphaville.github.io/optimization-engine/docs/example_navigation_ros_codegen) using ROS, collision-free navigation of heavy equipment ([paper](https://arxiv.org/pdf/2404.14257), [demo](https://youtu.be/YrUXZ3_oJlU)).

OpEn can automatically generate ROS packages, which can be used directly in robotics applications.

Lastly, OpEn is becoming popular: it currently counts 616 stars on GitHub and more than 300k downloads from [crates.io](https://crates.io/crates/optimization_engine). The Python package, `opengen` counted 804 downloads in the last month ([link](https://pypistats.org/packages/opengen)). [⭐ 638](https://github.com/alphaville/optimization-engine) ⭐ 643 | 🐛 12 | 🌐 Rust | 📅 2026-03-31

* 🟢 [ROS Motion Planning](https://github.com/ai-winter/ros_motion_planning) ⭐ 3,571 | 🐛 8 | 🌐 C++ | 📅 2026-04-24 - A computational problem that involves finding a sequence of valid configurations to move the robot from the source to the destination. Generally, it includes Path Searching and Trajectory Optimization. [⭐ 3.5k](https://github.com/ai-winter/ros_motion_planning) ⭐ 3,571 | 🐛 8 | 🌐 C++ | 📅 2026-04-24
* 🟢 [Ruckig](https://github.com/pantor/ruckig) ⭐ 1,341 | 🐛 29 | 🌐 C++ | 📅 2026-07-15 - Real-time, time-optimal and jerk-constrained online trajectory generation. [⭐ 1.3k](https://github.com/pantor/ruckig) ⭐ 1,341 | 🐛 29 | 🌐 C++ | 📅 2026-07-15
* 🟢 [Python Motion Planning](https://github.com/ai-winter/python_motion_planning) ⭐ 1,072 | 🐛 2 | 🌐 Python | 📅 2026-06-02 - Provides the implementations of common `Motion planning` algorithms, including path planners on N-D grid, controllers for path-tracking, curve generators, a visualizer based on matplotlib and a toy physical simulator to test controllers. [⭐ 1.1k](https://github.com/ai-winter/python_motion_planning) ⭐ 1,072 | 🐛 2 | 🌐 Python | 📅 2026-06-02
* 🟢 [TOPP-RA](https://hungpham2511.github.io/toppra/) - Time-parameterizing robot trajectories subject to kinematic and dynamic constraints. [⭐ 896](https://github.com/hungpham2511/toppra) ⭐ 922 | 🐛 41 | 🌐 Python | 📅 2026-07-28
* 🔴 ROS Behavior Tree - Behavior tree implementation for ROS-based robot task planning. [⭐ 364](https://github.com/miccol/ROS-Behavior-Tree) ⭐ 364 | 🐛 2 | 🌐 C++ | 📅 2018-10-22
* 💀 pymanoid - Humanoid robotics prototyping environment based on OpenRAVE. [⭐ 232](https://github.com/stephane-caron/pymanoid) ⚠️ Archived
* 🟡 [Ungar](https://github.com/fdevinc/ungar) ⭐ 108 | 🐛 5 | 🌐 C++ | 📅 2024-07-16 - Expressive and efficient implementation of optimal control problems using template metaprogramming. [⭐ 108](https://github.com/fdevinc/ungar) ⭐ 108 | 🐛 5 | 🌐 C++ | 📅 2024-07-16
* 🟢 [The Kautham Project](https://sir.upc.es/projects/kautham/) - A robot simulation toolkit for motion planning. [⭐ 24](https://github.com/iocroblab/kautham) ⭐ 24 | 🐛 0 | 🌐 C++ | 📅 2026-07-24

###### Motion Optimizer

* 🔴 [towr](http://wiki.ros.org/towr) - A light-weight, Eigen-based C++ library for trajectory optimization for legged robots. [⭐ 1.1k](https://github.com/ethz-adrl/towr) ⭐ 1,076 | 🐛 27 | 🌐 C++ | 📅 2023-04-17
* 🔴 [trajopt](http://rll.berkeley.edu/trajopt/doc/sphinx_build/html/) - Framework for generating robot trajectories by local optimization. [⭐ 462](https://github.com/joschu/trajopt) ⭐ 463 | 🐛 26 | 🌐 C++ | 📅 2022-12-05
* 🟡 TrajectoryOptimization - A fast trajectory optimization library written in Julia. [⭐ 394](https://github.com/RoboticExplorationLab/TrajectoryOptimization.jl) ⭐ 395 | 🐛 22 | 🌐 Julia | 📅 2025-03-27
* 🔴 TopiCo - Time-optimal Trajectory Generation and Control. [⭐ 147](https://github.com/AIS-Bonn/TopiCo) ⭐ 147 | 🐛 5 | 🌐 C++ | 📅 2021-07-12

###### Nearest Neighbor

* 🟢 [nanoflann](http://www.cs.ubc.ca/research/flann/) - Nearest Neighbor search with KD-trees. [⭐ 2.7k](https://github.com/jlblancoc/nanoflann) ⭐ 2,668 | 🐛 43 | 🌐 C++ | 📅 2026-08-13
* 🔴 [FLANN](http://www.cs.ubc.ca/research/flann/) - Fast Library for Approximate Nearest Neighbors. [⭐ 2.4k](https://github.com/flann-lib/flann) ⭐ 2,373 | 🐛 298 | 🌐 C++ | 📅 2024-07-29
* 🔴 [Cover-Tree](http://hunch.net/~jl/projects/cover_tree/cover_tree.html) - Cover tree data structure for quick k-nearest-neighbor search. [⭐ 64](https://github.com/DNCrane/Cover-Tree) ⭐ 64 | 🐛 5 | 🌐 C++ | 📅 2018-02-13
  * [Faster cover trees](http://proceedings.mlr.press/v37/izbicki15.pdf) - by Mike Izbicki et al., ICML 2015.

###### 3D Mapping

* 🟢 [PCL](https://pointclouds.org/) - 2D/3D image and point cloud processing. [⭐ 11k](https://github.com/PointCloudLibrary/pcl) ⭐ 11,092 | 🐛 585 | 🌐 C++ | 📅 2026-08-18
* 🟢 [Goxel](https://guillaumechereau.github.io/goxel/) - Free and open source 3D voxel editor. [⭐ 3.2k](https://github.com/guillaumechereau/goxel) ⭐ 3,177 | 🐛 129 | 🌐 C++ | 📅 2026-07-26
* 🟢 [OctoMap](http://octomap.github.io/) - Efficient Probabilistic 3D Mapping Framework Based on Octrees. [⭐ 2.3k](https://github.com/OctoMap/octomap) ⭐ 2,359 | 🐛 44 | 🌐 C++ | 📅 2026-08-02
* 🟢 [libpointmatcher](http://libpointmatcher.readthedocs.io/en/latest/) - Iterative Closest Point library for 2-D/3-D mapping in Robotics. [⭐ 1.8k](https://github.com/norlab-ulaval/libpointmatcher) ⭐ 1,827 | 🐛 100 | 🌐 C++ | 📅 2025-10-29
* 🔴 voxblox - Flexible voxel-based mapping focusing on truncated and Euclidean signed distance fields. [⭐ 1.6k](https://github.com/ethz-asl/voxblox) ⭐ 1,663 | 🐛 77 | 🌐 C++ | 📅 2024-07-01
* 🟢 Bonxai - Brutally fast, sparse, 3D Voxel Grid (formerly Treexy). [⭐ 861](https://github.com/facontidavide/Bonxai) ⭐ 867 | 🐛 8 | 🌐 C++ | 📅 2026-07-17
* 🟡 [wavemap](https://projects.asl.ethz.ch/wavemap/) - Fast, efficient and accurate multi-resolution, multi-sensor 3D occupancy mapping. [⭐ 562](https://github.com/ethz-asl/wavemap) ⭐ 568 | 🐛 12 | 🌐 C++ | 📅 2024-12-30
* 🔴 Octree - Fast radius neighbor search with an Octree. [⭐ 377](https://github.com/jbehley/octree) ⭐ 378 | 🐛 2 | 🌐 C++ | 📅 2019-12-17
* Utility Software

### [Optimization](#contents)

*Numerical optimization solvers and frameworks used in robotics.*

* 🟢 [Ceres Solver](http://ceres-solver.org/) - Large scale nonlinear optimization library. [⭐ 4.5k](https://github.com/ceres-solver/ceres-solver) ⭐ 4,540 | 🐛 69 | 🌐 C++ | 📅 2026-08-19
* 🟢 [CasADi](https://github.com/casadi/casadi/wiki) ⭐ 2,273 | 🐛 738 | 🌐 C++ | 📅 2026-08-17 - Symbolic framework for algorithmic differentiation and numeric optimization. [⭐ 2.2k](https://github.com/casadi/casadi) ⭐ 2,273 | 🐛 738 | 🌐 C++ | 📅 2026-08-17
* 🟢 [NLopt](https://nlopt.readthedocs.io/en/latest/) - Nonlinear optimization. [⭐ 2.2k](https://github.com/stevengj/nlopt) ⭐ 2,265 | 🐛 94 | 🌐 C | 📅 2026-06-06
* 🟢 [OSQP](https://osqp.org/) - The Operator Splitting QP Solver. [⭐ 2.2k](https://github.com/osqp/osqp) ⭐ 2,174 | 🐛 127 | 🌐 C | 📅 2026-01-12
* 🟢 [Ipopt](https://projects.coin-or.org/Ipopt) - Large scale nonlinear optimization library. [⭐ 1.8k](https://github.com/coin-or/Ipopt) ⭐ 1,778 | 🐛 16 | 🌐 C++ | 📅 2026-05-25
* 🟢 [Pagmo](https://esa.github.io/pagmo2/index.html) - Scientific library for massively parallel optimization. [⭐ 927](https://github.com/esa/pagmo2) ⭐ 934 | 🐛 59 | 🌐 C++ | 📅 2026-05-23
* 🔴 [OptimLib](https://github.com/kthohr/optim) ⭐ 899 | 🐛 12 | 🌐 C++ | 📅 2024-04-28 - Lightweight C++ library of numerical optimization methods for nonlinear functions. [⭐ 896](https://github.com/kthohr/optim) ⭐ 899 | 🐛 12 | 🌐 C++ | 📅 2024-04-28
* 🟢 ifopt - An Eigen-based, light-weight C++ Interface to Nonlinear Programming Solvers (Ipopt, Snopt). [⭐ 861](https://github.com/ethz-adrl/ifopt) ⭐ 865 | 🐛 18 | 🌐 C++ | 📅 2025-11-03
* 🟢 [HYPRE](https://hypre.readthedocs.io/) - Parallel solvers for sparse linear systems featuring multigrid methods. [⭐ 843](https://github.com/hypre-space/hypre) ⭐ 852 | 🐛 179 | 🌐 C | 📅 2026-08-18
* 🟢 qpsolvers - Quadratic Programming solvers in Python with a unified API. [⭐ 753](https://github.com/qpsolvers/qpsolvers) ⭐ 757 | 🐛 5 | 🌐 Python | 📅 2026-07-23
* 🟢 hpipm - High-performance interior-point-method QP solvers (Ipopt, Snopt). [⭐ 689](https://github.com/giaf/hpipm) ⭐ 699 | 🐛 49 | 🌐 C | 📅 2026-08-14
* 🟢 [SCS](http://web.stanford.edu/~boyd/papers/scs.html) - Numerical optimization for solving large-scale convex cone problems. [⭐ 626](https://github.com/cvxgrp/scs) ⭐ 629 | 🐛 55 | 🌐 C | 📅 2026-08-14
* 🟢 [ProxSuite](https://simple-robotics.github.io/proxsuite/) - The Advanced Proximal Optimization Toolbox. [⭐ 574](https://github.com/Simple-Robotics/ProxSuite) ⭐ 585 | 🐛 20 | 🌐 C++ | 📅 2026-08-01
* 🟢 libcmaes - Blackbox stochastic optimization using the CMA-ES algorithm. [⭐ 367](https://github.com/CMA-ES/libcmaes) ⭐ 368 | 🐛 55 | 🌐 C++ | 📅 2026-07-02
* 🔴 [limbo](http://www.resibots.eu/limbo/) - Gaussian processes and Bayesian optimization of black-box functions. [⭐ 267](https://github.com/resibots/limbo) ⭐ 269 | 🐛 20 | 🌐 C++ | 📅 2023-10-18
* 🔴 sferes2 - Evolutionary computation. [⭐ 169](https://github.com/sferes2/sferes2) ⭐ 170 | 🐛 22 | 🌐 C++ | 📅 2022-07-11
* 🔴 EXOTica - Generic optimisation toolset for robotics platforms. [⭐ 163](https://github.com/ipab-slmc/exotica) ⭐ 163 | 🐛 57 | 🌐 C++ | 📅 2026-08-14
* 🟢 SHOT - A solver for mixed-integer nonlinear optimization problems. [⭐ 131](https://github.com/coin-or/SHOT) ⭐ 131 | 🐛 10 | 🌐 C++ | 📅 2026-07-17
* 🟡 [RobOptim](http://roboptim.net/index.html) - Numerical Optimization for Robotics. [⭐ 64](https://github.com/roboptim/roboptim-core) ⭐ 64 | 🐛 11 | 🌐 C++ | 📅 2025-03-21
* 🔴 [pymoo](https://www.pymoo.org/) - Multi-objective Optimization in Python. [⭐ 26](https://github.com/msu-coinlab/pymoo) ⭐ 26 | 🐛 0 | 📅 2023-04-19
* 💀 lpsolvers - Linear Programming solvers in Python with a unified API. [⭐ 25](https://github.com/stephane-caron/lpsolvers) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2026-04-09
* 🟢 eigen-qld - Interface to use the QLD QP solver with the Eigen3 library. [⭐ 17](https://github.com/jrl-umi3218/eigen-qld) ⭐ 17 | 🐛 2 | 🌐 C | 📅 2026-07-13

### [Robot Modeling](#contents)

*Tools and formats for describing robot models.*

###### Robot Model Description Format

* [SDF](http://sdformat.org/) - XML format that describes objects and environments for robot simulators, visualization, and control. \[[bitbucket](https://bitbucket.org/osrf/sdformat)]
* 🟢 [urdf](http://wiki.ros.org/urdf) - XML format for representing a robot model. [⭐ 132](https://github.com/ros/urdfdom) ⭐ 133 | 🐛 57 | 🌐 C++ | 📅 2026-07-30

###### Utility to Build Robot Models

* 🟢 phobos - Add-on for Blender creating URDF and SMURF robot models. [⭐ 893](https://github.com/dfki-ric/phobos) ⭐ 899 | 🐛 14 | 🌐 Python | 📅 2026-07-14
* 🟢 [onshape-to-robot](https://github.com/Rhoban/onshape-to-robot) ⭐ 591 | 🐛 24 | 🌐 Python | 📅 2026-06-19 - Converting OnShape assembly to robot definition (SDF or URDF) through OnShape API. [⭐ 562](https://github.com/Rhoban/onshape-to-robot) ⭐ 591 | 🐛 24 | 🌐 Python | 📅 2026-06-19

### [Robot Platform](#contents)

*Middleware and frameworks for building robot software systems.*

* 🟢 [ROS 2](https://github.com/ros2/ros2/wiki) ⭐ 5,911 | 🐛 148 | 📅 2026-08-06 - Version 2.0 of the Robot Operating System (ROS) software stack. [⭐ 5.7k](https://github.com/ros2/ros2) ⭐ 5,911 | 🐛 148 | 📅 2026-08-06
* 🔴 [Linorobot](https://linorobot.org/) - ROS compatible ground robots. [⭐ 1.1k](https://github.com/linorobot/linorobot) ⭐ 1,109 | 🐛 27 | 🌐 C++ | 📅 2023-05-10
  * 🔴 onine - Service Robot based on Linorobot and Braccio Arm. [⭐ 49](https://github.com/grassjelly/onine) ⭐ 50 | 🐛 1 | 🌐 C++ | 📅 2018-09-19
* 🔴 [AutoRally](http://autorally.github.io/) - High-performance testbed for advanced perception and control research. [⭐ 786](https://github.com/autorally/autorally) ⭐ 789 | 🐛 13 | 🌐 C++ | 📅 2023-03-03
* 🟢 [YARP](https://www.yarp.it/) - Communication and device interfaces applicable from humanoids to embedded devices. [⭐ 596](https://github.com/robotology/yarp) ⭐ 602 | 🐛 251 | 🌐 C++ | 📅 2026-08-18
* 🟢 [ros2\_medkit](https://selfpatch.github.io/ros2_medkit/) - Structured fault management for ROS 2 — persistent fault lifecycle, REST/SSE API, root cause correlation, and automatic rosbag capture on fault. Inspired by SOVD (Service-Oriented Vehicle Diagnostics), the ASAM standard that brings HTTP/REST diagnostics to automotive and robotics. [⭐ 233](https://github.com/selfpatch/ros2_medkit) ⭐ 250 | 🐛 68 | 🌐 C++ | 📅 2026-08-17
* 🟡 [Micro-ROS for Arduino](https://github.com/kaiaai/micro_ros_arduino_kaiaai) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2024-10-28 - a Micro-ROS fork available in the Arduino Library Manager. [⭐ 12](https://github.com/kaiaai/micro_ros_arduino_kaiaai) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2024-10-28
* [Rock](https://www.rock-robotics.org/) - Software framework for robotic systems.
* [ROS](https://www.ros.org/) - Flexible framework for writing robot software.

### [Reinforcement Learning for Robotics](#contents)

*Reinforcement learning libraries commonly used in robotic control.*

* 🟢 [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) ⭐ 13,708 | 🐛 86 | 🌐 Python | 📅 2026-08-17 - Reliable implementations of reinforcement learning algorithms in PyTorch. [⭐ 13.5k](https://github.com/DLR-RM/stable-baselines3) ⭐ 13,708 | 🐛 86 | 🌐 Python | 📅 2026-08-17
* 🟢 [CleanRL](https://github.com/vwxyzjn/cleanrl) ⭐ 10,289 | 🐛 109 | 🌐 Python | 📅 2026-04-20 - Single-file implementations of deep reinforcement learning algorithms. [⭐ 10k](https://github.com/vwxyzjn/cleanrl) ⭐ 10,289 | 🐛 109 | 🌐 Python | 📅 2026-04-20
* 🟢 [Isaac Lab](https://isaac-sim.github.io/IsaacLab) - GPU-accelerated open-source framework for robot learning built on NVIDIA Isaac Sim. [⭐ 7.5k](https://github.com/isaac-sim/IsaacLab) ⭐ 7,914 | 🐛 782 | 🌐 Python | 📅 2026-08-19
* 🟢 [Brax](https://github.com/google/brax) ⭐ 3,220 | 🐛 113 | 🌐 Jupyter Notebook | 📅 2026-08-06 - Massively parallel differentiable rigid body physics engine in JAX for robotics and RL. [⭐ 3.2k](https://github.com/google/brax) ⭐ 3,220 | 🐛 113 | 🌐 Jupyter Notebook | 📅 2026-08-06
* 🟢 [rl\_games](https://github.com/Denys88/rl_games) ⭐ 1,381 | 🐛 64 | 🌐 Jupyter Notebook | 📅 2026-08-18 - High-performance RL library used in Isaac Gym environments. [⭐ 1.4k](https://github.com/Denys88/rl_games) ⭐ 1,381 | 🐛 64 | 🌐 Jupyter Notebook | 📅 2026-08-18
* 🟢 [SKRL](https://github.com/Toni-SM/skrl) ⭐ 1,089 | 🐛 28 | 🌐 Python | 📅 2026-05-11 - Modular reinforcement learning library with support for multiple ML frameworks. [⭐ 1.1k](https://github.com/Toni-SM/skrl) ⭐ 1,089 | 🐛 28 | 🌐 Python | 📅 2026-05-11

### [SLAM](#contents)

*Simultaneous Localization and Mapping libraries.*

* 🔴 ORB-SLAM2 - Real-time SLAM library for Monocular, Stereo and RGB-D cameras. [⭐ 10.2k](https://github.com/raulmur/ORB_SLAM2) ⭐ 10,212 | 🐛 805 | 🌐 C++ | 📅 2024-05-15
* 🔴 Cartographer - Real-time SLAM in 2D and 3D across multiple platforms and sensor configurations. [⭐ 7.9k](https://github.com/cartographer-project/cartographer) ⭐ 7,948 | 🐛 242 | 🌐 C++ | 📅 2024-01-05
* 🟢 [RTAP-Map](http://introlab.github.io/rtabmap/) - RGB-D Graph SLAM approach based on a global Bayesian loop closure detector. [⭐ 3.9k](https://github.com/introlab/rtabmap) ⭐ 3,951 | 🐛 578 | 🌐 C++ | 📅 2026-08-19
* 🟢 GTSAM - Smoothing and mapping (SAM) in robotics and vision. [⭐ 3.6k](https://github.com/borglab/gtsam) ⭐ 3,640 | 🐛 19 | 🌐 Jupyter Notebook | 📅 2026-08-19
* 🔴 [LSD-SLAM](https://vision.in.tum.de/research/vslam/lsdslam) - Real-time monocular SLAM. [⭐ 2.7k](https://github.com/tum-vision/lsd_slam) ⭐ 2,720 | 🐛 240 | 🌐 C++ | 📅 2023-03-23
* 🔴 [DSO](https://vision.in.tum.de/research/vslam/dso) - Novel direct and sparse formulation for Visual Odometry. [⭐ 2.4k](https://github.com/JakobEngel/dso) ⭐ 2,451 | 🐛 138 | 🌐 C++ | 📅 2024-02-23
* 🟢 ElasticFusion - Real-time dense visual SLAM system. [⭐ 1.9k](https://github.com/mp3guy/ElasticFusion) ⭐ 1,926 | 🐛 4 | 🌐 C++ | 📅 2025-08-03
* 🔴 Kintinuous - Real-time large scale dense visual SLAM system. [⭐ 954](https://github.com/mp3guy/Kintinuous) ⭐ 954 | 🐛 43 | 🌐 C++ | 📅 2022-08-26
* 🟢 [fiducials](http://wiki.ros.org/fiducials) - Simultaneous localization and mapping using fiducial markers. [⭐ 281](https://github.com/UbiquityRobotics/fiducials) ⭐ 284 | 🐛 38 | 🌐 C | 📅 2025-11-27
* 🔴 AprilSAM - Real-time smoothing and mapping. [⭐ 238](https://github.com/xipengwang/AprilSAM) ⭐ 238 | 🐛 1 | 🌐 C | 📅 2021-07-17
* 🔴 [SRBA](http://mrpt.github.io/srba/) - Solving SLAM/BA in relative coordinates with flexibility for different submapping strategies. [⭐ 75](https://github.com/MRPT/srba) ⭐ 75 | 🐛 6 | 🌐 C++ | 📅 2018-09-30

#### SLAM Dataset

* 🟡 [Awesome SLAM Datasets](https://github.com/youngguncho/awesome-slam-datasets) ⭐ 1,942 | 🐛 14 | 📅 2024-12-13 - Curated list of SLAM-related datasets. [⭐ 1.9k](https://github.com/youngguncho/awesome-slam-datasets) ⭐ 1,942 | 🐛 14 | 📅 2024-12-13

### [Vision](#contents)

*Computer vision libraries for robotic perception.*

* 🟢 [ViSP](http://visp.inria.fr/) - Visual Servoing Platform. [⭐ 893](https://github.com/lagadic/visp) ⭐ 908 | 🐛 3 | 🌐 C++ | 📅 2026-08-17
* 🟢 [BundleTrack](https://github.com/wenbowen123/BundleTrack) ⭐ 686 | 🐛 12 | 🌐 C++ | 📅 2026-04-13 - 6D Pose Tracking for Novel Objects without 3D Models. [⭐ 681](https://github.com/wenbowen123/BundleTrack) ⭐ 686 | 🐛 12 | 🌐 C++ | 📅 2026-04-13
* 🔴 [se(3)-TrackNet](https://github.com/wenbowen123/iros20-6d-pose-tracking) ⭐ 423 | 🐛 10 | 🌐 Python | 📅 2023-08-30 - 6D Pose Tracking for Novel Objects without 3D Models. [⭐ 421](https://github.com/wenbowen123/iros20-6d-pose-tracking) ⭐ 423 | 🐛 10 | 🌐 Python | 📅 2023-08-30

### [Fluid](#contents)

*Fluid dynamics simulation libraries.*

* 🔴 [Fluid Engine Dev - Jet](https://fluidenginedevelopment.org/) - Fluid simulation engine for computer graphics applications. [⭐ 2.1k](https://github.com/doyubkim/fluid-engine-dev) ⭐ 2,097 | 🐛 60 | 🌐 C++ | 📅 2023-12-24
* 🟢 [Ptera Software](https://docs.pterasoftware.com/) - Ptera Software is a fast, easy-to-use, and open-source software package for analyzing flapping-wing flight. [⭐ 250](https://github.com/camUrban/PteraSoftware) ⭐ 262 | 🐛 48 | 🌐 Python | 📅 2026-08-17

### [Grasping](#contents)

*Libraries and tools for robotic grasping and manipulation.*

* 🟢 [AnyGrasp SDK](https://github.com/graspnet/anygrasp_sdk) ⭐ 967 | 🐛 62 | 🌐 Python | 📅 2026-07-13 - SDK for AnyGrasp, a 6-DoF grasp pose detection method. [⭐ 905](https://github.com/graspnet/anygrasp_sdk) ⭐ 967 | 🐛 62 | 🌐 Python | 📅 2026-07-13
* 🟡 [Contact-GraspNet](https://github.com/NVlabs/contact_graspnet) ⭐ 522 | 🐛 25 | 🌐 Python | 📅 2024-11-21 - 6-DoF grasp generation for parallel-jaw grippers using contact maps. [⭐ 507](https://github.com/NVlabs/contact_graspnet) ⭐ 522 | 🐛 25 | 🌐 Python | 📅 2024-11-21
* 🟡 [GraspNet API](https://github.com/graspnet/graspnetAPI) ⭐ 362 | 🐛 15 | 🌐 Python | 📅 2026-06-29 - Python API and evaluation tools for the GraspNet benchmark. [⭐ 354](https://github.com/graspnet/graspnetAPI) ⭐ 362 | 🐛 15 | 🌐 Python | 📅 2026-06-29
* 🔴 [GraspIt!](https://graspit-simulator.github.io/) - Simulator for grasping research that can accommodate arbitrary hand and robot designs. [⭐ 216](https://github.com/graspit-simulator/graspit) ⭐ 218 | 🐛 36 | 🌐 C++ | 📅 2021-04-19

### [Humanoid Robotics](#contents)

*Environments and models for humanoid robot research.*

* 🟢 [MuJoCo Menagerie](https://github.com/google-deepmind/mujoco_menagerie) ⭐ 3,837 | 🐛 49 | 🌐 Python | 📅 2026-08-09 - Collection of well-tuned MuJoCo models for research and development. [⭐ 3.6k](https://github.com/google-deepmind/mujoco_menagerie) ⭐ 3,837 | 🐛 49 | 🌐 Python | 📅 2026-08-09
* 🟡 [Legged Gym](https://github.com/leggedrobotics/legged_gym) ⭐ 3,094 | 🐛 59 | 🌐 Python | 📅 2025-05-29 - Isaac Gym environments for legged robot locomotion training. [⭐ 3k](https://github.com/leggedrobotics/legged_gym) ⭐ 3,094 | 🐛 59 | 🌐 Python | 📅 2025-05-29
* 🟡 [Humanoid-Gym](https://github.com/roboterax/humanoid-gym) ⭐ 2,070 | 🐛 24 | 🌐 Python | 📅 2025-01-26 - Reinforcement learning environment for humanoid robot locomotion. [⭐ 2k](https://github.com/roboterax/humanoid-gym) ⭐ 2,070 | 🐛 24 | 🌐 Python | 📅 2025-01-26
* 🟢 [iCub](http://www.icub.org/) - Open-source cognitive humanoid robotic platform for embodied cognition research. [⭐ 119](https://github.com/robotology/icub-main) ⭐ 120 | 🐛 18 | 🌐 C++ | 📅 2026-08-10

### [Multiphysics](#contents)

*Frameworks for coupled multi-physics simulations.*

* 🟢 [Kratos](http://www.cimne.com/kratos/) - Framework for building parallel multi-disciplinary simulation software. [⭐ 1.3k](https://github.com/KratosMultiphysics/Kratos) ⭐ 1,315 | 🐛 742 | 🌐 C++ | 📅 2026-08-19

### [Math](#contents)

*Mathematics libraries for spatial algebra, Lie groups, and linear algebra.*

* 🔴 Sophus - Lie groups using Eigen. [⭐ 2.4k](https://github.com/strasdat/Sophus) ⭐ 2,446 | 🐛 15 | 🌐 C++ | 📅 2024-07-06
* 🟢 manif - Small c++11 header-only library for Lie theory. [⭐ 1.8k](https://github.com/artivis/manif) ⭐ 1,803 | 🐛 38 | 🌐 C++ | 📅 2026-08-05
* 🔴 linalg.h - Single header public domain linear algebra library for C++11. [⭐ 957](https://github.com/sgorsten/linalg) ⭐ 960 | 🐛 6 | 🌐 C++ | 📅 2023-07-02
* 🟢 Fastor - Light-weight high performance tensor algebra framework in C++11/14/17. [⭐ 839](https://github.com/romeric/Fastor) ⭐ 843 | 🐛 36 | 🌐 C++ | 📅 2025-07-08
* 🟢 spatialmath-python - Python classes for pose and orientation in 2D/3D with spatial operations toolbox. [⭐ 633](https://github.com/bdaiinstitute/spatialmath-python) ⭐ 639 | 🐛 30 | 🌐 Python | 📅 2026-08-13
* 🟢 SpaceVelAlg - Spatial vector algebra with the Eigen3. [⭐ 82](https://github.com/jrl-umi3218/SpaceVecAlg) ⭐ 81 | 🐛 6 | 🌐 C++ | 📅 2026-07-25

### [ETC](#contents)

*Other robotics-related tools and utilities.*

* [Foxglove Studio](https://foxglove.dev) - A fully integrated visualization and debugging desktop app for your robotics data.
* 🟢 fuse - General architecture for performing sensor fusion live on a robot. [⭐ 868](https://github.com/locusrobotics/fuse) ⭐ 874 | 🐛 49 | 🌐 C++ | 📅 2026-08-15

## [Simulators](#contents)

*Simulation environments for testing and developing robotic systems.*

###### Free or Open Source

* 🟢 AirSim - Simulator based on Unreal Engine for autonomous vehicles. [⭐ 18.3k](https://github.com/Microsoft/AirSim) ⭐ 18,408 | 🐛 780 | 🌐 C++ | 📅 2026-06-30
* 🟢 [PyBullet](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.2ye70wns7io3) - An easy to use simulator for robotics and deep reinforcement learning. [⭐ 14.6k](https://github.com/bulletphysics/bullet3) ⭐ 14,683 | 🐛 423 | 🌐 C++ | 📅 2025-10-22
* 🟢 [CARLA](https://carla.org/) - Open-source simulator for autonomous driving research. [⭐ 14.1k](https://github.com/carla-simulator/carla) ⭐ 14,302 | 🐛 1,190 | 🌐 C++ | 📅 2026-08-18
* 🟢 [Webots](http://www.cyberbotics.com/) - Development environment to model, program, and simulate robots and mechanical systems. [⭐ 4.4k](https://github.com/cyberbotics/webots) ⭐ 4,561 | 🐛 229 | 🌐 C++ | 📅 2026-08-18
* 🟢 [Isaac Sim](https://developer.nvidia.com/isaac/sim) - NVIDIA's GPU-accelerated robotics simulation platform with PhysX 5 and RTX rendering. [⭐ 3.6k](https://github.com/isaac-sim/IsaacSim) ⭐ 3,908 | 🐛 55 | 🌐 Python | 📅 2026-07-02
* 🟢 [Habitat-Sim](https://aihabitat.org/) - Simulation platform for research in embodied artificial intelligence. [⭐ 3.7k](https://github.com/facebookresearch/habitat-sim) ⭐ 3,794 | 🐛 270 | 🌐 C++ | 📅 2026-07-21
* 🟢 [ManiSkill](https://github.com/haosulab/ManiSkill) ⭐ 3,240 | 🐛 134 | 🌐 Python | 📅 2026-08-04 - Robot simulation and manipulation learning package powered by SAPIEN. [⭐ 3.1k](https://github.com/haosulab/ManiSkill) ⭐ 3,240 | 🐛 134 | 🌐 Python | 📅 2026-08-04
* 🟡 [Unity](https://unity.com/solutions/automotive-transportation-manufacturing/robotics) - Game engine with open-source robotics simulation tools and tutorials. [⭐ 2.5k](https://github.com/Unity-Technologies/Unity-Robotics-Hub) ⭐ 2,562 | 🐛 57 | 🌐 C# | 📅 2024-11-26
* 🟡 [AI2-THOR](https://ai2thor.allenai.org/) - Interactive household environment for embodied AI with Unity backend. [⭐ 1.8k](https://github.com/allenai/ai2thor) ⭐ 1,782 | 🐛 279 | 🌐 C# | 📅 2025-11-04
* 🟢 [Gazebo Sim](https://gazebosim.org/) - Open source robotics simulator (formerly Ignition Gazebo). [⭐ 1.4k](https://github.com/gazebosim/gz-sim) ⭐ 1,451 | 🐛 630 | 🌐 C++ | 📅 2026-08-19
* 💀 [Gazebo](https://gazebosim.org/) - Dynamic multi-robot simulator. [⭐ 1.3k](https://github.com/gazebosim/gazebo-classic) ⚠️ Archived
* 🟢 [SAPIEN](https://sapien.ucsd.edu) - Physics-rich simulation environment for articulated objects and manipulation. [⭐ 788](https://github.com/haosulab/SAPIEN) ⭐ 818 | 🐛 84 | 🌐 C++ | 📅 2026-07-18
* 🟢 [Hexapod Robot Simulator](https://hexapod.netlify.app/) - Open-source hexapod robot inverse kinematics and gaits visualizer. [⭐ 750](https://github.com/mithi/hexapod) ⭐ 782 | 🐛 17 | 🌐 JavaScript | 📅 2026-01-22
* 🔴 [Robot Gui](http://robot.glumb.de/) - A three.js based 3D robot interface. [⭐ 391](https://github.com/glumb/robot-gui) ⭐ 391 | 🐛 3 | 🌐 JavaScript | 📅 2023-06-26
* 🔴 [MORSE](http://morse-simulator.github.io/) - Modular open robots simulation engine. [⭐ 368](https://github.com/morse-simulator/morse) ⭐ 369 | 🐛 104 | 🌐 C | 📅 2022-05-13
* 🟢 [ARGoS](https://www.argos-sim.info/) - Physics-based simulator designed to simulate large-scale robot swarms. [⭐ 312](https://github.com/ilpincy/argos3) ⭐ 312 | 🐛 33 | 🌐 C++ | 📅 2026-02-12
* 🔴 [GraspIt!](http://graspit-simulator.github.io/) - Simulator for grasping research that can accommodate arbitrary hand and robot designs. [⭐ 216](https://github.com/graspit-simulator/graspit) ⭐ 218 | 🐛 36 | 🌐 C++ | 📅 2021-04-19
* 🟢 [CoppeliaSim](https://www.coppeliarobotics.com/) - Formaly V-REP. Virtual robot experimentation platform. [⭐ 148](https://github.com/CoppeliaRobotics/CoppeliaSimLib) ⭐ 149 | 🐛 1 | 🌐 C++ | 📅 2026-08-18
* 🟢 [ARTE](http://arvc.umh.es/arte/index_en.html) - Matlab toolbox focussed on robotic manipulators. [⭐ 103](https://github.com/4rtur1t0/ARTE) ⭐ 105 | 🐛 10 | 🌐 MATLAB | 📅 2026-04-29
* 🟡 [PyBullet\_Industrial](https://pybullet-industrial.readthedocs.io/en/latest/) - PyBullet extension for simulating robotic manufacturing processes like milling and 3D printing. [⭐ 54](https://github.com/WBK-Robotics/pybullet_industrial) ⭐ 56 | 🐛 17 | 🌐 Python | 📅 2025-06-17
* 🟡 [AVIS Engine](https://avisengine.com) - Fast simulation software for autonomous vehicle development. [⭐ 22](https://github.com/AvisEngine/AVIS-Engine-Python-API) ⭐ 22 | 🐛 9 | 🌐 Python | 📅 2025-05-20
* [Neurorobotics Platform](https://neurorobotics.net/) - Internet-accessible simulation of robots controlled by spiking neural networks. \[[bitbucket](https://bitbucket.org/hbpneurorobotics/neurorobotics-platform)]
* [Simbad](http://simbad.sourceforge.net/) - Java 3D robot simulator with custom controller and sensor support.

###### Commercial

* [Actin Simulation](http://www.energid.com/) - Real-time robot simulation and control software.
* [Artiminds](https://www.artiminds.com/) - Planning, programming, operation, analysis and optimization.
* [Kineo](https://www.plm.automation.siemens.com/global/en/products/plm-components/kineo.html) - Path planning and trajectory optimization for industrial robotics.
* [Robot Virtual Worlds](http://www.robotvirtualworlds.com/) - Virtual reality software for educational robotics.
* [RobotDK](https://robodk.com/) - Simulation and OLP for robots.
* [RobotStudio](https://www.abb.com/global/en/areas/robotics/products/software/robotstudio-suite) - ABB's simulation and offline programming software for robotics.
* [Virtual Robotics Toolkit](https://www.virtualroboticstoolkit.com/) - 3D virtual environment for programming and testing robots.
* [Visual Components](https://www.visualcomponents.com/) - 3D manufacturing simulation and visualization platform.

###### Cloud

* [AWS RoboMaker](https://aws.amazon.com/robomaker/) - Service that makes it easy to develop, test, and deploy intelligent robotics applications at scale.

## [Other Awesome Lists](#contents)

*Related curated lists of robotics and AI resources.*

* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) ⭐ 74,067 | 🐛 26 | 🌐 Python | 📅 2026-08-11 - Curated list of machine learning frameworks, libraries, and software.
* [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐ 30,319 | 🐛 50 | 🌐 Python | 📅 2026-08-17 - Python sample codes for robotics algorithms.
* [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 28,777 | 🐛 85 | 📅 2025-05-26 - Curated list of deep learning tutorials, projects, and communities.
* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) ⭐ 23,503 | 🐛 91 | 📅 2024-05-17 - Curated list of computer vision resources.
* [Awesome Artificial Intelligence](https://github.com/owainlewis/awesome-artificial-intelligence) ⭐ 15,896 | 🐛 68 | 🌐 Python | 📅 2026-08-15 - Curated list of AI courses, books, video lectures, and papers.
* [Awesome Robotics](https://github.com/Kiloreux/awesome-robotics) ⭐ 6,961 | 🐛 37 | 📅 2024-09-22 - Curated list of robotics resources (Kiloreux).
* [Robotics Coursework](https://github.com/mithi/robotics-coursework) ⭐ 5,124 | 🐛 3 | 📅 2026-05-11 - A list of robotics courses you can take online.
* [Awesome Robotic Tooling](https://github.com/Ly0n/awesome-robotic-tooling) ⭐ 3,881 | 🐛 13 | 📅 2023-11-20 - Tooling for professional robotic development in C++ and Python with ROS and autonomous driving.
* [Awesome Robotics](https://github.com/ahundt/awesome-robotics) ⭐ 1,476 | 🐛 8 | 📅 2024-01-10 - Curated list of robotics links and software libraries (ahundt).
* [Awesome Collision Detection](https://github.com/jslee02/awesome-collision-detection) ⭐ 1,041 | 🐛 2 | 🌐 Python | 📅 2026-08-17 - Curated list of collision detection libraries and resources.
* [Awesome Physical AI](https://github.com/keon/awesome-physical-ai) ⭐ 386 | 🐛 15 | 📅 2026-06-24 - Curated list of academic papers and resources on Physical AI.
* [Awesome VLA Study](https://github.com/MilkClouds/awesome-vla-study) ⭐ 358 | 🐛 0 | 📅 2026-03-21 - A curated VLA (Vision-Language-Action) study guide that organizes \~30 key papers into a 6-phase, 14-week reading curriculum — covering diffusion/flow matching foundations, robot foundation model architectures, data scaling, efficient inference, RL fine-tuning, and world models.
* [Awesome Gazebo](https://github.com/fkromer/awesome-gazebo) ⚠️ Archived - Curated list of Gazebo simulation framework resources.
* [Awesome Human Robot Interaction](https://github.com/Po-Jen/awesome-human-robot-interaction) ⭐ 152 | 🐛 0 | 📅 2019-02-12 - Curated list of human-robot interaction libraries and resources.
* [Awesome Grasping](https://github.com/Po-Jen/awesome-grasping) ⭐ 99 | 🐛 0 | 📅 2019-07-13 - Curated list of grasping libraries and resources.

## [Contributing](#contents)

Contributions are very welcome! Please read the [contribution guidelines](https://github.com/jslee02/awesome-robotics-libraries/blob/main/CONTRIBUTING.md) ⭐ 3,017 | 🐛 14 | 🌐 Python | 📅 2026-08-06 first. Also, please feel free to report any error.

## [Star History](#contents)

<a href="https://www.star-history.com/?repos=jslee02%2Fawesome-robotics-libraries">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=jslee02/awesome-robotics-libraries&type=date&theme=dark&legend=top-left" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=jslee02/awesome-robotics-libraries&type=date&legend=top-left" />
    <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=jslee02/awesome-robotics-libraries&type=date&legend=top-left" />
  </picture>
</a>

## [License](#contents)

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
