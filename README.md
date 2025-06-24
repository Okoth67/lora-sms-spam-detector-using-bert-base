# 📱 LoRA SMS Spam Detector

This project fine-tunes `bert-base-uncased` for SMS spam classification using [LoRA (Low-Rank Adaptation)](https://arxiv.org/abs/2106.09685), a parameter-efficient tuning method. Trained on the `sms_spam` dataset from Hugging Face, the model updates only ~0.27% of its weights and achieves fast, resource-friendly training.

---

## 🚀 Features

- ✅ Fine-tunes BERT with LoRA using PEFT
- ✅ Trained on the `sms_spam` dataset
- ✅ Less than 300K trainable parameters
- ✅ Gradio app for real-time SMS prediction

---
