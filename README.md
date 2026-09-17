# 👋 Hi, I'm Muhammad Shahmir Zaman

**AI / Machine Learning Engineer — Computer Vision, LLM & RAG Systems**

AI/ML Engineer with hands-on experience developing and deploying computer vision and LLM-based solutions. I build YOLO-based detection and pose-estimation systems for retail analytics, driver safety, and surveillance, and RAG applications using FastAPI, LangGraph, and Qdrant. I'm familiar with integrating AI agents into production workflows and turning AI models into practical, real-world solutions.

---

## 💼 Experience

### AI Software Engineer — QBS Co *(Sep 2025 – Present)*

- Built a YOLO-based customer density recognition system for retail surveillance, identifying high-traffic shelves and racks for merchandising decisions (~92% accuracy), plus parking dwell-time detection (~94% precision) using YOLO and OpenCV.
- Fine-tuned YOLO-based pose-estimation models with contrastive learning for human-behavior analysis, shipping 4 production computer vision models: driver drowsiness detection via blink tracking, safety-gear compliance detection, fabric defect detection, and video synopsis for CCTV theft identification.
- Deployed CV inference services as gRPC microservices, cutting average response latency by ~35% versus the prior REST setup while supporting concurrent requests.
- Migrated a face recognition and landmark inference service from a heavyweight CUDA container to a lightweight Python base image, cutting image size by ~60% and cold-start latency by ~40%; automated ML training workflows with Lightning AI, reducing pipeline setup time by ~30%.
- Built a 3D object reconstruction pipeline from monocular video, generating point clouds and reconstructing surface meshes; contributed to drone hardware integration, including flight-controller setup, power distribution board design, and onboard compute deployment on an NVIDIA Jetson Orin Nano.
- Built a full OCR model conversion and deployment pipeline (PaddleOCR → ONNX → NCNN), achieving ~2x faster inference than the original PaddleOCR runtime.

### AI Engineer — Intelik *(Jun 2025 – Sep 2025)*

- Delivered OCR (~95% accuracy) and LayoutLMv3-powered document intelligence pipelines for enterprise clients, combining image preprocessing with model inference to extract structured data from semi-structured documents, cutting manual data-entry effort by ~70%.
- Partnered directly with client stakeholders to scope requirements.

---

## 🔧 Technical Skills

**Programming:** Python, SQL, C, C++

**AI / Machine Learning:** Deep Learning, NLP, Model Fine-Tuning, PyTorch, TensorFlow, Scikit-learn, Hugging Face, Lightning AI

**Computer Vision:** Object Detection, YOLO, Instance Segmentation, Multi-Object Tracking, Pose Estimation, 3D Reconstruction, Point Cloud Processing, OCR

**Agentic AI:** LangChain, LangGraph, RAG, CrewAI, Prompt Engineering

**Backend & Infra:** FastAPI, gRPC Microservices, Celery, Redis, PostgreSQL, Qdrant (Vector DB), Docker, MLOps, AWS (EC2, S3, VPC, ECS), Git

---

## 🚀 Featured Projects

### [Multi-Tenant Legal Document RAG System](https://github.com/muhammadshahmirzaman/Multi-tenant-legal-document-RAG-system)
Multi-tenant RAG system for legal document Q&A (FastAPI, LangGraph, Qdrant, PostgreSQL, Redis, Celery) with isolated per-tenant retrieval pipelines and asynchronous task orchestration for concurrent document ingestion, embedding, and retrieval without cross-tenant data leakage.

### Real-Time Abandoned Object Detection & Tracking
Production-ready object detection system combining YOLO-based object detection with background subtraction, achieving ~90%+ detection accuracy on unattended items in complex indoor environments. Designed a hybrid centroid-based tracking algorithm using IoU and distance metrics with a five-state ownership classifier to associate objects with people across frames, reducing false-positive alerts. Exposed as a Python gRPC service with bidirectional frame streaming and isolated per-stream session state for concurrent multi-camera inference.

### [Alzheimer's Detection Using MRI Images](https://github.com/muhammadshahmirzaman/Alzheimer-detection-using-MRI-images) *(Final Year Project, 2024–2025)*
Supervised by Dr. Nasir ud Din (FAST-NUCES). Led a 3-member research team building a deep learning classification pipeline on 5,000+ structural MRI scans. Applied Kernel PCA for feature compression, reducing computational complexity by ~65% while preserving 98% of cumulative variance. Achieved a baseline of 0.723 AUC-ROC with a custom CNN.

### [Text Summarizer Using Transformers](https://github.com/muhammadshahmirzaman/Text_Summarizer)
Fine-tuned T5-base on the CNN/DailyMail corpus for abstractive summarization, benchmarked using ROUGE-L.

### [End-to-End MLOps Pipeline](https://github.com/muhammadshahmirzaman/end-to-end-MLOPS)
End-to-end machine learning pipeline covering data ingestion, training, and deployment with reproducible MLOps practices.

### [Django Research Assistant](https://github.com/muhammadshahmirzaman/Django_research_assistant)
Django-based research assistant application.

---

## 🎓 Education

**Bachelor of Science in Computer Science** — FAST-NUCES, Karachi, Pakistan *(2021 – 2025)*
Relevant coursework: Artificial Intelligence, Computer Vision, Natural Language Processing, Data Science, Database Systems, DevOps, Marketing Management.

---

## 📜 Certifications

- **Foundations of Data Science** — Coursera / Google (2024)

---

## 📊 GitHub Stats

![Muhammad's GitHub Stats](https://github-readme-stats.vercel.app/api?username=muhammadshahmirzaman&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadshahmirzaman&layout=compact&theme=radical)

---

## 🌐 Let's Connect

- 📧 [shahmirmuhammad3@gmail.com](mailto:shahmirmuhammad3@gmail.com)
- 💼 [linkedin.com/in/muhammad-shahmir-zaman](https://linkedin.com/in/muhammad-shahmir-zaman)
- 🐙 [github.com/muhammadshahmirzaman](https://github.com/muhammadshahmirzaman)
