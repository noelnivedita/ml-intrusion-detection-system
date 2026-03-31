# AI/ML Intrusion Detection System — Hybrid Cloud Environment

## 📌 Project Overview
Built a complete machine learning pipeline to detect network intrusions 
using the CIDDS-001 dataset, achieving 99% classification accuracy with 
an added IAM false-positive reduction layer.

## 🎯 What This Project Demonstrates
- End-to-end ML pipeline for cybersecurity
- Working with real network traffic datasets
- IAM integration for reducing false alarms

## 🧰 Tools Used
- **Python** (scikit-learn, pandas, numpy, XGBoost)
- **CIDDS-001 Dataset** (real network traffic data)
- **VirtualBox** (simulated cloud lab environment)
- **Kali Linux + Ubuntu** (attack simulation)

## 📊 Model Performance
| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression | 97.2% | 0.971 |
| Random Forest | 99.1% | 0.991 |
| XGBoost | 99.0% | 0.990 |

## 🛡️ IAM Layer
Applied Identity & Access Management rules on top of ML predictions to 
reduce false positives from trusted internal IP ranges and known-safe ports.

## 📁 Files
- `MRP_with_IAM.py` — Full ML pipeline with IAM layer

## 📸 Screenshots
<img width="1065" height="263" alt="Screenshot 2026-03-19 122054" src="https://github.com/user-attachments/assets/61b99ac5-e96f-4b54-a197-cd6542e4e98d" />

<img width="1106" height="288" alt="Screenshot 2026-03-19 130157" src="https://github.com/user-attachments/assets/5335ec97-8686-4010-acce-156f03c8003f" />

<img width="753" height="288" alt="Screenshot 2026-03-19 130217" src="https://github.com/user-attachments/assets/ec5e370c-19f5-429d-9a7f-8858627818fb" />
3" />

<img width="1102" height="525" alt="Screenshot 2026-03-19 121004" src="https://github.com/user-attachments/assets/0a736277-9ce1-450b-87a2-27081f8ff149" />

