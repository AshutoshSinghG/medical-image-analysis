# 🩺 Medical Image Analysis Tool

An AI-powered web application to analyze medical images (X-ray, MRI, CT, etc.) using Google's Gemini model via the `agno` framework. It provides detailed, structured diagnostic reports with patient-friendly explanations and relevant research references.

---

## 🚀 Features

- 📸 Upload medical images (X-ray, MRI, CT, Ultrasound, etc.)
- 🧠 Analyze images using Gemini AI with `agno` agent
- 📋 Structured diagnostic output (findings, diagnosis, patient summary)
- 🔎 Uses DuckDuckGo tools for literature references
- 🖥️ Built with **Streamlit** for an interactive web interface

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/AshutoshSinghG/medical-image-analysis.git
cd medical-image-analysis

### 2. Update env file

GOOGLE_API_KEY = "your_actual_google_api_key_here"

### 3. Installation/Setup

```bash
python -m venv venv
# Activate:
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
google-genai
duckduckgo-search

pip install -r requirements.txt

pip install google-genai

pip install duckduckgo-search

### 4. Run the app

```bash
streamlit run medical.py

### 5. 📁 File Structure

```bash

medical-image-analysis/
├── medical.py           # Main application file
├── requirements.txt     # Python dependencies
├── README.md            # You're here!
└── demo_screenshot.png  # Optional: image for preview

### 6. 📜 License

MIT License

### 7. 🙋‍♂️ Author

Ashutosh Kumar
MCA @ NIT Karnataka
GitHub: @AshutoshSinghG
