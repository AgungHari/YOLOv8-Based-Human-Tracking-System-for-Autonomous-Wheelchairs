[![banner2](banner2.png)](https://www.agungg.com/)

# YOLOv8 Based Human Tracking System for Autonomous Wheelchairs. (Sistem Pelacakan Manusia Berbasis YOLOv8 untuk Kursi Roda Otonom.)

![MediaPipe version](https://img.shields.io/badge/MediaPipe-v0.10.14-blue)
![Ultralytics version](https://img.shields.io/badge/Ultralytics-v8.1.42-darkred)
![Tensorflow version](https://img.shields.io/badge/Tensorflow-v2.10.1-orange)
![OpenCV version](https://img.shields.io/badge/OpenCV-v4.9.0.80-darkgreen)
![IPyKernel version](https://img.shields.io/badge/IPyKernel-v6.29.4-yellow)
![License](https://img.shields.io/badge/License-MIT-darkblue)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

Same as the previous project but for human tracking, requested by Dr. Eko Mulyanto Yuniarno,S.T.,M.T

Combining YOLOV8 and pose landmark, the screen is divided into 3 sections to determine the position of the human. If the bounding box is detected in the left partition, it will turn right, and vice versa, if the bounding box is detected in the right partition, it will turn left, ensuring the human remains in the center. If the human is within a distance of less than 1 meter, it will stop.

## Acknowledgements

```bash
  Coniuncti sumus quod hostes non sunt.
```

## Project Result

In this project, a test was conducted at Tower 2 with a scenario that involved navigating the area around Tower 2. The wheelchair followed a path from the second floor to the elevator and then exited toward the parking area. The following video shows the results of this test :

![aldiyolo](https://github.com/user-attachments/assets/876d6f00-ef9b-4f14-a8c0-fc7b76152c97)

Based on the test results, the following conclusions can be drawn:

![Test](https://img.shields.io/badge/Test_Status-Success-green)

- The wheelchair successfully followed the human from the second floor to the elevator and all the way to the parking area without any issues.

## Installation
Actually, you need an ESP32 and the wheelchair to run it.

```bash
  python --version
  python -m venv nama_venv
  nama_venv\Scripts\activate
  pip install mediapipe
  pip install ultralytics
  pip install opencv-python
```
## Contributing

I am open to contributions and collaboration. If you would like to contribute, please create a pull request or contact me directly!
- Fork this repo.
- Create a new feature branch:

```bash
git checkout -b new-feature
```

- Commit your changes.
```bash
git commit -m "ver..."
```

- Push to the branch:
```bash
git push origin new-feature
```

## Features

- Automatic anti-collision safety feature, when the detected human is within 1 meter.
- Two speed modes: when going downhill, it will send a delay with each command sent, while in default mode, it uses the standard speed. 🚀

<p align="center">
  <img src="./logo.svg" alt="LOGO" width="300">
</p>

## Authors

<img alt="Static Badge" src="https://img.shields.io/badge/AgungHari-black?style=social&logo=github&link=https%3A%2F%2Fgithub.com%2FAgungHari">
<img alt="Static Badge" src="https://img.shields.io/badge/AldiFahmi-black?style=social&logo=github&link=https%3A%2F%2Fgithub.com%2Fvetc2">

## License

<img alt="GitHub License" src="https://img.shields.io/github/license/AgungHari/YOLOv8-Based-Human-Tracking-System-for-Autonomous-Wheelchairs">

