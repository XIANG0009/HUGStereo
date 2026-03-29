# HUGStereo: A Hierarchical Fusion and Geometry-Aware Refinement Network for High-Resolution Satellite Stereo Matching

## 📌 Introduction

This repository provides the official implementation of **HUGStereo**, proposed in our paper:

> **HUGStereo: A Hierarchical Fusion and Geometry-Aware Refinement Network for High-Resolution Satellite Stereo Matching**  
> Yuxiang Yao, Lina Yang, Haoyan Yang, et al.  
> *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (J-STARS), 2026*

---

## 🚀 Highlights

- Designed for remote sensing stereo matching  
- Strong performance on US3D, WHU-MVS, WHU-Stereo  
- Robust in challenging regions  
- Efficient modular design  

---

## 📂 Structure

HUGStereo/
├── datasets/  
├── models/  
├── utils/  
├── configs/  
├── scripts/  
├── checkpoints/  
├── train.py  
├── test.py  

---

## ⚙️ Installation

Requirements:
- Python >= 3.8
- PyTorch >= 1.10

```bash
pip install -r requirements.txt
```

---

## 📊 Datasets

- US3D  
- WHU-MVS  
- WHU-Stereo  

---

## 🏋️ Training

```bash
python train.py --config configs/hugstereo.yaml
```

---

## 🔍 Evaluation

```bash
python test.py --checkpoint checkpoints/hugstereo.pth
```

---

## 📦 Pretrained Models

Will be released upon acceptance.

---

## 📜 Citation

```bibtex
@article{yao2026hugstereo,
  title={HUGStereo},
  author={Yao, Yuxiang},
  journal={IEEE JSTARS},
  year={2026}
}
```

---

## 📬 Contact

- yaoyuxiang@st.gxu.edu.cn
