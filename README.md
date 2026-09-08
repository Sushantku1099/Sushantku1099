<div align="center">

# Sushant Sagar

**Software Developer · AI/ML Engineer · IoT & Embedded Systems · Open Source Author**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sushant-sagar-723b65338/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sushantku1099)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sushant1892004@gmail.com)

📍 Pawai Dih, Banka, Bihar — 813101 &nbsp;|&nbsp; 📞 +91-6207504908

</div>

---

## 👨‍💻 About Me

AI/ML Engineer and Software Developer focused on building production-ready intelligent applications using Machine Learning, Deep Learning, Computer Vision, Python, and modern software engineering technologies.



My primary interests are Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Generative AI, and AI application development.



I enjoy taking AI projects beyond model training — from data preprocessing and experimentation to backend APIs, user interfaces, deployment, and complete production applications.



My AI/ML experience includes:

• Machine Learning and Deep Learning

• Computer Vision and Image Classification

• Transfer Learning and Ensemble Learning

• Explainable AI using Grad-CAM

• TensorFlow and model development

• Data preprocessing and augmentation

• Model evaluation and optimization

• Python-based AI application development

• FastAPI model-serving APIs

• AI model integration with web applications



One of my key projects is SafeSkin AI, a deep-learning-based skin cancer detection platform built using the HAM10000 dataset. I worked with DenseNet201 and InceptionV3 transfer-learning models, ensemble learning, class-imbalance handling, image augmentation, Grad-CAM explainability, FastAPI, and a full web-based inference workflow.



Alongside AI/ML, I have hands-on software engineering and full-stack development experience using:

• Python

• C/C++

• JavaScript

• TypeScript

• React

• Next.js

• Node.js

• FastAPI

• PostgreSQL

• MongoDB

• REST APIs

• Docker

• Git/GitHub

• Vercel



I have built production-style applications involving authentication, role-based access control, APIs, databases, payment integrations, admin dashboards, cloud storage, automation, and deployment.



I also have experience working with IoT and embedded systems, giving me additional understanding of how software interacts with real-world devices and hardware.



My target opportunities:

- AI/ML Engineer

- Machine Learning Engineer

- AI Engineer

- Deep Learning / Computer Vision Engineer

- Software Development Engineer

- Full-Stack Software Engineer



I am especially interested in teams building practical AI products where machine learning, backend engineering, APIs, and modern application development work together.

---

## 🏆 Achievements

| Award | Date | Details |
|---|---|---|
| 🥇 **Winner — Smart Bihar Hackathon 2023** | May 2023 | 1st Prize for IoT EV Wireless Charging Monitor (ESP32 + Arduino + Blynk) |
| 🥈 **2nd Prize — World Youth Day 2023** | Jul 2023 | State-level innovation competition, Patna, Bihar |
| 🎓 **Academic Topper — Diploma** | 2021–2023 | 2nd Rank all three years, Government Polytechnic Banka — CGPA 8.96 |
| 💼 **Campus Placement** | 2026 | Selected as Software Developer Intern at Pashupatastra Solutions, New Delhi |

---

## 💼 Work Experience

### Software Developer Intern — Pashupatastra Solutions, New Delhi
*Jun 2026 – Present · Full-time (Campus Placement)*

Working as a Software Development Engineer with responsibilities across software engineering, Python development, IoT systems, embedded integration, automation, and product development.



Key responsibilities and work:

• Develop software and tools using Python, C/C++, and modern development technologies.

• Build Python-based automation, debugging, testing, and development utilities.

• Design and integrate APIs and application components for hardware-connected products.

• Work on communication between software applications and embedded devices.

• Develop and debug STM32 and Arduino-based systems.

• Work with UART, SPI, I²C, USB, and device communication protocols.

• Analyze hardware interfaces, evaluation boards, sensors, and PCB-level communication.

• Contribute across firmware, backend services, application software, testing, and deployment.

• Research AI/ML integration opportunities for intelligent software and connected-device products.

• Work across complete product-development lifecycle, from prototype and debugging to application integration.

### Data & Records Management Intern — Land Revenue Department, Bihar Government
*Dec 2025 – Jun 2026 · Patna, Bihar*

- 📊 Digitised and restructured **10,000+ legacy land records** into a queryable relational schema
- ✅ Achieved **100% data integrity** across migrated records with validation scripts
- ⚡ Improved data retrieval speed by an estimated **50%** across 11 Block-level workflows in Banka District 

### Arduino & Robotics Instructor (Freelance)
*Jul 2023 – Jun 2025 · 4 engagements across Bihar*

- 🎯 **90%+ project completion rate** among 300+ students
- 🏫 Taught at SVN Infra & Solar Services, TechGlaz Labs, NKB Infinity
- 🔧 Designed structured lab modules in Arduino programming, sensor integration, IoT prototyping

---

## 🚀 Featured Open Source Project

### [java-broadlink](https://github.com/Sushantku1099/java-broadlink) — Java SDK for Broadlink IoT Devices

[![Stars](https://img.shields.io/github/stars/Sushantku1099/java-broadlink?style=social)](https://github.com/Sushantku1099/java-broadlink)
[![Tests](https://img.shields.io/badge/tests-53%2F53_passing-brightgreen)](https://github.com/Sushantku1099/java-broadlink)
[![JDK](https://img.shields.io/badge/JDK-11%2B-blue)](https://github.com/Sushantku1099/java-broadlink)
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/Sushantku1099/java-broadlink)

A production-grade Java SDK for controlling **124 Broadlink IoT device types** across 19 categories — IR remotes, smart plugs, sensors, bulbs, thermostats, curtains, alarms, and hubs.

```
📱 Android · ☕ Spring Boot · 🖥️ Desktop Java · 🔷 Kotlin · ⚡ Zero Dependencies
```

- `broadlink-core` — **ZERO external dependencies**, runs on JDK 11+
- SPI pluggable architecture (Logger, JsonSerializer, NetworkProvider)
- Reverse-engineered proprietary UDP protocol with AES-128-CBC encryption
- 53 unit tests validating exact packet byte structures against reference implementation

```java
BroadlinkClient client = new BroadlinkClient();
List<BroadlinkDevice> devices = client.discover().get();
devices.get(0).authenticate().get();

if (device instanceof RmMiniDevice rm) {
    rm.enterLearning().get();
    byte[] irCode = rm.checkData().get();
    rm.sendData(irCode).get();
}
```

---

## 📂 Projects

### 🤖 AI / Machine Learning

| Project | Stack | Highlights |
|---|---|---|
| **[SafeSkinAI 2.0](https://github.com/Sushantku1099)** | Python, TensorFlow, Keras, DenseNet201, Inception V3 | Ensemble CNN classifying **7 skin disease categories** from dermoscopic images. Transfer learning + augmentation pipeline for clinical screening. |
| **SafeSkinAI 1.0** | Python, CNN, TensorFlow, Keras | Binary benign/malignant skin lesion classification. Established preprocessing pipeline for SafeSkinAI 2.0. |
| **[Breast Cancer Detection](https://github.com/Sushantku1099/Breast-Cancer-Detection)** | Python, Scikit-learn, Logistic Regression | **96.4% accuracy** classifier with ROC-AUC validation + interactive web interface for real-time tumour classification. |

### 🌐 Full Stack Web

| Project | Stack | Highlights |
|---|---|---|
| **Developer Portfolio & Marketplace** | Next.js 14, TypeScript, PostgreSQL, Prisma ORM, NextAuth, Razorpay, Cloudinary | Full-stack marketplace with RBAC, payment gateway, **50+ routes**, **13+ relational models**, PWA, SEO — production deployed. |
| **SVN Student Registration & Payment Portal** | Next.js, React, Node.js, MongoDB Atlas, JWT, Razorpay, Nodemailer | Production platform for SVN Infra & Solar. Admin dashboard with analytics + Excel export. Certificate validation system. JWT + bcrypt + HTTP-only cookie auth. |

### 🔌 IoT & Embedded Systems

| Project | Stack | Highlights |
|---|---|---|
| **[Smart EV Wireless Charging Monitor](https://github.com/Sushantku1099/Smart-Monitoring-WirelessChargingEVs)** | ESP32, Arduino UNO, Embedded C, Blynk | 🥇 **Winner — Smart Bihar Hackathon 2023**. Real-time energy tracking, grid integration, Blynk remote control. |
| **[Smart Home Automation](https://github.com/Sushantku1099/Smart-Home-Google-Alexa-NodeMCUArduino-SinricPro)** | Arduino, NodeMCU, Embedded C, SinricPro, Google Assistant API, Alexa | Multi-mode control (voice, IR, manual) — works online and offline. No costly smart hubs needed. |

---

## 🛠️ Technical Skills

### Languages & Frameworks

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded_C-555555?style=for-the-badge&logo=c&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)

### AI & Machine Learning

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### Backend & DevOps

![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### IoT & Embedded

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Blynk](https://img.shields.io/badge/Blynk-2AC08F?style=for-the-badge&logo=iot&logoColor=white)

### Cloud & Tools

![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📜 Certifications

| Certification | Issuer | Date |
|---|---|---|
| Oracle Cloud Infrastructure 2025 AI Foundations Associate | Oracle | Aug 2025 |
| CCNA: Enterprise Networking, Security & Automation | Cisco Networking Academy | May 2025 |
| CCNA: Switching, Routing & Wireless Essentials | Cisco Networking Academy | May 2025 |
| CCNA: Introduction to Networks | Cisco Networking Academy | May 2025 |
| Cybersecurity Essentials | Cisco Networking Academy | Jul 2023 |
| Python Essentials 1 & 2 | Cisco Networking Academy | May 2025 |
| Machine Learning | Internshala / Scholiverse Educare | Jan 2024 |
| Python for ML, Data Science & Web Dev | iHUB DivyaSampark, IIT Roorkee | Dec 2023 |
| Google IT Support Professional | Coursera | Oct 2022 |
| Full Stack Web Development | TechGlaz Labs | Jul 2025 |
| Electric Vehicles Part-1 | NPTEL | Jan 2023 |
| Arduino Certification | Spoken Tutorial, IIT Bombay | Sep 2022 |
| Salesforce Developer Virtual Internship | Salesforce | Dec 2023 |

---

## 🎓 Education

| Degree | Institution | Year | CGPA |
|---|---|---|---|
| **B.Tech — CSE (Artificial Intelligence)** | Purnea College of Engineering, Bihar Engineering University, Patna | 2023–2026 | **8.81** |
| **Diploma — Electronics Engineering** | Government Polytechnic Banka, SBTE Patna | 2020–2023 | **8.96** (2nd Rank) |
| **10th — Matriculation** | High School Marhianath, Banka, BSEB Patna | 2020 | **84.4%** |

---

## 📊 GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Sushantku1099&show_icons=true&theme=dark&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sushantku1099&layout=compact&theme=dark" />
</p>

---

## 🔗 Connect With Me

- 💼 **LinkedIn:** [linkedin.com/in/sushant-sagar-723b65338](https://www.linkedin.com/in/sushant-sagar-723b65338/)
- 💻 **GitHub:** [github.com/Sushantku1099](https://github.com/Sushantku1099)
- 📧 **Email:** sushant1892004@gmail.com
- 📞 **Phone:** +91-6207504908
- 📍 **Location:** Pawai Dih, Banka, Bihar — 813101

---

<p align="center">
  <i>Open to opportunities in Software Development, AI/ML Engineering, IoT & Embedded Systems, and Full Stack Development.</i>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sushantku1099&color=blue&style=flat-square" alt="Profile views" />
</p>
