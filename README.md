Inverse-kinematic-modeling-using-robo-analyzer-
AIM:
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given input end effector position .

COMPONENTS REQUIRED:
1.Robo analyzer software

THEORY:
Inverse Kinematics
Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

solving inverse kinematic model
image

image

image

image image

PROCEDURE:
open the roboanalyzer software.
select the robot and its degrees of freedom.
change the values of X and Y wherever necessary.
simulate the model for inverse kinematics.
plot the graph between the joints.
update the DH parameters of the link configuration and end effector configuration.
SIMULATION
RPR ROBOT:
inv rpr

dh rpr

3R ROBOT:
3r inv

3r dh

PLOT
RPR ROBOT:
image

rpr

3R ROBOT:
image

3r graph

RESULTS :
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.

