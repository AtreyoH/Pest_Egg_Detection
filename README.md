# Pomacea canaliculata (Golden Apple Snail) Egg UAV Dataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23181680.svg)](https://doi.org/10.5281/zenodo.23181680)
## 1. Dataset Overview
This repository contains the dataset and annotations used in the research paper *"Microscopic Detection of Pomacea canaliculata Eggs Using YOLO11-p2-spd"*[cite: 20]. It is designed to train and evaluate computer vision models on the challenging task of microscopic agricultural pest detection in highly occluded environments[cite: 20, 22].

## 2. Motivation
The Golden Apple Snail is a highly destructive agricultural pest[cite: 20]. Early detection of their distinct egg masses using UAVs is critical to prevent crop loss[cite: 20]. However, these eggs are microscopic in high-resolution images, making them highly vulnerable to standard convolutional downsampling and difficult to distinguish from background foliage[cite: 20, 22].

## 3. Dataset Composition
The dataset contains 10,592 high-resolution images captured via DJI Phantom 4 Pro UAVs and supplemental web-crawled data to ensure environmental diversity[cite: 23, 24]. 
* **Training Set:** 8,473 images[cite: 24]
* **Validation Set:** 2,119 images (containing 4,850 target instances)[cite: 24]
* **Target Scale:** <10% of spatial dimensions[cite: 24]

## 4. Annotation Format
Annotations are provided directly in this GitHub repository inside the `labels/` directory. They are formatted in the standard YOLO format (Normalized `class_id cx cy w h`)[cite: 24]. The single target class is `0` (`egg`)[cite: 24].

## 5. Dataset Download Link (Zenodo)
Due to the large file size of the high-resolution UAV images, the raw image dataset is securely hosted on Zenodo. 
**[Download the complete image dataset here](https://doi.org/10.5281/zenodo.23181680)**

## 6. Citation
If you use this dataset in your research, please cite it as:
```bibtex
@dataset{hazra_pomacea_2026,
  author       = {Atreyo Hazra},
  title        = {Pomacea canaliculata Egg UAV Dataset for Microscopic Object Detection},
  month        = {October},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {https://doi.org/10.5281/zenodo.23181680},
  url          = {https://zenodo.org/records/23181680}
}