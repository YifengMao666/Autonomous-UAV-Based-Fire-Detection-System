Autonomous UAV-Based Fire Detection System

Suzhou, China | Feb 2025 – May 2025

Developed an autonomous UAV system integrating intelligent path planning, low-latency communication, 
and image-based fire detection, enabling self-guided patrolling and real-time hazard recognition.

Designed a multi-sensor UAV platform combining the Pixhawk flight controller, stereo vision module, 
and Intel NUC onboard computer.

Implemented a two-stage path planning strategy: a global TSP-based coverage planner for area exploration 
and a gradient-based local trajectory generator independent of ESDF for obstacle-aware navigation.

Built a low-latency UDP video transmission module for real-time image streaming from UAV to ground station.

Deployed a YOLOv11–Vision Transformer hybrid detection model on the ground station; trained on a mixed 
dataset, it achieved 69.3% mAP and 128 FPS inference speed for flame and smoke recognition on test data.