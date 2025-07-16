# Autonomous-Robot-for-Food-Warehouse-Automation
In this project, we aim to design an intelligent robot capable of transforming a traditional food warehouse into an automated warehouse that operates without human intervention.

## Execution Algorithm:
1. When the robot starts, it checks if everything is working — like the sensors, camera, and robotic arm.
2. It connects to the main system and receives a task.
For example: “Pick up the box from shelf A2 and move it to shelf B4.”
3. The robot uses its sensors and camera to find where it is on the map, then drives to shelf A2.
4. Once it arrives, it checks that it’s in front of the right box (by scanning a barcode or tag).
5. The robot moves its arm and picks up the box.
6. It drives to the destination (shelf B4).
7. It places the box carefully on the shelf.
8. It sends a message to the system saying the task is done.
9. Then it waits for the next task — or goes to recharge if the battery is low.

 ## Robot Design:
The robot has a few main parts that help it do its job inside the warehouse:
1. Wheels (Moving Base): These allow the robot to move around the warehouse, like a small smart car.
2. Robotic Arm: This arm can move up, down, left, and right. It picks up boxes and places them on shelves.
3. Camera: The camera helps the robot see boxes and read barcodes, so it knows what item it’s handling.
4. Sensors (like LIDAR): These help the robot avoid hitting anything and understand where it is in the warehouse.
5. Weight Sensor: It checks if the robot is holding a box or not, and how heavy it is.
6. Battery: The robot runs on a rechargeable battery so it can work without cables.
7. Main Computer (Controller): A small computer inside the robot controls everything — like moving, grabbing, and talking to the main system.
8. Wireless Connection: The robot connects to the central system through Wi-Fi to get tasks and send updates.

## Working Envelope: 
For 10×10 m Warehouse:
1. Movement Area: The robot operates freely within a 10 meters by 10 meters square space.
2. Working Height: The robotic arm can reach up to 2 meters, suitable for medium-height shelves.
3. Load Capacity: The maximum weight the robot can carry is 15 kilograms.
4. Accuracy: The robot can locate and place items with an accuracy of ±2 centimeters.
5. Movement Speed: The robot moves at a moderate speed of 0.5 meters per second to ensure safety in the confined space.
6. Operating Time: It can operate continuously for up to 6 hours before needing a recharge.



