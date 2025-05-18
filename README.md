# 🤖 Fake News Classifier – Sahte Haber Sınıflandırıcı

🌍 Türkçe & English | 🧠 DistilGPT2 + Logistic Regression | 🎛️ Streamlit UI

---

## 🇹🇷 Proje Tanımı

Bu uygulama, sosyal medyada karşılaşılan sahte haberleri **7 kategoriye ayırmak** üzere geliştirilmiş bir yapay zekâ projesidir. Hugging Face tabanlı **DistilGPT2** modeli kullanılarak tweetlerden **embedding çıkarılmış**, ardından sklearn ile sınıflandırma yapılmıştır. 

Tahminler interaktif bir Streamlit arayüzü ile görsel olarak sunulmaktadır.

### 🔍 Sınıflar:
- 🧲 **Propaganda**
- 🔄 **Disinformation**
- ❌ **Misinformation**
- 🎣 **Clickbait**
- 👻 **Hoax**
- 🗞️ **Junk News**
- 😂 **Satirical**

---

## 🇬🇧 Project Overview

This is an AI-powered text classifier that identifies **fake news types** across social media. The model uses **DistilGPT2** embeddings and a logistic regression classifier. A Streamlit UI is built for easy interaction.

### 🧠 Label Classes:
- Propaganda
- Disinformation
- Misinformation
- Clickbait
- Hoax
- Junk News
- Satirical

---

## 🎬 Demo

### 📷 Ekran Görüntüsü

[![Demo Screenshot](https://github.com/MuratGoksu/fake-news-classifier/blob/main/images/demo_screenshot.png?raw=true)](https://github.com/MuratGoksu/fake-news-classifier/blob/main/images/demo_screenshot.png?raw=true) 

### 🧪 Örnek Tweet:

Click here to become a millionaire overnight!


Tahmin sonucu: **Clickbait**

### ▶️ Uygulama Nasıl Başlatılır?

```bash
streamlit run streamlit_app.py
git clone https://github.com/MuratGoksu/fake-news-classifier.git
cd fake-news-classifier
pip install -r requirements.txt

Model Performansı (F1-Skorları)
| Class          | F1 Score |
| -------------- | -------- |
| Propaganda     | 0.89     |
| Misinformation | 0.88     |
| Clickbait      | 0.81     |
| Hoax           | 0.76     |
| Satirical      | 0.81     |
| Junk News      | 0.86     |
| Disinformation | 0.80     |

🎯 Accuracy: %83

Proje Yapısı
fake-news-classifier/
├── README.md
├── requirements.txt
├── streamlit_app.py
├── fake_news_labeled_dataset.csv
├── saved_fake_news_model/
│   ├── classifier.pkl
│   ├── tokenizer_config.json
│   └── vocab.json, merges.txt, vb.

🙌 Katkı & Lisans

Bu proje geliştirilmeye açıktır.
Yeni örnekler, farklı modeller, Gradio veya Hugging Face Spaces entegrasyonu için katkılara açığız.

© 2025 Murat Göksu
