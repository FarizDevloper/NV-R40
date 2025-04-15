🛰️⚡ TACTICAL THERMAL CAMERA SYSTEM
"Eyes in the Dark. Intel in Real-Time."
An advanced AI-powered thermal surveillance system engineered for defense, tactical reconnaissance, and real-world field operations.
Combining infrared thermal imaging, night vision, and real-time target detection in a single compact software solution.

🪖 MILITARY-GRADE FEATURES
🔥 Feature	🛠 Description
🎯 Real-Time Target Detection	Integrated with YOLOv3 Deep Learning to identify humans, vehicles, and more with precision.
🌡️ Thermal Vision Support	Native integration with MLX90640 thermal sensors for high-accuracy infrared imaging (24x32 resolution).
🌙 Night Vision Mode	Converts low-light environments into readable grayscale vision with histogram equalization.
🧠 Tactical HUD Interface	Displays key intel: timestamps, system mode, and a dynamic minimap tracker showing detected object paths.
🎨 Colormap Switching	Change thermal visuals instantly with high-contrast palettes: Jet, Inferno, Plasma, Hot, Viridis.
🔍 Zoom Mode	Focused magnification for long-range target clarity.
📼 Video & Snapshot Capture	Automatically record and save mission footage and tactical snapshots.
🧾 Telemetry Logging	Every detection is logged with: `Time
📍 Minimap Tracking	Tracks and draws object movement across time, visualized as pathlines.
🖥️ SYSTEM INTERFACE
🧭 Intuitive, Field-Ready Control Panel

plaintext
Copy
Edit
[Q] Quit     [R] Record Video     [S] Snapshot
[C] Change Colormap     [N] Toggle Night Vision     [Z] Zoom
✅ Real-time visual feedback
✅ On-screen overlay with mission telemetry
✅ Integrated alert system (Beep sound on detection)

📂 OUTPUT STRUCTURE
All mission logs and media are automatically saved to:

nginx
Copy
Edit
camera sensor panas/
├── snapshot_YYYYMMDD_HHMMSS.jpg
├── recording_YYYYMMDD_HHMMSS.avi
└── telemetry_log.txt
⚙️ INSTALLATION
Install Python Packages:

bash
Copy
Edit
pip install opencv-python numpy scipy
(Optional) If using MLX90640:

bash
Copy
Edit
pip install adafruit-circuitpython-mlx90640
Download YOLOv3 Model Files:

File	Description
yolov3.cfg	YOLOv3 configuration file
yolov3.weights	Pre-trained weights (200MB+)
coco.names	Object class labels
Download links:

📦 YOLOv3 Weights

🧠 YOLOv3 Config

📄 COCO Names

🛡️ MILITARY & SECURITY APPLICATIONS
🟢 Perimeter Defense
🟢 Border Surveillance
🟢 Night Recon Missions
🟢 Intruder Detection in Restricted Zones
🟢 UAV / UGV Payload Vision System
🟢 Mission Playback and Debriefing

📊 SAMPLE TELEMETRY LOG
txt
Copy
Edit
Timestamp            Object     Confidence     X     Y     Width     Height
2025-04-16 14:02:11  person     0.93           221   102   60        120
2025-04-16 14:02:14  vehicle    0.87           412   160   80        60
🧰 EXPANDABILITY
Replace YOLOv3 with YOLOv5 / YOLOv8

Add GPS/Geotagging

Encrypt logs & footage

Stream to command center via WebRTC / Flask

Deploy on Raspberry Pi, Jetson Nano, or ARM-based drones

🎖️ WHY THIS SYSTEM STANDS OUT
✔️ Real-time AI vision
✔️ Modular sensor support
✔️ Built for rugged use
✔️ Logs every move
✔️ Tactical-grade overlay
✔️ Easy to extend, fast to deploy

