<p align="center"> <a href="https://plansys2.github.io/" target="blank"><img src="https://github.com/PlanSys2/.github/blob/main/plansys2_logo.png" width="250" alt="" /></a> </p>
<h1 align="center"></h1>
<p align="center">

<h2 align="center">
  🌐 <a href="https://plansys2.github.io/" target="_blank">https://plansys2.github.io/</a>
</h2>

## 🧠 PlanSys2

**ROS2 Planning System (PlanSys2)** is a project whose objective is to provide Robotics developers with a reliable, simple, and efficient PDDL-based planning system. It is implemented in ROS 2, applying the latest concepts developed in this currently de-facto standard in Robotics.

This project is the result of several years of experience in the development of robotic behaviors using [ROSPlan](https://github.com/KCL-Planning/ROSPlan). ROSPlan has greatly inspired this project. In addition to the migration to ROS 2, we contribute to key aspects: ease of use, efficiency, and new tools, such as our terminal.

We hope that this software helps to include planning in more Robotics projects, offering simple and powerful software to generate intelligent behaviors for robots.

Please, cite us if you use PlanSys2 in your research:

```
@INPROCEEDINGS
 {PlanSys2,
    author    = "Francisco Mart{\'{\i}}n and Jonatan Gin{\'{e}}s and Francisco J. Rodr{\'{i}}guez and Vicente Matell{\'{a}}n",
    title     = "PlanSys2: A Planning System Framework for ROS2",
    booktitle = "{{IEEE/RSJ} International Conference on Intelligent Robots and Systems,  {IROS} 2021, Prague, Czech Republic, September 27 - October 1, 2021}",
    year      = "2021",
    publisher = "{IEEE}"
}
```

---

## 🧩 CI Status

| Repository | Doxygen | Rolling | Lyrical | Kilted | Jazzy | Humble |
|-------------|----------|----------|----------|----------|----------|----------|
| [**ros2_planning_system**](https://github.com/PlanSys2/ros2_planning_system) | [![Doxygen Deployment](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/doxygen-doc.yml/badge.svg)](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/doxygen-doc.yml) | [![rolling](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/rolling.yaml/badge.svg?branch=rolling)](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/lyrical-devel.yaml/badge.svg?branch=lyrical-devel)](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/lyrical-devel.yaml) | [![kilted](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/kilted-devel.yaml/badge.svg?branch=kilted-devel)](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/kilted-devel.yaml) | [![jazzy](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/jazzy-devel.yaml/badge.svg?branch=jazzy-devel)](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/jazzy-devel.yaml) | [![humble](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/humble-devel.yaml/badge.svg?branch=humble-devel)](https://github.com/PlanSys2/ros2_planning_system/actions/workflows/humble-devel.yaml) |
| [**ros2_planning_system_examples**](https://github.com/PlanSys2/ros2_planning_system_examples) | — | [![rolling](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/rolling.yaml/badge.svg?branch=rolling)](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/lyrical.yaml/badge.svg?branch=lyrical)](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/lyrical.yaml) | [![kilted](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/kilted.yaml/badge.svg?branch=kilted)](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/kilted.yaml) | [![jazzy](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/jazzy.yaml/badge.svg?branch=jazzy)](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/jazzy.yaml) | [![humble](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/humble.yaml/badge.svg?branch=humble)](https://github.com/PlanSys2/ros2_planning_system_examples/actions/workflows/humble.yaml) |
| [**cascade_lifecycle**](https://github.com/fmrico/cascade_lifecycle) | — | [![rolling](https://github.com/fmrico/cascade_lifecycle/actions/workflows/rolling.yaml/badge.svg?branch=rolling)](https://github.com/fmrico/cascade_lifecycle/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/fmrico/cascade_lifecycle/actions/workflows/lyrical-devel.yaml/badge.svg?branch=lyrical-devel)](https://github.com/fmrico/cascade_lifecycle/actions/workflows/lyrical-devel.yaml) | [![kilted](https://github.com/fmrico/cascade_lifecycle/actions/workflows/kilted-devel.yaml/badge.svg?branch=kilted-devel)](https://github.com/fmrico/cascade_lifecycle/actions/workflows/kilted-devel.yaml) | [![jazzy](https://github.com/fmrico/cascade_lifecycle/actions/workflows/jazzy-devel.yaml/badge.svg?branch=jazzy-devel)](https://github.com/fmrico/cascade_lifecycle/actions/workflows/jazzy-devel.yaml) | [![humble](https://github.com/fmrico/cascade_lifecycle/actions/workflows/humble-devel.yaml/badge.svg?branch=humble-devel)](https://github.com/fmrico/cascade_lifecycle/actions/workflows/humble-devel.yaml) |
| [**popf**](https://github.com/fmrico/popf) | — | [![rolling](https://github.com/fmrico/popf/actions/workflows/rolling.yaml/badge.svg?branch=rolling-devel)](https://github.com/fmrico/popf/actions/workflows/rolling.yaml) | [![lyrical](https://github.com/fmrico/popf/actions/workflows/lyrical.yaml/badge.svg?branch=lyrical-devel)](https://github.com/fmrico/popf/actions/workflows/lyrical.yaml) | [![kilted](https://github.com/fmrico/popf/actions/workflows/kilted.yaml/badge.svg?branch=kilted-devel)](https://github.com/fmrico/popf/actions/workflows/kilted.yaml) | [![jazzy](https://github.com/fmrico/popf/actions/workflows/jazzy.yaml/badge.svg?branch=jazzy-devel)](https://github.com/fmrico/popf/actions/workflows/jazzy.yaml) | [![humble](https://github.com/fmrico/popf/actions/workflows/humble.yaml/badge.svg?branch=humble-devel)](https://github.com/fmrico/popf/actions/workflows/humble.yaml) |

---

## 📦 Main Repositories

| Repository | Description |
|-------------|-------------|
| [**ros2_planning_system**](https://github.com/PlanSys2/ros2_planning_system) | Core of PlanSys2: the DomainExpert, ProblemExpert, Planner and Executor nodes, the terminal, and the plugin interfaces for plan solvers and actions. |
| [**ros2_planning_system_examples**](https://github.com/PlanSys2/ros2_planning_system_examples) | Example applications demonstrating how to build PDDL-based robot behaviors with PlanSys2. |
| [**cascade_lifecycle**](https://github.com/fmrico/cascade_lifecycle) | Extension of ROS 2 managed lifecycle nodes with cascading activation, used by PlanSys2 to coordinate the lifecycle of its nodes. |
| [**popf**](https://github.com/fmrico/popf) | The POPF PDDL temporal planner, packaged as PlanSys2's default plan solver plugin. |

---

## 👥 Project Maintainers

| Name | Organization | GitHub | Role |
|------|---------------|--------|------|
| Francisco Martín Rico | Universidad Rey Juan Carlos | [fmrico](https://github.com/fmrico) | Project Lead |
| Marco Roveri | University of Trento | [roveri-marco](https://github.com/roveri-marco) | Core Developer |
| Francisco Miguel Moreno Olivo | Universidad Rey Juan Carlos | [butakus](https://github.com/butakus) | Core Developer |

---

<p align="center">
  <a href="https://plansys2.github.io/">
    <strong>PlanSys2 – https://plansys2.github.io/</strong>
  </a>
</p>

---
