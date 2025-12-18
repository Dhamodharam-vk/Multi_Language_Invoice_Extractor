# 🧾 Multi-Language Invoice Extractor

A powerful Streamlit application that leverages **Google Gemini 2.0 Flash** to analyze invoice images and extract specific information based on natural language queries.



## 🌟 Overview

The **Multi-Language Invoice Extractor** allows users to upload images of invoices (in various languages) and ask questions about them. Whether you need to find the total amount, the vendor name, or specific line items, the AI "sees" the image and provides accurate text-based answers.

## ✨ Features

* **Multimodal Analysis:** Uses Gemini's vision capabilities to process image data.
* **Natural Language Querying:** Ask questions like *"What is the invoice date?"* or *"List the tax breakdown."*
* **Multi-Language Support:** Efficiently interprets invoices in different languages.
* **Interactive UI:** Clean and simple interface built with Streamlit.

---

## 🛠️ Tech Stack

* **LLM:** [Google Gemini 2.0 Flash](https://aistudio.google.com/)
* **Frontend:** [Streamlit](https://streamlit.io/)
* **Image Processing:** [Pillow (PIL)](https://python-pillow.org/)
* **Environment:** Python-dotenv

---

## 🚀 Getting Started

### 1. Prerequisites
* Python 3.10+
* A Google Cloud API Key for Gemini.

### 2. Installation
Clone this repository and navigate to the project folder:
```bash
git clone <your-repo-url>
cd <project-folder-name>
