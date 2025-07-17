# README.md

# 🇻🇳 VietNam Banking Captcha Model Archive

A collection of machine learning models designed to solve captchas used by Vietnamese banks.

## 📦 Features

- Pretrained models for major Vietnamese banks (VCB, BIDV, MB, etc.)
- Clean CNN-RNN architectures optimized for OCR
- Ready-to-run prediction & training scripts
- Easily extendable datasets and models

## 🏁 Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/vn-banking-captcha-models.git
cd vn-banking-captcha-models

# Install dependencies
pip install -r requirements.txt

# Run a demo prediction
python demo.py \
  --image samples/vcb_01.png \
  --model models/vcb_model.keras
```

## 📁 Project Structure

models/        → Pretrained .keras model files  
datasets/      → Captcha images for each bank  
samples/       → Sample captcha images for testing  
src/           → Source code for training & prediction

## ⚠️ License

MIT License.  
For research or educational use only. Do **not** use for any illegal or unethical purposes.

## 📬 Contact

Author: Netrotion

GitHub: https://github.com/netrotion
