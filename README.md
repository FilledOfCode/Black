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

To use add a new application in the Spark Build IDE, add an extra set of files and copy and paste the move.cpp and move.h files into the project. Next add the SparkIntervalTimer library using the Spark Build interface. Then copy and paste the main code from Spark-MeArm.ino into the main sketch. Flash your core and you should be working.

You can use the tester.html file to control your Spark Core. Its not a great UI, but it lets you try out the inverse kinematics by specifying target positions.

You will need to get your Spark Core ID, and your Access Token from the Spark Build IDE.