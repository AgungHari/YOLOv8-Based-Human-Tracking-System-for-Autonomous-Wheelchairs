# YOLOv8 Based Human Tracking System for Autonomous Wheelchairs. (Sistem Pelacakan Manusia Berbasis YOLOv8 untuk Kursi Roda Otonom.)

Same as the previous project but for human tracking, requested by Dr. Eko Mulyanto Yuniarno,S.T.,M.T

🚀 Combining YOLOV8 and pose landmark, the screen is divided into 3 sections to determine the position of the human. If the bounding box is detected in the left partition, it will turn right, and vice versa, if the bounding box is detected in the right partition, it will turn left, ensuring the human remains in the center. If the human is within a distance of less than 1 meter, it will stop.
## Demo

![aldiyolo](https://github.com/user-attachments/assets/876d6f00-ef9b-4f14-a8c0-fc7b76152c97)

## Installation
PyPi version

![MediaPipe version](https://img.shields.io/badge/MediaPipe-v0.10.14-blue)
![Ultralytics version](https://img.shields.io/badge/Ultralytics-v8.1.42-pink)
![Tensorflow version](https://img.shields.io/badge/Tensorflow-v2.10.1-orange)
![OpenCV version](https://img.shields.io/badge/OpenCV-v4.9.0.80-green)
![IPyKernel version](https://img.shields.io/badge/IPyKernel-v6.29.4-yellow)

Actually, you need an ESP32 and the wheelchair to run it.

```bash
  python --version
  python -m venv nama_venv
  nama_venv\Scripts\activate
  pip install mediapipe
  pip install ultralytics
  pip install opencv-python
```
    
## Features

- Automatic anti-collision safety feature, when the detected human is within 1 meter.
- Two speed modes: when going downhill, it will send a delay with each command sent, while in default mode, it uses the standard speed. 🚀

![LOGO](https://github.com/user-attachments/assets/95a6c264-e6cd-4ea9-b378-208966d44ba6)



## Authors

- [@AgungHari](https://github.com/AgungHari)
- [@AldiFahmi](https://github.com/vetc2)

