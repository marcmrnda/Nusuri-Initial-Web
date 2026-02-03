# NuSuri: AI-Powered TB Triage System 🫁

> **National 2nd Runner-Up** | DICT Philippine Startup Challenge X (Startup Category)  
> **Regional Champion** | DICT Philippine Startup Challenge X (Calabarzon)

![Project Status](https://img.shields.io/badge/Status-In%20Development-yellow)
![Security](https://img.shields.io/badge/Code-Private%20(IP%20Protected)-red)
![Stack](https://img.shields.io/badge/Stack-React%20Native%20%7C%20IoT%20%7C%20AI-blue)

## 📖 About the Project

**[span_0](start_span)NuSuri** is an AI-powered cough screening and triage tool designed to detect Tuberculosis (TB) risks in community health facilities[span_0](end_span). Developed by **Team Hirayón**, it bridges the gap between hardware and software by combining IoT-enabled audio capture with on-device machine learning predictions.

Our goal is to provide a low-cost, accessible screening method that delivers risk results ("Low", "Review", "High") in under 60 seconds.

## 🔒 Source Code Availability

**⚠️ Note to Recruiters and Visitors:**

This repository serves as a technical overview of the NuSuri project. **The source code is currently private** to protect:
1.  **Intellectual Property:** The software is copyrighted and currently part of an active startup incubation.
2.  **Data Privacy:** The application handles sensitive medical data (audio recordings) in compliance with ethical standards.

*Access to the codebase or a live demo may be granted upon request for interview purposes.*

## 🛠️ System Architecture & Tech Stack

Even though the code is hidden, here is how we built it:

### 📱 Mobile Application (React Native / Expo)
* **[span_1](start_span)Audio Engineering:** Implemented strict timing workflows and dynamic sample rate switching to ensure high-fidelity recordings for AI analysis[span_1](end_span).
* **[span_2](start_span)IoT Integration:** Built a custom Bluetooth Low Energy (BLE) module to interface with external recording hardware[span_2](end_span).
* **[span_3](start_span)UI/UX:** Designed a patient-facing symptom questionnaire that feeds data directly into the risk prediction model[span_3](end_span).

### 🧠 AI & Backend Integration
* **[span_4](start_span)On-Device Inference:** Deployed Logistic Regression models directly to the mobile app for offline risk assessment[span_4](end_span).
* **[span_5](start_span)Data Pipeline:** Engineered a pipeline that coordinates data transfer, preprocessing, and feature alignment between the mobile app and the AI server[span_5](end_span).

## 🏆 Awards & Recognition

* **[span_6](start_span)National 2nd Runner-Up:** DICT Philippine Startup Challenge X[span_6](end_span)
* **Regional Champion:** DICT Region 4A (Calabarzon)
* **[span_7](start_span)Huawei Innovation Track:** 3rd Place Winner[span_7](end_span)

## 👥 Team Hirayón

* **Marc Louisse Miranda** - Co-Founder & Lead Mobile Developer
* *[List other members if you want]*

---
*For inquiries regarding this project, please contact me at marcmrnda@gmail.com*
