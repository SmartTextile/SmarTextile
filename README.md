SmarTextile
===========
9/5/2014
quadruped


This is a git for development of a quadruped (mammalien) robot with ROS but it can be used with every four legged if you re-write the reverse kinetic module.


design of an URDF file (parametric memer lenght with xacro)

a joints service 
a joints-statte publisher for siulation with Rvis
a quick tansert od 12 servos command to an arduino via a serial USB link
I have tried to use the nice arduino_Ros_Bridge write_servo service ut it is too slow, only 10 Hz, to have a nice move.


The use of teleop-keyborad or teleop_joystick for command.

I have already a nice parametric walking gait (including turn, ckward that can start from any position) tested on arduino 2560.
I have to clean up the code and convert high speed aproximation (int) to float for a better result on a powerful computer with ROS.
