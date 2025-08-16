📌 Overview

This project is a simple chat application built with ROS (Robot Operating System).
It demonstrates the publisher–subscriber model in ROS using two nodes:

Speaker Node → Publishes messages to the microphone.

Microphone Node → Subscribes to the speaker and sends responses back.

It also leverages AsyncSpinner to enable multithreading so that publishing and subscribing can happen concurrently without blocking.

⚙️ Tools & Skills Demonstrated

Operating System: Ubuntu 18.04 / 20.04

ROS Versions: Melodic / Noetic

Language: C++ (ROS nodes with roscpp)

Build System: Catkin & CMake

Concepts:

Publisher & Subscriber communication in ROS

Multithreading with AsyncSpinner

Topic-based messaging
