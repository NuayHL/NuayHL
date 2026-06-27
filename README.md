<div align="center">
  <h1>Hi there, I'm Haoyuan Liu 👋</h1>
  <p>
    <b>Ph.D. Candidate @ Waseda University (AMS Lab)</b><br>
    <i>Small / Dense Object Detection · Multi-Modal Perception · Vision-Language Models</i>
  </p>

  <a href="mailto:liuhaoyuan@akane.waseda.jp">
    <img src="https://img.shields.io/badge/Email-Contact-blue?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/NuayHL">
    <img src="https://img.shields.io/badge/GitHub-NuayHL-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="./Haoyuan_Liu_CV.pdf">
    <img src="https://img.shields.io/badge/CV-Download%20PDF-D32F2F?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="CV" />
  </a>
  <!--
  Fill in your Scholar ID and uncomment to enable.
  <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID">
    <img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square&logo=google-scholar&logoColor=white" alt="Google Scholar" />
  </a>
  -->
</div>

---

### About Me

I am a Ph.D. candidate at **Waseda University**, Japan, advised by [**Prof. Hiroshi Watanabe**](https://www.ams.giti.waseda.ac.jp/) at the [AMS Lab](https://www.ams.giti.waseda.ac.jp/), where I also lead the Recognition Research Group. I hold a B.S. in Information and Computing Science from the School of Mathematical Sciences at **Beihang University**, and I keep a mathematical view on detection: reconstructing static hyperparameters as functions of object geometry such as scale and area, and validating these mappings through large-scale systematic experiments.

My Ph.D. research centers on **small object detection in aerial and UAV imagery**, covering label assignment, bounding box regression, and feature modeling under small-object, dense, and cross-scale conditions. My **ongoing work** extends this line from task-specific detection toward **open-vocabulary detection and language-guided localization** with compact vision-language models, and toward multimodal agent systems that build on reliable perception.

> *Expected graduation: late 2026. I am open to postdoctoral and research positions.*

<div align="left">
  <a href="./Haoyuan_Liu_CV.pdf">
    <img src="https://img.shields.io/badge/%F0%9F%93%84%20Download%20My%20CV-PDF-D32F2F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download CV" />
  </a>
</div>

---

### Research Interests

* **Visual Perception & Scene Understanding:** Object detection, segmentation, and fine-grained recognition, with a focus on representation stability and generalization under small-object, dense, and cross-scale settings, extending to open-vocabulary detection.
* **Self-Supervised Representation Learning:** Transformer-based self-supervised methods (e.g., the DINO series), and their transfer to downstream detection and localization tasks.
* **Multi-Modal Perception & Agent Systems:** RGB-infrared/thermal fusion and remote sensing understanding, and agent systems built on compact vision-language models with open-vocabulary grounding, referring localization, and tool use.

---

### Selected Projects & Papers

<sub>Only works with public code are listed here. † Corresponding author.</sub>


#### 1. [InterpIoU: Robust Bounding Box Regression Loss](https://github.com/NuayHL/interpiou)
> **Haoyuan Liu**, Hiroshi Watanabe. *Neurocomputing, 2026.*

An interpolation-based IoU loss that removes handcrafted geometric penalty terms while keeping stable, IoU-aligned gradients. It improves optimization stability for **small object localization** and early-stage training, and has been adopted by several follow-up works.

* **Keywords:** Small Object Detection, Bounding Box Regression, Loss Function.

#### 2. [GSA: Guided Supervised Attention (CrowdDetection)](https://github.com/NuayHL/CrowdDetection)
> **Haoyuan Liu**, Hiroshi Watanabe. *Journal of Electronic Imaging (JEI), 2024.*

A parameter-free, lightweight attention scheme for single-stage detectors in **dense pedestrian scenarios**, addressing feature degradation caused by heavy occlusion.

* **Keywords:** Pedestrian Detection, Dense Scenes, Attention Mechanism.

**Selected Co-authored**

#### 3. [Time Step Generating: Universal Deepfake Detection](https://github.com/NuayHL/TimeStepGenerating)
> Ziyue Zeng, Yupei Guo, **Haoyuan Liu**, Dingjie Peng, Hiroshi Watanabe. *ACM Multimedia Asia (MMAsia), 2025.*

A universal synthesized-image detector built on temporal-step artifacts of diffusion models.

* **Keywords:** Deepfake Detection, AIGC, Diffusion Models.

#### 4. [MRFA: Frozen-Backbone RGB-Infrared Detection](https://github.com/LuBingyu11/MRFA)
> Bingyu Lu, **Haoyuan Liu**, Hiroshi Watanabe. *The Visual Computer (Springer), 2026.*

A frozen-backbone approach for **RGB-infrared object detection**, using multi-receptive-field attention for cross-modal fusion.

* **Keywords:** RGB-Infrared Fusion, Multi-Modal Detection, Attention.

---

### Technical Skills

* **Languages:** Python (proficient), C / C++
* **Deep Learning:** PyTorch (advanced, including custom C++/CUDA extensions), Ultralytics (YOLO), MMCV / MMDetection.
* **Tools & Systems:** Linux, Git, LaTeX, Docker; HPC clusters (Singularity, UGE scheduling).
