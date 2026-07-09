# WASP Research Group

The **[WASP Research Group](https://www.uma.es/avispa)** is a research team at the **University of Málaga (UMA)** specializing in **social robotics** and **cognitive architectures**. Our main goal is to develop innovative technologies that enable robots to interact more naturally and effectively with humans, integrating advanced cognitive capabilities.

## Research Areas

- **Social Robotics**: Design and implementation of robots capable of socially interacting with people in various environments, such as homes, hospitals, and public spaces.
- **Cognitive Architectures**: Development of systems that provide robots with cognitive skills, such as reasoning, learning, and decision-making.
- **Human-Robot Interaction (HRI)**: Study and improvement of interfaces and communication methods between robots and humans.
- **Perception and Recognition**: Implementation of algorithms for visual, auditory, and tactile perception, as well as for recognizing human emotions and behaviors.

## Main repositories
The group has developed several open-source projects that contribute to the field of social robotics and cognitive architectures. Some of our main repositories include:

### Robot drivers

- **[scitos2](https://github.com/grupo-avispa/scitos2)**: ROS 2 stack designed for Metralabs robots that utilize the MIRA framework, including models such as SCITOS, TORY, MORPHIA, etc.
- **[pioneer_ros2](https://github.com/grupo-avispa/pioneer_ros2)**: ROS 2 stack designed for MobileRobots Pioneer robots.

### Cognitive architectures

- **[dsr_ros](https://github.com/grupo-avispa/dsr_ros)**: A ROS 2 stack that contains agents, interfaces and RQT plugins for connecting to CORTEX architecture using a Deep State Representation (DSR) graph.
- **[dsr_aal](https://github.com/grupo-avispa/dsr_aal)**: DSR agents for Ambient Assisted Living environments.
- **[mqtt_dsr_agent](https://github.com/grupo-avispa/mqtt_dsr_agent)**: DSR agent that communicates with MQTT brokers.
- **[wasp_dsr_planner](https://github.com/grupo-avispa/wasp_dsr_planner)**: Behavior Tree (BT) planner with DSR.

### Large Language Model / Agents

- **[langgraph_base_ros](https://github.com/grupo-avispa/langgraph_base_ros)**: A ROS2 package providing an intelligent conversational agent framework for robots using language models (LLMs) and tools via the Model Context Protocol (MCP)
- **[rag_ros](https://github.com/grupo-avispa/rag_ros)**: ROS 2 wrapper for Retrieval-Augmented Generation (RAG) systems.

### Navigation

- **[semantic_navigation](https://github.com/grupo-avispa/semantic_navigation)**: A ROS metapackage for semantic navigation. Includes goals generation and semantic position services and Rviz plugin.

### Perception

- **[ros_perception_pipeline](https://github.com/grupo-avispa/ros_perception_pipeline)**: Collection of perception-related nodes and tools for ROS2.
- **[depth_anything_v2_ros2](https://github.com/grupo-avispa/depth_anything_v2_ros2)**: ROS2 Wrapper for DepthAnything V2 model.
- **[ip_camera_ros2](https://github.com/grupo-avispa/ip_camera_ros2)**: Generic ROS2 node for IP camera image publishing.
- **[object_with_region](https://github.com/grupo-avispa/object_with_region)**: ROS 2 package that enriches 3D object detections with semantic region information.

### Sensors

- **[gnss_air530z_uros](https://github.com/grupo-avispa/gnss_air530z_uros)**: Global Navigation System using micro-ros.
- **[imu_bmi160_uros](https://github.com/grupo-avispa/imu_bmi160_uros)**: IMU using micro-ros.

### Interaction / Natural Language Understanding (NLU)

- **[nemo_ros](https://github.com/grupo-avispa/nemo_ros)**: ROS node for STT using NeMo Toolkit.
- **[rasa_ros](https://github.com/grupo-avispa/rasa_ros)**: A ROS2 wrapper for Rasa NLU, enabling natural language understanding capabilities in robots.

## Collaborations

The group actively collaborates with other universities, research centers, and technology companies to advance the field of social robotics and cognitive architectures.

Join us in our mission to build smarter and more social robots!

## Build Status

| Package | ROS | Build |
|---------|-----|-------|
| scitos2 | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/scitos2/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/scitos2/actions/workflows/build.yml) |
| pioneer_ros2 | ![ROS Rolling](https://img.shields.io/badge/ros2-rolling-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/pioneer_ros2/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/pioneer_ros2/actions/workflows/build.yml) |
| dsr_ros | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/dsr_ros/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/dsr_ros/actions/workflows/build.yml) |
| dsr_aal | - | [![Build](https://github.com/grupo-avispa/dsr_aal/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/dsr_aal/actions/workflows/build.yml) |
| mqtt_dsr_agent | - | [![Build](https://github.com/grupo-avispa/mqtt_dsr_agent/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/mqtt_dsr_agent/actions/workflows/build.yml) |
| wasp_dsr_planner | - | [![Build](https://github.com/grupo-avispa/wasp_dsr_planner/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/wasp_dsr_planner/actions/workflows/build.yml) |
| langgraph_base_ros | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/langgraph_base_ros/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/langgraph_base_ros/actions/workflows/build.yml) |
| rag_ros | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/rag_ros/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/rag_ros/actions/workflows/build.yml) |
| semantic_navigation | ![ROS Rolling](https://img.shields.io/badge/ros2-rolling-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/semantic_navigation/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/semantic_navigation/actions/workflows/build.yml) |
| ros_perception_pipeline | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/ros_perception_pipeline/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/ros_perception_pipeline/actions/workflows/build.yml) |
| depth_anything_v2_ros2 | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/depth_anything_v2_ros2/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/depth_anything_v2_ros2/actions/workflows/build.yml) |
| ip_camera_ros2 | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/ip_camera_ros2/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/ip_camera_ros2/actions/workflows/build.yml) |
| object_with_region | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/object_with_region/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/object_with_region/actions/workflows/build.yml) |
| gnss_air530z_uros | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/gnss_air530z_uros/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/gnss_air530z_uros/actions/workflows/build.yml) |
| imu_bmi160_uros | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/imu_bmi160_uros/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/imu_bmi160_uros/actions/workflows/build.yml) |
| nemo_ros | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/nemo_ros/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/nemo_ros/actions/workflows/build.yml) |
| rasa_ros | ![ROS Rolling](https://img.shields.io/badge/ros2-rolling-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/rasa_ros/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/rasa_ros/actions/workflows/build.yml) |
| llm_interactions_msgs | ![ROS Jazzy](https://img.shields.io/badge/ros2-jazzy-blue?logo=ros&logoColor=white) | [![Build](https://github.com/grupo-avispa/llm_interactions_msgs/actions/workflows/build.yml/badge.svg)](https://github.com/grupo-avispa/llm_interactions_msgs/actions/workflows/build.yml) |
