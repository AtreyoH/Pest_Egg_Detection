# Dataset Structure

The heavy image files are hosted on Zenodo, while the YOLO-format bounding box annotations are hosted directly in this GitHub repository. 

## GitHub Repository Structure
```text
pomacea-canaliculata-uav-dataset/
│
├── labels/
│   ├── train/          # 8,473 YOLO format .txt files
│   └── val/            # 2,119 YOLO format .txt files
│
├── documentation/
│   ├── class_distribution.md
│   └── dataset_structure.md
│
└── README.md