<div align="center">
  <h1>Hi there, I'm Haoyuan Liu 👋</h1>
  <p>
    <b>Ph.D. Candidate @ Waseda University (AMS Lab)</b><br>
    <i>Focusing on 2D/3D Recognition Tasks</i>
  </p>

  <!-- <a href="liuhaoyuan@akane.waseda.jp">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-blue?style=flat-square&logo=gmail" alt="Email" />
  </a> -->
  <!-- <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID">
    <img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square&logo=google-scholar&logoColor=white" alt="Google Scholar" />
  </a> -->
</div>

---

### About Me

I am currently a Ph.D. candidate at **Waseda University**, Japan, supervised by [**Prof. Hiroshi Watanabe**](https://www.ams.giti.waseda.ac.jp/information/our-members/hiroshi-watanabe/) at [AMS LAB](https://www.ams.giti.waseda.ac.jp/). I also serve as the **Group Leader** of the Recognition Research Group in the lab.

Currently, I am actively exploring:
* **Robust Training Strategies:** Designing loss functions (e.g., *InterpIoU*) and label assignment schemes to stabilize optimization.
* **Lightweight Architectures:** Building efficient detectors for edge/mobile deployment.
* **Multi-Modal & 3D Perception:** Extending 2D dense detection methodologies to RGB-IR fusion and 3D environments.

---

### Research Interests

My research interests align with building robust and efficient perception systems:

* **Object Detection & Dense Prediction:** Robust bounding box regression, positive sample assignment, and crowd counting.
* **Lightweight & Efficient Vision Models:** Real-time visual perception, attention mechanisms, and model compression.
* **Multi-Modal Visual Perception:** RGB-Infrared fusion, remote sensing imagery, and cross-modal consistency.
* **3D Object Detection:** Geometry-aware approaches and BEV-based perception (Future Focus).

---

### Selected Projects & Papers

#### 1. [InterpIoU: Robust Bounding Box Regression Loss](https://github.com/NuayHL/interpiou)
> **Haoyuan Liu**, Hiroshi Watanabe. *Neurocomputing, 2026.*

A novel interpolation-based IoU loss designed to resolve the gradient vanishing problem when predicted boxes do not overlap with ground truth. It significantly improves optimization stability for **small object detection** and **early-stage training**.

* **Keywords:** Tiny Object Detection, Loss Function, Optimization Theory.
* **Tech:** PyTorch, MMDetection.

#### 2. [GSA: Guided Supervised Attention (CrowdDetection)](https://github.com/NuayHL/CrowdDetection)
> **Haoyuan Liu**, Hiroshi Watanabe. *Journal of Electronic Imaging (JEI), 2024.*

A parameter-free, lightweight attention mechanism developed to enhance single-stage detectors in **dense pedestrian scenarios**. This work addresses feature degradation caused by heavy occlusion.

* **Keywords:** Pedestrian Detection, Dense Scenarios, Attention Mechanism.
* **Tech:** PyTorch, YOLO-style Architectures.

#### 3. [Time Step Generating: Deepfake Detection](https://github.com/NuayHL/TimeStepGenerating)
> Ziyue Zeng, Yupei Guo, **Haoyuan Liu**, et al. *ACM Multimedia Asia (MMAsia), 2025.*

A collaborative project studying temporal-step-based artifacts in synthesized images, proposing a universal deepfake detection framework.

* **Keywords:** Deepfake Detection, AIGC, Generative Models.


---
### Technical Skills

I have extensive engineering experience in developing and customizing deep learning models using **PyTorch**.

- **Deep Learning Frameworks:** Highly proficient in **MMDetection (OpenMMLab)** and **Ultralytics (YOLO)** for building end-to-end training pipelines.

