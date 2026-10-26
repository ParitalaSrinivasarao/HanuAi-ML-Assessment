# HanuAI - ML Data Assessment & Validation

This project focuses on **ML Data Operations** for HanuAI, a multilingual AI assistant. The main goal is to prepare, validate, and document high-quality training data for ML models.

### 🎯 Project Objectives
- Curate and annotate multilingual text data (English, Hindi, Telugu)
- Perform data cleaning, validation, and quality audit
- Ensure data accuracy, consistency, and model-readiness

### 🛠️ Tools & Technologies Used
- **Python:** For data cleaning and validation scripts
- **MS Excel:** For data tracking, annotation, and reporting
- **Git & GitHub:** For version control and documentation
- **Data Handling:** Structured data handling in JSON/CSV format

### 📁 Dataset Details
- **Total Samples:** 500+ text samples
- **Categories:** Greetings, Cultural Stories (Hanuman related), General Queries
- **Labels:** Positive, Negative, Neutral, Informational
- **Format:** CSV / JSON

### ⚙️ Workflow
1.  **Data Collection:** Gathered raw text data via internet research
2.  **Data Annotation:** Labeled data manually with attention to detail
3.  **Data Cleaning:** Removed duplicates, noisy data, and incomplete records using Python
4.  **Data Validation:** Created validation script to check for formatting errors and inconsistencies
5.  **Documentation:** Documented all processes for future reference

### ✅ Quality Checks Performed
- Duplicate record removal
- Spelling and formatting validation
- Label consistency check
- Missing value identification

### 📊 Result
- Achieved 98% data accuracy after validation
- Created a clean, structured dataset ready for ML model training

### 🚀 How to Run
```bash
# Clone the repo
git clone https://github.com/ParitalaSrinivasarao/HanuAi-ML-Assessment.git

# Run validation script
python validate_data.py
