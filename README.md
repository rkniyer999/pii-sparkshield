# 🔐 PII SparkShield

A PySpark-based framework for detecting and anonymizing Personally Identifiable Information (PII) using Microsoft Presidio, Faker, and Microsoft Fabric.

## 🚀 Features

- 🔍 PII Detection & redaction with Microsoft Presidio
- 🛡️ Anonymization via Masking, Hashing, and Encryption
- 🧪 Synthetic Data Generation using Faker
- ⚙️ Scalable on Microsoft Fabric (Lakehouse + Data Factory)

## 📁 Project Structure

- `notebooks/`: Jupyter notebooks with step-by-step examples
- `src/`: Core PySpark pipeline and utility functions
- `data/`: Sample input data
- `requirements.txt`: Python dependencies

## 🧰 Setup

```bash
git clone https://github.com/your-username/pii-sparkshield.git
cd pii-sparkshield
pip install -r requirements.txt

📓 Notebooks
01_pii_detection_presidio.ipynb: Detect PII using Presidio
02_synthetic_data_faker.ipynb: Generate synthetic data
03_anonymization_masking_hashing.ipynb: Apply masking and hashing

