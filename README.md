# This is a Django Project where we built Full-Stack Application which will classify by radiation with SVM
BugsOut Systems – Radiation Intelligence Platform
📌 Overview
BugsOut Systems is a Django-based web application that integrates Support Vector Machine (SVM) models to classify radiation signals.
The platform ensures data integrity for satellite and medical applications by distinguishing high-energy Gamma signals from Hadronic background noise using a 10-feature sensor array.

✨ Features
- Secure web interface for radiation data input and analysis
- Real-time classification powered by SVM with non-linear decision boundaries
- Audit logs for system scans and hardware status monitoring
- Modular Django backend for scalability and maintainability

🏗️ Architecture
- Frontend: Django templates with Bootstrap for UI
- Backend: Django REST Framework for APIs
- Machine Learning: SVM model trained on radiation datasets
- Database: PostgreSQL (production) or SQLite (development)
- Deployment: Gunicorn + Nginx (production-ready), Docker optional

⚙️ Installation
- Clone the repository
- Set up a Python virtual environment
- Install dependencies from requirements.txt
- Apply Django migrations
- Run the development server

📡 Usage
- Access the web interface at http://127.0.0.1:8000/
- Input or upload 10-feature sensor array data
- Run System Scan to classify signals
- Review results in Audit Logs and Hardware Status

🧠 Machine Learning
- Algorithm: Support Vector Machine (SVM) with RBF kernel
- Features: 10 geometric radiation features (energy, angle, frequency, etc.)
- Output: Binary classification → Gamma Identified or Hadronic Noise

![output1](https://github.com/user-attachments/assets/c7bbdd90-6d86-4083-bafd-cdc06fed98b4)
![output2](https://github.com/user-attachments/assets/e36bcb65-2f38-46a0-bf8a-13726e26bea1)
![output3](https://github.com/user-attachments/assets/22bb3fb1-957d-4f01-92d4-350876111834)


