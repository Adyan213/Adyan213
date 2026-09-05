# Hi, I'm Adyan Mukadam 👋

I'm a Computer Science student at Pillai College of Engineering specializing in Biomedical Machine Learning, Medical Imaging AI, and Clinical Data Science. My work spans clinical risk prediction and medical image analysis using real-world healthcare datasets, including MIMIC-IV electronic health records and NIH ChestX-ray14 radiographs. I focus on building interpretable AI systems that combine strong predictive performance with clinically meaningful explanations through techniques such as SHAP and Grad-CAM.

Currently building toward graduate school opportunities in Biomedical ML, Health Informatics, and Medical AI.

---

### 🛠️ Tech Stack

*   **Languages:** Python, SQL, JavaScript (ES6+), C
*   **ML & Deep Learning:** PyTorch, Scikit-Learn, XGBoost, TensorFlow, SHAP, torchvision
*   **Medical Imaging & Vision:** OpenCV, Grad-CAM (Interpretability Frameworks)
*   **Data & Infrastructure:** Google BigQuery, SQLite, Pandas, NumPy, Git/GitHub

---

### 🩺 Biomedical Machine Learning Projects

#### ChestX-ray14 Multi-Label Disease Classification

- **Overview:** Built an interpretable deep learning pipeline for automated thoracic disease detection using the NIH ChestX-ray14 dataset (112,120 chest radiographs, 14 disease labels).
- **Architecture:** Fine-tuned an ImageNet-pretrained DenseNet121 with staged transfer learning (frozen backbone → differential learning rates → full fine-tuning).
- **Clinical Interpretability:** Implemented Grad-CAM from scratch to visualize disease-specific attention maps and investigate failure cases, false positives, and false negatives.
- **Research Contribution:** Conducted an ablation study on class imbalance mitigation using weighted BCE loss and showed that performance bottlenecks for Pneumonia and Infiltration are driven more by visual ambiguity than label frequency.
- **Metrics:** **Macro AUROC: 0.788** across 14 thoracic disease classes on the official NIH test split.
- [📁 Repository](https://github.com/Adyan213/Chest-X-Ray14-Classification)

#### **MIMIC-IV ICU Mortality Prediction**
*   **Overview:** Developed an in-hospital mortality prediction pipeline using real-world, restricted-access electronic health records (EHR).
*   **Engineering:** Built complex data extraction pipelines via SQL on Google BigQuery, joining 8+ relational clinical tables to aggregate patient vitals, labs, and demographics.
*   **Modeling & Interpretability:** Evaluated XGBoost models optimized with SHAP framework to provide feature-level clinical explanations for ICU mortality risk.
*   **Metrics:** **AUC-ROC: 0.918** | *Credentialed PhysioNet Access*
*   [📁 Repository](https://github.com/Adyan213/mimic-iv-mortality-prediction)

#### **Chest X-Ray Pneumonia Classification**
*   **Overview:** End-to-end deep learning pipeline for binary classification of chest radiographs (Normal vs. Pneumonia).
*   **Architecture:** Benchmarked a custom CNN architecture against a DenseNet121 transfer learning pipeline in PyTorch.
*   **Clinical Interpretability:** Implemented a from-scratch Grad-CAM localization layer to map model activations directly onto anatomical regions, providing visual verification for clinicians.
*   **Metrics:** **AUC-ROC: 0.941** | **Macro F1: 0.87**
*   [📁 Repository](https://github.com/Adyan213/Chest-X-Ray-Pneumonia-Classification)

#### **WiDS Datathon ICU Mortality Prediction**
*   **Overview:** Predictive modeling on a large-scale dataset of 91,713 ICU patient records to analyze feature dependency.
*   **Key Insight:** Proved through iterative baseline comparisons (Logistic Regression vs. XGBoost) that removing pre-computed clinical severity scores did not degrade model performance, highlighting the robustness of raw physiological features.
*   **Metrics:** **AUC-ROC: 0.900** | **Macro F1: 0.71**
*   [📁 Repository](https://github.com/Adyan213/WiDS-Datathon-2020-Mortality-Prediction)

---

### 🚀 Data Engineering & Core Software Projects

#### **Indian Food Nutrition Analysis Dashboard**
*   **Tech:** Python, Streamlit, SQLite
*    Engineered a custom data ingestion pipeline to parse, clean, and migrate nutritional datasets from CSV into a structured SQLite database. Built an interactive Streamlit application to track daily nutritional targets.
*   [📁 Repository](https://github.com/Adyan213/Indian-Food-Nutrition-Analysis)

#### **FIFA World Cup 2026 Simulation Framework**
*   **Tech:** XGBoost, Deep NN, Python
*   Developed a dual-engine classification core featuring a 1,000x Monte Carlo simulation loop to evaluate performance distributions and outcomes post-tournament.
*   [🔗 Live App](https://fifa-world-cup-2026-predictor-mtu3qnzrb2wgk3nbecwwko.streamlit.app/) | [📁 Repository](https://github.com/Adyan213/FIFA-World-Cup-2026-Predictor)

#### **GeneLife — Algorithmic Medical Report Generator**
*   **Tech:** JavaScript (ES6+)
*   Built a lightweight, client-side rule-engine designed to parse user metrics and dynamically generate personalized preventative health risk assessments.
*   [📁 Repository](https://github.com/Adyan213/GeneLife)

---

### 📬 Connect with Me

*   **LinkedIn:** [adyan-mukadam](https://www.linkedin.com/in/adyan-mukadam-44011a375/)
*   **GitHub:** [Adyan213](https://github.com/Adyan213)
