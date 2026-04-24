# Computer Vision Learning Roadmap

## Phase 1: The Foundations — Math & Pixels (4–6 weeks)

**Math**
- Vectors, Matrices, Dot Products
- Eigenvalues & Eigenvectors (PCA)
- Partial Derivatives & Gradients
- Chain Rule — foundation of backprop

**Image Processing**
- Pixels, Color Spaces (RGB / HSV / LAB)
- Histograms & Histogram Equalization
- Convolution & Cross-Correlation
- Frequency Domain (FFT basics)
- Morphological Operations (erosion / dilation)
- NumPy image manipulation

**Milestone Project:** NumPy Image Filter Library (Gaussian blur, Sobel, histogram equalization — no OpenCV)

---

## Phase 2: Feature Engineering & Classical CV (4–5 weeks)

- SIFT — Scale Invariant Feature Transform
- SURF & ORB (fast alternatives)
- HOG — Histogram of Oriented Gradients
- Harris Corner Detector
- Canny Edge Detection (full pipeline)
- Camera Calibration — Zhang's method
- Homography & RANSAC
- Optical Flow — Lucas-Kanade
- Bag of Visual Words
- Feature Matching: Brute-Force vs. FLANN

**Milestone Project:** Panorama Stitcher (SIFT + FLANN + RANSAC + perspective warp)

---

## Phase 3: The Deep Learning Era (6–8 weeks)

- CNN: Convolution, Pooling, Padding, Stride
- Backpropagation & Gradient Descent variants
- Architecture evolution: LeNet → AlexNet → VGG → ResNet
- Transfer Learning & Fine-Tuning
- Data Augmentation
- Object Detection: Faster R-CNN, SSD
- YOLO family (v3 → v8)
- Semantic Segmentation: FCN, DeepLab
- Instance Segmentation: U-Net, Mask R-CNN
- Evaluation: mAP, IoU, Precision-Recall

**Milestone Project:** Custom 5-class object detector (YOLOv8 + U-Net segmentation, logged to W&B)

---

## Phase 4: Modern Frontiers (5–7 weeks)

- Self-Attention mechanism
- Vision Transformer (ViT) — patch embeddings
- CLIP — contrastive language-image pre-training
- SAM — Segment Anything Model
- 3D Vision: stereo, depth estimation, point clouds
- NeRF — Neural Radiance Fields
- Diffusion Models — DDPM, Stable Diffusion
- Model Quantization: INT8, FP16
- TFLite & ONNX export + runtime
- Edge deployment: Raspberry Pi / Jetson Nano

**Milestone Project:** Real-time edge AI detector (INT8 ONNX/TFLite, ≥10 FPS on hardware)

---
