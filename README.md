# MaterialScienceResearch

# Solid-State Battery Conductors Research

## Overview
This repository contains the research work and code developed under the guidance of Professor Yifei Mo and with the assistance of PhD student Yunsheng Liu. The project explores the computational analysis of solid-state lithium-ion conductors, which are crucial for advancing battery technology.

## Research Objective
The goal of this research is to compare the X-ray diffraction patterns of known ideal and non-ideal solid electrolyte materials to identify promising candidates for solid-state batteries. This involves the use of unsupervised machine learning techniques to classify materials based on their modified X-Ray Diffraction (mXRD) patterns.

## Methodology
The analysis is performed using Python and several libraries for scientific computing and data visualization:

- `numpy`: For numerical computing.
- `pymatgen`: For materials analysis and handling crystallographic data.
- `scipy`: For scientific and technical computing.
- `matplotlib`: For creating static, interactive, and 3D visualizations.
- `sklearn`: For machine learning and data mining.

We employ data normalization techniques, Gaussian smearing of mXRD patterns, and Agglomerative Hierarchical Clustering with Ward's method to discover patterns in the mXRD data.

## Installation

To run the code, you will need to install the required Python libraries. You can install them using the following command:

```bash
pip install -r requirements.txt
