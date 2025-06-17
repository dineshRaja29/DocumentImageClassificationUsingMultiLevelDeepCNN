# Document Image Classification

This project classifies document images into one of 16 categories using Convolutional Neural Networks (CNNs).

## Dataset

- **Name**: RVL-CDIP
- **Total Images**: 400,000
- **Classes**: 16
- **Image Format**: Grayscale `.tif`
- **Split**:
  - Train: 320,000
  - Validation: 40,000
  - Test: 40,000

## Categories

0. Letter  
1. Form  
2. Email  
3. Handwritten  
4. Advertisement  
5. Scientific Report  
6. Scientific Publication  
7. Specification  
8. File Folder  
9. News Article  
10. Budget  
11. Invoice  
12. Presentation  
13. Questionnaire  
14. Resume  
15. Memo

## Approach

- Used deep CNNs for image classification.
- Combined holistic and region-based CNNs.
- Pretrained models (like ImageNet) were fine-tuned.
- Final accuracy achieved: **93%** (better than paper's 90%).

## Resources

- [Research Paper](https://ieeexplore.ieee.org/abstract/document/7333910)  
- [Dataset](https://adamharley.com/rvl-cdip/)

