# RGB CAMERAS

## 📌 Project Purpose
This project explores the operation principles, applications, and technical implementations of **RGB-D cameras** (capturing both color and depth information). It reviews existing technologies, market devices, and current trends, while presenting two Intel RealSense–based algorithms tested in real-world scenarios.

---

## 📖 Contents
- **RGB-D Camera Technology**
  - Simultaneous RGB and Depth capture
  - Structured Light, Time-of-Flight (ToF), Stereo Vision
- **Main Manufacturers and Devices**
  - Microsoft Kinect, Intel RealSense, Orbbec Astra
- **Applications**
  - Mobile robotics (SLAM)
  - 3D reconstruction
  - Healthcare (prosthetic design, surgical planning)
  - Biometrics (facial recognition)
- **Recent Trends**
  - AI integration
  - HDR depth imaging
  - Higher precision sensors

---

## 🔬 Main Findings
- RGB-D cameras became mainstream after Microsoft Kinect’s 2010 launch.
- Each depth capture technology has specific pros and cons.
- Hardware + algorithm improvements enabled real-time 3D scanning and object tracking.
- Challenges include noise in low-light, ambient light sensitivity, and limited range.

---

## 🚀 Future Opportunities
- Depth sensor integration into mobile devices
- Metaverse and spatial computing applications
- Quantum-dot based depth sensors
- AI-powered adaptive perception

---

## 💻 Implementation
### Algorithm 1
- **Goal:** Capture RGB and depth data, calculate distance to center point  
- **Hardware:** Intel RealSense camera  
- **Output:** RGB image + depth map with distance overlay  

### Algorithm 2
- **Goal:** Detect and track objects of a specific color  
- **Process:** HSV masking, contour detection, rectangle and line drawing  

---

## 📦 How to Run
1. Install Intel RealSense SDK.  
2. Install dependencies (OpenCV, NumPy, etc.).  
3. Run the desired algorithm file.  
4. View real-time RGB and depth outputs.

---

## 📚 References
1. Intel Corporation (2020a), ‘Intel realsense lidar camera l515’, https://www.intelrealsense.com/lidar-camera-l515/. Accessed: 2025-05-01.  
2. Intel Corporation (2020b), ‘Slam with intel realsense cameras’, https://github.com/IntelRealSense/librealsense/blob/master/doc/slam.md. Accessed: 2025-05-01.  
3. Intel Corporation (2024), ‘Intel realsense depth module d421’, https://www.intelrealsense.com/depth-module-d421/. Accessed: 2025-05-01.  
4. Intel Corporation (2025), ‘Intel realsense technology overview’, https://www.intelrealsense.com/. Accessed: 2025-05-01.  
5. Kindem, J. M. et al. (2019), ‘Single-photon imaging with a quantum dot image sensor’, Nature Photonics 13, 800–805.  
6. Microsoft Corporation (2011a), ‘Kinect for windows sdk beta’, https://www.microsoft.com/en-us/research/project/kinect-for-windows-sdk-beta/. Accessed: 2025-05-01.  
7. Microsoft Corporation (2011b), ‘Kinect fusion: Real-time 3d reconstruction’, https://www.microsoft.com/en-us/research/project/fusion/. Accessed: 2025-05-01.  
8. Müller, T. et al. (2020), ‘Spatial fusion gan for image synthesis’, Computer Graphics Forum 39(2), 265–276.  
9. Occipital Inc. (2025), ‘Structure sensor’, https://structure.io. Accessed: 2025-05-01.  
10. Stereolabs (2020), ‘Zed 2 depth sensing camera’, https://www.stereolabs.com/en-es/products/zed-2. Accessed: 2025-05-01.  
11. Zhang, H. et al. (2020), ‘Depth sensing for precision agriculture using rgb-d camera and deep learning’, Computers and Electronics in Agriculture 173, 105379.  
