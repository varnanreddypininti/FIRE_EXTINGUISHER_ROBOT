# FIRE_EXTINGUISHER_ROBOT
The Fire Extinguisher Robot is a semi-autonomous system designed to detect and extinguish fires in emergency situations. Equipped with an IR sensor for fire detection and an ultrasonic sensor for obstacle avoidance, the robot is controlled wirelessly via the Blynk app through an ESP32 microcontroller. This allows the robot to autonomously navigate towards fire sources while avoiding obstacles, but it can also be manually controlled in real time when needed.

The IR sensor detects infrared radiation from flames, triggering the robot to activate its fire suppression system once a fire is identified. This feature ensures a swift response, which is critical in reducing fire damage in urgent scenarios. The ultrasonic sensor helps the robot navigate its surroundings by detecting obstacles, enabling smooth movement even in complex environments.

While the robot is capable of autonomous operation, it also provides manual control through the Blynk app, which offers a user-friendly interface for steering the robot and monitoring its status. This flexibility ensures that the robot can adapt to different situations, whether operating on its own or being controlled remotely by the user.

The ESP32 microcontroller is the backbone of the robot, enabling communication with the Blynk app and coordinating the various sensors and fire suppression mechanisms. The use of the ESP32 ensures reliable wireless communication, which is crucial for remote control and monitoring.

This Fire Extinguisher Robot has numerous practical applications, such as in industrial settings, public buildings, or disaster zones. It reduces human exposure to fire hazards while providing a faster response to fire emergencies. The robot’s ability to both autonomously detect fires and be manually controlled through the Blynk app makes it a versatile and effective tool in fire safety.
