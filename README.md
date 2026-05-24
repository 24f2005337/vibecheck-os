# VibeCheck OS 🧠 | AI-Driven Mental Analytics SaaS Dashboard

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
[![Live Demo](https://img.shields.io/badge/%F0%9F%9A%80-LIVE%20DEMO-21262d?style=for-the-badge&logoColor=white)](https://github.com/24f2005337/vibecheck-os)

An academic, industry-grade Full-Stack Machine Learning web application designed to track and analyze daily subconscious cognitive states using Natural Language Processing (NLP). Moving away from rudimentary API reliance, this architecture implements an end-to-end local ML pipeline paired with a responsive, glassmorphic Bento Box UX.

## 🚀 Core Production Features
* **Custom Machine Learning Inference:** Implements a locally trained **Multinomial Naive Bayes Classifier** via `scikit-learn` to categorize emotional states.
* **TF-IDF Feature Space Mapping:** Text feeds are mathematically processed into multi-dimensional feature vectors in real-time.
* **Continuous Range Float Probabilities:** Computes precise probability confidence scores (`predict_proba`) mapping precise energy variations ($0\%$ to $100\%$) rather than hardcoded integer categories.
* **Dynamic Structural UI Transitions:** The entire frontend template automatically switches theme properties (e.g., Deep Crimson for heavy cognitive strain, Cyber Teal for peak performance states) instantly based on mathematical output states.
* **Persistent Analytics Vector Grid:** Leverages `Flask-SQLAlchemy` & `SQLite` to store state logs, maintaining tracking mechanisms like a 30-Day Matrix Spectrum, Gamified Badges, and Statistical Breakdown Report metrics.
* **Data Portability Hub:** Integrated Multi-Channel Social Sharing (X, LinkedIn, WhatsApp) and full journal log data extraction as `.txt` manifests.

## 🛠️ System Architecture & Tech Stack
* **Backend Framework:** Python / Flask
* **Machine Learning Engine:** Scikit-Learn, NumPy, SciPy
* **Database Layer:** SQLite, Flask-SQLAlchemy
* **Frontend Matrix UI:** Vanilla HTML5, CSS3 (Modern Bento Box Architecture, Advanced CSS Grid, Glassmorphic Layering)