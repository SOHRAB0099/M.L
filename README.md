🦷 Dental Radiographs EDA & Visualization
📖 Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) and visualization pipeline for the Children's Dental Panoramic Radiographs Dataset. It is designed to parse COCO-formatted annotations, translate original clinical labels, and render bounding boxes alongside segmentation masks on pediatric dental X-rays.
🗂️ Dataset
The analysis is performed on the Children's Dental Panoramic Radiographs Dataset, which focuses on pediatric dental health and includes:
Dental Caries Segmentation
Pediatric Dental Disease Detection
Annotations provided in standard COCO JSON format.
Target Classes:
The dataset covers the following clinical conditions (translated from original Chinese labels):
🦷 Caries (龋齿)
🔥 Pulpitis (牙髓炎)
🕳️ Deep Pit (深龋)
⚠️ Abnormal Tooth Development (异常牙发育)
✨ Key Features
COCO Annotation Parsing: Efficiently loads and processes complex JSON annotations using pycocotools.
Label Translation: Maps original clinical terms to English for better accessibility and integration with standard ML pipelines.
Advanced Visualization: Overlays bounding boxes and segmentation masks directly onto grayscale radiographs using custom Matplotlib and OpenCV functions.
Statistical Insights: Analyzes category distributions, instance counts, and image-level statistics to understand dataset balance and characteristics.
🛠️ Requirements & Dependencies
To run this notebook, ensure you have the following libraries installed
