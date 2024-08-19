# BanglaDocAtlas

This repository contains the official release of the model **"BanglaDocAtlas"** and associated downstream fine-tuning code and datasets introduced in the paper titled [**"BanglaBERT: Language Model Pretraining and Benchmarks for
Low-Resource Language Understanding Evaluation in Bangla"**](https://aclanthology.org/2022.findings-naacl.98/) published in *Findings of the Association for Computational Linguistics: NAACL 2022*.

## Updates
* We have released [BanglaBERT (small)](https://huggingface.co/csebuetnlp/banglabert_small). It can be fine-tuned with as little as 4 GB VRAM!
* We have released a large variant of BanglaBERT! Have a look [here](https://huggingface.co/csebuetnlp/banglabert_large).
* The Bangla2B+ pretraining corpus is now available upon request! See [here](#datasets).

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

We are also releasing the Bangla Natural Language Inference (NLI) and Bangla Question Answering (QA) datasets introduced in the paper. 
- [**NLI**](https://huggingface.co/datasets/csebuetnlp/xnli_bn)
- [**QA**](https://huggingface.co/datasets/csebuetnlp/squad_bn)

Please fill out this [**Google Form**](https://forms.gle/qiEW8f7i6Bw3FmmQA) to request access to the Bangla2B+ pretraining corpus. 
  
## Acknowledgements

We would like to thank [Intelligent Machines](https://bd.linkedin.com/company/intelligentmachines) and [Google TFRC Program](https://sites.research.google/trc/) for providing cloud support for pretraining the models.

