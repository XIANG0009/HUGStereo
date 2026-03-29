# HUGStereo: A Hierarchical Fusion and Geometry-Aware Refinement Network for High-Resolution Satellite Stereo Matching

## 📌 Introduction

This repository provides the official implementation of **HUGStereo**, proposed in our paper:

> **HUGStereo: A Hierarchical Fusion and Geometry-Aware Refinement Network for High-Resolution Satellite Stereo Matching**  
> Yuxiang Yao, Lina Yang, Haoyan Yang, et al.  
> *Submitted to IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (J-STARS), 2026*

---

## ⚙️ Installation

Requirements:
- Python 3.7
- PyTorch 1.12

```bash
pip install -r requirements.txt
```

---

## 📊 Datasets

- [US3D](https://ieee-dataport.org/open-access/data-fusion-contest-2019-dfc2019)
- [WHU-MVS](https://gpcv.whu.edu.cn/data/WHU_MVS_Stereo_dataset.html)  
- [WHU-Stereo](https://github.com/Sheng029/WHU-Stereo)  

---

## 🏋️ Training

**US3D**

```bash
python train_us3d.py
```

**WHU-MVS**

```bash
python train_whu_mvs.py
```

**WHU-Stereo**

```bash
python train_whu_stereo.py
```

---

## 🔍 Evaluation

**US3D**

```bash
python test_us3d.py
```

**WHU-MVS**

```bash
python test_whu_mvs.py
```

**WHU-Stereo**

```bash
python test_whu_stereo.py
```

---

## 📦 Pretrained Models

Will be released upon acceptance.

---

## 📜 Citation

```bibtex

```

---

## 📬 Contact

- yaoyuxiang@st.gxu.edu.cn
