# Automated Segmentation and Analysis of High-Speed Video Phase-Detection Data for Boiling Heat Transfer Characterization Using U-Net Convolutional Neural Networks and Uncertainty Quantification

![MIT](https://img.shields.io/badge/Made%20at-MIT-blue.svg)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Boiling%20Dynamics-brightgreen.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-U--Net-brightgreen.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-Convolutional%20Neural%20Networks-critical.svg)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-High%20Speed%20Video-orange.svg)

This repository is the official GitHub page accompanying the thesis titled above, authored at MIT. It details a comprehensive approach to characterizing and understanding boiling dynamics using high-speed video (HSV) imaging and advanced computer vision techniques. The focus is on developing and applying U-Net Convolutional Neural Networks (CNNs) for the automated segmentation of boiling phenomena in various fluids and experimental conditions, coupled with uncertainty quantification to enhance the reliability of the analyses.

## Table of Contents
- [Overview](#overview)
- [Abstract](#abstract)
- [Installation](#installation)
- [Tutorials](#tutorials)
  - [Installation Guide](#installation-guide)
  - [Segmentation](#segmentation)
  - [Fine-Tuning](#fine-tuning)
  - [Detection](#detection)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Citations](#citations)

## Overview
This project applies U-Net CNNs to the automated segmentation and analysis of high-speed video data, aiming to improve the accuracy and efficiency of boiling heat transfer characterization. It spans a variety of fluids, including liquid nitrogen and high-pressure water, under different experimental setups.

## Abstract
Boiling heat transfer is a complex phenomenon essential for cooling and heat management in various industrial applications. This thesis presents a novel approach using U-Net CNNs for the automated segmentation of HSV phase-detection images to enhance the characterization of boiling dynamics. It involves developing tailored U-Net models, evaluating their performance against traditional methods, and integrating comprehensive uncertainty quantification analyses to validate the reliability of the derived metrics. The findings underscore the potential of advanced computer vision techniques in revolutionizing boiling heat transfer research and industrial applications.

## Installation
To set up this project for replication of results or further development, follow these steps:
```bash
git clone https://github.com/chikap421/cvboil
cd cvboil
pip install -r requirements.txt