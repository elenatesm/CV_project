### README.md

```markdown
# Fruit Detection and Classification Pipeline

This repository contains a two-stage computer vision pipeline designed for detecting and classifying fruits in images. The pipeline combines image segmentation and classification to provide accurate results in real-world scenarios.

## Project Overview

The pipeline consists of:
1. **Image Segmentation**: Using a U-Net model to generate precise masks for isolating fruits from their backgrounds.
2. **Image Classification**: Leveraging a ResNet-18 model to classify the segmented fruits into predefined categories.

### Features
- Accurate segmentation of fruits using U-Net.
- Multi-class classification of fruits using ResNet-18.
- Integration of segmentation and classification for end-to-end fruit detection and recognition.

## File Structure
- `fruit_classifier.ipynb`: Jupyter notebook implementing the segmentation and classification models.
- `requirements.txt`: File listing the Python dependencies for running the project.
- `README.md`: Project documentation.

## Getting Started

### Prerequisites
- Python 3.8 or later
- GPU (optional, but recommended for faster training)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/elenatesm/CV_project.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebook
1. Open the Jupyter notebook:
   ```bash
   jupyter notebook fruit_classifier.ipynb
   ```
2. Follow the instructions in the notebook to:
   - Train the segmentation model.
   - Train the classification model.
   - Evaluate the integrated pipeline.

## Datasets
- **Segmentation Dataset**: [FruitSeg30](https://www.sciencedirect.com/science/article/pii/S2352340924007856)
- **Classification Dataset**: [Kaggle Fruits Classification](https://www.kaggle.com/datasets/moltean/fruits)

Ensure to download these datasets and update the paths in the notebook accordingly.

## Results
- **Segmentation Model**: Achieved a validation accuracy of 69.8%.
- **Classification Model**: Achieved a validation accuracy of 71.0%.

## Authors
- [Elina Pavlova](mailto:e.pavlova@innopolis.university)
- [Elena Tesmeeva](mailto:e.tesmeeva@innopolis.university)
- [Gleb Pavlov](mailto:g.pavlov@innopolis.university)

For further details, please refer to the IEEE conference paper.

### Download Pre-trained Models
- You can download the pre-trained models used in this project from [Google Disk](https://drive.google.com/drive/folders/1ww-3Hzc87WV-kTUq7gR3-rmlmYch49Zv?usp=sharing).

Make sure to update the file paths in the notebook after downloading.

---

## References
- U-Net: [Original Paper](https://arxiv.org/abs/1505.04597)
- ResNet: [Original Paper](https://arxiv.org/abs/1512.03385)
```





