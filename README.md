# BanglaDocAtlas

This repository offers the information about the **BanglaDocAtlas** datasets, trained models for evaluating the custom made datasets, along with the related code, as detailed in the paper titled **"BanglaDocAtlas: A Complex Bangla Document Layout Analysis Dataset"**
BanglaDocAtlas is a custom dataset for Document Layout Analysis(DLA) System designed specifically for Bengali Language consisting of 2,167 images out of 5,000 images in total featuring a total of 8 classes **(Advertisement, Image, Caption, Title, Paragraph, Text, Table, Page Number)** from 4 distinct domains **(Magazines, Books, Newspapers, and Official Documents)**.

## Table of Contents

- [BanglaDocAtlas](#BanglaDocAtlas)
  - [Table of Contents](#table-of-contents)
  - [Models](#models)
  - [Datasets](#datasets)
  - [Acknowledgements](#acknowledgements)

## Models

The pretrained model checkpoints are available at [https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/tree/main/Notebooks).

- [**YOLOv9**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/blob/main/Notebooks/YOLO/V9/yolov9-fydp-document-layout-analysis.ipynb)
- [**YOLOv8**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/blob/main/Notebooks/YOLO/V8/yolov8-fydp-document-layout-analysis.ipynb)
- [**YOLOv5**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/blob/main/Notebooks/YOLO/V5/yolov5-fydp-document-layout-analysis.ipynb)
- [**RT-DETR**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/blob/main/Notebooks/RT-DETR/rt-detr-fydp-document-layout-analysis.ipynb)
- [**U-Net**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/blob/main/Notebooks/U_NET/u-net-document-layout-analysis.ipynb)
- [**Detectron2**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/blob/main/Notebooks/DETECTRON2/detectron2-fydp-document-layout-analysis.ipynb)


## Datasets

Our dataset is split into a 75-10-15 ratio for training, validation, and testing respectedly. The dataset's lebel data is then divided into two formats: .txt for YOLO and RT-DETR models, and coco.json for the Detectron 2 model. Additionally, we generated masked images from the coco.json format lebel to train the U-NET model.

- [**YOLO(v9, v8, v5) Dataset**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/tree/main/Dataset/YOLO(v5__v8__v9))
- [**RT-DETR Dataset**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/tree/main/Dataset/RT_DETR)
- [**U-Net Dataset**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/tree/main/Dataset/U_NET)
- [**Detectron2 Dataset**](https://github.com/MD-SAFAYAT-HOSSAIN-SIFAT/BanglaDocAtlas/tree/main/Dataset/DETECTRON2)

  
## Acknowledgements

We would like to thank [Professor Swakkhar Shatabda](https://scholar.google.com/citations?hl=en&user=2DhrWFgAAAAJ&view_op=list_works&sortby=pubdate) and [Md Ashiqur Rahman](https://scholar.google.com/citations?user=ujAbMnwAAAAJ&hl=en) for providing enourmous support and guidence for completing our research project.

