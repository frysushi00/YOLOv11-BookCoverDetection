# YOLOv11-BookCoverDetection

> Book cover text detection using YOLOv11 to find titles and authors.

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white) 
![PYTHON](https://badgen.net/badge/Python/3.10/)
![yolo](https://badgen.net/badge/YOLOv11/Small/yellow)
![acc](https://badgen.net/badge/Accuracy/0.887/green)
![mAP50](https://badgen.net/badge/mAP50/0.89/red)

## 📑 Table of Contents

- [Description](#description)
- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [Quick Start](#quick-start)

## 📝 Description

YOLOv11-BookCoverDetection is a specialized computer vision project designed to identify and locate key textual elements on book covers. Using the YOLOv11 object detection architecture, the system is designed to recognize and delineate two primary zones on a book's front cover: the title and the author. This addresses the challenge of automated book metadata extraction and cataloging from physical cover images.

## ✨ Key Features

- **📖 Book Title Detection** — Identifies and localizes the main title area on diverse book cover designs.
- **✍️ Author Name Localization** — Detects and places bounding boxes around author names printed on book covers.
- **📓 Best result after 12 trials** — After 12 trials from both small and nano version of YOLOv11, and each with different optimizers (Adam, AdamW, RMSProp, SGD). RMSProp with YOLOv11 Small give the best result.

## 🎯 Use Cases

- Automating inventory categorization for libraries and digital archives by scanning book covers.
- Pre-processing book cover images to crop key regions before sending them to OCR text-recognition systems.

## ⚡ Quick Start

```bash

# Clone the repository
git clone https://github.com/frysushi00/YOLOv11-BookCoverDetection.git
