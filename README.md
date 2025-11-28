# 🌍 Multi-Language Translator (NLLB-200)

A simple and powerful **English-to-Any-Language translator** built using **Hugging Face Transformers**, **NLLB-200 model**, and **Gradio**.
This project allows you to translate English text into hundreds of languages using the **FLORES-200 language codes**.

---

## 🚀 Features

* Translate English text into **200+ languages**
* Uses **Meta’s NLLB-200 (No Language Left Behind)** model
* Simple and fast **Gradio UI**
* Dynamic language dropdown generated from `language.json`
* Clean workflow for mapping language names → FLORES codes

---

## 🧠 Model Used

**facebook/nllb-200-distilled-600M**
A distilled, lightweight, high-accuracy multilingual translation model.

---

## 📌 Requirements

```
torch
transformers
gradio
```

---

## 📝 How It Works

1. User selects a target language
2. App fetches the correct **FLORES-200 code** from `language.json`
3. NLLB model translates text from **eng_Latn → target language**
4. Output shows translated text in chosen language

---
