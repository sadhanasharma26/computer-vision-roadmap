# Curated Resources

Format: **Difficulty** · **Time** · **Type** · *Why this?* — **every resource here is free.**

The interactive site has a searchable, filterable version of this list.

---

## Phase 1 — The Foundations

**3Blue1Brown — Essence of Linear Algebra**
Easy · 6h · Video · *Visual proofs build intuition faster than any textbook — watch before reading anything else.*
https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab

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

**The Scientist and Engineer's Guide to Digital Signal Processing (Steven W. Smith) — Free Online Book**
Easy · 20h · Book · *The clearest free explanation of convolution, the DFT/FFT, and the frequency domain (with dedicated linear image-processing chapters), using analogies over heavy math to demystify why filtering works on pixels.*
https://www.dspguide.com/pdfbook.htm

**Digital Image Processing — Gonzalez & Woods (Ch. 1–5)**
Intermediate · 8h · Book · *The authoritative reference — Ch. 3 on spatial filtering is the single best treatment of convolution in print.*

**Szeliski — Computer Vision: Algorithms and Applications (2nd ed.), Ch. 3 Image Processing**
Intermediate · 5h · Book · *Author-hosted free PDF; Ch. 3 is the modern, rigorous companion to Gonzalez & Woods covering filtering, pyramids, and the Fourier domain.*
https://szeliski.org/Book/

**Mathematics for Machine Learning (Deisenroth, Faisal, Ong) — Free PDF Book**
Intermediate · 40h · Book · *The best single free book tying linear algebra, vector calculus/gradients, and probability together specifically for ML; the authors keep the full PDF free and frame every concept toward downstream learning algorithms.*
https://mml-book.github.io/

**Harvard Stat 110: Probability (Joe Blitzstein) — Lecture Playlist**
Intermediate · 34h · Video · *Blitzstein's celebrated Harvard course builds genuine probabilistic intuition (random variables, distributions, expectation, conditioning) that underpins generative models and uncertainty in vision — far deeper than a refresher.*
https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo

**NPTEL Digital Image Processing (Prof. P.K. Biswas, IIT Kharagpur) — Course Page**
Intermediate · 40h · Course · *A complete, rigorous IIT Kharagpur video course on DIP fundamentals (sampling/quantization, spatial filtering, convolution, and the 2D Fourier/frequency domain), offering a lecture-driven complement to the textbook references already on the site.*
https://nptel.ac.in/courses/117105135

**MIT 18.06 Linear Algebra (Gilbert Strang) — OCW Video Lectures**
Hard · 36h · Course · *Strang's full 34-lecture MIT course adds the rigorous, proof-backed linear algebra (column space, eigenvalues, SVD, pseudoinverse) that 3Blue1Brown's intuition-only series leaves out — the backbone of image transforms and PCA.*
https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/video_galleries/video-lectures/

---

## Phase 2 — Feature Engineering & Classical CV

**Computerphile — Canny Edge Detector (Mike Pound)**
Easy · 0.3h · Video · *The clearest short explanation of non-max suppression and hysteresis thresholding — the two steps everyone gets wrong implementing Canny.*
https://www.youtube.com/watch?v=sRFM5IEqR2w

**UCF Fundamentals of Computer Vision (Mubarak Shah) — Lecture Videos**
Easy · 24h · Video · *Mubarak Shah's accessible UCF blackboard-style lecture series walks through filtering, edge detection, SIFT, corner detection and KLT/mean-shift tracking with clear step-by-step derivations.*
https://www.youtube.com/playlist?list=PLmyoWnoyCKo8epWKGHAm4m_SyzoYhslk5

**First Principles of CV — Camera Calibration (Columbia / Shree Nayar)**
Intermediate · 3h · Video · *Clearest derivation of Zhang's method on YouTube — used in every production pipeline.*
https://www.youtube.com/channel/UCf0WB91t8Ky6AuYcQV0CcLw

**OpenCV Python — Feature Detection & Matching (Official Docs)**
Intermediate · 4h · Tutorial · *Authoritative working code for SIFT, ORB, FLANN — copy, modify, break it to learn.*
https://docs.opencv.org/4.x/db/d27/tutorial_py_table_of_contents_feature2d.html

**First Principles of Computer Vision — Detectors & Descriptors Monographs (Nayar, Columbia)**
Intermediate · 4h · Book · *Free SIFT-detector monograph (PDF) plus the companion lecture videos for Harris and HOG — re-derive the feature math at your own pace.*
https://fpcv.cs.columbia.edu/Monographs

**Szeliski CV 2nd ed., Ch. 7 — Feature Detection & Matching**
Intermediate · 4h · Book · *Free PDF chapter unifying Harris, SIFT, ORB, RANSAC and feature matching with the geometry you'll use in the panorama stitcher.*
https://szeliski.org/Book/

**OpenCV — Optical Flow (Lucas-Kanade & Dense) Official Tutorial**
Intermediate · 2h · Tutorial · *Working calcOpticalFlowPyrLK code with the math behind it — the canonical reference for the optical-flow item in the roadmap.*
https://docs.opencv.org/4.x/d4/dee/tutorial_optical_flow.html

**Carnegie Mellon 16-385 Computer Vision (Ioannis Gkioulekas) — Lecture Slides**
Intermediate · 25h · Course · *Gkioulekas's CMU course offers a complete set of freely downloadable PDF/PPT slides mapping directly onto this phase: corner detection, feature descriptors and matching, image homographies, camera models, optical flow, and tracking.*
https://www.cs.cmu.edu/~16385/

**Stanford CS131: Computer Vision — Foundations and Applications (Niebles, Krishna, Fei-Fei Li)**
Intermediate · 22h · Course · *Stanford's dedicated classical-CV course (distinct from the CS231n deep-learning notes already on the site) is built around edges/Canny, Harris corners, SIFT/HOG, RANSAC, feature matching and bag of visual words, with public slides and notes.*
https://cs131.stanford.edu/

**Lowe (2004) — Distinctive Image Features from Scale-Invariant Keypoints**
Hard · 2h · Paper · *Original SIFT paper — reading it reveals why scale-space and orientation stability matter in practice.*

**Stanford CS131 Release Assignments (StanfordVL) — Hands-On Notebooks**
Hard · 18h · Repo · *MIT-licensed Jupyter assignments let you implement Canny, Harris corners, HOG, RANSAC, panorama stitching, k-means and bag-of-words from scratch — the demanding practical companion to the CS131 lectures.*
https://github.com/StanfordVL/CS131_release

---

## Phase 3 — Multi-View Geometry & 3D Vision

**Cyrill Stachniss — Photogrammetry & Computer Vision Lectures (Univ. Bonn)**
Intermediate · 6h · Course · *The clearest lecture series on the fundamental/essential matrices, the 8-point algorithm, and bundle adjustment.*
https://www.youtube.com/playlist?list=PLgnQpQtFTOGRsi5vzy9PiQpNWHjq-bKN1

**OpenCV — Epipolar Geometry (Fundamental Matrix & Epilines)**
Intermediate · 2h · Tutorial · *Runnable findFundamentalMat + computeCorrespondEpilines code — turns the epipolar constraint into a picture you can see.*
https://docs.opencv.org/4.x/da/de9/tutorial_py_epipolar_geometry.html

**OpenCV — Depth Map from Stereo Images Official Tutorial**
Intermediate · 1.5h · Tutorial · *Goes from rectified pairs to a disparity/depth map with StereoBM — the practical follow-on to epipolar geometry for 3D reconstruction.*
https://docs.opencv.org/4.x/dd/d53/tutorial_py_depthmap.html

**COLMAP — Structure-from-Motion Official Tutorial**
Intermediate · 3h · Tutorial · *The de-facto open-source SfM/MVS pipeline; running it on your own photos shows feature matching, bundle adjustment, and dense reconstruction end-to-end.*
https://colmap.github.io/tutorial.html

**Szeliski — Computer Vision: Algorithms & Applications (2nd ed.) — Ch. 11 SfM, Ch. 12 Depth & Stereo**
Hard · 8h · Book · *The free, canonical text tying epipolar geometry, triangulation, stereo, and bundle adjustment together.*
https://szeliski.org/Book/

**Hartley & Zisserman — Multiple View Geometry in Computer Vision (2nd ed.)**
Hard · 12h · Book · *The definitive text on projective geometry and the fundamental/essential matrices — borrow free via the Internet Archive.*
https://archive.org/details/multipleviewgeom0000hart

**Cyrill Stachniss — Photogrammetry I & II (Uni Bonn, full lecture playlist)**
Hard · 20h · Course · *University-grade derivations of camera models, epipolar geometry, bundle adjustment, and SfM from a photogrammetry expert, all free on YouTube.*
https://www.youtube.com/playlist?list=PLgnQpQtFTOGRYjqjdZxTEQPZuFHQa7O7Y

**ORB-SLAM2 — Official Open-Source Implementation (raulmur)**
Hard · 4h · Repo · *Real-time monocular/stereo/RGB-D SLAM with loop closure; reading and running it connects feature matching, pose estimation, and mapping into one system.*
https://github.com/raulmur/ORB_SLAM2

**TU Munich — Multiple View Geometry (Prof. Daniel Cremers) — Lecture Videos**
Hard · 30h · Course · *Daniel Cremers' definitive rigorous treatment derives SO(3)/SE(3) rigid motion, the 8-point algorithm, essential/fundamental matrices, triangulation, and bundle adjustment all from first principles.*
https://www.youtube.com/playlist?list=PLTBdjV_4f-EJn6udZ34tht9EVIW7lbeo4

**14 Lectures on Visual SLAM: From Theory to Practice (Gao Xiang et al.) — Free Book + Code**
Hard · 25h · Book · *This English slambook ships a freely downloadable PDF plus full C++ code, walking you hands-on through PnP, triangulation, g2o/Ceres bundle adjustment, and a complete visual-odometry SLAM pipeline.*
https://github.com/gaoxiang12/slambook-en

**University of Bonn/Freiburg — SLAM Course 2013/14 (Cyrill Stachniss) — Lecture Videos**
Hard · 20h · Course · *Stachniss teaches the probabilistic estimation backend (EKF-SLAM, FastSLAM, least-squares/graph-based SLAM) that the geometry and visual-odometry resources assume but never derive in depth.*
https://www.youtube.com/playlist?list=PLgnQpQtFTOGQrZ4O5QzbIHgl3b1JHimN_

---

## Phase 4 — The Deep Learning Era

**Ultralytics YOLOv8 — Train a Custom Object Detector**
Easy · 2h · Tutorial · *Best ROI in CV learning: train a real detector in 30 lines, forces you to understand mAP and anchors.*
https://docs.ultralytics.com

**PyTorch — Transfer Learning for Computer Vision Official Tutorial**
Easy · 1.5h · Tutorial · *Canonical, runnable fine-tuning vs. fixed-feature-extractor recipe on ResNet — the exact pattern for the custom-detector milestone.*
https://docs.pytorch.org/tutorials/beginner/transfer_learning_tutorial.html

**CNN Explainer — Interactive Visualization (Georgia Tech Polo Club)**
Easy · 1h · Interactive · *Click through every conv/pool/ReLU activation of a live CNN to see how an image becomes a class score — best intuition tool for the deep-learning phase.*
https://poloclub.github.io/cnn-explainer/

**MIT 6.S191: Introduction to Deep Learning (Alexander & Ava Amini) — Course Site + Videos**
Easy · 12h · Course · *MIT's fast-paced intro with a dedicated Deep Computer Vision lecture on CNNs; all lectures, slides, and labs are open-sourced free and refreshed yearly, ideal as a quick on-ramp before the heavier courses.*
https://introtodeeplearning.com/

**CS231n — Convolutional Neural Networks (Stanford)**
Intermediate · 30h · Course · *Gold-standard CNN education — the lecture notes alone are worth more than most full courses.*
https://cs231n.github.io

**Andrej Karpathy — Neural Networks: Zero to Hero**
Intermediate · 12h · Course · *Build autograd and backprop from scratch in code so the CNN training loop is never a black box — the best free 'why it works' companion to CS231n.*
https://karpathy.ai/zero-to-hero.html

**fast.ai — Practical Deep Learning for Coders**
Intermediate · 14h · Course · *Top-down course that gets a working image classifier trained in lesson 1, then fills in transfer learning, augmentation, and training tricks.*
https://course.fast.ai/

**Distill — Feature Visualization (Olah, Mordvintsev, Schubert)**
Intermediate · 1.5h · Tutorial · *Shows what CNN filters actually learn at each layer, giving a mental model of hierarchical features that makes architecture choices less arbitrary.*
https://distill.pub/2017/feature-visualization/

**Hugging Face — Community Computer Vision Course**
Intermediate · 15h · Course · *Free, hands-on course spanning CNNs, detection, and segmentation with Transformers/Datasets code you can run for the segmentation milestone.*
https://huggingface.co/learn/computer-vision-course/en/unit0/welcome/welcome

**University of Michigan EECS 498-007 / 598-005: Deep Learning for Computer Vision (Justin Johnson) — Full Course**
Intermediate · 40h · Course · *Justin Johnson co-created CS231n and rebuilt it at Michigan with refreshed PyTorch assignments and free lecture videos, slides, and notes covering backprop, CNN architectures, detection, and segmentation.*
https://web.eecs.umich.edu/~justincj/teaching/eecs498/

**Stanford CS231n: Convolutional Neural Networks for Visual Recognition (Spring 2017, Fei-Fei Li, Johnson, Yeung) — Lecture Videos**
Intermediate · 18h · Video · *The legendary CS231n video lectures (the site lists only the written notes); 16 lectures walk through CNNs, training, architectures, and detection/segmentation in Fei-Fei Li's own course.*
https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv

**NPTEL Deep Learning for Computer Vision (Vineeth N Balasubramanian, IIT Hyderabad) — Full Playlist**
Intermediate · 35h · Course · *A rigorous IIT-Hyderabad course that bridges classical CV into deep CNNs (AlexNet/VGG/Inception/ResNet), detection, and segmentation, with an accompanying free online book.*
https://www.youtube.com/playlist?list=PLEAYkSg4uSQ0Q5Z1IYI-0g2cbD-2Rt-I6

**Ronneberger et al. (2015) — U-Net: CNNs for Biomedical Image Segmentation**
Hard · 1.5h · Paper · *Skip connections introduced here appear in every modern architecture — 30k+ citations for a reason.*

**Deep Residual Learning for Image Recognition — ResNet (He, Zhang, Ren, Sun, 2015)**
Hard · 3h · Paper · *The single most influential architecture paper of the deep learning era; the original ResNet paper explains skip connections and why very deep networks finally became trainable.*
https://arxiv.org/abs/1512.03385

---

## Phase 5 — Modern Frontiers

**Hugging Face Diffusers — Stable Diffusion from Scratch**
Intermediate · 4h · Tutorial · *Most practical diffusion path: modify the denoising loop and see exactly what breaks.*
https://huggingface.co/docs/diffusers

**TensorFlow Lite — Model Optimization & Raspberry Pi Guide**
Intermediate · 3h · Tutorial · *Quantization + TFLite is the fastest path from trained model to real hardware in under 100 lines.*
https://www.tensorflow.org/lite/guide

**OpenAI — CLIP: Connecting Text and Images (Official Blog)**
Intermediate · 1h · Tutorial · *Authoritative, approachable explanation of contrastive image-text pretraining and zero-shot transfer straight from the authors, with code links.*
https://openai.com/index/clip/

**ONNX Runtime — Quantize ONNX Models (Official Docs)**
Intermediate · 2h · Tutorial · *Complements the TFLite guide with the ONNX path: static vs. dynamic INT8 quantization APIs for the real-time edge-AI deployment milestone.*
https://onnxruntime.ai/docs/performance/model-optimizations/quantization.html

**Stanford CS25: Transformers United (Div Garg, Steven Feng, Chetanya Rastogi et al.) — Seminar Lecture Videos**
Intermediate · 20h · Course · *Stanford's flagship Transformers seminar with guest lectures from field leaders (Vaswani, Karpathy, Hinton) whose vision and multimodal talks cover self-attention, ViT and CLIP-style frontiers.*
https://www.youtube.com/playlist?list=PLoROMvodv4rNiJRchCzutFw5ItR_Z27CM

**Hugging Face Diffusion Models Course (Jonathan Whitaker, Lewis Tunstall) — Hands-On Notebooks**
Intermediate · 25h · Course · *Unlike the Diffusers library docs, this structured four-unit course has you build a diffusion model from scratch then fine-tune and condition Stable Diffusion in free Colab notebooks.*
https://huggingface.co/learn/diffusion-course/unit0/1

**Dosovitskiy et al. (2021) — An Image is Worth 16×16 Words (ViT)**
Hard · 2h · Paper · *Short, readable, paradigm-shifting — proved transformers beat CNNs at scale without convolution.*
https://arxiv.org/abs/2010.11929

**Kirillov et al. (2023) — Segment Anything (SAM) Paper**
Hard · 2h · Paper · *Introduces promptable segmentation and the SA-1B data engine; understanding the mask decoder is key to using SAM as a labeling/foundation tool.*
https://arxiv.org/abs/2304.02643

**Lilian Weng — What Are Diffusion Models? (Lil'Log)**
Hard · 2.5h · Tutorial · *The clearest free derivation of DDPM forward/reverse processes and classifier-free guidance — the theory the HF Diffusers tutorial assumes.*
https://lilianweng.github.io/posts/2021-07-11-diffusion-models/

**Kerbl et al. (2023) — 3D Gaussian Splatting Project Page (Inria GraphDeco)**
Hard · 2h · Interactive · *The real-time successor to NeRF; the project page bundles paper, videos, and the reference repo so you see why splatting beats volumetric rendering on speed.*
https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/

**Stanford CS236: Deep Generative Models (Stefano Ermon) — Course Site, Notes & Lectures**
Hard · 35h · Course · *The rigorous probabilistic treatment of VAEs, GANs, normalizing flows, autoregressive and score-based diffusion models, with self-contained free notes plus the public 2023 lecture playlist.*
https://deepgenerativemodels.github.io/

**MIT 6.5940 EfficientML.ai: TinyML and Efficient Deep Learning Computing (Song Han) — Slides & Lecture Videos**
Hard · 30h · Course · *The authoritative course on quantization, pruning, NAS, distillation and on-device deployment (ending with running Llama-2-7B on a laptop), taught by the researcher behind Deep Compression.*
https://hanlab.mit.edu/courses/2024-fall-65940

---

## Communities & Competitions

- **Kaggle** — CV competitions with real datasets and leaderboards
- **Papers With Code** — state-of-the-art benchmarks + linked implementations
- **r/computervision** — discussion, paper breakdowns, project feedback
- **Roboflow Universe** — 100k+ annotated datasets, free tier available
