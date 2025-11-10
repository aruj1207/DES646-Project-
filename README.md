# DES646-Project-
DES646 Project  || 2025-26 Odd Semester
# 🧵 AI-Vastra: A Multimodal AI Assistant for E-Commerce Trust and Fit

//https://github.com/aruj1207/DES646-Project-

### DES646 Mid-Term Project  
**Team Members:**  
- **Ayushmaan Singh [220276]**  
- **Prathamesh Baviskar [220285]**  
- **Dheeraj Dagar [220355]**
- **Rishith [220484]**
- **Rajesh Inapakurti [220463]**

---

## 📘 Overview

**AI-Vastra** is a prototype web application designed to enhance **trust**, **accessibility**, and **visualization** for online shoppers.  
The system integrates multiple AI/ML APIs into a unified, multimodal experience.  
It allows users to **interact via voice or text**, receive **AI-generated product insights**, and visualize products using **Virtual Try-On** and **AR-based scale estimation** tools.

---

## 🎯 Objectives

- **Implement Multimodal Interaction:**  
  Use Azure Cognitive Services for a voice-based, hands-free shopping assistant.

- **Enable AI-Powered Review Summarization:**  
  Use LLMs (Gemini / Perplexity) to generate answers from existing product reviews.

- **Integrate Visualization Tools:**  
  Combine a Streamlit-based **Virtual Try-On (VTO)** and **AR Size Visualizer** (ClipDrop API).

- **Deliver a Cohesive, Multilingual Prototype:**  
  Seamlessly connect all features within a single web interface supporting English and Hindi.

---

## 🧩 Features & Functionalities

### 1. Multimodal & Multilingual Assistant
- **Speech-to-Speech Mode:** Real-time voice conversation using Azure STT/TTS.  
- **Review Q&A Chatbot:** LLM-powered assistant to answer product-related queries.  
- **Language Switcher:** Dynamic text and voice translation between supported languages.

### 2. AR-Lite Visualization Suite
- **Virtual Try-On (VTO):** Streamlit-based tool to visualize garment fit using 2D pose estimation.  
- **AR Size Visualizer:** ClipDrop API integration to display product scale next to a hand image.

### 3. Static Trust Signal
- **Verified Badge:** A visual trust marker on product cards for credibility and authenticity.

---

## ⚙️ Technical Architecture

| Component | Technology / API |
|------------|------------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Speech AI** | Azure Cognitive Services (Speech-to-Text / Text-to-Speech) |
| **LLM Backend** | Perplexity / Google Gemini API |
| **Virtual Try-On** | Streamlit App (Pose Estimation + Garment Warping) |
| **AR Size Visualizer** | ClipDrop Computer Vision API |
| **Language Support** | JS-based module for multilingual UI switching |

---

## 🗓️ Project Plan & Timeline

| Phase | Duration | Key Tasks | Milestone |
|-------|-----------|------------|------------|
| **Phase 1:** Foundation & Visualization | Weeks 1–2 | Build static site, integrate VTO and AR Size Visualizer | Functional prototype with visualization |
| **Phase 2:** Multimodal Assistant | Weeks 2–3 | Integrate Azure Speech SDK and LLM API | Functional multilingual assistant |
| **Phase 3:** Integration & Testing | Week 4 | Add trust signals, polish UI, conduct user testing | Final working prototype ready |

---

## 🧠 Research & Dissemination

**Direction:** Academic publication preferred over patenting.  
The innovation lies in **system integration and inclusive design**, not in novel algorithms.  
Potential venues include **HCI, Design Research, and Tech-for-Social-Good** conferences.

---

## 🚀 Installation & Setup (Prototype)

1. Clone the repository:
   ```bash
   git clone https://github.com/aruj1207/DES646-Project- AI-Vastra
   cd AI-Vastra
   ```
2. Add the API keys for Perplexity and Azure Speech Services in the main html file
3. Run using LiveServer on VS Code
