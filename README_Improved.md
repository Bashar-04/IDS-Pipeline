
## 🔐 Intrusion Detection System (IDS) Pipeline

### Overview
This project implements a robust, three-stage machine learning pipeline for network intrusion detection and attack classification. It is designed to enhance cybersecurity through accurate detection, modular design, and real-time analysis using the CICIDS2017 dataset.

### 🚀 Pipeline Stages
1. **Traffic Type Classification**
   - Multi-class classification of network traffic by protocol (e.g., DNS, FTP, HTTP).

2. **Suspicious vs. Benign Detection**
   - Binary classification to detect whether traffic is benign or potentially malicious.

3. **Attack Type Classification**
   - Multi-class classification to identify the exact type of malicious activity (e.g., DoS, Bot, Heartbleed).

### 🧠 Technologies & Models
- **Algorithms**: XGBoost, Random Forest
- **Interface**: Gradio GUI for interactive testing
- **Saved Models**: Stored as `.joblib` files for reuse

### 📁 Project Structure
- `Code(preprocessing+feature_selection+modeling).ipynb`: Data cleaning, feature engineering, and model training.
- `Code(Pipeline+GUI).ipynb`: Integrates the trained models into a pipeline and builds the GUI using Gradio.
- `*.joblib`: Pre-trained models for the three classification tasks.
- `README.md`: Project documentation and usage instructions.
- `Project_Schedule_IDS_Pipeline_4_Weeks.docx`: Timeline and task breakdown.
- `Dataset link.txt`: Source URL for CICIDS2017 dataset.

### 🛠️ How to Use
1. **Prepare Dataset**
   - Download from: https://www.unb.ca/cic/datasets/ids-2017.html
   - Clean and preprocess data using the provided notebook.

2. **Train Models**
   - Run the preprocessing notebook to generate and save trained models.

3. **Run Pipeline & GUI**
   - Launch `Code(Pipeline+GUI).ipynb` to start the interactive interface.

### 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion matrices and classification reports for model insights

### 📦 Dependencies
- Python 3.10
- pandas, numpy, matplotlib, seaborn
- scikit-learn, xgboost, joblib, gradio

### 📌 Team & Project Plan
- Project completed over 4 weeks with collaborative team roles.
- Details provided in `Project_Schedule_IDS_Pipeline_4_Weeks.docx`

---

### ✅ Future Improvements
- Integration with live traffic monitoring tools (e.g., Wireshark)
- Deployment to cloud platforms for scalable real-time protection
- More attack categories and ensemble model improvements

---

### 👨‍💻 Author
This project was created as part of an academic collaboration exploring real-world cybersecurity solutions through machine learning.
