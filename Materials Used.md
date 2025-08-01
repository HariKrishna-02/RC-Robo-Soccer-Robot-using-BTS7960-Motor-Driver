# Materials Used:

1. BTS7960 Motor Driver (43A Dual H-Bridge)(x2):
The BTS7960 is a high-power dual H-Bridge motor driver capable of handling up to 43A current. It is responsible for controlling 
the speed and direction of two brushed DC motors. In this project, it directly receives PWM signals from the RC receiver and translates 
them into voltage signals for the motors. This eliminates the need for a microcontroller like Arduino, making the circuit simpler and hardware-based.

2. FlySky FS-i6 Transmitter and Receiver (Tx/Rx):
This is a 2.4GHz 6-channel radio control system. The transmitter is used by the user to send movement commands (like forward, reverse, turn). 
The receiver, placed on the robot, receives these commands and outputs PWM signals. These signals are then connected directly to the BTS7960
motor driver to control motor movement. This setup ensures wireless remote control of the robot.

3. 500 RPM Johnson Gear Motors (×2):
These are high-torque brushed DC motors with gear reduction, making them perfect for robot movement. Each motor is connected to one wheel. 
They provide the required torque and speed to move the robot smoothly on the playing surface. At 500 RPM, they offer a good balance between speed
and torque for RoboSoccer gameplay.

4. Plastic Robot Wheels (×4):
These wheels are attached to the shafts of the Johnson motors. They allow the robot to move forward, backward, and turn based on the differential 
drive from the motors. The size and grip of the wheels are chosen to suit indoor soccer environments and ensure good maneuverability.

5. SG90 Micro Servo Motor (Optional):
The SG90 is a small and lightweight servo motor. While not mandatory, it is often used for additional functions such as a ball kicker, arm mechanism,
 or dribbler. It can be connected to one of the extra RC channels for remote actuation. Its compact size and ease of control make it ideal for lightweight 
robotic attachments.

6. 12V Battery Pack (Li-ion or LiPo, or SLA Battery):
This battery is the main power source for the robot. It supplies power to both the BTS7960 motor driver and the DC motors. The battery must be 
capable of providing enough current (usually around 3A–10A continuous) without voltage drop. A 3S Li-ion (11.1V) or sealed lead-acid (12V) 
battery is typically used.

7. Robot Chassis (Frame/Base):
The chassis is the physical structure that holds all components: motors, wheels, battery, motor driver, and receiver. It is usually made of acrylic, 
plastic, or lightweight metal. The design should be compact, balanced, and stable enough to handle quick movement and collisions during a RoboSoccer match.

8. Caster Wheel (×1, Optional but Recommended):
A caster wheel is a freely rotating third wheel that provides balance to the robot. It is not powered but supports the robot’s weight and allows it to 
turn and rotate without tipping over. This is especially useful in a 2-wheel drive robot design.

9. Wires and Connectors:
Used for electrical connections between all components. Quality wires are needed to handle the current flow from the battery to motors. 
Connectors help in quick and safe plug-and-play assembly of parts like motor terminals, battery inputs, and receiver signal outputs.

10. Power Switch:
A toggle or push-button switch is used to turn the robot on or off. This adds convenience and safety, allowing you to power down the robot 
without disconnecting the battery every time.
