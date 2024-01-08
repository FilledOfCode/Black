### Hi there 👋

<!--
**FilledOfCode/FilledOfCode** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
Spark-MeArm
===========

A spark core controller for the MeArm robotic arm. Complete with S-Curve motion planning and inverse kinematics.

This sketch provides servo control for the [MeArm robotic arm](https://github.com/phenoptix/MeArm) kit using a Spark Core. It implements S-Curve motion planning borrowing heavily from the [TinyG firmware](https://github.com/synthetos/TinyG) implementation. It also uses the [Inverse Kinematics](https://github.com/phenoptix/MeArm/blob/master/MeArmIK/MeArmIK.ino) implementation provided by Phenoptix.

To use add a new application in the Spark Build IDE, add an e