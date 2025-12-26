# piamarinaMedici_porfolio
# MandaCare: Intelligent Complaint Analysis System
### Capstone Project 2025 | Mandaluyong City Health Department

![Status](https://img.shields.io/badge/Status-Completed-success)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Laravel](https://img.shields.io/badge/Laravel-Framework-red)
![ML](https://img.shields.io/badge/AI-NLP%20%26%20ML-orange)

## 📖 Overview

**MandaCare** is a web-based complaint analysis system developed for the **Mandaluyong City Health Department (CHD)**. It automates the processing, categorization, and prioritization of citizen complaints to assist the Public Information Office (PIO).

In an era where digital technology is pivotal for public service efficiency, MandaCare addresses the limitations of outdated feedback mechanisms by integrating **Natural Language Processing (NLP)**, **Machine Learning**, and **Prescriptive Analytics**.

## 🚀 Key Features

* **Automated Categorization:** Utilizes unsupervised clustering to sort complaints into 15 validated categories.
* **Urgency Detection:** Applies a fine-tuned multilingual Sentiment Analysis model to determine the urgency of a complaint and assign priority automatically.
* **Prescriptive Analytics:** An intelligent engine that generates solution-oriented recommendations (prescriptions) based on the specific category and priority level of the issue.
* **Admin Dashboard:** A comprehensive interface for administrators to view trends, monitor real-time statistics, and export detailed reports for official documentation.

## 🛠️ Tech Stack

**Machine Learning & NLP (Backend)**
* **Language:** Python
* **Framework:** Flask
* **Techniques:** Ensemble Learning (Selected over Logistic Regression, Random Forest, and SVM), Unsupervised Clustering, Sentiment Analysis.

**Web Development**
* **Framework:** Laravel (PHP)
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
* **Database:** MySQL

## 🧠 Methodology & Algorithms

The development followed a **Modified Waterfall SDLC**. The core intelligence of the system relies on advanced data processing:

1.  **Clustering:** Used to identify distinct complaint categories from raw, unstructured text.
2.  **Supervised Learning:** After evaluating four models, the **Ensemble Model** was deployed for its balanced and reliable performance in classifying new complaints.
3.  **Prescription:** A lookup-based prescriptive logic derived from historical data to suggest immediate courses of action.

## 📊 System Architecture

The system is designed to handle data flow between Citizens, the Barangay, and the City Health Department.

* **User Flow:** Citizens submit unstructured complaints → System analyzes text → System routes to dashboard with priority tags.
* **Evaluation:** The system was evaluated using **ISO 25010:2023**, receiving high ratings for Functional Suitability, Reliability, Security, and Interaction Capability.

## 📦 Installation & Setup

_Note: This project requires both a Python environment (for ML) and a PHP environment (for the Web App)._

### Prerequisites
* Python 3.8+
* PHP 8.x / Composer
* MySQL

### Steps
1.  **Clone the repository**
    ```bash
    git clone [https://github.com/piamarinamedici739-lgtm/mandacare.git](https://github.com/piamarinamedici739-lgtm/mandacare.git)
    ```

2.  **Setup Python (ML Service)**
    ```bash
    cd ml-service
    pip install -r requirements.txt
    python app.py
    ```

3.  **Setup Laravel (Web App)**
    ```bash
    cd web-app
    composer install
    cp .env.example .env
    php artisan key:generate
    php artisan migrate
    php artisan serve
    ```

## 📄 License

This project is a Capstone requirement and is the intellectual property of **Pia Marina Medici//IntelligenZ Group** and the **Mandaluyong City Health Department**.

## 👩‍💻 Author

**Pia Marina Medici**
* **Role:** Lead Machine Learning and UI/UX Developer / Researcher
* **Connect:** [LinkedIn](https://www.linkedin.com/in/pia-marina-medici-a86443399)
