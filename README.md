# SUIM Dataset in Pascal VOC Format

This repository provides the **SUIM dataset converted to Pascal VOC format** for convenient use in semantic segmentation workflows.

The original SUIM dataset was released by the official project:

- **Original SUIM Project**: [https://github.com/xahidbuffon/SUIM](https://github.com/xahidbuffon/SUIM)

---

## Overview

SUIM is a widely used benchmark for underwater semantic segmentation.  
To facilitate training and evaluation in frameworks that support the **Pascal VOC format**, this repository reorganizes the dataset into a VOC-style directory structure.

This repository is intended for researchers and developers who want to directly use SUIM in Pascal VOC-based pipelines without manually converting the dataset.

---

## Preview

### 1. Dataset Example

> Replace the image path below with your own image file.

![SUIM Sample](docs/images/suim_sample.png)

### 2. Pascal VOC Directory Structure

> Replace the image path below with your own structure illustration.

![Pascal VOC Structure](docs/images/voc_structure.png)

---

## Download

You can download the converted Pascal VOC version of SUIM from the following links:

- **Baidu Netdisk**: [Baidu Download Link](https://pan.baidu.com/s/1mNvAzOC5jFBTU2Hn6OF7oQ?pwd=suim)
- **Google Drive**: [Google Drive Download Link](https://drive.google.com/file/d/13pYwno9Kgd-YVBsh9I1EYVpyD3f9V7DI/view?usp=drive_link)

---

## Pascal VOC Directory Structure

The converted dataset is organized as follows:

```text
SUIM/
├── ImageSets/
│   └── Segmentation/
│       ├── train.txt
│       ├── val.txt
│       └── test.txt
├── Images/
│   ├── d_r_1_.jpg
│   ├── d_r_3_.jpg
│   └── ...
├── Label/
│   ├── d_r_1_.png
│   ├── d_r_3_.png
│   └── ...
└── README.md
