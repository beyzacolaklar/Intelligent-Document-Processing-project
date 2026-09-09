
# 🧠 Intelligent Document Processing with Local LLMs

An end-to-end document intelligence system that automatically validates PDF files, extracts text, classifies document types, and retrieves structured information using a local Large Language Model.

---
<p align="center">
  <img src="assets/Kayıt 2026-09-09 141835.gif" alt="Project Demo" width="900px">
</p>

## 🚀 Overview

This project is an **AI-powered Document Intelligence** application developed in Python. It processes financial PDF reports (such as BDR and JCR reports) through a complete analysis pipeline and extracts meaningful structured information without relying on cloud-based AI services.

The system combines **rule-based document classification** with a locally hosted Large Language Model (**Qwen2.5-1.5B-Instruct**) to provide fast, privacy-friendly, and structured document understanding.

---

## ✨ Key Features

* **PDF Validation & Cleaning:** Automatically verifies and cleans input documents.
* **Smart Classification:** Rule-based document type classification.
* **Local LLM Extraction:** Powered by local Qwen2.5 model for secure information retrieval.
* **Structured Data Output:** Extracts Company Names, Reporting Years, and Subsidiary Presence into JSON and Excel formats.
* **Interactive UI:** Modern Gradio-powered web interface.
* **100% Local Execution:** Runs completely on your local machine with zero external API dependencies.

---

## 🛠️ Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Language** | Python |
| **AI Model** | Qwen2.5-1.5B-Instruct |
| **Frameworks** | Hugging Face Transformers, Gradio |
| **Data Processing** | Pandas, PyPDF / PDF libraries |

---

## 🚀 Quick Start

```bash
# Clone the repository
git clone [https://github.com/ilaydaylcnz/Intelligent_Document_Processing_with_Local_LLMs.git](https://github.com/ilaydaylcnz/Intelligent_Document_Processing_with_Local_LLMs.git)

# Move into the project directory
cd Intelligent_Document_Processing_with_Local_LLMs

# Install dependencies
pip install -r requirements.txt
