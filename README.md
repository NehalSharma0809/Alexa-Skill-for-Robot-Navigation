# Alexa-Skill-for-Robot-Navigation

## Introduction:
This skill aims to control robots with our voice using the Alexa Skills Kit. The following services have been used to design this Alexa skill:
i)   the Alexa Skills Kit (ASK)
ii)  the Robotics Operating System (ROS)
iii) services from Amazon Web Services (AWS), including AWS Lambda, AWS IoT Core and AWS RoboMaker

## Setup:
i) Sign into the AWS console

ii) Set up your infrastructure with AWS CloudFormation: There are two primary components to the system. The first component is a collection of AWS resources that process the commands we give your robot, and allow us to simulate the robot in a virtual environment. The second is part of the Alexa Skills Kit, and takes care of letting you interact with your robot via an Alexa-enabled device.
The resources in the first component include a Virtual Private Cloud, IAM roles and security groups to control access, and an Amazon S3 bucket to store artifacts.To setup these resources, we run a CloudFormation script to take care of the heavy lifting.

iii) Creating a ROS Development Environment in AWS Robomaker

iv) Update the default security group

## Secure Communication with AWS IoT
### MQTT 
 MQTT is a widely adopted, lightweight messaging protocol designed for constrained devices. A common way to communicate with robotics remotely is to send messages to robots via MQTT messages. The system you build today will use X.509 Certificates to authenticate the robot with AWS IoT Core, allowing you to pass messages securely.

We need to follow the following steps for establishing a secure communication with AWS IoT to useit to securely pass messages to your robot: create certificates, attach a new policy to our certificate and get the AWS IoT endpoint

