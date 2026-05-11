# Lidar-Scout-Rover

## Introduction
The LiDAR Scout Rover is an autonomous mobile robotics platform designed to map and navigate diverse environments using real-time sensing. Developed as a senior project at the University of Houston-Clear Lake, the rover integrates advanced hardware and software to bridge the gap between theoretical autonomous concepts and practical implementation.

## Abstract 
The LiDAR-based Scout Rover project was developed to map spaces, navigate obstacle awareness, monitor gas readings, and display live sensor feedback within a ROS 2 Jazzy system. The final platform used a distributed architecture in which an Arduino Mega handled low-level motor and gas-sensor functions, a Raspberry Pi 5 published LiDAR, camera, and bridge topics, and a workstation ran Point-LIO, Nav2, RViz2, and the main visualization tools. During testing, the rover was able to generate LiDAR maps, publish gas data, stream camera output, and execute navigation experiments with both a frontfocused obstacle pipeline, 360-degree costmap pipeline, and our final pipeline used Point_LIO and Map Corrected pipeline. The results show that a relatively compact multi-computer rover can support practical sensing and semiautonomous navigation, while also highlighting future work in TF stability, software tuning, and demonstration reliability.

## Rover 

## Electrical 

## Software
