<p align="center">
  <a href="https://farizdevloper.blogspot.com/">
    <img src="https://github.com/user-attachments/assets/ea5d3ce8-7b37-4af7-bb9a-3c8371db7b9d" alt="NV -R 40 logo">
  </a>
</p>

<h3 align="center">NV -R 40</h3>

<p align="center">
 NV -R 40
  <br>
  <br>
  <a href="https://wpscan.com/](https://farizdevloper.blogspot.com" title="homepage" target="_blank">NV -R 40 Camera</a> - <a href="https://wordpress.org/plugins/wpscan/" title="NV -R 40" target="_blank">R- 40</a>
</p>

<p align="center">
  <a href="https://badge.fury.io/rb/wpscan" target="_blank"><img src="https://badge.fury.io/rb/wpscan.svg"></a>
  <a href="https://hub.docker.com/r/wpscanteam/wpscan/" target="_blank"><img src="https://img.shields.io/docker/pulls/wpscanteam/wpscan.svg"></a>
  <a href="https://github.com/wpscanteam/wpscan/actions?query=workflow%3ABuild" target="_blank"><img src="https://github.com/wpscanteam/wpscan/workflows/Build/badge.svg"></a>
  <a href="https://codeclimate.com/github/wpscanteam/wpscan" target="_blank"><img src="https://codeclimate.com/github/wpscanteam/wpscan/badges/gpa.svg"></a>
</p>



# 🛰️⚡ Tactical Thermal Camera System  
### *"Eyes in the Dark. Intel in Real-Time."*


> An **advanced AI-powered thermal surveillance system** engineered for **defense, tactical reconnaissance**, and **real-world field operations**.  
> Combines **infrared thermal imaging**, **night vision**, and **real-time object detection** in one compact solution.

---

## 🪖 Military-Grade Features

| 🔥 Feature | Description |
|-----------|-------------|
| 🎯 **Real-Time Object Detection** | YOLOv3 Deep Learning integration detects humans, vehicles, and more with high confidence. |
| 🌡️ **Thermal Imaging** | Supports MLX90640 thermal sensor. Falls back to simulated thermal if not available. |
| 🌙 **Night Vision Mode** | Enhances low-light visibility using histogram equalization. |
| 🧠 **Tactical HUD** | On-screen overlay with timestamp, system status, and live object minimap tracking. |
| 🎨 **Colormap Switching** | Dynamic color palettes: Jet, Hot, Inferno, Plasma, Viridis. |
| 🔍 **Zoom Mode** | Digital zoom for close-up observation. |
| 📼 **Video & Snapshot Recording** | Automatically saves mission footage and stills. |
| 🧾 **Telemetry Logging** | Logs every detection with time, object, confidence, and position. |
| 📍 **Minimap Tracker** | Tracks object movement across time and space. |

---

## 🧭 Controls (Keyboard)

| Key | Action |
|-----|--------|
| `Q` | Quit program |
| `R` | Toggle recording |
| `S` | Save snapshot |
| `C` | Change thermal colormap |
| `N` | Toggle night vision |
| `Z` | Enable/disable zoom |

---

## 📂 Output Structure

All mission data is saved to:

camera sensor panas/ ├── recording_YYYYMMDD_HHMMSS.avi ├── snapshot_YYYYMMDD_HHMMSS.jpg └── telemetry_log.txt

bash
Copy
Edit

Example log:

Timestamp Object Confidence X Y Width Height 2025-04-16 14:02:11 person 0.93 221 102 60 120 2025-04-16 14:02:14 vehicle 0.87 412 160 80 60


---

## ⚙️ Installation Guide

### 1. Install Python dependencies

```bash
pip install opencv-python numpy scipy
2. (Optional) Install MLX90640 support
bash
Copy
Edit
pip install adafruit-circuitpython-mlx90640
3. Download YOLOv3 model files
Download the following files and place them in your project directory:

yolov3.cfg

yolov3.weights

coco.names

🎖️ Use Cases in Defense
✅ Perimeter Surveillance

✅ Border Patrol

✅ Covert Recon Missions

✅ Intruder Detection in Restricted Zones

✅ Payload Camera for Drones / UGVs

✅ After-Action Review & Intelligence Briefing

🚀 Launch Instructions
bash
Copy
Edit
python tactical_thermal_camera.py
🧰 Expandability Ideas
Upgrade to YOLOv5 or YOLOv8

Add encrypted telemetry & GPS geotags

Stream footage via Flask / WebRTC

Deploy on Raspberry Pi or Jetson Nano

Integrate with secure command-and-control networks


---

✅ **Tips to use it perfectly:**

- Name the file `README.md` and place it in the root directory of your GitHub repository.
- If you're uploading it elsewhere (e.g., GitLab or a private server), Markdown formatting will still work.
- For visual appeal, add a screenshot or short GIF of the system in action right under the first section (optional but highly recommended).

Want me to include a GitHub badge layout too (like Python version, license, build passing)? Let me know!
