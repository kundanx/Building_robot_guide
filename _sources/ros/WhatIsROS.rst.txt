ROS
===
ROS( Robot operating System) is framework used for robot development. Why ros and what are its features of ros are available in internet but some of the benifits which we felt are
as follows.

* ROS allows easy data flow between various components of the robot. Such as:
    1. Easy communication between multiple robots
    2. Easy data flow between various functions/algorithms.
    3. Allows a particular system(algorithms) to be independent of other systems.(i.e. Source of Input to a system can be anything, like a script(ros node) which produces fake odometry data)

* Allows easier intergration of work done by others programmers. In our case:
    1. Linefollower algorithm, openCV pipeline and navigation algorithms were developed independent to each other but we had defined what are the inputs and outputs of the system are.

* Huge collection of packages for all sorts of work (Localization, odometry, Imu, self navigation, Slam, Transformation, etc)

How to get Started
-------------------

Even if you are complete beginner to ros ,you can follow these guidelines and become quite good actually.

1. Here are two playlist which will help you to have an overview of what ros is.
    * https://www.youtube.com/playlist?list=PLunhqkrRNRhYYCaSTVP-qJnyUPkTxJnBt
    * https://www.youtube.com/playlist?list=PLunhqkrRNRhYAffV8JDiFOatQXuU-NnxT

.. Note::
    I encourage beginners to watch these videos in sequence without attempting to write code initially.
    This will provide an overview of how ROS works, what nodes are, and how packages are implemented.
    After completing the videos once, you can rewatch them and write your own code alongside.

2. After simulating your robot in gazebo or igntion, you should develop your own turtle-bot.
    Simulation work is very easy, everything automatically (If your are beginner like i was, you will have hard time
    understanding how data flows and which part is generating the command velocities.) 

.. figure:: images/turtle_bot.jpg
   :align: centre