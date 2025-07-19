🦾 Autonomous Warehouse Robot

This project is a conceptual design for an automated robot system intended to convert a traditional food storage warehouse into a fully automated warehouse with minimal or no human intervention.

📐 Description

This robot is designed using [Tinkercad] and built on a mobile base equipped with wheels. It features a 5 DOF robotic arm mounted on the base for handling food packages. The current model includes a placeholder camera module which can be replaced by sensors such as a depth camera, LiDAR, or barcode scanner. Additional sensors can be added on the arm to improve precision, obstacle avoidance, and object detection.

⚠️ Note: The dimensions in this model are not accurate and were designed for conceptual visualization only.

🤖 Design Components

Mobile Base (Red box): Represents the drive unit for movement inside the warehouse.

Robotic Arm (Orange): Previously designed and reused in this model. It provides the flexibility to reach, grab, and place items.

Camera Placeholder: This is a visual representation of where the camera or sensor system can be installed.

Wheels: Four simulated wheels to represent mobility.

Sensor Ports: Sensors can be mounted on the gripper or joints to detect item location, orientation, and surroundings.

🔁 Working Envelope

The robot's working envelope (range of motion) includes:

1.Horizontal Range: Covers the platform width and extended area reachable by the arm.

2.Vertical Range: The robotic arm can reach varying shelf levels due to its 5 DOF.

3.Rotation: Base rotation enables access to multiple directions without needing to move the whole robot.

4.Arm Joints: Allow for object manipulation in tight spaces and complex orientations.

🧠 Task Execution Algorithm

1. Start robot and initialize all motors and sensors.
2. Scan warehouse for available food packages.
3. Plan path to nearest available item using object recognition.
4. Navigate to item using obstacle avoidance.
5. Use the robotic arm to pick the item.
6. Transport the item to the assigned delivery zone or shelf.
7. Repeat the process until all tasks are completed.
8. Return to charging station or idle zone when no tasks remain.

 ✅ Future Improvements
 
Add real-time mapping (SLAM)

Integrate RFID scanning

Optimize gripping mechanism for soft or fragile items

Implement AI-based sorting and prioritization

