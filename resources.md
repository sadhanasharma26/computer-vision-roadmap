# Curated Resources

Format: **Difficulty** · **Time** · **Type** · *Why this?* — **every resource here is free.**

The interactive site has a searchable, filterable version of this list.

---

## Phase 1 — The Foundations

**3Blue1Brown — Essence of Linear Algebra**
Easy · 6h · Video · *Visual proofs build intuition faster than any textbook — watch before reading anything else.*
https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab

**Digital Image Processing — Gonzalez & Woods (Ch. 1–5)**
Intermediate · 8h · Book · *The authoritative reference — Ch. 3 on spatial filtering is the single best treatment of convolution in print.*

**Real Python — Image Processing with NumPy & Pillow**
Easy · 2h · Tutorial · *Hands-on pixel manipulation before touching OpenCV — reveals exactly what the library abstracts.*
https://realpython.com/image-processing-with-the-python-pillow-library/

**Khan Academy — Multivariable Calculus: Partial Derivatives & The Gradient**
Easy · 4h · Course · *Free guided lessons plus practice problems that cement gradients and the chain rule — the exact calculus backprop is built on.*
https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives

**Setosa — Image Kernels Explained Visually**
Easy · 0.5h · Interactive · *Drag-and-drop kernel playground that makes convolution and edge filters click in minutes before you write a single line of NumPy.*
https://setosa.io/ev/image-kernels/

**Computerphile — How Blurs & Filters Work / Convolution**
Easy · 0.5h · Video · *Dr Mike Pound walks through spatial filtering on real images, giving intuition for the Gaussian/Sobel kernels you'll implement in the milestone project.*
https://www.youtube.com/watch?v=C_zFhWdM4ic

**Szeliski — Computer Vision: Algorithms and Applications (2nd ed.), Ch. 3 Image Processing**
Intermediate · 5h · Book · *Author-hosted free PDF; Ch. 3 is the modern, rigorous companion to Gonzalez & Woods covering filtering, pyramids, and the Fourier domain.*
https://szeliski.org/Book/

---

## Phase 2 — Feature Engineering & Classical CV

**First Principles of CV — Camera Calibration (Columbia / Shree Nayar)**
Intermediate · 3h · Video · *Clearest derivation of Zhang's method on YouTube — used in every production pipeline.*
https://www.youtube.com/channel/UCf0WB91t8Ky6AuYcQV0CcLw

**OpenCV Python — Feature Detection & Matching (Official Docs)**
Intermediate · 4h · Tutorial · *Authoritative working code for SIFT, ORB, FLANN — copy, modify, break it to learn.*
https://docs.opencv.org/4.x/db/d27/tutorial_py_table_of_contents_feature2d.html

**Lowe (2004) — Distinctive Image Features from Scale-Invariant Keypoints**
Hard · 2h · Paper · *Original SIFT paper — reading it reveals why scale-space and orientation stability matter in practice.*

**First Principles of Computer Vision — Detectors & Descriptors Monographs (Nayar, Columbia)**
Intermediate · 4h · Book · *Free SIFT-detector monograph (PDF) plus the companion lecture videos for Harris and HOG — re-derive the feature math at your own pace.*
https://fpcv.cs.columbia.edu/Monographs

**Computerphile — Canny Edge Detector (Mike Pound)**
Easy · 0.3h · Video · *The clearest short explanation of non-max suppression and hysteresis thresholding — the two steps everyone gets wrong implementing Canny.*
https://www.youtube.com/watch?v=sRFM5IEqR2w

**Szeliski CV 2nd ed., Ch. 7 — Feature Detection & Matching**
Intermediate · 4h · Book · *Free PDF chapter unifying Harris, SIFT, ORB, RANSAC and feature matching with the geometry you'll use in the panorama stitcher.*
https://szeliski.org/Book/

**OpenCV — Optical Flow (Lucas-Kanade & Dense) Official Tutorial**
Intermediate · 2h · Tutorial · *Working calcOpticalFlowPyrLK code with the math behind it — the canonical reference for the optical-flow item in the roadmap.*
https://docs.opencv.org/4.x/d4/dee/tutorial_optical_flow.html

---

## Phase 3 — Multi-View Geometry & 3D Vision

**Szeliski — Computer Vision: Algorithms & Applications (2nd ed.) — Ch. 11 SfM, Ch. 12 Depth & Stereo**
Hard · 8h · Book · *The free, canonical text tying epipolar geometry, triangulation, stereo, and bundle adjustment together.*
https://szeliski.org/Book/

**Hartley & Zisserman — Multiple View Geometry in Computer Vision (2nd ed.)**
Hard · 12h · Book · *The definitive text on projective geometry and the fundamental/essential matrices — borrow free via the Internet Archive.*
https://archive.org/details/multipleviewgeom0000hart

**Cyrill Stachniss — Photogrammetry & Computer Vision Lectures (Univ. Bonn)**
Intermediate · 6h · Course · *The clearest lecture series on the fundamental/essential matrices, the 8-point algorithm, and bundle adjustment.*
https://www.youtube.com/playlist?list=PLgnQpQtFTOGRsi5vzy9PiQpNWHjq-bKN1

**OpenCV — Epipolar Geometry (Fundamental Matrix & Epilines)**
Intermediate · 2h · Tutorial · *Runnable findFundamentalMat + computeCorrespondEpilines code — turns the epipolar constraint into a picture you can see.*
https://docs.opencv.org/4.x/da/de9/tutorial_py_epipolar_geometry.html

**Cyrill Stachniss — Photogrammetry I & II (Uni Bonn, full lecture playlist)**
Hard · 20h · Course · *University-grade derivations of camera models, epipolar geometry, bundle adjustment, and SfM from a photogrammetry expert, all free on YouTube.*
https://www.youtube.com/playlist?list=PLgnQpQtFTOGRYjqjdZxTEQPZuFHQa7O7Y

**OpenCV — Depth Map from Stereo Images Official Tutorial**
Intermediate · 1.5h · Tutorial · *Goes from rectified pairs to a disparity/depth map with StereoBM — the practical follow-on to epipolar geometry for 3D reconstruction.*
https://docs.opencv.org/4.x/dd/d53/tutorial_py_depthmap.html

**COLMAP — Structure-from-Motion Official Tutorial**
Intermediate · 3h · Tutorial · *The de-facto open-source SfM/MVS pipeline; running it on your own photos shows feature matching, bundle adjustment, and dense reconstruction end-to-end.*
https://colmap.github.io/tutorial.html

**ORB-SLAM2 — Official Open-Source Implementation (raulmur)**
Hard · 4h · Repo · *Real-time monocular/stereo/RGB-D SLAM with loop closure; reading and running it connects feature matching, pose estimation, and mapping into one system.*
https://github.com/raulmur/ORB_SLAM2

---

## Phase 4 — The Deep Learning Era

**CS231n — Convolutional Neural Networks (Stanford)**
Intermediate · 30h · Course · *Gold-standard CNN education — the lecture notes alone are worth more than most full courses.*
https://cs231n.github.io

**Ultralytics YOLOv8 — Train a Custom Object Detector**
Easy · 2h · Tutorial · *Best ROI in CV learning: train a real detector in 30 lines, forces you to understand mAP and anchors.*
https://docs.ultralytics.com

**Ronneberger et al. (2015) — U-Net: CNNs for Biomedical Image Segmentation**
Hard · 1.5h · Paper · *Skip connections introduced here appear in every modern architecture — 30k+ citations for a reason.*

**Andrej Karpathy — Neural Networks: Zero to Hero**
Intermediate · 12h · Course · *Build autograd and backprop from scratch in code so the CNN training loop is never a black box — the best free 'why it works' companion to CS231n.*
https://karpathy.ai/zero-to-hero.html

**fast.ai — Practical Deep Learning for Coders**
Intermediate · 14h · Course · *Top-down course that gets a working image classifier trained in lesson 1, then fills in transfer learning, augmentation, and training tricks.*
https://course.fast.ai/

**PyTorch — Transfer Learning for Computer Vision Official Tutorial**
Easy · 1.5h · Tutorial · *Canonical, runnable fine-tuning vs. fixed-feature-extractor recipe on ResNet — the exact pattern for the custom-detector milestone.*
https://docs.pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

**CNN Explainer — Interactive Visualization (Georgia Tech Polo Club)**
Easy · 1h · Interactive · *Click through every conv/pool/ReLU activation of a live CNN to see how an image becomes a class score — best intuition tool for the deep-learning phase.*
https://poloclub.github.io/cnn-explainer/

**Distill — Feature Visualization (Olah, Mordvintsev, Schubert)**
Intermediate · 1.5h · Tutorial · *Shows what CNN filters actually learn at each layer, giving a mental model of hierarchical features that makes architecture choices less arbitrary.*
https://distill.pub/2017/feature-visualization/

**Hugging Face — Community Computer Vision Course**
Intermediate · 15h · Course · *Free, hands-on course spanning CNNs, detection, and segmentation with Transformers/Datasets code you can run for the segmentation milestone.*
https://huggingface.co/learn/computer-vision-course/en/unit0/welcome/welcome

---

## Phase 5 — Modern Frontiers

**Dosovitskiy et al. (2021) — An Image is Worth 16×16 Words (ViT)**
Hard · 2h · Paper · *Short, readable, paradigm-shifting — proved transformers beat CNNs at scale without convolution.*
https://arxiv.org/abs/2010.11929

**Hugging Face Diffusers — Stable Diffusion from Scratch**
Intermediate · 4h · Tutorial · *Most practical diffusion path: modify the denoising loop and see exactly what breaks.*
https://huggingface.co/docs/diffusers

**TensorFlow Lite — Model Optimization & Raspberry Pi Guide**
Intermediate · 3h · Tutorial · *Quantization + TFLite is the fastest path from trained model to real hardware in under 100 lines.*
https://www.tensorflow.org/lite/guide

**OpenAI — CLIP: Connecting Text and Images (Official Blog)**
Intermediate · 1h · Tutorial · *Authoritative, approachable explanation of contrastive image-text pretraining and zero-shot transfer straight from the authors, with code links.*
https://openai.com/index/clip/

**Kirillov et al. (2023) — Segment Anything (SAM) Paper**
Hard · 2h · Paper · *Introduces promptable segmentation and the SA-1B data engine; understanding the mask decoder is key to using SAM as a labeling/foundation tool.*
https://arxiv.org/abs/2304.02643

**Lilian Weng — What Are Diffusion Models? (Lil'Log)**
Hard · 2.5h · Tutorial · *The clearest free derivation of DDPM forward/reverse processes and classifier-free guidance — the theory the HF Diffusers tutorial assumes.*
https://lilianweng.github.io/posts/2021-07-11-diffusion-models/

**Kerbl et al. (2023) — 3D Gaussian Splatting Project Page (Inria GraphDeco)**
Hard · 2h · Interactive · *The real-time successor to NeRF; the project page bundles paper, videos, and the reference repo so you see why splatting beats volumetric rendering on speed.*
https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/

**ONNX Runtime — Quantize ONNX Models (Official Docs)**
Intermediate · 2h · Tutorial · *Complements the TFLite guide with the ONNX path: static vs. dynamic INT8 quantization APIs for the real-time edge-AI deployment milestone.*
https://onnxruntime.ai/docs/performance/model-optimizations/quantization.html

---

## Communities & Competitions

- **Kaggle** — CV competitions with real datasets and leaderboards
- **Papers With Code** — state-of-the-art benchmarks + linked implementations
- **r/computervision** — discussion, paper breakdowns, project feedback
- **Roboflow Universe** — 100k+ annotated datasets, free tier available
