# Diabetic Retinopathy Detection CNN

![Python](https://img.shields.io/badge/Python-3.11-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-orange)
![MLflow](https://img.shields.io/badge/MLflow-Tracked-purple)
![Streamlit](https://img.shields.io/badge/Demo-Live-red)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Project Overview
Diabetic Retinopathy (DR) is graded on a 5-class severity scale (where 0 = No DR, 1 = Mild, 2 = Moderate, 3 = Severe & 4 = Proliferative DR). The goal is a production quality CNN classifier using EfficientNet-B4 with transfer learning, focal loss for class imbalance and Grad-CAM heatmaps for clinical explainability which are all tracked via MLflow.

## 🏥 Clinical Motivation
Diabetic Retinopathy affects **1 in 3 people with diabetes** globally, making it the
leading cause of preventable blindness. Early-stage DR (Grades 1–2) is asymptomatic,
yet treatment at this stage is 95% effective at preventing vision loss.

Current screening bottlenecks:
- Shortage of trained ophthalmologists in rural/developing regions
- Manual grading is time-intensive and subject to inter-rater variability (κ ~0.63)
- AI-assisted tools can pre-screen patients, flagging high-risk cases for specialist review

This project simulates an **AI-assisted screening tool** aligned with
FDA AI/ML SaMD (Software as a Medical Device) principles.
