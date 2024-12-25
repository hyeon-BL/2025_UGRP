# F1TENTH Autonomous Racing: Algorithm Development and Verification for 2025 UGRP

## Overview

This project, part of the 2025 Undergraduate Group Research Program (UGRP), focuses on the development and verification of novel autonomous driving algorithms for the F1TENTH platform. F1TENTH is an open-source platform for autonomous systems research, utilizing 1/10th scale racing cars to provide a challenging yet accessible environment for developing and testing cutting-edge algorithms in a real-world setting (https://f1tenth.org/).

Our research will dive deep into advanced autonomous navigation techniques, pushing the boundaries of existing solutions. We aim to contribute to the field of autonomous racing by implementing and validating innovative algorithms that enhance the performance, robustness, and efficiency of these high-speed vehicles.

## Research Objectives

This project aims to achieve the following key objectives:

1. **Develop and implement advanced autonomous driving algorithms** for F1TENTH racing cars, focusing on improving performance in dynamic and unstructured environments.
2. **Design and implement a robust verification framework** utilizing both simulation-based testing and real-world experimentation to rigorously evaluate the performance of our developed algorithms.
3. **Participate in and complete a domestic F1TENTH competition** to demonstrate the efficacy of our algorithms in a competitive environment.

## Research Areas

Our research will encompass the following key areas:

### 1. F1TENTH Platform Setup and Baseline Algorithm Familiarization

*   **Hardware Assembly:** Utilize available resources and guides to assemble the F1TENTH car platform, gaining hands-on experience with the hardware components.
*   **Baseline Algorithm Exploration:** Leverage open-source autonomous driving algorithms to understand the fundamental principles and logic of autonomous navigation within the F1TENTH framework.

### 2. Novel Algorithm Development

We will focus on developing new algorithms to address the limitations of existing solutions, specifically in the following areas:

*   **Mapless Navigation using Dynamic Window Approach (DWA):**
    *   Traditional algorithms, like TEB, rely on pre-built maps and can struggle in dynamic environments due to high computational load.
    *   We will implement the DWA Local Planner as the navigation stack, aiming for faster, more efficient control by focusing on immediate, dynamically generated paths. This approach should improve performance in situations with moving obstacles and changing track conditions.
    *   **Expected Outcome:** Enhanced responsiveness and adaptability in dynamic racing scenarios, with reduced instances of momentary stops or inefficient maneuvers.
*   **Camera-Based Edge Detection for Track Perception:**
    *   Current F1TENTH setups often rely on expensive LiDAR sensors.
    *   We will explore using solely camera-based vision for environment perception, leveraging edge detection techniques to distinguish between track boundaries, obstacles, and navigable areas. This will not only reduce costs but also lower computational overhead.
    *   **Expected Outcome:** A cost-effective and computationally efficient perception system capable of accurate track identification in visually simple environments.
*   **Section-Specific Optimal Driving Strategies:**
    *   Existing motion planning algorithms often lack specific instructions on how to traverse a given path.
    *   We will develop a system that pre-trains optimal driving strategies for specific track segments (e.g., sharp turns, U-turns). This involves dividing the track into smaller sections and training a model to execute the most efficient maneuvers for each segment, considering factors like braking, acceleration, and steering.
    *   **Expected Outcome:** Improved lap times and overall racing performance through optimized execution of different track sections.

### 3. Algorithm Verification and Validation

We will employ a comprehensive verification framework to evaluate the performance of our algorithms:

*   **Simulation-Based Testing using GAZEBO:**
    *   Create a highly accurate 3D model of the target competition track in GAZEBO.
    *   Compare the performance of our novel algorithms against established baseline algorithms using key metrics:
        *   **Safety:** Number of collisions.
        *   **Efficiency:** Lap time, path optimization.
        *   **Comfort:** Smoothness of acceleration and deceleration profiles.
        *   **Navigation Accuracy:** Localization precision and path-following ability.
    *   Utilize tools like 'CARLA' and 'AWSUN', when appropriate, for additional simulation and environment variation.
*   **Real-World Validation on F1TENTH Platform:**
    *   Deploy the developed algorithms on the physical F1TENTH car.
    *   Conduct real-world testing on a physical track, comparing the performance against baseline algorithms and the simulation results.
    *   Refine and iterate on the algorithms based on real-world performance data.

## Project Timeline

*   **2025:**
    *   Platform assembly and baseline algorithm familiarization.
    *   Algorithm development and simulation-based testing.
    *   Real-world validation on the F1TENTH platform.
    *   Participation in a domestic F1TENTH competition by the end of the year.

## Expected Outcomes

*   **Novel, high-performance autonomous driving algorithms** specifically tailored for the F1TENTH platform.
*   **A comprehensive verification framework** demonstrating the effectiveness and robustness of our algorithms.
*   **Successful completion of an F1TENTH race** using the developed algorithms.
*   **Contribution to the growing body of knowledge in autonomous racing and mobile robotics.**
*   **Publication of research findings** in relevant academic conferences and journals (as appropriate).


## References

[1] F1/10 Autonomous Racing Competition, [https://korea-race24f1tenth.org/].
[2] F1/10 Guide, [https://roboracer.ai/].
