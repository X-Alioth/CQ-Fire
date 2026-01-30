# CQ-Fire Dataset

CQ-Fire is a UAV-based forest fire and smoke detection dataset designed for early wildfire monitoring in complex real-world environments.

---

## 1. Introduction

CQ-Fire is constructed to support research on intelligent forest fire detection using unmanned aerial vehicles (UAVs).

The dataset focuses on challenging wildfire scenarios, including:

- Low-illumination and nighttime environments  
- Small-scale flame targets  
- Diffused and semi-transparent smoke  
- Complex mountainous backgrounds  
- Vegetation interference and lighting variations  

CQ-Fire is intended for training and evaluating object detection models in forest fire monitoring applications.

---

## 2. Categories

The dataset contains two object classes:

- `fire`  
- `smoke`  

All objects are manually annotated using bounding boxes.

---

## 3. Annotation Format

Annotations follow the YOLO format:

class_id x_center y_center width height

- All coordinates are normalized to the range [0, 1]  
- Each image corresponds to one `.txt` label file  

Example:

0 0.512 0.433 0.084 0.120

Where:
- `0` represents the class index (e.g., fire)  
- The remaining values represent normalized bounding box coordinates  

---

## 4. Directory Structure

```
CQ-Fire/
│
├── images/
│   ├── train/
│   ├── val/
│   └── test/
│
├── labels/
│   ├── train/
│   ├── val/
│   └── test/
│
└── data.yaml
```

## 5. Dataset Status

The CQ-Fire dataset is currently under preparation.

The full dataset will be publicly released after final organization and verification.

---

## 6. Intended Use

CQ-Fire is suitable for:

- Forest fire object detection  
- Smoke detection research  
- Lightweight model benchmarking  
- UAV-based vision system development  
- Real-time wildfire monitoring algorithm evaluation  

---

## 7. License

This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).

You are free to share and adapt the material under proper attribution.

Full license:  
https://creativecommons.org/licenses/by/4.0/

---

## 8. Citation

If you use CQ-Fire in your research, please cite:

Wu, X. CQ-Fire: A UAV-based forest fire and smoke detection dataset. 2026.

BibTeX:

@dataset{Wu2026CQFire,
  title={CQ-Fire: A UAV-based forest fire and smoke detection dataset},
  author={Wu, Xingkun},
  year={2026},
  note={Dataset under preparation}
}

---

## 9. Contact

Xingkun Wu  
Email: Maybek2025@163.com
Jiawei Xiang
Email: xjw2830235187@gmail.com
