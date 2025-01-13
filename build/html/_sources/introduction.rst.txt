Building fully Autonoous robot guide!
======================================

Introduction
-------------
This documentation contains everything we learnt(batch 2078 members) while building robots for ABU Robocon 2024, vietnam.
To give an overview, our main task was to develop 2 robots: one automatic robot and one manual/automatic robot

* Automatic robot had to be capable of ball selection based on color of the ball and self navigation with run-time decisions
* Manual robot had to be eqquiped with ball shooting mechanism and item (seedling) pick-drop mechanism.

This section specifically deals with development of **automatic robot**. The key concepts used in this robot are:

1. ROS2 framewrok
2. OpenCV
3. Nav2 ros package
4. BehaviorTree
5. Linefollower

