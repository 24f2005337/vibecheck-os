# VibeCheck OS 🧠 | AI-Driven Mental Analytics SaaS Dashboard

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