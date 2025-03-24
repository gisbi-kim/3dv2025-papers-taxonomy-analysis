# 3dv2025-papers-taxonomy-analysis

## **1. 3D Scene Reconstruction and Rendering (3D 장면 재구성 및 렌더링)**

- 초점: 3D 장면, 환경, 객체의 재구성 및 사실적인 렌더링 기술.

### **1-1. Structure-from-Motion and Multi-View Reconstruction (SfM 및 다중 뷰 재구성)**

- 초점: 다중 이미지나 비디오를 활용한 3D 재구성, SfM 및 카메라 위치 추정 기반 기술.
- 포함 논문:
    - "MASt3R-SfM: a Fully-Integrated Solution for Unconstrained Structure-from-Motion" (Poster 1-01)
    - "Geometry-Aware Feature Matching for Large-Scale Structure from Motion" (Poster 1-03)
    - "FlowMap: High-Quality Camera Poses, Intrinsics, and Depth via Gradient Descent" (Poster 1-16)
    - "Synthesizing Consistent Novel Views via 3D Epipolar Attention without Re-training" (Poster 1-11)
    - "Oblique-MERF: Revisiting and Improving MERF for Oblique Photography" (Poster 1-10)
- 설명: SfM, 카메라 위치 추정, 다중 뷰를 통한 정밀한 3D 재구성에 초점을 둔 연구.

### **1-2. Neural Radiance Fields (NeRF) and Variants (NeRF 및 변형 기술)**

- 초점: NeRF 기반의 신경망 렌더링 및 그 변형(속도 개선, 품질 향상 등).
- 포함 논문:
    - "MonoPatchNeRF: Improving Neural Radiance Fields with Patch-based Monocular Guidance" (Poster 2-05)
    - "Plenoptic PNG: Real-Time Neural Radiance Fields in 150 KB" (Poster 2-07)
    - "OD-NeRF: Efficient Training of On-the-Fly Dynamic Neural Radiance Fields" (Poster 2-09)
    - "LSE-NeRF: Learning Sensor Modeling Errors for Deblured Neural Radiance Fields" (Poster 2-10)
    - "MLI-NeRF: Multi-Light Intrinsic-Aware Neural Radiance Fields" (Poster 2-15)
    - "FourieRF: Few-Shot NeRFs via Progressive Fourier Frequency Control" (Poster 2-17)
    - "Direct and Explicit 3D Generation from a Single Image" (Poster 2-06)
    - "UrbanIR: Large-Scale Urban Scene Inverse Rendering from a Single Video" (Poster 2-08)
- 설명: NeRF를 기반으로 한 장면 렌더링, 특히 단일 이미지나 동적 장면에 대한 최적화 연구.

### **1-3. Gaussian Splatting-Based Techniques (Gaussian Splatting 기반 기술)**

- 초점: 3D Gaussian Splatting을 활용한 고속, 고품질 렌더링 및 재구성.
- 포함 논문:
    - "RadSplat: Radiance Field-Informed Gaussian Splatting for Robust Real-Time Rendering" (Poster 4-01)
    - "A Large-scale Dataset of Gaussian Splats and Their Self-Supervised Pretraining" (Poster 4-02)
    - "LoopSplat: Loop Closure by Registering 3D Gaussian Splats" (Poster 4-03)
    - "E-3DGS: Event-Based Novel View Rendering of Large-Scale Scenes Using 3D Gaussian Splatting" (Poster 4-05)
    - "Mipmap-GS: Let Gaussians Deform with Scale-specific Mipmap for Anti-aliasing Rendering" (Poster 4-06)
    - "WaterSplatting: Fast Underwater 3D Scene Reconstruction using Gaussian Splatting" (Poster 4-09)
    - "LapisGS: Layered Progressive 3D Gaussian Splatting for Adaptive Streaming" (Poster 4-11)
    - "SparseGS: Sparse View Synthesis using 3D Gaussian Splatting" (Poster 4-15)
    - "360-GS: Layout-guided Panoramic Gaussian Splatting For Indoor Roaming" (Poster 4-16)
    - "AGS-Mesh: Adaptive Gaussian Splatting and Meshing with Geometric Priors" (Poster 4-19)
    - "EgoGaussian: Dynamic Scene Understanding from Egocentric Video with 3D Gaussian Splatting" (Poster 4-20)
- 설명: Gaussian Splatting을 활용한 실시간 렌더링, 동적 장면 처리, 메싱 등 다양한 응용.

### **1-4. Surface and Implicit Representation Methods (표면 및 암묵적 표현 방법)**

- 초점: 표면 재구성, 암묵적 표현(Implicit Fields), 물체의 구조적 특성 활용.
- 포함 논문:
    - "αSurf: Implicit Surface Reconstruction for Semi-Transparent and Thin Objects with Decoupled Geometry and Opacity" (Poster 2-01)
    - "Spurfies: Sparse-View Surface Reconstruction using Local Geometry Priors" (Poster 2-02)
    - "3D Reconstruction with Spatial Memory" (Poster 2-03)
    - "OpticFusion: Multi-Modal Neural Implicit 3D Reconstruction of Microstructures" (Poster 2-04)
    - "INPC: Implicit Neural Point Clouds for Radiance Field Rendering" (Poster 4-04)
    - "PIR: Photometric Inverse Rendering with Shading Cues Modeling and Surface Reflectance Regularization" (Poster 2-11)
    - "SurfR: Surface Reconstruction with Multi-scale Attention" (Poster 2-12)
    - "NoKSR: Kernel-Free Neural Surface Reconstruction via Point Cloud Serialization" (Poster 2-13)
    - "Lightplane: Highly-Scalable Components for Neural 3D Fields" (Poster 2-14)
    - "RISE-SDF: Relightable Information-Shared Signed Distance Field for Glossy Object Inverse Rendering" (Poster 2-16)
    - "Gen3DSR: Generalizable 3D Scene Reconstruction via Divide and Conquer from a Single View" (Poster 2-18)
    - "Particle Rendering: Implicitly Aggregating Incident and Outgoing Light Fields for Novel View Synthesis" (Poster 2-19)
    - "Incorporating dense metric depth into neural 3D representations for view synthesis and relighting" (Poster 2-20)
    - "CamCtrl3D: Single-Image Scene Exploration With Precise 3D Camera Control" (Poster 2-21)
    - "Flash3D: Feed-Forward Generalisable 3D Scene Reconstruction from a Single Image" (Poster 2-23)
    - "Invisible Stitch: Generating Smooth 3D Scenes with Depth Inpainting" (Poster 1-22)
- 설명: 암묵적 표현(SDF, Neural Fields) 및 표면 기반 재구성에 초점을 둔 연구.

## **2. 3D Object Detection and Segmentation (3D 객체 탐지 및 분할)**

- 초점: 3D 공간에서의 객체 탐지, 분할, 인식 및 관련 응용.
- 포함 논문:
    - "CatFree3D: Category-Agnostic 3D Object Detection With Diffusion" (Poster 3-01)
    - "GRIN: Zero-Shot Metric Depth with Pixel-Level Diffusion" (Poster 3-02)
    - "An Object is Worth 64x64 Pixels: Generating 3D Object via Image Diffusion" (Poster 3-03)
    - "Betsu-Betsu: Separable 3D Reconstruction of Two Interacting Objects from Multiple Views" (Poster 5-05)
    - "Reason3D: Searching and Reasoning 3D Segmentation via Large Language Model" (Poster 5-06)
    - "LSSInst: Improving Geometric Modeling in LSS-Based BEV Perception" (Poster 5-07)
    - "Vocabulary-Free 3D Instance Segmentation with Vision-Language Assistant" (Poster 5-08)
    - "SAMPro3D: Locating SAM Prompts in 3D for Zero-Shot Instance Segmentation" (Poster 5-10)
    - "DreamBeast: Distilling 3D Fantastic Animals with Part-Aware Knowledge Transfer" (Poster 5-12)
    - "TTT-KD: Test-Time Training for 3D Semantic Segmentation through Knowledge Distillation" (Poster 5-14)
    - "ObjectCarver: Semi-automatic segmentation, reconstruction and separation of 3D objects" (Poster 5-17)
    - "UNIT: Unsupervised Online Instance Segmentation through Time" (Poster 5-18)
    - "SPAFormer: Sequential 3D Part Assembly with Transformers" (Poster 5-19)
    - "ZeroPS: High-quality Cross-modal Knowledge Transfer for Zero-Shot 3D Part Segmentation" (Poster 5-20)
    - "GS-Pose: Generalizable Segmentation-Based 6D Object Pose Estimation With 3D Gaussian Splatting" (Poster 4-12)
    - "Open-Vocabulary Semantic Part Segmentation of 3D Human" (Poster 6-21)

## **3. Human Modeling and Animation (인간 모델링 및 애니메이션)**

- 초점: 3D 인간 모델, 모션 합성, 아바타, 의상 재구성 및 애니메이션.
- 포함 논문:
    - "HeadEvolver: Text to Head Avatars via Expressive and Attribute-Preserving Mesh Deformation" (Poster 6-01)
    - "MeshUp: Multi-Target Mesh Deformation via Blended Score Distillation" (Poster 6-02)
    - "UniMotion: Unifying 3D Human Motion Synthesis and Understanding" (Poster 6-03)
    - "DressRecon: Freeform 4D Human Reconstruction from Monocular Video" (Poster 6-04)
    - "Garment3DGen: 3D Garment Stylization and Texture Generation" (Poster 6-05)
    - "HMD^2: Environment-aware Motion Generation from Single Egocentric Head-Mounted Device" (Poster 6-06)
    - "AG-MAE: Anatomically Guided Spatio-Temporal Masked Auto-Encoder for Online Hand Gesture Recognition" (Poster 6-07)
    - "GarmentDreamer: 3DGS Guided Garment Synthesis with Diverse Geometry and Texture Details" (Poster 6-08)
    - "InterTrack: Tracking Human Object Interaction without Object Templates" (Poster 6-09)
    - "Interactive Humanoid: Online Full Body Human Motion Reaction Synthesis" (Poster 6-10)
    - "TEDRA: Text-based Editing of Dynamic and Photoreal Actors" (Poster 6-11)
    - "3DiFACE: Synthesizing and Editing Holistic 3D Facial Animation" (Poster 6-12)
    - "FORCE: Physics-aware Human-object Interaction" (Poster 6-13)
    - "ViSkin: Physics-based Simulation of Virtual Skin on Personalized Avatars" (Poster 6-14)
    - "3D Whole-body Grasp Synthesis with Directional Controllability" (Poster 6-15)
    - "NeuHMR: Neural Rendering-Guided Human Motion Reconstruction" (Poster 6-16)
    - "DEGAS: Detailed Expressions on Full-body Gaussian Avatars" (Poster 6-17)
    - "Rig3DGS: Creating Controllable Portraits from Casual Monocular Videos" (Poster 6-18)
    - "HeadCraft: Modeling High-Detail Shape Variations for Animated 3DMMs" (Poster 6-19)
    - "CameraHMR: Aligning People with Perspective" (Poster 6-20)
    - "Joker: Conditional 3D Head Synthesis With Extreme Facial Expressions" (Poster 6-22)
    - "DeforHMR: Vision Transformer with Deformable Cross-Attention for 3D Human Mesh Recovery" (Poster 6-23)
    - "HeadGAP: Few-Shot 3D Head Avatar via Generalizable Gaussian Priors" (Poster 4-07)
    - "Gaussians-to-Life: Text-Driven Animation of 3D Gaussian Splatting Scenes" (Poster 4-08)
    - "Drivable 3D Gaussian Avatars" (Poster 4-10)
    - "GaussianStyle: Gaussian Head Avatar via StyleGAN" (Poster 4-18)
    - "GaussianAvatar-Editor: Photorealistic Animatable Gaussian Head Avatar Editor" (Poster 4-23)

## **4. Generative Models and Text-to-3D (생성 모델 및 텍스트-3D 변환)**

- 초점: 생성 모델(Diffusion 등) 및 텍스트 기반 3D 콘텐츠 생성.
- 포함 논문:
    - "SceneMotifCoder: Example-driven Visual Program Learning for 3D Object Arrangements" (Poster 5-01)
    - "Ctrl-Room: Controllable Text-to-3D Room Meshes Generation with Layout Constraints" (Poster 3-04)
    - "4D-Editor: Interactive Object-level Editing in Dynamic Neural Radiance Fields" (Poster 3-05)
    - "VividTalk: One-Shot Audio-Driven Talking Head Generation Based on 3D Hybrid Prior" (Poster 3-06)
    - "FastGrasp: Efficient Grasp Synthesis with Diffusion" (Poster 3-08)
    - "HoleGest: Decoupled Diffusion and Motion Priors for Generating Holisticly Expressive Co-speech Gestures" (Poster 3-09)
    - "Learning Naturally Aggregated Appearance for Efficient 3D Editing" (Poster 3-10)
    - "AutoVFX: Physically Realistic Video Editing from Natural Language Instructions" (Poster 3-11)
    - "mmDiffusion: mmWave Diffusion for Sequential 3D Human Dense Point Cloud Generation" (Poster 3-12)
    - "JADE: Joint-aware Latent Diffusion for 3D Human Generative Modeling" (Poster 3-13)
    - "MaterialFusion: Enhancing Inverse Rendering with Material Diffusion Priors" (Poster 3-14)
    - "iFusion: Inverting Diffusion for Pose-Free Reconstruction from Sparse Views" (Poster 3-15)
    - "Reflecting Reality: Enabling Diffusion Models to Produce Faithful Mirror Reflections" (Poster 3-16)
    - "Denoising Monte Carlo Renders with Diffusion Models" (Poster 3-17)
    - "Geometry-guided Cross-view Diffusion for One-to-many Cross-view Image Synthesis" (Poster 3-20)
    - "RealmDreamer: Text-Driven 3D Scene Generation with Inpainting and Depth Diffusion" (Poster 3-21)
    - "MotionDreamer: Exploring Semantic Video Diffusion features for Zero-Shot 3D Mesh Animation" (Poster 3-22)
    - "Dream-in-Style: Text-to-3D Generation using Stylized Score Distillation" (Poster 3-24)
    - "3D-GPT: Procedural 3D modeling with large language models" (Poster 5-13)
    - "Controllable Text-to-3D Generation via Surface-Aligned Gaussian Splatting" (Poster 4-22)

##  **5. Point Cloud Processing and Registration (포인트 클라우드 처리 및 정합)**

- 초점: 포인트 클라우드 데이터 처리, 정합, 카메라 위치 추정 및 관련 기술.
- 포함 논문:
    - "MAC++: Going Further with Maximal Cliques for 3D Registration" (Poster 1-04)
    - "Robust Spectral Translation Synchronization" (Poster 1-05)
    - "CoE: Deep Coupled Embedding for Non-Rigid Point Cloud Correspondences" (Poster 1-06)
    - "SSRFlow: Semantic-aware Fusion with Spatial Temporal Re-embedding for Real-world Scene Flow" (Poster 1-07)
    - "FOCUS - Multi-View Foot Reconstruction From Synthetically Trained Dense Correspondences" (Poster 1-08)
    - "Fully-Geometric Cross-attention for Point Cloud Registration" (Poster 1-12)
    - "A2-GNN: Angle-Annular GNN for Visual Descriptor-free Camera Relocalization" (Poster 1-13)
    - "GVP: Generative Volumetric Primitives" (Poster 1-15)
    - "CFPNet: Improving Lightweight ToF Depth Completion via Cross-zone Feature Propagation" (Poster 1-17)
    - "U–ARE–ME: Uncertainty-Aware Rotation Estimation in Manhattan Environments" (Poster 1-18)
    - "Approximate 2D-3D Shape Matching for Interactive Applications" (Poster 1-19)
    - "Geometric Correspondence Consistency in RGB-D Relative Pose Estimation" (Poster 1-23)
    - "Robustifying Point Cloud Networks by Refocusing" (Poster 5-04)
    - "VXP: Voxel-Cross-Pixel Large-Scale Camera-LiDAR Place Recognition" (Poster 5-11)
    - "MorphoSkel3D: Morphological Skeletonization of 3D Point Clouds for Informed Sampling" (Poster 5-22)
    - "Efficient Continuous Group Convolutions for Local SE(3) Equivariance in 3D Point Clouds" (Poster 5-24)
    - "DynOMo: Online Point Tracking by Dynamic Online Monocular Gaussian Reconstruction" (Poster 4-13)
 

## **6. Miscellaneous and Emerging Topics (기타 및 신흥 주제)**

- 초점: 기존 5개 주요 카테고리에 명확히 속하지 않는 독립적이거나 새로운 주제.

### **6-1. Datasets and Benchmarks (데이터셋 및 벤치마킹)**

- 초점: 새로운 데이터셋 생성, 벤치마킹, 성능 평가를 위한 기반 연구.
- 포함 논문:
    - "Para-Lane: Multi-Lane Dataset Registering Parallel Scans for Benchmarking Novel View Synthesis" (Poster 1-09)
    - "XLD: A Cross-Lane Dataset for Benchmarking Novel Driving View Synthesis" (Poster 2-22)
    - "Pushing the Limits of LiDAR: Accurate Performance Analysis of Indoor 3D LiDARs" (Poster 5-21)
- 설명: 이 논문들은 새로운 데이터셋을 제안하거나 특정 기술(예: LiDAR, 뷰 합성)의 성능 평가를 위한 기준을 제시합니다.

### **6-2. Interactive and Novel Modeling Techniques (인터랙티브 및 새로운 모델링 기법)**

- 초점: 사용자 인터랙션, 새로운 표현 방식, 독창적인 3D 모델링 접근법.
- 포함 논문:
    - "ARC-Flow: Articulated, Resolution-Agnostic, Correspondence-Free Matching and Interpolation" (Poster 1-02)
    - "Deep Polycuboid Fitting for Compact 3D Representation of Indoor Scenes" (Poster 1-14)
    - "Learning assisted Interactive Modelling with Rough Freehand 3D Sketch Strokes" (Poster 5-15)
    - "Snap-it, Tap-it, Splat-it: Tactile-Informed 3D Gaussian Splatting for Reconstructing Challenging Surfaces" (Poster 4-24)
    - "Object Agnostic 3D Lifting in Space and Time" (Poster 2-24)
- 설명: 이 논문들은 사용자와의 상호작용(예: 스케치, 촉각)이나 새로운 모델링 방법(예: Polycuboid, 해상도 무관 매칭)을 다룹니다.

### **6-3. Scene Understanding and Mapping (장면 이해 및 매핑)**

- 초점: 3D 장면 이해, 맵 생성, 공간 인지와 관련된 연구.
- 포함 논문:
    - "Maps from Motion (MfM): Generating 2D Semantic Maps from Sparse Multi-view Images" (Poster 1-20)
    - "SMORE: Simultaneous Map and Object REconstruction" (Poster 1-21)
    - "Online 3D Scene Reconstruction Using Neural Object Priors" (Poster 3-07)
    - "Spatial Cognition from Egocentric Video: Out of Sight, Not Out of Mind" (Poster 5-09)
    - "SphereFusion: Efficient Panorama Depth Estimation via Gated Fusion" (Poster 3-19)
- 설명: 이 논문들은 장면의 공간적 이해, 맵 생성, 객체와 환경의 동시 재구성에 초점을 맞춥니다.

### **6-4. Privacy, Security, and Emerging Representations (프라이버시, 보안 및 신흥 표현)**

- 초점: 프라이버시 보호, 보안 문제, 새로운 3D 표현 방식(예: INR, 조명 모델 등).
- 포함 논문:
    - "Obfuscation Based Privacy Preserving Representations are Recoverable Using Neighborhood Information" (Poster 5-02)
    - "LangOcc: Open Vocabulary Occupancy Estimation via Volume Rendering" (Poster 5-03)
    - "Towards Foundation Models for 3D Vision: How Close Are We?" (Poster 5-16)
    - "Rigid Body Adversarial Attacks" (Poster 5-23)
    - "INRet: A General Framework for Accurate Retrieval of INRs for Shapes" (Poster 3-23)
    - "BiGS: Bidirectional Primitives for Relightable 3D Gaussian Splatting" (Poster 4-14)
    - "Gaussian Garments: Reconstructing Simulation-Ready Clothing with Photorealistic Appearance" (Poster 4-17)
    - "ShadowSG: Spherical Gaussian Illumination from Shadows" (Poster 4-21)
    - "Mesh Extraction for Unbounded Scenes Using Camera-Aware Octrees" (Poster 3-18)
- 설명: 이 논문들은 프라이버시(난독화), 보안(적대적 공격), 새로운 표현법(예: INR, Gaussian 기반 의상/조명) 등 다양한 신흥 주제를 다룹니다.
