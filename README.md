# 🚀 LLM Powered Text Translation Web App using Groq Cloud (LLaMA Models)

This project demonstrates how to access **LLaMA series Large Language Models (LLMs)** using **Groq Cloud**, build a **Streamlit Web UI**, and deploy the application.

---

## 📌 Prerequisites

* Python 3.8 or higher
* Git
* Conda / Virtual Environment support
* Streamlit

---

## 🔑 LLM Access & API Key Setup

### 1️⃣ Create Groq Cloud API Key

* Visit: [https://console.groq.com/keys](https://console.groq.com/keys)
* Generate a new API key

### 2️⃣ Store API Key Securely

Create a `.env` file in the project root and add:

```env
GROQ_API_KEY=your_api_key_here
```

### 3️⃣ Load API Key in Application

Use environment variable loading inside your application file.

---

## 🧪 Environment Setup

### Deactivate Base Conda Environment (Optional)

```bash
conda.bat deactivate
```

### Create a Virtual Environment

```bash
python -m venv myenv
```

### Activate Virtual Environment (Windows)

```bash
myenv\Scripts\activate.bat
```

---

## 📦 Install Dependencies

### Update `requirements.txt`

Ensure all required libraries are listed.

### Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 🤖 LLM Client Configuration

* Configure the Groq LLM client using the API key
* Select **LLaMA series models** from Groq Cloud
* Define model parameters (temperature, max tokens, etc.)

---

## 🖥️ Web UI Development

* The application UI is built using **Streamlit**
* Provides a simple interface to interact with the LLM

---

## ▶️ Run the Streamlit Application

```bash
streamlit run script_name.py
```

Replace `script_name.py` with your actual Python file name.

---

## 📤 GitHub Setup

### Add `.gitignore`

Make sure to ignore sensitive and unnecessary files:

```
.env
myenv/
__pycache__/
```

### Push Code to GitHub

```bash
git add .
git commit -m "Initial commit"
git push
```

---

## ☁️ Deployment (Streamlit Cloud)

* Visit: [https://share.streamlit.io/](https://share.streamlit.io/)
* Connect your GitHub repository
* Select the main script file
* Add environment variables in Streamlit Cloud settings
