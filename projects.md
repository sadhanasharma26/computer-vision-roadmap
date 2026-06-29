# 🛠️ Beginner Projects

## Project 1: Basic Image Operations
- Skills: OpenCV basics, image manipulation
- Description: Create a tool for resizing, rotating, and filtering images

## Project 2: Face Detection Application
- Skills: Haar cascades, real-time processing
- Description: Build a webcam app for real-time face detection

## Project 3: Object Tracking
- Skills: Feature detection, tracking algorithms
- Description: Track objects in video streams

## Project 4: Handwritten Digit Recognition
- Skills: CNN, deep learning, MNIST
- Description: Train a neural network to recognize handwritten digits

## Project 5: Image Classification Web App
- Skills: Transfer learning, web deployment
- Description: Create a web app that classifies uploaded images

## Project 6: Document Scanner
- Skills: Perspective transformation, edge detection
- Description: Build an app to scan and straighten documents

---

# 🧭 Multi-View Geometry & 3D Projects

## Two-View Structure from Motion from Scratch  · _Advanced_
- Skills: Feature matching, epipolar geometry, fundamental/essential matrix, RANSAC, triangulation, bundle adjustment, point clouds
- Description: Take two overlapping photos, match SIFT/ORB features, estimate the fundamental and essential matrices with RANSAC, recover relative pose (R, t) via the cheirality check, triangulate matches into a 3D point cloud, and refine with a simple bundle adjustment. Compare against OpenCV's `recoverPose`/`triangulatePoints`. The classical multi-view geometry capstone.

## Stereo Depth Map from a Calibrated Camera Pair  · _Intermediate_
- Skills: Stereo calibration, rectification, disparity, block matching, depth from disparity
- Description: Calibrate a two-camera rig (or use Middlebury/KITTI), rectify the pair so epipolar lines are horizontal, compute a disparity map with block matching / SGBM, and convert to a metric depth map via `Z = f·B/d`. Visualize depth and back-project to a point cloud.

## Marker-Based AR Cube via Homography and PnP  · _Intermediate_
- Skills: Camera calibration, homography, PnP, pose estimation, real-time video
- Description: Detect a planar marker in a webcam stream, estimate camera pose with `solvePnP`, and render a 3D cube glued to the marker as the camera moves. Implement the homography-to-pose decomposition yourself once, then use PnP for the live loop; add temporal smoothing to reduce jitter.

---

# 🚀 Capstone & Practice Projects

## From-Scratch Convolution and Edge Detector in NumPy  · _Beginner_
- Skills: Convolution, image gradients, non-maximum suppression, NumPy vectorization, Canny pipeline
- Description: Implement 2D convolution, Gaussian blur, and a full Canny pipeline (gradients, NMS, hysteresis) using only NumPy, then validate against `cv2.Canny`.

## Fine-Tune and Export an Edge Object Detector  · _Advanced_
- Skills: Transfer learning, object detection, mAP/IoU evaluation, ONNX export, INT8 quantization, edge benchmarking
- Description: Fine-tune a small YOLO model on a custom 3–5 class dataset, evaluate with mAP and a precision-recall curve, export to ONNX, INT8-quantize, and benchmark FPS vs. accuracy on CPU (or a Raspberry Pi / Jetson). Ties the deep-learning and edge phases together.

---

## 🌟 My Computer Vision Projects

Below are some of my own computer vision projects. Explore the code, try them out, and get inspired!

### [Open-CV-examples](https://github.com/sadhanasharma26/Open-CV-examples.git)
**Short Description:** This repository contains few snippets of codes that I practiced while learning Open CV.

### [depth-estimation-using-OpenCV](https://github.com/sadhanasharma26/depth-estimation-using-OpenCV.git)
**Short Description:** A Python project for real-time depth estimation using stereo vision, leveraging OpenCV and live video from two cameras. This system demonstrates the practical use of computer vision to compute accurate depth and disparity maps — essential for robotics, augmented reality, and autonomous vehicle applications.

### [numberplate_ocr](https://github.com/sadhanasharma26/numberplate_ocr.git)
**Short Description:** A Python project for automatic detection and Optical Character Recognition (OCR) of vehicle license plates from images using OpenCV, EasyOCR, and computer vision techniques.

---

_You can fork, star, or contribute to any of these projects!_
