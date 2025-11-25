# Brain Tumor Segmentation Project 🧠

## Overview
This project implements brain tumor segmentation on MRI images using **K-Means clustering** and **morphological image processing**. It aims to detect tumor regions automatically and visualize them clearly.  

Techniques used:
- Image preprocessing and normalization
- K-Means clustering for tumor region detection
- Morphological operations to refine segmentation
- Visualization of results on MRI scans

---

## Project Files

| File/Folder | Description |
|-------------|-------------|
| `brain_tumor_segmentation.ipynb` | Full Jupyter Notebook with the segmentation pipeline and visualizations. |
| `presentation.pdf` | Slides explaining the pipeline, methods, and results. |

---

## Dataset
The MRI dataset is available on Kaggle. You can download it directly:

[Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

**Instructions:**  
1. Download the dataset ZIP file from Kaggle.  
2. Place it anywhere on your system.  
3. In the notebook, update the `initial_file` variable in the "Load the data" cell with the full path to your downloaded ZIP file.

---

## Usage

1. **Clone the repository**
```bash
git clone https://github.com/your-username/brain-tumor-segmentation.git
cd brain-tumor-segmentation

