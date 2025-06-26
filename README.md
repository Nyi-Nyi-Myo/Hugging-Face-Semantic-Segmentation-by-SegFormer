# Hugging-Face Semantic Segmentation by SegFormer

[![pytorch](https://img.shields.io/badge/PyTorch-2.6.0-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org)
[![Hugging Face](https://img.shields.io/badge/-Hugging_Face-3B4252?style=flat&logo=huggingface&logoColor=)](https://huggingface.co/)
![Static Badge](https://img.shields.io/badge/Semantic-Segmentation-cyan)
![Static Badge](https://img.shields.io/badge/SegFormer-8A2BE2)

Semantic Segmentation for the caps of marker pens using **SegFormer** Deep Learning Algorithm in **Hugging Face**.

## Dataset
- Marker Pens' Caps (Custom)

Annotation Type - Polygon (masks)

Class &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &ensp; - CAP

## Methodology
![Hugging Face](https://img.shields.io/badge/-HuggingFace-yellow?style=for-the-badge&logo=HuggingFace&logoColor=black&logoHeight=20)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)

- `"nvidia/segformer-b4-finetuned-ade-512-512"` Model
- Applied Augmentations from albumentations
- Used lightning.pytorch, epochs=5-50
- Used dice_coef_loss and f1 for validation

## Results
- ### Validation of trained model (50 epochs)
  
|      valid/f1     |     valid/loss   |
|       -----       |      -----       |
|       0.9918      |       0.0119     |

---
⭐ Example Images results in `SegFormer_Huggingface_seg.ipynb`
