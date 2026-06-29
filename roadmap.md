# Computer Vision Learning Roadmap

A free, structured path from raw pixels to production — five phases, each gated by a milestone project.

**Interactive version →** https://sadhanasharma26.github.io/computer-vision-roadmap/roadmap.html

---

## Phase 1: The Foundations (4–6 weeks)

_The math and pixels that everything else is built on_

- Vectors, Matrices, Dot Products
- Eigenvalues & Eigenvectors (PCA)
- Partial Derivatives & Gradients
- Chain Rule — foundation of backprop
- Pixels, Color Spaces (RGB / HSV / LAB)
- Histograms & Histogram Equalization
- Convolution & Cross-Correlation
- Frequency Domain (FFT basics)
- Morphological Ops (erosion / dilation)
- NumPy image manipulation from scratch

**Milestone — NumPy Image Filter Library:** Build Gaussian blur, Sobel edge detection, histogram equalization, and binary thresholding from scratch using only NumPy — zero OpenCV allowed. Test on BSDS500 sample images.

---

## Phase 2: Feature Engineering & Classical CV (4–5 weeks)

_The pre-deep-learning toolkit that still runs in real pipelines today_

- SIFT — Scale Invariant Feature Transform
- SURF & ORB (fast SIFT alternatives)
- HOG — Histogram of Oriented Gradients
- Harris Corner Detector
- Canny Edge Detection (full pipeline)
- Camera Calibration — Zhang's method
- Homography & RANSAC
- Optical Flow — Lucas-Kanade
- Bag of Visual Words
- Feature Matching: Brute-Force vs. FLANN

**Milestone — Image Panorama Stitcher:** Stitch 3+ overlapping photos into a seamless panorama using SIFT keypoints, FLANN feature matching, RANSAC homography estimation, and perspective warping. No high-level stitching APIs allowed.

---

## Phase 3: Multi-View Geometry & 3D Vision (4–5 weeks)

_How two flat photos become real 3D, the part deep learning tends to skip_

- Epipolar geometry & the epipolar constraint (x′ᵀ F x = 0)
- Fundamental matrix F & the normalized 8-point algorithm (uncalibrated)
- Essential matrix E & decomposition into R, t (calibrated)
- Triangulation — back-projecting matches to 3D points
- PnP — camera pose from 2D–3D correspondences
- Stereo rectification — aligning epipolar lines to scanlines
- Disparity matching & depth from a stereo pair
- Dense depth maps & point-cloud reconstruction
- Structure-from-Motion (incremental SfM)
- Bundle adjustment & intro to visual odometry / SLAM

**Milestone — Two-View Structure-from-Motion (Sparse 3D Reconstruction):** Take two photos of a static scene and get the intrinsics K from calibration (Phase 2) or image EXIF. Match SIFT/ORB features, estimate the fundamental matrix with the normalized 8-point algorithm inside RANSAC, convert it to the essential matrix (E = K′ᵀ F K), and decompose E into its four candidate (R, t) solutions. Use the cheirality check — reconstructed points must lie in front of both cameras — to pick the correct pose, then triangulate the matches into a sparse 3D point cloud and visualize it. No high-level SfM pipelines (e.g. COLMAP) for the core estimation.

---

## Phase 4: The Deep Learning Era (6–8 weeks)

_CNNs, detection, and segmentation, the everyday working stack_

- CNN: Convolution, Pooling, Padding, Stride
- Backpropagation & Gradient Descent variants
- LeNet → AlexNet → VGG → ResNet evolution
- Transfer Learning & Fine-Tuning
- Data Augmentation strategies
- Object Detection: Faster R-CNN & SSD
- YOLO family (v3 → v8) — architecture & training
- Semantic Segmentation: FCN, DeepLab
- Instance Segmentation: U-Net, Mask R-CNN
- mAP, IoU, Precision-Recall for CV evaluation

**Milestone — Custom Object Detector + Segmentation:** Label 300+ images with Roboflow (5 classes), train YOLOv8, then apply U-Net segmentation on detected regions. Log all metrics to Weights & Biases.

---

## Phase 5: Modern Frontiers (5–7 weeks)

_Transformers, generative models, and getting it onto real devices_

- Self-Attention mechanism — from scratch
- Vision Transformer (ViT) — patch embeddings
- CLIP — contrastive language-image pre-training
- SAM — Segment Anything Model
- NeRF — Neural Radiance Fields
- 3D Gaussian Splatting — real-time radiance fields
- Diffusion Models — DDPM, Stable Diffusion
- Model Quantization: INT8, FP16
- TFLite & ONNX export + runtime
- Edge deployment: Raspberry Pi / Jetson Nano

**Milestone — Real-Time Edge AI Detector:** Export your Phase 4 YOLOv8 model to ONNX/TFLite with INT8 quantization. Deploy on Raspberry Pi 4 or laptop webcam. Target ≥10 FPS with <5% mAP drop from quantization.

---
