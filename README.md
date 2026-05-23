# RoadGuard CV - Milestone 1: Road Hazard Baseline Classifier

An AI-powered road hazard detection system commissioned for the Urban Infrastructure & Smart Mobility Division of Berlin (2026). This milestone builds a robust pipeline to scrape and classify road hazards into Potholes and Debris using a HOG + SVM baseline.

## Pipeline Overview
1. **Data Collection:** Scraped 1,377 images using iCrawler (Bing & Baidu fallbacks).
2. **Preprocessing:** Gray scaling, 128x128 resizing, Gaussian Blur, CLAHE equalization, and image sharpening.
3. **Feature Extraction:** 1,764-dimensional Histogram of Oriented Gradients (HOG) features.
4. **Classification:** Scikit-Learn SVM Pipeline with a Standard Scaler and RBF kernel.

## Shared Google Colab Notebook
[Click here to view the live execution and EDA notebook](https://colab.research.google.com/drive/1yippVeTh7PVEucdtl2pt6COJ-qzUvbuJ?usp=sharing)

