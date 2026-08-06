# 🩺 MediExplain AI – A Multimodal System for Interpreting Medical Laboratory Reports using LLM 

> AI-powered research project that simplifies complex medical laboratory reports into easy-to-understand explanations using  Large Language Models (LLMs).

![Status](https://img.shields.io/badge/Status-Research%20Project-success)
![AI](https://img.shields.io/badge/AI-LLM-blue)
![Conference](https://img.shields.io/badge/Published-ICSAICS%202026-green)

---

# 📌 Project Overview

Medical laboratory reports are often difficult for patients to understand because they contain complex medical terminology, abbreviations, reference ranges, and numerical values. Traditional OCR systems also struggle to preserve the relationship between medical tests, values, and units when processing scanned reports.

MediExplain AI is a research-based multimodal system designed to bridge this gap by combining image preprocessing, and Large Language Models (LLMs) to generate accurate, structured, and patient-friendly explanations of medical laboratory reports.

This project was presented and published as a research paper at the International Conference on Sustainable AI for Cyber Security (ICSAICS 2026).

> **Note:** This repository documents the project architecture, research methodology, evaluation results, and system design. The original implementation source code is not included.

---

# 🎯 Problem Statement

Patients often receive laboratory reports containing technical medical terms that are difficult to interpret without professional assistance.

Some common challenges include:

- Complex medical terminology
- Difficult-to-read laboratory values
- Medical abbreviations
- Paper-based reports
- Poor image quality
- Lack of contextual explanation
- English-only reports

The objective of MediExplain AI is to simplify these reports into clear, understandable language while preserving medical accuracy.

---

# 💡 Proposed Solution

The proposed system combines image preprocessing, Vision-Language Models, Large Language Models, and cloud storage to create an end-to-end medical report interpretation pipeline.

Major capabilities include:

- Medical report image processing
- Intelligent text extraction
- Structured JSON generation
- Context-aware explanation generation
- Cloud-based report storage
- Patient-friendly output

---

# ⚙️ System Workflow

```text
Medical Report Image
        │
        ▼
Image Preprocessing
(OpenCV)
        │
        ▼
Visual Information Extraction
(Qwen2-VL)
        │
        ▼
Structured Medical Data (JSON)
        │
        ▼
Large Language Model
(Llama-3-8B)
        │
        ▼
Patient-Friendly Explanation
        │
        ▼
MongoDB Atlas Storage
        │
        ▼
Gradio User Interface
```

---

# 🛠️ Technology Stack

| Category | Technology |
|----------|------------|
| Programming | Python |
| Image Processing | OpenCV |
| Vision Language Model | Qwen2-VL |
| Large Language Model | Llama-3-8B |
| Database | MongoDB Atlas |
| User Interface | Gradio |
| Data Format | JSON |
| Optimization | Unsloth (4-bit Quantization) |

---

# ✨ Key Features

- OCR-assisted medical report understanding
- Image preprocessing using OpenCV
- Vision-Language based information extraction
- Structured JSON generation
- AI-powered medical explanation
- Improved patient readability
- Cloud storage using MongoDB Atlas
- User-friendly Gradio interface

---

# 📊 Evaluation Results

The proposed system was evaluated using heterogeneous medical laboratory reports.

| Evaluation Metric | Result |
|------------------|--------|
| Key-Value Extraction Accuracy | **96.5%** |
| Text Extraction Accuracy | **98.2%** |
| Flesch Reading Ease Score | **70.47** |
| Hindi Translation BLEU Score | **45.0** |
| Average Processing Time | **~4.6 seconds/report** |

The evaluation demonstrated improved readability, faster processing, and high extraction accuracy compared to conventional OCR-based approaches.

---

# 📈 Project Highlights

- Research-based AI healthcare solution
- Multimodal document understanding
- Vision-Language + LLM pipeline
- Improved medical report readability
- Near real-time report interpretation
- Context-aware medical explanations
- Structured information extraction
- AI-assisted healthcare communication

---

# 🧠 Skills Demonstrated

- Artificial Intelligence
- Large Language Models (LLMs)
- Vision-Language Models (VLMs)
- Image Processing Concepts
- OCR Workflow
- Medical Document Analysis
- Research & Technical Documentation
- Workflow Analysis
- JSON Data Structuring
- System Design
- Research Presentation

---

# 👩‍💻 My Contribution

As a co-author of the MediExplain AI research project, I contributed to:

- Research and literature review
- Understanding the business problem and healthcare use case
- System workflow analysis
- Research paper documentation
- Evaluation and results interpretation
- Technical presentation of the research work
- Understanding the proposed AI architecture and methodology

---

# 🚀 Future Enhancements

Future improvements for the proposed system include:

- Support for additional Indian languages
- Mobile application deployment
- Explainable AI (XAI) integration
- Larger medical dataset evaluation
- Analytics dashboard for historical reports
- Clinical validation with healthcare professionals

---

# 📄 Research Publication

**Title**

**Medi Explain AI: Multimodal System for Interpreting Medical Laboratory Reports Using Large Language Models**

**Conference**

ICSAICS 2026

---

# ⚠️ Disclaimer

This repository is intended for educational and research purposes only.

The proposed system is designed to assist users in understanding medical laboratory reports and **should not be used as a substitute for professional medical advice or diagnosis.**

---

# 👩‍💻 Author

**Astha Jain**

📧 Email: 123jainastha@gmail.com

🔗 LinkedIn: https://linkedin.com/in/your-linkedin

💻 GitHub: https://github.com/asthajain326

---
