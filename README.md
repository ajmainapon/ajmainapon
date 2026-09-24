<div align="center">

# Ajmain Istiak Apon

### Computer Vision & Machine Learning Researcher

**Self-Supervised Learning · World Models · Medical Imaging · Generative Models**

Final-year Robotics & Mechatronics Engineering student at the University of Dhaka. I study label-efficient visual representation learning, predictive world-model objectives (JEPA), medical image analysis, and reliable control of generative models.

[Portfolio](https://ajmainapon.github.io) · [LinkedIn](https://www.linkedin.com/in/ajmain-istiak-apon-902672140/) · [Email](mailto:ajmain.apon123@gmail.com)

</div>

---

## Research

### Label-Efficient Medical CT Segmentation

Adapted joint-embedding predictive pretraining to 2.5D CT slice pairs and tested which natural-image design choices survive the shift to volumetric medical data.

- Ran a controlled 2×2 factorial study of context–target slice separation and masking geometry; slice separation dominated, and the two factors interacted non-additively
- Evaluated data efficiency through linear probing and end-to-end fine-tuning across five label budgets
- Tested robustness with a matched SwinUNETR comparison, cross-dataset transfer to AMOS-CT, and CT-to-MR transfer without MR pretraining
- Quantified run-to-run reliability with repeated seeds and Welch's t-tests

`PyTorch` `I-JEPA` `ViT` `Self-Supervised Learning` `Medical Segmentation` `SwinUNETR`

### Auditing Memorability Guidance in Text-to-Image Diffusion

My undergraduate thesis audits training-free predicted-memorability guidance by differentiating AMNet through the DDIM trajectory of Stable Diffusion. The emphasis is not merely whether a proxy score rises, but whether the effect transfers beyond the optimizing critic and remains competitive with simpler sampling alternatives.

- Held out ResMem and ViTMem from guidance and evaluated transfer across datasets and seed bases
- Used prompt/latent-paired comparisons, prompt-clustered inference, and an outcome-untouched test set
- Compared guidance with prompt modification and best-of-four reranking
- Characterized Goodhart-style failure modes through directional controls and a native-resolution SDXL diagnostic

`PyTorch` `Stable Diffusion` `DDIM` `Universal Guidance` `Statistical Evaluation`

### AI-Assisted Stomatal Phenotyping

A cross-disciplinary chickpea study benchmarked instance-segmentation systems for guard-cell complexes and stomatal pores under control and drought conditions.

- Benchmark scale: **506 microscopy images** and **6,605 annotated instances**
- Evaluation design: 359 training, 99 validation, and 48 locked test images
- Model comparison: YOLOv8s-seg, YOLO26s-seg, and Mask R-CNN under a common test protocol
- Main limitation: small-pore segmentation, followed by the need for repeated runs and external validation

| Best observed test result | Model | Mask AP |
| :-- | :-- | --: |
| IoU 0.50 | YOLO26s-seg | 0.638 |
| IoU 0.50:0.95 | Mask R-CNN | 0.428 |

`PyTorch` `Ultralytics` `Mask R-CNN` `Instance Segmentation` `Roboflow`

---

## Other Work

### Robotics & Embedded Systems

Worked with ROS 2, STM32 motor control, URDF/Xacro modeling, mobile-robot kinematics, and an instrumented DJI F450 drone platform involving CAD, data acquisition, signal conditioning, and uncertainty analysis.

`ROS 2` `STM32` `C/C++` `Python` `CAD`

---

## Technical Toolkit

| Area | Technologies |
| :-- | :-- |
| Machine learning | PyTorch, torchvision, timm, MONAI, Hugging Face, Ultralytics, scikit-learn, OpenCV |
| Research methods | Self-supervised pretraining (JEPA), medical segmentation, instance segmentation, diffusion guidance, controlled ablations |
| Robotics | ROS 2, STM32, URDF/Xacro |
| Languages & tools | Python, C++, C, LaTeX, Git, Linux |

---

## Highlights

- **Champion**, [Insight 2.0 Datathon 2026](https://github.com/ajmainapon/datathon-Insight2.0-NeurAps) (79 teams), IASDS Students' Club, University of Dhaka
- **President**, Robotics & Mechatronics Student Club, University of Dhaka — October 2025 to present
- **Program Coordinator**, IEEE Robotics & Automation Society, University of Dhaka — March 2024 to September 2025

---

## Current Direction

I am applying to PhD programs for Fall 2027, with particular interest in self-supervised representation learning and world models, label-efficient medical imaging, and controllable generative models. I am open to research collaborations aligned with these areas.

<div align="center">

[View my portfolio](https://ajmainapon.github.io) · [Connect on LinkedIn](https://www.linkedin.com/in/ajmain-istiak-apon-902672140/) · [Email me](mailto:ajmain.apon123@gmail.com)

</div>
