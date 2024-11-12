---
title: "Motion Compensation Using Deep Reinforcement Learning"
collection: experiences
type: "Research Projects"
permalink: /experiences/2024-motion-compensation
venue: "UESTC"
start: 2024-01-01
end: "Present"
location: "Chengdu, China"
---

This project aims to achieve motion compensation for surgical robots by developing an end-to-end visual model for controlling the robot's end-effector torque. A virtualized robot model is implemented in Unity to facilitate reinforcement learning for model training, which is subsequently transferred to the real robot using Sim2Real transfer techniques.

I was responsible for:

* Digital twin of surgical machinery built in **Unity ML Agent** based on **system identification**;
* Training the model in a virtual environment by **SAC-LSTM** / **PPO-LSTM**;
* Sim2Real deployment;