# Alexa-Skill-for-Robot-Navigation

## Introduction:
This skill aims to control robots with our voice using the Alexa Skills Kit. The following services have been used to design this Alexa skill:
i)   the Alexa Skills Kit (ASK)
ii)  the Robotics Operating System (ROS)
iii) services from Amazon Web Services (AWS), including AWS Lambda, AWS IoT Core and AWS RoboMaker

By the end of this project, we have a skill that lets us send voice commands to a robot, like "tell the robot to move forward," or "ask the robot to spin around." Each command is converted to a directive via ASK, which is then securely passed along to the robot. The robot will monitor for messages on a special "node" that we will create. When the robot recognizes a new command, it can then execute the associated action (e.g., move forward).
