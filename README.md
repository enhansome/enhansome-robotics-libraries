# Awesome Robotics Libraries with stars

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of robotics libraries and simulators.

## Contents

* [Middleware & Frameworks](#middleware--frameworks)
* [Robot Hardware & Drivers](#robot-hardware--drivers)
* [Robot Description & Models](#robot-description--models)
* [Kinematics & Dynamics](#kinematics--dynamics)
* [Physics Engines](#physics-engines)
* [Simulators](#simulators)
* [Motion Planning & Navigation](#motion-planning--navigation)
* [Control](#control)
* [Optimization](#optimization)
* [Math & Geometry](#math--geometry)
* [SLAM & State Estimation](#slam--state-estimation)
* [Perception](#perception)
* [Grasping & Manipulation](#grasping--manipulation)
* [Robot Learning](#robot-learning)
* [Robot Data & Visualization](#robot-data--visualization)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

> **Legend**: 🟢 commit within 1 yr · 🟡 commit within 3 yr · 💀 archived · ⭐ GitHub stars as of 2026-10-12. Entries are ordered by stars; inactive entries (archived, or no commits for 3+ years) are folded at the end of each category.

## [Middleware & Frameworks](#contents)

*Communication middleware, robot software frameworks, runtime services such as launch and diagnostics, and agent orchestration for robots.*

* 🟢 [ROS 2](https://github.com/ros2/ros2/wiki) ⭐ 6,193 | 🐛 151 | 📅 2026-10-07 - Version 2.0 of the Robot Operating System (ROS) software stack. [⭐ 6.2k](https://github.com/ros2/ros2) ⭐ 6,193 | 🐛 151 | 📅 2026-10-07
* 🟢 [Dimensional](https://dimensional.org/) - Agentic operating system for physical space. [⭐ 4.6k](https://github.com/dimensionalOS/dimos) ⭐ 4,666 | 🐛 734 | 🌐 Python | 📅 2026-10-19
* 🟢 [YARP](https://www.yarp.it/) - Communication and device interfaces applicable from humanoids to embedded devices. [⭐ 603](https://github.com/robotology/yarp) ⭐ 604 | 🐛 250 | 🌐 C++ | 📅 2026-10-19
* 🟢 [ros2\_medkit](https://selfpatch.github.io/ros2_medkit/) - Fault management and diagnostics gateway for ROS 2 with a REST API. [⭐ 276](https://github.com/selfpatch/ros2_medkit) ⭐ 277 | 🐛 118 | 🌐 C++ | 📅 2026-10-19
* 🟢 [Robot Control Stack (RCS)](https://robotcontrolstack.org) - ROS-free Gymnasium framework unifying MuJoCo sim and real robots for robot learning. [⭐ 164](https://github.com/RobotControlStack/robot-control-stack) ⭐ 166 | 🐛 16 | 🌐 Python | 📅 2026-10-17
* 🟡 [Micro-ROS for Arduino](https://github.com/kaiaai/micro_ros_arduino_kaiaai) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2024-10-28 - a Micro-ROS fork available in the Arduino Library Manager. [⭐ 14](https://github.com/kaiaai/micro_ros_arduino_kaiaai) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2024-10-28
* [Rock](https://www.rock-robotics.org/) - Software framework for robotic systems.
* [ROS](https://www.ros.org/) - Flexible framework for writing robot software.

## [Robot Hardware & Drivers](#contents)

*Open robot platforms and hardware designs, and drivers or firmware for sensors and actuators.*

* 🟢 [iCub](http://www.icub.org/) - Open-source cognitive humanoid robotic platform for embodied cognition research. [⭐ 121](https://github.com/robotology/icub-main) ⭐ 121 | 🐛 20 | 🌐 C++ | 📅 2026-10-09

<details>
<summary>Inactive (3): archived or no commits for 3+ years</summary>

* [Linorobot](https://linorobot.org/) - ROS compatible ground robots. [⭐ 1.1k](https://github.com/linorobot/linorobot) ⭐ 1,112 | 🐛 27 | 🌐 C++ | 📅 2023-05-10 · last commit 2022
  * onine - Service Robot based on Linorobot and Braccio Arm. [⭐ 50](https://github.com/grassjelly/onine) ⭐ 50 | 🐛 1 | 🌐 C++ | 📅 2018-09-19 · last commit 2018
* [AutoRally](http://autorally.github.io/) - High-performance testbed for advanced perception and control research. [⭐ 791](https://github.com/autorally/autorally) ⭐ 793 | 🐛 13 | 🌐 C++ | 📅 2023-03-03 · last commit 2021

</details>

## [Robot Description & Models](#contents)

*Robot description formats (URDF, SDF, MJCF, USD), their parsers and exporters, and robot model collections.*

* 🟢 [MuJoCo Menagerie](https://github.com/google-deepmind/mujoco_menagerie) ⭐ 4,222 | 🐛 55 | 🌐 Python | 📅 2026-10-15 - Collection of well-tuned MuJoCo models for research and development. [⭐ 4.2k](https://github.com/google-deepmind/mujoco_menagerie) ⭐ 4,222 | 🐛 55 | 🌐 Python | 📅 2026-10-15
* 🟢 phobos - Add-on for Blender creating URDF and SMURF robot models. [⭐ 908](https://github.com/dfki-ric/phobos) ⭐ 909 | 🐛 15 | 🌐 Python | 📅 2026-07-14
* 🟢 [onshape-to-robot](https://github.com/Rhoban/onshape-to-robot) ⭐ 641 | 🐛 22 | 🌐 Python | 📅 2026-08-26 - Converting OnShape assembly to robot definition (SDF or URDF) through OnShape API. [⭐ 638](https://github.com/Rhoban/onshape-to-robot) ⭐ 641 | 🐛 22 | 🌐 Python | 📅 2026-08-26
* 🟢 [urdf](http://wiki.ros.org/urdf) - XML format for representing a robot model. [⭐ 138](https://github.com/ros/urdfdom) ⭐ 138 | 🐛 54 | 🌐 C++ | 📅 2026-10-06
* [SDF](http://sdformat.org/) - XML format that describes objects and environments for robot simulators, visualization, and control. \[[bitbucket](https://bitbucket.org/osrf/sdformat)]

## [Kinematics & Dynamics](#contents)

*Forward and inverse kinematics and rigid-body dynamics algorithms, without contact time-stepping.*

* 🟢 [pinocchio](https://stack-of-tasks.github.io/pinocchio/) - Fast and flexible algorithms for rigid-body dynamics with analytical derivatives. [⭐ 3.8k](https://github.com/stack-of-tasks/pinocchio) ⭐ 3,800 | 🐛 105 | 🌐 C++ | 📅 2026-10-19
* 🟡 [Robotics Library](https://www.roboticslibrary.org/) - Self-contained C++ library for robot kinematics, planning, and control. [⭐ 1.2k](https://github.com/roboticslibrary/rl) ⭐ 1,208 | 🐛 54 | 🌐 C++ | 📅 2025-04-15
* 🟢 [KDL](https://www.orocos.org/kdl.html) - Orocos Kinematics and Dynamics Library for kinematic chains. [⭐ 904](https://github.com/orocos/orocos_kinematics_dynamics) ⭐ 904 | 🐛 61 | 🌐 C++ | 📅 2026-09-23
* 🟡 [RBDL](https://rbdl.github.io/) - Rigid Body Dynamics Library based on Featherstone algorithms. [⭐ 708](https://github.com/rbdl/rbdl) ⭐ 709 | 🐛 33 | 🌐 C++ | 📅 2025-06-09
* 🟢 [PyDy](https://www.pydy.org/) - Multibody dynamics analysis with symbolic Python using SymPy. [⭐ 416](https://github.com/pydy/pydy) ⭐ 416 | 🐛 88 | 🌐 Python | 📅 2026-07-28
* 🟡 RigidBodyDynamics.jl - Julia library for rigid body dynamics algorithms. [⭐ 312](https://github.com/JuliaRobotics/RigidBodyDynamics.jl) ⭐ 312 | 🐛 40 | 🌐 Julia | 📅 2024-11-08
* 🟢 idyntree - Library for estimation and whole-body dynamics of floating-base robots. [⭐ 234](https://github.com/gbionics/idyntree) ⭐ 234 | 🐛 197 | 🌐 C++ | 📅 2026-10-13
* 🟢 RBDyn - Rigid body dynamics algorithms using spatial algebra with Eigen. [⭐ 224](https://github.com/jrl-umi3218/RBDyn) ⭐ 225 | 🐛 14 | 🌐 C++ | 📅 2026-10-12
* 🟢 [ARTE](http://arvc.umh.es/arte/index_en.html) - Matlab toolbox focussed on robotic manipulators. [⭐ 106](https://github.com/4rtur1t0/ARTE) ⭐ 106 | 🐛 10 | 🌐 MATLAB | 📅 2026-04-29
* [RobWork](https://robwork.dk/) - Framework for simulation and control of robot systems. \[[gitlab](https://gitlab.com/sdurobotics/RobWork)]

### Inverse Kinematics

* 🟢 IKBT - A python package to solve robot arm inverse kinematics in symbolic form. [⭐ 220](https://github.com/uw-biorobotics/IKBT) ⭐ 221 | 🐛 4 | 🌐 Python | 📅 2026-10-14
* 🟢 ssik - Analytical inverse kinematics for 6R and 7R revolute robot arms, returning every IK branch. [⭐ 188](https://github.com/personalrobotics/ssik) ⭐ 189 | 🐛 64 | 🌐 Python | 📅 2026-10-14
* 🟢 Kinpy - A simple pure python package to solve inverse kinematics. [⭐ 181](https://github.com/neka-nat/kinpy) ⭐ 182 | 🐛 4 | 🌐 Python | 📅 2026-10-17

<details>
<summary>Inactive (6): archived or no commits for 3+ years</summary>

* RelaxedIK - Real-time Synthesis of Accurate and Feasible Robot Arm Motion. [⭐ 254](https://github.com/uwgraphics/relaxed_ik) ⭐ 254 | 🐛 20 | 🌐 Python | 📅 2023-04-13 · last commit 2023
* [Robopy](https://adityadua24.github.io/robopy/) - Python robotics toolbox inspired by Peter Corke's Robotics Toolbox. [⭐ 229](https://github.com/adityadua24/robopy) ⭐ 229 | 🐛 6 | 🌐 Python | 📅 2021-02-10 · last commit 2021
* [Trip](https://trip-kinematics.readthedocs.io/en/main/index.html) - A python package that solves inverse kinematics of parallel-, serial- or hybrid-robots. [⭐ 43](https://github.com/TriPed-Robot/trip_kinematics) ⭐ 43 | 🐛 21 | 🌐 Python | 📅 2022-05-06 · last commit 2022
* [trep](http://murpheylab.github.io/trep/) - Simulation and optimal control using variational integrators. [⭐ 20](https://github.com/MurpheyLab/trep) ⭐ 20 | 🐛 4 | 🌐 C | 📅 2023-09-03 · last commit 2023
* 💀 metapod - Template-based robot dynamics library using spatial algebra. [⭐ 14](https://github.com/laas/metapod) ⚠️ Archived · last commit 2018
* Lively - A highly configurable toolkit for commanding robots in mixed modalities. [⭐ 8](https://github.com/Wisc-HCI/lively) ⭐ 8 | 🐛 2 | 🌐 Rust | 📅 2023-08-15 · last commit 2023

</details>

## [Physics Engines](#contents)

*Embeddable engines that time-step rigid, soft, fluid, or particle dynamics with contact. See also [Comparisons](COMPARISONS.md).*

* 🟢 [Genesis](https://genesis-world.readthedocs.io) - Generative and universal physics platform for robotics with GPU-accelerated parallel simulation. [⭐ 30k](https://github.com/Genesis-Embodied-AI/genesis-world) ⭐ 30,087 | 🐛 160 | 🌐 Python | 📅 2026-10-19
* 🟢 [MuJoCo](https://mujoco.org/) - Multi-joint dynamics with contact for physics-based simulation and control. [⭐ 15.6k](https://github.com/google-deepmind/mujoco) ⭐ 15,757 | 🐛 300 | 🌐 C++ | 📅 2026-10-19
* 🟢 [Bullet](https://pybullet.org/) - Real-time physics simulation for games, visual effects, and robotics. [⭐ 14.8k](https://github.com/bulletphysics/bullet3) ⭐ 14,805 | 🐛 435 | 🌐 C++ | 📅 2026-10-09
* 🟢 [Newton](https://newton-physics.github.io/newton/) - GPU-accelerated differentiable physics engine built on NVIDIA Warp for robotics simulation. [⭐ 5.8k](https://github.com/newton-physics/newton) ⭐ 5,806 | 🐛 462 | 🌐 Python | 📅 2026-10-19
* 🟢 [PhysX](https://nvidia-omniverse.github.io/PhysX/physx/5.5.0/index.html) - NVIDIA physics engine for real-time rigid body and vehicle simulation. [⭐ 4.8k](https://github.com/NVIDIA-Omniverse/PhysX) ⭐ 4,803 | 🐛 124 | 🌐 C++ | 📅 2026-10-15
* 🟢 [Drake](https://drake.mit.edu/) - Planning, control, and analysis toolbox for nonlinear dynamical systems. [⭐ 4.2k](https://github.com/RobotLocomotion/drake) ⭐ 4,229 | 🐛 649 | 🌐 C++ | 📅 2026-10-19
* 🟢 [Brax](https://github.com/google/brax) ⭐ 3,249 | 🐛 114 | 🌐 Jupyter Notebook | 📅 2026-10-07 - Massively parallel differentiable rigid body physics engine in JAX for robotics and RL. [⭐ 3.2k](https://github.com/google/brax) ⭐ 3,249 | 🐛 114 | 🌐 Jupyter Notebook | 📅 2026-10-07
* 🟢 [CHRONO::ENGINE](https://projectchrono.org/) - Multi-physics simulation of rigid and flexible bodies, granular, and fluid systems. [⭐ 3.1k](https://github.com/projectchrono/chrono) ⭐ 3,097 | 🐛 11 | 🌐 C++ | 📅 2026-10-19
* 🟢 [Simbody](https://simtk.org/home/simbody/) - Multibody dynamics library for biomechanical and mechanical systems. [⭐ 2.6k](https://github.com/simbody/simbody) ⭐ 2,561 | 🐛 147 | 🌐 C++ | 📅 2026-10-19
* 🟡 [ReactPhysics3d](https://www.reactphysics3d.com/) - Open-source 3D physics engine for rigid body simulation and collision detection. [⭐ 1.8k](https://github.com/DanielChappuis/reactphysics3d) ⭐ 1,776 | 🐛 93 | 🌐 C++ | 📅 2025-03-28
* 🟢 [DART](http://dartsim.github.io/) - Dynamic Animation and Robotics Toolkit for multibody simulation and planning. [⭐ 1.2k](https://github.com/dartsim/dart) ⭐ 1,217 | 🐛 9 | 🌐 C++ | 📅 2026-10-19
* 🟢 [Newton Dynamics](https://newtondynamics.com/) - Real-time physics engine for rigid body simulation. [⭐ 1k](https://github.com/MADEAPPS/newton-dynamics) ⭐ 1,022 | 🐛 1 | 🌐 HTML | 📅 2026-01-17
* 🟢 [siconos](https://nonsmooth.gricad-pages.univ-grenoble-alpes.fr/siconos/) - Nonsmooth dynamical systems modeling and simulation platform. [⭐ 186](https://github.com/siconos/siconos) ⭐ 187 | 🐛 11 | 🌐 C | 📅 2026-10-19
* 🟢 [MBSim](https://www.mbsim-env.de/) - Multi-body simulation environment for flexible and rigid systems. [⭐ 53](https://github.com/mbsim-env/mbsim) ⭐ 53 | 🐛 3 | 🌐 C++ | 📅 2026-10-17
* [IBDS](http://www.interactive-graphics.de/index.php/downloads/12-ibds) - Impulse-based dynamics simulation for rigid bodies and particle systems.
* [MBDyn](https://www.mbdyn.org/) - General-purpose multibody dynamics analysis software. \[[code](https://www.mbdyn.org/?Software_Download)]
* [ODE](https://ode.org/) - Open Dynamics Engine for simulating rigid body dynamics. \[[bitbucket](https://bitbucket.org/odedevs/ode)]

### Soft, Fluid & Multiphysics

* 🟢 PositionBasedDynamics - Position-based methods for simulating deformable objects and fluids. [⭐ 2.3k](https://github.com/InteractiveComputerGraphics/PositionBasedDynamics) ⭐ 2,291 | 🐛 11 | 🌐 C++ | 📅 2026-09-01
* 🟢 [Kratos](http://www.cimne.com/kratos/) - Framework for building parallel multi-disciplinary simulation software. [⭐ 1.4k](https://github.com/KratosMultiphysics/Kratos) ⭐ 1,385 | 🐛 745 | 🌐 C++ | 📅 2026-10-19
* 🟢 [SOFA](https://www.sofa-framework.org/) - Simulation Open Framework Architecture for medical and physics simulation. [⭐ 1.3k](https://github.com/sofa-framework/sofa) ⭐ 1,277 | 🐛 469 | 🌐 C++ | 📅 2026-10-19
* 🟢 [Ptera Software](https://docs.pterasoftware.com/) - Open-source package for analyzing flapping-wing flight. [⭐ 270](https://github.com/camUrban/PteraSoftware) ⭐ 270 | 🐛 36 | 🌐 Python | 📅 2026-10-18
* [ARCSim](http://graphics.berkeley.edu/resources/ARCSim/index.html) - Adaptive remeshing cloth and shell simulator for thin deformable objects.

<details>
<summary>Inactive (8): archived or no commits for 3+ years</summary>

* [Fluid Engine Dev - Jet](https://fluidenginedevelopment.org/) - Fluid simulation engine for computer graphics applications. [⭐ 2.1k](https://github.com/doyubkim/fluid-engine-dev) ⭐ 2,100 | 🐛 60 | 🌐 C++ | 📅 2023-12-24 · last commit 2022
* [nphysics](https://nphysics.org/) - 2D and 3D rigid body physics engine written in Rust. [⭐ 1.6k](https://github.com/dimforge/nphysics) ⭐ 1,648 | 🐛 44 | 🌐 Rust | 📅 2021-07-27 · last commit 2021
* Tiny Differentiable Simulator - Header-only differentiable physics engine for robotics. [⭐ 1.4k](https://github.com/erwincoumans/tiny-differentiable-simulator) ⭐ 1,376 | 🐛 12 | 🌐 C++ | 📅 2026-10-16 · last commit 2023
* 💀 qu3e - Lightweight 3D physics engine for rigid body dynamics. [⭐ 993](https://github.com/RandyGaul/qu3e) ⚠️ Archived · last commit 2021
* 💀 [Flex](https://developer.nvidia.com/flex) - GPU-based particle simulation for rigid bodies, fluids, and deformables. [⭐ 815](https://github.com/NVIDIAGameWorks/FleX) ⭐ 815 | 🐛 96 | 🌐 C++ | 📅 2021-04-15 · last commit 2021
* 💀 [RaiSim](https://slides.com/jeminhwangbo/raisim-manual) - Cross-platform physics engine for robotics and reinforcement learning. [⭐ 328](https://github.com/leggedrobotics/raisimLib) ⚠️ Archived · last commit 2020
* [Moby](http://physsim.sourceforge.net/index.html) - Multi-body dynamics simulation for rigid bodies with contact. [⭐ 37](https://github.com/PositronicsLab/Moby) ⭐ 37 | 🐛 2 | 🌐 C++ | 📅 2021-11-26 · last commit 2021
* [MBSlib](http://www.sim.informatik.tu-darmstadt.de/res/sw/mbslib) - Lightweight multibody system dynamics library. [⭐ 11](https://github.com/SIM-TU-Darmstadt/mbslib) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2016-08-17 · last commit 2016

</details>

## [Simulators](#contents)

*Simulation applications with worlds, sensors, rendering, and robot middleware bridges.*

* 🟢 AirSim - Simulator based on Unreal Engine for autonomous vehicles. [⭐ 18.5k](https://github.com/Microsoft/AirSim) ⭐ 18,562 | 🐛 781 | 🌐 C++ | 📅 2026-09-15
* 🟢 [PyBullet](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.2ye70wns7io3) - An easy to use simulator for robotics and deep reinforcement learning. [⭐ 14.8k](https://github.com/bulletphysics/bullet3) ⭐ 14,805 | 🐛 435 | 🌐 C++ | 📅 2026-10-09
* 🟢 [CARLA](https://carla.org/) - Open-source simulator for autonomous driving research. [⭐ 14.5k](https://github.com/carla-simulator/carla) ⭐ 14,505 | 🐛 1,206 | 🌐 C++ | 📅 2026-10-19
* 🟢 [Webots](http://www.cyberbotics.com/) - Development environment to model, program, and simulate robots and mechanical systems. [⭐ 4.7k](https://github.com/cyberbotics/webots) ⭐ 4,716 | 🐛 230 | 🌐 C++ | 📅 2026-10-16
* 🟢 [Isaac Sim](https://developer.nvidia.com/isaac/sim) - NVIDIA's GPU-accelerated robotics simulation platform with PhysX 5 and RTX rendering. [⭐ 4.2k](https://github.com/isaac-sim/IsaacSim) ⭐ 4,293 | 🐛 108 | 🌐 Python | 📅 2026-10-15
* 🟢 [Habitat-Sim](https://aihabitat.org/) - Simulation platform for research in embodied artificial intelligence. [⭐ 3.8k](https://github.com/facebookresearch/habitat-sim) ⭐ 3,845 | 🐛 270 | 🌐 C++ | 📅 2026-07-21
* 🟢 [Unity](https://unity.com/solutions/automotive-transportation-manufacturing/robotics) - Game engine with open-source robotics simulation tools and tutorials. [⭐ 2.6k](https://github.com/Unity-Technologies/Unity-Robotics-Hub) ⭐ 2,598 | 🐛 56 | 🌐 C# | 📅 2026-09-22
* 🟡 [AI2-THOR](https://ai2thor.allenai.org/) - Interactive household environment for embodied AI with Unity backend. [⭐ 1.8k](https://github.com/allenai/ai2thor) ⭐ 1,812 | 🐛 281 | 🌐 C# | 📅 2025-11-04
* 🟢 [Gazebo Sim](https://gazebosim.org/) - Open source robotics simulator (formerly Ignition Gazebo). [⭐ 1.5k](https://github.com/gazebosim/gz-sim) ⭐ 1,542 | 🐛 636 | 🌐 C++ | 📅 2026-10-18
* 🟢 [Rigs of Rods](https://www.rigsofrods.org/) - Soft-body vehicle simulator using beam physics. [⭐ 1.3k](https://github.com/RigsOfRods/rigs-of-rods) ⭐ 1,269 | 🐛 243 | 🌐 C++ | 📅 2026-10-16
* 🟢 [SAPIEN](https://sapien.ucsd.edu) - Physics-rich simulation environment for articulated objects and manipulation. [⭐ 853](https://github.com/haosulab/SAPIEN) ⭐ 857 | 🐛 88 | 🌐 C++ | 📅 2026-10-09
* 🟢 [Hexapod Robot Simulator](https://hexapod.netlify.app/) - Open-source hexapod robot inverse kinematics and gaits visualizer. [⭐ 796](https://github.com/mithi/hexapod) ⭐ 797 | 🐛 19 | 🌐 JavaScript | 📅 2026-01-22
* 🟢 [mvsim](http://wiki.ros.org/mvsim) - Lightweight multi-vehicle 2D simulator with ROS integration. [⭐ 417](https://github.com/MRPT/mvsim) ⭐ 417 | 🐛 4 | 🌐 C++ | 📅 2026-10-18
* 🟢 [ARGoS](https://www.argos-sim.info/) - Physics-based simulator designed to simulate large-scale robot swarms. [⭐ 321](https://github.com/ilpincy/argos3) ⭐ 322 | 🐛 33 | 🌐 C++ | 📅 2026-10-05
* 🟢 [CoppeliaSim](https://www.coppeliarobotics.com/) - Formaly V-REP. Virtual robot experimentation platform. [⭐ 152](https://github.com/CoppeliaRobotics/CoppeliaSimLib) ⭐ 152 | 🐛 1 | 🌐 C++ | 📅 2026-10-19
* 🟡 [MARS](http://rock-simulation.github.io/mars/) - Machina Arte Robotum Simulans — a cross-platform simulation environment. [⭐ 69](https://github.com/rock-simulation/mars) ⭐ 69 | 🐛 30 | 🌐 C++ | 📅 2025-09-01
* 🟡 [PyBullet\_Industrial](https://pybullet-industrial.readthedocs.io/en/latest/) - PyBullet extension for simulating robotic manufacturing processes like milling and 3D printing. [⭐ 56](https://github.com/WBK-Robotics/pybullet_industrial) ⭐ 56 | 🐛 17 | 🌐 Python | 📅 2025-06-17
* 🟡 [AVIS Engine](https://avisengine.com) - Fast simulation software for autonomous vehicle development. [⭐ 22](https://github.com/AvisEngine/AVIS-Engine-Python-API) ⭐ 22 | 🐛 9 | 🌐 Python | 📅 2025-05-20
* [Neurorobotics Platform](https://neurorobotics.net/) - Internet-accessible simulation of robots controlled by spiking neural networks. \[[bitbucket](https://bitbucket.org/hbpneurorobotics/neurorobotics-platform)]
* [Simbad](http://simbad.sourceforge.net/) - Java 3D robot simulator with custom controller and sensor support.

### Commercial

* [Actin Simulation](http://www.energid.com/) - Real-time robot simulation and control software.
* [Artiminds](https://www.artiminds.com/) - Planning, programming, operation, analysis and optimization.
* [Kineo](https://www.plm.automation.siemens.com/global/en/products/plm-components/kineo.html) - Path planning and trajectory optimization for industrial robotics.
* [Robot Virtual Worlds](http://www.robotvirtualworlds.com/) - Virtual reality software for educational robotics.
* [RobotDK](https://robodk.com/) - Simulation and OLP for robots.
* [RobotStudio](https://www.abb.com/global/en/areas/robotics/products/software/robotstudio-suite) - ABB's simulation and offline programming software for robotics.
* [Virtual Robotics Toolkit](https://www.virtualroboticstoolkit.com/) - 3D virtual environment for programming and testing robots.
* [Visual Components](https://www.visualcomponents.com/) - 3D manufacturing simulation and visualization platform.

<details>
<summary>Inactive (2): archived or no commits for 3+ years</summary>

* 💀 [Gazebo Classic](https://gazebosim.org/) - Dynamic multi-robot simulator. [⭐ 1.4k](https://github.com/gazebosim/gazebo-classic) ⚠️ Archived · last commit 2024
* [MORSE](http://morse-simulator.github.io/) - Modular open robots simulation engine. [⭐ 370](https://github.com/morse-simulator/morse) ⭐ 370 | 🐛 104 | 🌐 C | 📅 2022-05-13 · last commit 2022

</details>

## [Motion Planning & Navigation](#contents)

*Path planning, trajectory generation and time-parameterization, task and behavior planning, and navigation stacks.*

* 🟢 [ROS Motion Planning](https://github.com/ai-winter/ros_motion_planning) ⭐ 3,600 | 🐛 8 | 🌐 C++ | 📅 2026-04-24 - ROS planner and controller plugins for mobile robot navigation. [⭐ 3.6k](https://github.com/ai-winter/ros_motion_planning) ⭐ 3,600 | 🐛 8 | 🌐 C++ | 📅 2026-04-24
* 🟢 [OMPL](https://ompl.kavrakilab.org/) - Open motion planning library. [⭐ 2.2k](https://github.com/ompl/ompl) ⭐ 2,178 | 🐛 105 | 🌐 C++ | 📅 2026-09-25
* 🟢 [MoveIt!](https://moveit.ai/) - Motion planning framework. [⭐ 2.1k](https://github.com/moveit/moveit) ⭐ 2,097 | 🐛 622 | 🌐 C++ | 📅 2026-07-20
* 🟢 [cuRobo](https://curobo.org) - A CUDA accelerated library containing a suite of robotics algorithms that run significantly faster. [⭐ 1.9k](https://github.com/nvlabs/curobo) ⭐ 1,927 | 🐛 29 | 🌐 Python | 📅 2026-09-10
* 🟢 [Ruckig](https://github.com/pantor/ruckig) ⭐ 1,411 | 🐛 24 | 🌐 C++ | 📅 2026-09-29 - Real-time, time-optimal and jerk-constrained online trajectory generation. [⭐ 1.4k](https://github.com/pantor/ruckig) ⭐ 1,411 | 🐛 24 | 🌐 C++ | 📅 2026-09-29
* 🟢 [Python Motion Planning](https://github.com/ai-winter/python_motion_planning) ⭐ 1,098 | 🐛 2 | 🌐 Python | 📅 2026-09-15 - Python implementations of path planners, trajectory trackers, and curve generators. [⭐ 1.1k](https://github.com/ai-winter/python_motion_planning) ⭐ 1,098 | 🐛 2 | 🌐 Python | 📅 2026-09-15
* 🟢 [TOPP-RA](https://hungpham2511.github.io/toppra/) - Time-parameterizing robot trajectories subject to kinematic and dynamic constraints. [⭐ 934](https://github.com/hungpham2511/toppra) ⭐ 938 | 🐛 39 | 🌐 Python | 📅 2026-10-19
* 🟢 Fields2Cover - Robust and efficient coverage paths for autonomous agricultural vehicles. [⭐ 909](https://github.com/fields2cover/fields2cover) ⭐ 915 | 🐛 30 | 🌐 C++ | 📅 2026-09-22
* 🟢 [OpenRAVE](https://www.openrave.org/) - Open Robotics Automation Virtual Environment for planning and simulation. [⭐ 821](https://github.com/rdiankov/openrave) ⭐ 821 | 🐛 351 | 🌐 C++ | 📅 2026-10-15
* 🟢 [Klampt](https://klampt.org/) - Robot planning, control, and simulation with visualization support. [⭐ 437](https://github.com/krishauser/Klampt) ⭐ 437 | 🐛 27 | 🌐 C++ | 📅 2026-01-10
* 🟢 [The Kautham Project](https://sir.upc.es/projects/kautham/) - A robot simulation toolkit for motion planning. [⭐ 24](https://github.com/iocroblab/kautham) ⭐ 24 | 🐛 0 | 🌐 C++ | 📅 2026-07-24
* [CuiKSuite](http://www.iri.upc.edu/people/porta/Soft/CuikSuite2-Doc/html) - Applications to solve position analysis and path planning problems.
* [HPP](https://humanoid-path-planner.github.io/hpp-doc/) - Path planning for kinematic chains in environments cluttered with obstacles.

<details>
<summary>Inactive (7): archived or no commits for 3+ years</summary>

* [trajopt](http://rll.berkeley.edu/trajopt/doc/sphinx_build/html/) - Framework for generating robot trajectories by local optimization. [⭐ 466](https://github.com/joschu/trajopt) ⭐ 467 | 🐛 26 | 🌐 C++ | 📅 2022-12-05 · last commit 2017
* ROS Behavior Tree - Behavior tree implementation for ROS-based robot task planning. [⭐ 365](https://github.com/miccol/ROS-Behavior-Tree) ⭐ 366 | 🐛 2 | 🌐 C++ | 📅 2018-10-22 · last commit 2018
* [LibrePilot](http://www.librepilot.org/site/index.html) - Open-source autopilot for UAVs and other autonomous vehicles. [⭐ 358](https://github.com/librepilot/LibrePilot) ⭐ 359 | 🐛 18 | 🌐 C | 📅 2023-12-14 · last commit 2019
* GPMP2 - Gaussian Process Motion Planner 2. [⭐ 358](https://github.com/gtrll/gpmp2) ⭐ 358 | 🐛 13 | 🌐 C++ | 📅 2022-08-28 · last commit 2022
* [AIKIDO](https://github.com/personalrobotics/aikido) ⭐ 235 | 🐛 99 | 🌐 C++ | 📅 2023-03-10 - Solving robotic motion planning and decision making problems. [⭐ 235](https://github.com/personalrobotics/aikido) ⭐ 235 | 🐛 99 | 🌐 C++ | 📅 2023-03-10 · last commit 2023
* 💀 pymanoid - Humanoid robotics prototyping environment based on OpenRAVE. [⭐ 234](https://github.com/stephane-caron/pymanoid) ⚠️ Archived · last commit 2024
* TopiCo - Time-optimal Trajectory Generation and Control. [⭐ 146](https://github.com/AIS-Bonn/TopiCo) ⭐ 146 | 🐛 5 | 🌐 C++ | 📅 2021-07-12 · last commit 2021

</details>

## [Control](#contents)

*Model-based control: MPC, trajectory optimization, whole-body and task-space control.*

* 🟢 OCS2 - Efficient continuous and discrete time optimal control implementation. [⭐ 1.5k](https://github.com/leggedrobotics/ocs2) ⭐ 1,529 | 🐛 54 | 🌐 C++ | 📅 2026-09-29
* 🟢 Crocoddyl - Optimal control library for robot control under contact sequence. [⭐ 1.3k](https://github.com/loco-3d/crocoddyl) ⭐ 1,322 | 🐛 19 | 🌐 C++ | 📅 2026-10-13
* 🟡 TrajectoryOptimization - A fast trajectory optimization library written in Julia. [⭐ 400](https://github.com/RoboticExplorationLab/TrajectoryOptimization.jl) ⭐ 400 | 🐛 23 | 🌐 Julia | 📅 2026-10-15
* 🟢 Bioptim - Python framework for musculoskeletal optimal control in biomechanics. [⭐ 120](https://github.com/pyomeca/bioptim) ⭐ 121 | 🐛 101 | 🌐 Python | 📅 2026-10-18
* 🟡 [Ungar](https://github.com/fdevinc/ungar) ⭐ 108 | 🐛 5 | 🌐 C++ | 📅 2024-07-16 - Expressive and efficient implementation of optimal control problems using template metaprogramming. [⭐ 108](https://github.com/fdevinc/ungar) ⭐ 108 | 🐛 5 | 🌐 C++ | 📅 2024-07-16

<details>
<summary>Inactive (3): archived or no commits for 3+ years</summary>

* [Control Toolbox](https://ethz-adrl.github.io/ct/) - Open-Source C++ Library for Robotics, Optimal and Model Predictive Control. [⭐ 1.7k](https://github.com/ethz-adrl/control-toolbox) ⭐ 1,716 | 🐛 64 | 🌐 C++ | 📅 2022-11-09 · last commit 2021
* [towr](http://wiki.ros.org/towr) - A light-weight, Eigen-based C++ library for trajectory optimization for legged robots. [⭐ 1.1k](https://github.com/ethz-adrl/towr) ⭐ 1,085 | 🐛 27 | 🌐 C++ | 📅 2023-04-17 · last commit 2021
* [FROST](https://ayonga.github.io/frost-dev/index.html) - Fast Robot Optimization and Simulation Toolkit for hybrid dynamical systems in MATLAB. [⭐ 170](https://github.com/ayonga/frost-dev) ⭐ 170 | 🐛 11 | 🌐 MATLAB | 📅 2023-11-29 · last commit 2021

</details>

## [Optimization](#contents)

*General-purpose numerical solvers (LP, QP, NLP, least squares, black-box) and modeling layers.*

* 🟢 [Ceres Solver](http://ceres-solver.org/) - Large scale nonlinear optimization library. [⭐ 4.6k](https://github.com/ceres-solver/ceres-solver) ⭐ 4,581 | 🐛 65 | 🌐 C++ | 📅 2026-10-19
* 🟢 [pymoo](https://www.pymoo.org/) - Multi-objective Optimization in Python. [⭐ 3k](https://github.com/anyoptimization/pymoo) ⭐ 2,977 | 🐛 15 | 🌐 Python | 📅 2026-07-07
* 🟢 [CasADi](https://github.com/casadi/casadi/wiki) ⭐ 2,314 | 🐛 726 | 🌐 C++ | 📅 2026-10-19 - Symbolic framework for algorithmic differentiation and numeric optimization. [⭐ 2.3k](https://github.com/casadi/casadi) ⭐ 2,314 | 🐛 726 | 🌐 C++ | 📅 2026-10-19
* 🟢 [NLopt](https://nlopt.readthedocs.io/en/latest/) - Nonlinear optimization. [⭐ 2.3k](https://github.com/stevengj/nlopt) ⭐ 2,283 | 🐛 93 | 🌐 C | 📅 2026-10-17
* 🟢 [OSQP](https://osqp.org/) - The Operator Splitting QP Solver. [⭐ 2.2k](https://github.com/osqp/osqp) ⭐ 2,211 | 🐛 132 | 🌐 C | 📅 2026-01-12
* 🟢 [Ipopt](https://projects.coin-or.org/Ipopt) - Large scale nonlinear optimization library. [⭐ 1.8k](https://github.com/coin-or/Ipopt) ⭐ 1,792 | 🐛 13 | 🌐 C++ | 📅 2026-10-10
* 🟢 [Pagmo](https://esa.github.io/pagmo2/index.html) - Scientific library for massively parallel optimization. [⭐ 937](https://github.com/esa/pagmo2) ⭐ 938 | 🐛 37 | 🌐 C++ | 📅 2026-09-29
* 🟡 [OptimLib](https://github.com/kthohr/optim) ⭐ 898 | 🐛 12 | 🌐 C++ | 📅 2024-04-28 - Lightweight C++ library of numerical optimization methods for nonlinear functions. [⭐ 898](https://github.com/kthohr/optim) ⭐ 898 | 🐛 12 | 🌐 C++ | 📅 2024-04-28
* 🟢 ifopt - An Eigen-based, light-weight C++ Interface to Nonlinear Programming Solvers (Ipopt, Snopt). [⭐ 866](https://github.com/ethz-adrl/ifopt) ⭐ 866 | 🐛 19 | 🌐 C++ | 📅 2025-11-03
* 🟢 qpsolvers - Quadratic Programming solvers in Python with a unified API. [⭐ 760](https://github.com/qpsolvers/qpsolvers) ⭐ 762 | 🐛 7 | 🌐 Python | 📅 2026-10-19
* 🟢 hpipm - High-performance interior-point-method QP solvers (Ipopt, Snopt). [⭐ 710](https://github.com/giaf/hpipm) ⭐ 711 | 🐛 51 | 🌐 C | 📅 2026-10-03
* 🟢 [Optimization Engine (OpEn)](https://alphaville.github.io/optimization-engine/) - Embedded nonconvex optimization with code generation for real-time control, with ROS support. [⭐ 651](https://github.com/alphaville/optimization-engine) ⭐ 650 | 🐛 12 | 🌐 Rust | 📅 2026-03-31
* 🟢 [SCS](http://web.stanford.edu/~boyd/papers/scs.html) - Numerical optimization for solving large-scale convex cone problems. [⭐ 638](https://github.com/cvxgrp/scs) ⭐ 638 | 🐛 8 | 🌐 C | 📅 2026-10-16
* 🟢 [ProxSuite](https://simple-robotics.github.io/proxsuite/) - The Advanced Proximal Optimization Toolbox. [⭐ 596](https://github.com/Simple-Robotics/ProxSuite) ⭐ 597 | 🐛 16 | 🌐 C++ | 📅 2026-10-19
* 🟢 libcmaes - Blackbox stochastic optimization using the CMA-ES algorithm. [⭐ 372](https://github.com/CMA-ES/libcmaes) ⭐ 372 | 🐛 57 | 🌐 C++ | 📅 2026-07-02
* 🟡 [limbo](http://www.resibots.eu/limbo/) - Gaussian processes and Bayesian optimization of black-box functions. [⭐ 270](https://github.com/resibots/limbo) ⭐ 270 | 🐛 20 | 🌐 C++ | 📅 2023-10-18
* 🟡 EXOTica - Generic optimisation toolset for robotics platforms. [⭐ 164](https://github.com/ipab-slmc/exotica) ⭐ 164 | 🐛 57 | 🌐 C++ | 📅 2026-10-14
* 🟢 SHOT - A solver for mixed-integer nonlinear optimization problems. [⭐ 135](https://github.com/coin-or/SHOT) ⭐ 135 | 🐛 8 | 🌐 C++ | 📅 2026-10-18
* 🟡 [RobOptim](http://roboptim.net/index.html) - Numerical Optimization for Robotics. [⭐ 66](https://github.com/roboptim/roboptim-core) ⭐ 66 | 🐛 11 | 🌐 C++ | 📅 2025-03-21
* 🟢 lpsolvers - Linear Programming solvers in Python with a unified API. [⭐ 26](https://github.com/stephane-caron/lpsolvers) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2026-04-09
* 🟢 eigen-qld - Interface to use the QLD QP solver with the Eigen3 library. [⭐ 17](https://github.com/jrl-umi3218/eigen-qld) ⭐ 17 | 🐛 1 | 🌐 C | 📅 2026-10-12

<details>
<summary>Inactive (1): archived or no commits for 3+ years</summary>

* sferes2 - Evolutionary computation. [⭐ 170](https://github.com/sferes2/sferes2) ⭐ 170 | 🐛 22 | 🌐 C++ | 📅 2022-07-11 · last commit 2021

</details>

## [Math & Geometry](#contents)

*Linear algebra, Lie groups, spatial transforms, and spatial data structures such as nearest-neighbor search.*

* 🟢 nanoflann - Nearest Neighbor search with KD-trees. [⭐ 2.7k](https://github.com/jlblancoc/nanoflann) ⭐ 2,698 | 🐛 39 | 🌐 C++ | 📅 2026-10-16
* 🟡 Sophus - Lie groups using Eigen. [⭐ 2.5k](https://github.com/strasdat/Sophus) ⭐ 2,463 | 🐛 16 | 🌐 C++ | 📅 2024-07-06
* 🟢 manif - Small c++11 header-only library for Lie theory. [⭐ 1.8k](https://github.com/artivis/manif) ⭐ 1,825 | 🐛 38 | 🌐 C++ | 📅 2026-08-05
* 🟢 [HYPRE](https://hypre.readthedocs.io/) - Parallel solvers for sparse linear systems featuring multigrid methods. [⭐ 867](https://github.com/hypre-space/hypre) ⭐ 870 | 🐛 168 | 🌐 C | 📅 2026-10-12
* 🟡 Fastor - Light-weight high performance tensor algebra framework in C++11/14/17. [⭐ 844](https://github.com/romeric/Fastor) ⭐ 844 | 🐛 36 | 🌐 C++ | 📅 2025-07-08
* 🟢 spatialmath-python - Python classes for pose and orientation in 2D/3D with spatial operations toolbox. [⭐ 646](https://github.com/rai-opensource/spatialmath-python) ⭐ 648 | 🐛 37 | 🌐 Python | 📅 2026-10-16
* 🟡 kindr - Kinematics and dynamics library for rigid body transformations. [⭐ 618](https://github.com/ANYbotics/kindr) ⭐ 617 | 🐛 29 | 🌐 C++ | 📅 2025-02-15
* 🟢 SpaceVelAlg - Spatial vector algebra with the Eigen3. [⭐ 81](https://github.com/jrl-umi3218/SpaceVecAlg) ⭐ 81 | 🐛 5 | 🌐 C++ | 📅 2026-10-12

<details>
<summary>Inactive (4): archived or no commits for 3+ years</summary>

* [FLANN](http://www.cs.ubc.ca/research/flann/) - Fast Library for Approximate Nearest Neighbors. [⭐ 2.4k](https://github.com/flann-lib/flann) ⭐ 2,379 | 🐛 298 | 🌐 C++ | 📅 2024-07-29 · last commit 2022
* linalg.h - Single header public domain linear algebra library for C++11. [⭐ 969](https://github.com/sgorsten/linalg) ⭐ 970 | 🐛 6 | 🌐 C++ | 📅 2023-07-02 · last commit 2023
* Octree - Fast radius neighbor search with an Octree. [⭐ 378](https://github.com/jbehley/octree) ⭐ 378 | 🐛 2 | 🌐 C++ | 📅 2019-12-17 · last commit 2019
* [Cover-Tree](http://hunch.net/~jl/projects/cover_tree/cover_tree.html) - Cover tree data structure for quick k-nearest-neighbor search. [⭐ 64](https://github.com/DNCrane/Cover-Tree) ⭐ 64 | 🐛 5 | 🌐 C++ | 📅 2018-02-13 · last commit 2017

</details>

## [SLAM & State Estimation](#contents)

*SLAM, odometry, factor graphs, filtering and sensor fusion, calibration, and mapping.*

* 🟡 Cartographer - Real-time SLAM in 2D and 3D across multiple platforms and sensor configurations. [⭐ 8k](https://github.com/cartographer-project/cartographer) ⭐ 7,987 | 🐛 241 | 🌐 C++ | 📅 2024-01-05
* 🟢 [RTAB-Map](http://introlab.github.io/rtabmap/) - RGB-D Graph SLAM approach based on a global Bayesian loop closure detector. [⭐ 4k](https://github.com/introlab/rtabmap) ⭐ 4,045 | 🐛 594 | 🌐 C++ | 📅 2026-10-19
* 🟢 GTSAM - Smoothing and mapping (SAM) in robotics and vision. [⭐ 3.7k](https://github.com/borglab/gtsam) ⭐ 3,759 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2026-10-19
* 🟢 [mrpt](https://www.mrpt.org/) - Mobile Robot Programming Toolkit for SLAM, navigation, and computer vision. [⭐ 2.2k](https://github.com/MRPT/mrpt) ⭐ 2,169 | 🐛 21 | 🌐 C++ | 📅 2026-10-19
* 🟡 ElasticFusion - Real-time dense visual SLAM system. [⭐ 1.9k](https://github.com/mp3guy/ElasticFusion) ⭐ 1,929 | 🐛 4 | 🌐 C++ | 📅 2025-08-03
* 🟢 fuse - General architecture for performing sensor fusion live on a robot. [⭐ 882](https://github.com/locusrobotics/fuse) ⭐ 881 | 🐛 48 | 🌐 C++ | 📅 2026-08-19
* 🟢 [FusionCore](https://manankharwar.github.io/fusioncore/) - ROS 2 UKF fusing GPS, IMU, and wheel odometry with adaptive noise and GPS outlier rejection. [⭐ 378](https://github.com/manankharwar/fusioncore) ⭐ 382 | 🐛 48 | 🌐 C++ | 📅 2026-10-18
* 🟢 [fiducials](http://wiki.ros.org/fiducials) - Simultaneous localization and mapping using fiducial markers. [⭐ 284](https://github.com/UbiquityRobotics/fiducials) ⭐ 284 | 🐛 38 | 🌐 C | 📅 2025-11-27

### Mapping

* 🟢 [OctoMap](http://octomap.github.io/) - Efficient Probabilistic 3D Mapping Framework Based on Octrees. [⭐ 2.4k](https://github.com/OctoMap/octomap) ⭐ 2,392 | 🐛 41 | 🌐 C++ | 📅 2026-09-26
* 🟢 [libpointmatcher](http://libpointmatcher.readthedocs.io/en/latest/) - Iterative Closest Point library for 2-D/3-D mapping in Robotics. [⭐ 1.8k](https://github.com/norlab-ulaval/libpointmatcher) ⭐ 1,839 | 🐛 100 | 🌐 C++ | 📅 2026-08-27
* 🟢 Bonxai - Brutally fast, sparse, 3D Voxel Grid (formerly Treexy). [⭐ 884](https://github.com/facontidavide/Bonxai) ⭐ 886 | 🐛 6 | 🌐 C++ | 📅 2026-09-29
* 🟡 [wavemap](https://projects.asl.ethz.ch/wavemap/) - Fast, efficient and accurate multi-resolution, multi-sensor 3D occupancy mapping. [⭐ 573](https://github.com/ethz-asl/wavemap) ⭐ 575 | 🐛 12 | 🌐 C++ | 📅 2024-12-30

<details>
<summary>Inactive (7): archived or no commits for 3+ years</summary>

* ORB-SLAM2 - Real-time SLAM library for Monocular, Stereo and RGB-D cameras. [⭐ 10.2k](https://github.com/raulmur/ORB_SLAM2) ⭐ 10,256 | 🐛 806 | 🌐 C++ | 📅 2024-05-15 · last commit 2017
* [LSD-SLAM](https://vision.in.tum.de/research/vslam/lsdslam) - Real-time monocular SLAM. [⭐ 2.7k](https://github.com/tum-vision/lsd_slam) ⭐ 2,731 | 🐛 240 | 🌐 C++ | 📅 2023-03-23 · last commit 2014
* [DSO](https://vision.in.tum.de/research/vslam/dso) - Novel direct and sparse formulation for Visual Odometry. [⭐ 2.5k](https://github.com/JakobEngel/dso) ⭐ 2,459 | 🐛 138 | 🌐 C++ | 📅 2024-02-23 · last commit 2021
* voxblox - Flexible voxel-based mapping focusing on truncated and Euclidean signed distance fields. [⭐ 1.7k](https://github.com/ethz-asl/voxblox) ⭐ 1,675 | 🐛 77 | 🌐 C++ | 📅 2024-07-01 · last commit 2021
* Kintinuous - Real-time large scale dense visual SLAM system. [⭐ 953](https://github.com/mp3guy/Kintinuous) ⭐ 953 | 🐛 43 | 🌐 C++ | 📅 2022-08-26 · last commit 2022
* AprilSAM - Real-time smoothing and mapping. [⭐ 238](https://github.com/xipengwang/AprilSAM) ⭐ 238 | 🐛 1 | 🌐 C | 📅 2021-07-17 · last commit 2021
* [SRBA](http://mrpt.github.io/srba/) - Solving SLAM/BA in relative coordinates with flexibility for different submapping strategies. [⭐ 75](https://github.com/MRPT/srba) ⭐ 75 | 🐛 6 | 🌐 C++ | 📅 2018-09-30 · last commit 2016

</details>

## [Perception](#contents)

*Image and point-cloud processing, detection, pose estimation and tracking, and visual servoing.*

* 🟢 [PCL](https://pointclouds.org/) - 2D/3D image and point cloud processing. [⭐ 11.2k](https://github.com/PointCloudLibrary/pcl) ⭐ 11,164 | 🐛 578 | 🌐 C++ | 📅 2026-10-17
* 🟢 [ViSP](http://visp.inria.fr/) - Visual Servoing Platform. [⭐ 928](https://github.com/lagadic/visp) ⭐ 931 | 🐛 3 | 🌐 C++ | 📅 2026-10-19
* 🟢 [BundleTrack](https://github.com/wenbowen123/BundleTrack) ⭐ 687 | 🐛 12 | 🌐 C++ | 📅 2026-04-13 - 6D Pose Tracking for Novel Objects without 3D Models. [⭐ 687](https://github.com/wenbowen123/BundleTrack) ⭐ 687 | 🐛 12 | 🌐 C++ | 📅 2026-04-13

<details>
<summary>Inactive (1): archived or no commits for 3+ years</summary>

* [se(3)-TrackNet](https://github.com/wenbowen123/iros20-6d-pose-tracking) ⭐ 424 | 🐛 10 | 🌐 Python | 📅 2023-08-30 - 6D Pose Tracking for Novel Objects without 3D Models. [⭐ 424](https://github.com/wenbowen123/iros20-6d-pose-tracking) ⭐ 424 | 🐛 10 | 🌐 Python | 📅 2023-08-30 · last commit 2023

</details>

## [Grasping & Manipulation](#contents)

*Grasp synthesis, detection, and planning, and dexterous manipulation.*

* 🟢 [AnyGrasp SDK](https://github.com/graspnet/anygrasp_sdk) ⭐ 1,029 | 🐛 66 | 🌐 Python | 📅 2026-07-13 - SDK for AnyGrasp, a 6-DoF grasp pose detection method. [⭐ 1k](https://github.com/graspnet/anygrasp_sdk) ⭐ 1,029 | 🐛 66 | 🌐 Python | 📅 2026-07-13
* 🟡 [Contact-GraspNet](https://github.com/NVlabs/contact_graspnet) ⭐ 540 | 🐛 25 | 🌐 Python | 📅 2024-11-21 - 6-DoF grasp generation for parallel-jaw grippers using contact maps. [⭐ 538](https://github.com/NVlabs/contact_graspnet) ⭐ 540 | 🐛 25 | 🌐 Python | 📅 2024-11-21
* 🟢 [GraspNet API](https://github.com/graspnet/graspnetAPI) ⭐ 369 | 🐛 15 | 🌐 Python | 📅 2026-06-29 - Python API and evaluation tools for the GraspNet benchmark. [⭐ 369](https://github.com/graspnet/graspnetAPI) ⭐ 369 | 🐛 15 | 🌐 Python | 📅 2026-06-29

<details>
<summary>Inactive (1): archived or no commits for 3+ years</summary>

* [GraspIt!](https://graspit-simulator.github.io/) - Simulator for grasping research that can accommodate arbitrary hand and robot designs. [⭐ 221](https://github.com/graspit-simulator/graspit) ⭐ 222 | 🐛 36 | 🌐 C++ | 📅 2021-04-19 · last commit 2020

</details>

## [Robot Learning](#contents)

*Robot foundation models (VLA), imitation and reinforcement learning libraries, learning environments, and benchmarks.*

* 🟢 LeRobot - Pretrained models, datasets, and simulation environments for real-world robotics in PyTorch. [⭐ 28.1k](https://github.com/huggingface/lerobot) ⭐ 28,296 | 🐛 1,033 | 🌐 Python | 📅 2026-10-19
* 🟢 [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) ⭐ 13,908 | 🐛 89 | 🌐 Python | 📅 2026-10-13 - Reliable implementations of reinforcement learning algorithms in PyTorch. [⭐ 13.9k](https://github.com/DLR-RM/stable-baselines3) ⭐ 13,908 | 🐛 89 | 🌐 Python | 📅 2026-10-13
* 🟢 [Gymnasium](https://gymnasium.farama.org/) - Developing and comparing reinforcement learning algorithms. [⭐ 12.7k](https://github.com/Farama-Foundation/Gymnasium) ⭐ 12,699 | 🐛 116 | 🌐 Python | 📅 2026-10-14
* 🟢 [CleanRL](https://github.com/vwxyzjn/cleanrl) ⭐ 10,575 | 🐛 109 | 🌐 Python | 📅 2026-04-20 - Single-file implementations of deep reinforcement learning algorithms. [⭐ 10.5k](https://github.com/vwxyzjn/cleanrl) ⭐ 10,575 | 🐛 109 | 🌐 Python | 📅 2026-04-20
* 🟢 [Isaac Lab](https://isaac-sim.github.io/IsaacLab) - GPU-accelerated open-source framework for robot learning built on NVIDIA Isaac Sim. [⭐ 8.3k](https://github.com/isaac-sim/IsaacLab) ⭐ 8,383 | 🐛 407 | 🌐 Python | 📅 2026-10-19
* 🟢 [ManiSkill](https://github.com/haosulab/ManiSkill) ⭐ 3,432 | 🐛 149 | 🌐 Python | 📅 2026-08-04 - Robot simulation and manipulation learning package powered by SAPIEN. [⭐ 3.4k](https://github.com/mani-skill/ManiSkill) ⭐ 3,432 | 🐛 149 | 🌐 Python | 📅 2026-08-04
* 🟡 [Legged Gym](https://github.com/leggedrobotics/legged_gym) ⭐ 3,148 | 🐛 59 | 🌐 Python | 📅 2025-05-29 - Isaac Gym environments for legged robot locomotion training. [⭐ 3.1k](https://github.com/leggedrobotics/legged_gym) ⭐ 3,148 | 🐛 59 | 🌐 Python | 📅 2025-05-29
* 🟢 [robosuite](https://robosuite.ai/docs/) - A modular simulation framework and benchmark for robot learning. [⭐ 2.7k](https://github.com/ARISE-Initiative/robosuite) ⭐ 2,669 | 🐛 123 | 🌐 Python | 📅 2026-07-11
* 🟡 [Humanoid-Gym](https://github.com/roboterax/humanoid-gym) ⭐ 2,104 | 🐛 24 | 🌐 Python | 📅 2025-01-26 - Reinforcement learning environment for humanoid robot locomotion. [⭐ 2.1k](https://github.com/roboterax/humanoid-gym) ⭐ 2,104 | 🐛 24 | 🌐 Python | 📅 2025-01-26
* 🟢 [rl\_games](https://github.com/Denys88/rl_games) ⭐ 1,400 | 🐛 48 | 🌐 Jupyter Notebook | 📅 2026-10-19 - High-performance RL library used in Isaac Gym environments. [⭐ 1.4k](https://github.com/Denys88/rl_games) ⭐ 1,400 | 🐛 48 | 🌐 Jupyter Notebook | 📅 2026-10-19
* 🟢 [SKRL](https://github.com/Toni-SM/skrl) ⭐ 1,101 | 🐛 35 | 🌐 Python | 📅 2026-10-18 - Modular reinforcement learning library with support for multiple ML frameworks. [⭐ 1.1k](https://github.com/Toni-SM/skrl) ⭐ 1,101 | 🐛 35 | 🌐 Python | 📅 2026-10-18
* 🟡 [AllenAct](https://allenact.org/) - Python/PyTorch-based Research Framework for Embodied AI. [⭐ 384](https://github.com/allenai/allenact) ⭐ 384 | 🐛 58 | 🌐 Python | 📅 2026-05-19

### General Machine Learning

* 🟢 [mlpack](https://www.mlpack.org/) - Scalable C++ machine learning library. [⭐ 5.7k](https://github.com/mlpack/mlpack) ⭐ 5,714 | 🐛 17 | 🌐 C++ | 📅 2026-10-15
* 🟡 [DyNet](https://dynet.readthedocs.io/en/latest/) - The Dynamic Neural Network Toolkit. [⭐ 3.4k](https://github.com/clab/dynet) ⭐ 3,430 | 🐛 232 | 🌐 C++ | 📅 2023-12-01
* 🟡 DLL - Deep Learning Library (DLL) for C++. [⭐ 688](https://github.com/wichtounet/dll) ⭐ 689 | 🐛 1 | 🌐 C++ | 📅 2025-05-27

<details>
<summary>Inactive (7): archived or no commits for 3+ years</summary>

* 💀 [Ivy](https://lets-unify.ai/) - Unified Machine Learning Framework. [⭐ 14.2k](https://github.com/unifyai/ivy) ⭐ 14,167 | 🐛 985 | 🌐 Python | 📅 2026-10-16 · last commit 2026
* [tiny-dnn](http://tiny-dnn.readthedocs.io/en/latest/) - Header only, dependency-free deep learning framework in C++14. [⭐ 6k](https://github.com/tiny-dnn/tiny-dnn) ⭐ 6,028 | 🐛 297 | 🌐 C++ | 📅 2022-04-17 · last commit 2018
* 💀 gym-gazebo - OpenAI Gym environments for the Gazebo simulator. [⭐ 845](https://github.com/erlerobot/gym-gazebo) ⚠️ Archived · last commit 2019
* [Fido](http://fidoproject.github.io/) - Lightweight C++ machine learning library for embedded electronics and robotics. [⭐ 464](https://github.com/FidoProject/Fido) ⭐ 464 | 🐛 15 | 🌐 C++ | 📅 2020-01-05 · last commit 2017
* MiniDNN - A header-only C++ library for deep neural networks. [⭐ 434](https://github.com/yixuan/MiniDNN) ⭐ 434 | 🐛 12 | 🌐 C++ | 📅 2021-04-16 · last commit 2021
* RLLib - Temporal-difference learning algorithms in reinforcement learning. [⭐ 211](https://github.com/samindaa/RLLib) ⭐ 211 | 🐛 13 | 🌐 C++ | 📅 2016-08-15 · last commit 2016
* gym-dart - OpenAI Gym environments using the DART physics engine. [⭐ 140](https://github.com/DartEnv/dart-env) ⭐ 140 | 🐛 0 | 🌐 Python | 📅 2020-10-20 · last commit 2020

</details>

## [Robot Data & Visualization](#contents)

*Logging, storing, converting, and visualizing robot data, dataset tools, and teleoperation for data collection.*

* 🟢 Any4LeRobot - A collection of utilities and tools for LeRobot. [⭐ 1.2k](https://github.com/Tavish9/any4lerobot) ⭐ 1,171 | 🐛 4 | 🌐 Python | 📅 2026-10-01
* 🟢 [ReductStore](https://www.reduct.store) - High-performance, time-indexed object storage for robotics and industrial IoT. [⭐ 373](https://github.com/reductstore/reductstore) ⭐ 374 | 🐛 22 | 🌐 Rust | 📅 2026-10-19
* 🟢 [LeRobot Episode Scoring Toolkit](https://github.com/RoboticsData/score_lerobot_episodes) ⭐ 78 | 🐛 8 | 🌐 Python | 📅 2026-03-13 - One-click tool to score, filter, and export higher-quality LeRobot datasets. [⭐ 77](https://github.com/RoboticsData/score_lerobot_episodes) ⭐ 78 | 🐛 8 | 🌐 Python | 📅 2026-03-13
* [Foxglove Studio](https://foxglove.dev) - A fully integrated visualization and debugging desktop app for your robotics data.

<details>
<summary>Inactive (1): archived or no commits for 3+ years</summary>

* [Robot Gui](http://robot.glumb.de/) - A three.js based 3D robot interface. [⭐ 391](https://github.com/glumb/robot-gui) ⭐ 391 | 🐛 3 | 🌐 JavaScript | 📅 2023-06-26 · last commit 2020

</details>

## [Other Awesome Lists](#contents)

*Related curated lists and collections.*

* 🟢 [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) ⭐ 74,613 | 🐛 23 | 🌐 Python | 📅 2026-10-19 - Curated list of machine learning frameworks, libraries, and software. [⭐ 74.6k](https://github.com/josephmisiti/awesome-machine-learning) ⭐ 74,613 | 🐛 23 | 🌐 Python | 📅 2026-10-19
* 🟢 [PythonRobotics](https://github.com/AtsushiSakai/PythonRobotics) ⭐ 30,741 | 🐛 62 | 🌐 Python | 📅 2026-10-14 - Python sample codes for robotics algorithms. [⭐ 30.7k](https://github.com/AtsushiSakai/PythonRobotics) ⭐ 30,741 | 🐛 62 | 🌐 Python | 📅 2026-10-14
* 🟡 [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 29,065 | 🐛 91 | 📅 2025-05-26 - Curated list of deep learning tutorials, projects, and communities. [⭐ 29k](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 29,065 | 🐛 91 | 📅 2025-05-26
* 🟢 [Awesome Artificial Intelligence](https://github.com/owainlewis/awesome-artificial-intelligence) ⭐ 16,698 | 🐛 78 | 🌐 Python | 📅 2026-08-15 - Curated list of AI courses, books, video lectures, and papers. [⭐ 16.7k](https://github.com/owainlewis/awesome-artificial-intelligence) ⭐ 16,698 | 🐛 78 | 🌐 Python | 📅 2026-08-15
* 🟡 [Awesome Robotics (Kiloreux)](https://github.com/Kiloreux/awesome-robotics) ⭐ 7,245 | 🐛 47 | 📅 2024-09-22 - Curated list of robotics resources (Kiloreux). [⭐ 7.2k](https://github.com/Kiloreux/awesome-robotics) ⭐ 7,245 | 🐛 47 | 📅 2024-09-22
* 🟢 [Robotics Coursework](https://github.com/mithi/robotics-coursework) ⭐ 5,335 | 🐛 2 | 📅 2026-08-31 - A list of robotics courses you can take online. [⭐ 5.3k](https://github.com/mithi/robotics-coursework) ⭐ 5,335 | 🐛 2 | 📅 2026-08-31
* 🟡 [Awesome SLAM Datasets](https://github.com/youngguncho/awesome-slam-datasets) ⭐ 1,948 | 🐛 14 | 📅 2024-12-13 - Curated list of SLAM-related datasets. [⭐ 1.9k](https://github.com/youngguncho/awesome-slam-datasets) ⭐ 1,948 | 🐛 14 | 📅 2024-12-13
* 🟢 [Awesome Collision Detection](https://github.com/jslee02/awesome-collision-detection) ⭐ 1,045 | 🐛 1 | 🌐 Python | 📅 2026-10-13 - Curated list of collision detection libraries and resources. [⭐ 1k](https://github.com/jslee02/awesome-collision-detection) ⭐ 1,045 | 🐛 1 | 🌐 Python | 📅 2026-10-13
* 🟢 [Awesome Physical AI](https://github.com/keon/awesome-physical-ai) ⭐ 444 | 🐛 22 | 📅 2026-06-24 - Curated list of academic papers and resources on Physical AI. [⭐ 439](https://github.com/keon/awesome-physical-ai) ⭐ 444 | 🐛 22 | 📅 2026-06-24
* 🟢 [Awesome VLA Study](https://github.com/MilkClouds/awesome-vla-study) ⭐ 409 | 🐛 0 | 📅 2026-03-21 - Study guide to vision-language-action (VLA) papers for robot learning. [⭐ 402](https://github.com/MilkClouds/awesome-vla-study) ⭐ 409 | 🐛 0 | 📅 2026-03-21

<details>
<summary>Inactive (6): archived or no commits for 3+ years</summary>

* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision) ⭐ 23,605 | 🐛 99 | 📅 2024-05-17 - Curated list of computer vision resources. [⭐ 23.6k](https://github.com/jbhuang0604/awesome-computer-vision) ⭐ 23,605 | 🐛 99 | 📅 2024-05-17 · last commit 2021
* [Awesome Robotic Tooling](https://github.com/Ly0n/awesome-robotic-tooling) ⭐ 3,909 | 🐛 13 | 📅 2023-11-20 - Tooling for professional robotic development in C++ and Python with ROS and autonomous driving. [⭐ 3.9k](https://github.com/Ly0n/awesome-robotic-tooling) ⭐ 3,909 | 🐛 13 | 📅 2023-11-20 · last commit 2023
* [Awesome Robotics (ahundt)](https://github.com/ahundt/awesome-robotics) ⭐ 1,517 | 🐛 9 | 📅 2024-01-10 - Curated list of robotics links and software libraries (ahundt). [⭐ 1.5k](https://github.com/ahundt/awesome-robotics) ⭐ 1,517 | 🐛 9 | 📅 2024-01-10 · last commit 2023
* 💀 [Awesome Gazebo](https://github.com/fkromer/awesome-gazebo) ⚠️ Archived - Curated list of Gazebo simulation framework resources. [⭐ 155](https://github.com/fkromer/awesome-gazebo) ⚠️ Archived · last commit 2021
* [Awesome Human Robot Interaction](https://github.com/Po-Jen/awesome-human-robot-interaction) ⭐ 153 | 🐛 0 | 📅 2019-02-12 - Curated list of human-robot interaction libraries and resources. [⭐ 153](https://github.com/Po-Jen/awesome-human-robot-interaction) ⭐ 153 | 🐛 0 | 📅 2019-02-12 · last commit 2019
* [Awesome Grasping](https://github.com/Po-Jen/awesome-grasping) ⭐ 99 | 🐛 0 | 📅 2019-07-13 - Curated list of grasping libraries and resources. [⭐ 99](https://github.com/Po-Jen/awesome-grasping) ⭐ 99 | 🐛 0 | 📅 2019-07-13 · last commit 2019

</details>

## [Contributing](#contents)

Contributions are very welcome! Please read the [contribution guidelines](https://github.com/jslee02/awesome-robotics-libraries/blob/main/CONTRIBUTING.md) first. Also, please feel free to report any error.

## [Star History](#contents)

<a href="https://www.star-history.com/?repos=jslee02%2Fawesome-robotics-libraries">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=jslee02/awesome-robotics-libraries&type=date&theme=dark&legend=top-left" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=jslee02/awesome-robotics-libraries&type=date&legend=top-left" />
    <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=jslee02/awesome-robotics-libraries&type=date&legend=top-left" />
  </picture>
</a>

## [License](#contents)

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-19._
