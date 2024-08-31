# Final Project - Fetal Head Circumference Prediction
## **Introduction**
Ultrasound imaging is essential for monitoring fetal development, with head circumference (HC) being a key measurement.
Traditional HC measurement methods can be inconsistent due to factors like operator experience and fetal position, leading to inaccurate assessments that affect clinical decisions.
Aim: Improve accuracy using advanced machine-learning techniques

## **Motivation**
Currently, the common approach for HC prediction is through image segmentation. However, accurate segmentation and measurement remain challenging and imperfect.
Classification models have shown unexpected effectiveness in various applications and studies show that classification networks can sometimes outperform regression models in terms of performance.

## **Installation**
We ran the code on Kaggle instead of Google Colab. When running the code, ensure that the upcoming libraries are pre-installed:

- **Torch**
- **Timm**
- **OpenCV (cv2)**

To install these libraries, you can use the following commands:

```python
!pip install torch timm opencv-python-headless
```

## **Data Sources**
HC18 challenge dataset was used to train models. Dataset Link:- https://zenodo.org/record/1327317.
In addition, we created synthetic data by training StyleGAN2 using the HC18 dataset, and we trained a Nested U-net segmentation model to measure the synthetic images HC. 





