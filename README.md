# AI Deployment Pipeline for Renal Mass Management
This project integrates a pre-trained AI pipeline that combines tumor segmentation and classification to assist clinicians in renal tumor diagnosis. The segmentation model extracts tumor regions from CT images, which are then processed by a classification model to determine whether the tumor is Benign, Malignant-Indolent, or Malignant-Aggressive.

The system is deployed using Django REST Framework and FastAPI, with a React/Vue.js frontend for an intuitive clinical workflow. Docker and Kubernetes enable scalable deployment, ensuring seamless integration into real-world clinical environments.

## Overview
This project integrates two pre-trained AI models into a Django REST API and a React/Vue.js frontend, allowing clinicians to classify renal tumors from medical imaging data. The model is deployed via Docker & Kubernetes for scalability and real-world clinical application.

Key Features:
- AI Model Integration – Uses self-supervised learning (SimCLR) to extract features and classify tumors.
- Web Interface for Clinicians – Upload CT images, receive model predictions, and provide feedback.
✅ Scalable Backend (Django REST API + FastAPI) – Serves AI predictions efficiently.
✅ Frontend (React/Vue.js) – Displays results, confidence scores, and visualization tools.
✅ Containerized Deployment – Uses Docker & Kubernetes for easy scalability and cloud integration.
