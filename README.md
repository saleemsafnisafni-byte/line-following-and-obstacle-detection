# line-following-and-obstacle-detection
A line-following robot with obstacle detection, built using ATmega328P, L298N motor driver, 2 IR sensors for line tracking, and an ultrasonic sensor for collision avoidance.

This project is a Line Following Robot with Obstacle Detection designed using the ATmega328P microcontroller. The robot is capable of following a predefined path (line) and intelligently detecting obstacles in its way.

Microcontroller (ATmega328P): Acts as the brain of the system, processing sensor inputs and controlling the motors.

Motor Driver (L298N): Used to drive the DC motors, enabling forward, backward, left, and right movements.

Line Detection: Implemented using two IR sensors, placed at the bottom of the robot to detect the black/white line contrast on the floor. The microcontroller interprets these signals to keep the robot on track.

Obstacle Detection: An ultrasonic sensor is mounted at the front of the robot to detect objects in its path. When an obstacle is detected within a predefined range, the robot can stop or change its movement to avoid collision.

Functionality:

The IR sensors continuously track the line.

The ATmega328P processes sensor readings and controls the motors through the L298N driver.

If no obstacle is detected, the robot follows the line.

If an obstacle is detected by the ultrasonic sensor, the robot halts or executes an avoidance maneuver.

This project demonstrates the integration of embedded systems, sensor interfacing, and motor control, and has applications in autonomous navigation, robotics competitions, and intelligent transport systems.
Demo Video

Watch the project in action on YouTube: https://youtube.com/shorts/s5YyHKs8GqY, @SafniSaleemsafni
