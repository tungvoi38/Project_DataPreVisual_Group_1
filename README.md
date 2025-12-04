# 🧠 Project: Child Mind Institute - Data Storytelling

> **Topic:** Child Mental Health & Behavioral Data Analysis

## Overview 
The objective of this project is to develop a predictive model capable of analyzing children’s physical activity and fitness data to identify early indicators of unhealthy or problematic internet use. Detecting these behavioral patterns can facilitate timely interventions aimed at promoting healthier and more responsible digital habits.

## Description
In today’s digital era, uncontrolled or excessive Internet use among children and adolescents has emerged as an increasingly significant concern. Gaining a deeper understanding of this issue is essential for addressing associated mental health problems, including depression and anxiety.

Existing methods for assessing problematic internet use in young populations are often complex and reliant on professional evaluation. Such requirements create substantial barriers related to accessibility, culture, and language for many families. Consequently, problematic internet use is frequently not measured directly but instead inferred through correlated mental health issues such as anxiety and depressive symptoms.

In contrast, physical and fitness-related indicators are highly accessible, widely available, and typically require minimal clinical expertise. Behavioral and lifestyle changes—such as deteriorating posture, irregular eating patterns, and reduced levels of physical activity—are commonly observed among individuals who engage in excessive technology use. We propose leveraging these easily obtainable physical and fitness metrics as proxy indicators for identifying problematic internet use, particularly in contexts where clinical expertise or standardized assessment tools are unavailable.

This project aims to investigate and develop a predictive model capable of analyzing children’s physical activity data to detect early signs of unhealthy or uncontrolled internet and technology use. Such early detection would enable timely interventions that promote healthier and more responsible digital behaviors.

Ultimately, the project aspires to contribute to a healthier and more fulfilling future in which children are better equipped to navigate the digital landscape responsibly and sustainably.

## Dataset Description: Healthy Brain Network (HBN)

### Overview
The Healthy Brain Network (HBN) dataset constitutes a clinical cohort comprising approximately 5,000 individuals aged 5–22 years, who have undergone comprehensive clinical and research assessments.

The primary objective of the HBN initiative is to identify biological markers (biomarkers) to enhance the diagnosis and therapeutic intervention of psychiatric and learning disorders through an objective biological lens.

### Data Modalities
This project utilizes two distinct data modalities derived from the study:

* Physical Activity Data: Encompassing time-series data from wrist-worn accelerometers, fitness assessments, and self-reported questionnaires.
    
* Internet Usage Behavior Data: Metrics reflecting online activity patterns.

📂 Data Architecture
The competition data is aggregated from two primary sources:

Parquet Files: Containing time-series actigraphy (accelerometer) data.

CSV Files: Containing the remaining tabular phenotypic and behavioral data.

💡 Data Characteristics
High Sparsity: The dataset exhibits a significant degree of missingness, with a majority of measures absent for most participants.

Target Variable: Notably, the target variable, Severity Impairment Index (sii), is missing for a subset of subjects within the Training Set.

## 🎯 Project Objectives
This project is engineered to address the challenges associated with raw data processing and the extraction of valuable intelligence regarding child health and behavior. We have established four pivotal objectives:

1. Construct a Robust Data Preprocessing Pipeline
* The primary goal is to generate a clean, consistent dataset prepared for analytical rigor.

* Data Cleansing: Establish a systematic procedure to rigorously handle data imperfections, including the imputation of missing values, noise reduction, and the elimination of duplicate entries.

* Standardization & Transformation: Execute data reformatting, outlier detection and mitigation, and structural normalization to guarantee Data Integrity throughout the pipeline.

2. Exploratory Data Analysis (EDA) & Visualization
The goal is to transmute raw numerical data into interpretative visual models.

* Exploratory Data Analysis (EDA): Apply descriptive statistics to elucidate the underlying distribution and characteristics of the dataset.

* Data Visualization: Develop a comprehensive system of visual representations (Bar, Line, Scatter, Heatmap charts) to vividly illustrate key trends and multivariate correlations among variables.

3. Domain-Specific Insights (Health & Behavior)
* The goal is to derive empirical value from the data to support the domain context.

* Pattern Recognition: Identify and analyze associations between environmental factors, lifestyle habits, and the status of child health and behavioral development.

* Decision Support: Provide data-driven insights that serve as a reliable foundation for parents and researchers in making informed decisions.

4. Collaborative Workflow & Version Control
The goal is to simulate a professional software development environment.

* Version Control Management: Proficiently utilize Git & GitHub for source code management (SCM), version history tracking, and effective conflict resolution.

* Team Collaboration: Enhance proficiency in task distribution and the maintenance of clear, comprehensive Technical Documentation.

## 🛠️ Technologies & Tools

The project leverages a robust stack of open-source tools within the Python ecosystem:

| Category | Technologies |
| :--- | :--- |
| **Language** | ![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white) |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) |
| **Visualization** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-7db0bc?style=for-the-badge&logo=python&logoColor=white) |
| **Tools & VCs** | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) |

## 👥 Team Members

| No. | Name | Role |
| :---: | :--- | :--- |
| 1 | **[Vũ Bùi Đình Tùng]** | Leader |
| 2 | [Đoàn Tùng Lâm] |   
| 3 | [Trương Đức Anh] |
| 4 | [Thiều Diệu Thúy] | 
| 5 | [Bùi Thị Lan Anh] | 

---

# 🛠️ Installation & Setup

## 📋 Prerequisites

Before starting, ensure your machine has the following installed:

* **Python** (Version 3.8 or higher): [Download here](https://www.python.org/downloads/)
* **Git**: [Download here](https://git-scm.com/downloads)
* A Code Editor (VS Code, PyCharm, etc.)

## 🚀 Step-by-Step Installation

Follow these steps to run the project:

### 1. Clone the Repository

Open your Terminal (or Git Bash) and run the following command to download the source code:

```bash
git clone [https://github.com/tungvoi38/Project_DataPreVisual_Group_1.git](https://github.com/tungvoi38/Project_DataPreVisual_Group_1.git)
```

Then, navigate to the project directory:

```bash
cd Project_DataPreVisual_Group_1
```

### 2. Set Up Virtual Environment

It is recommended to use a virtual environment to avoid library conflicts:

```bash
# Create a virtual environment named 'venv'
python -m venv venv
```

**Activate the virtual environment:**

* **On Windows:**
    ```bash
    .\venv\Scripts\activate
    ```
* **On macOS / Linux:**
    ```bash
    source venv/bin/activate
    ```

### 3. Install Dependencies

Once the virtual environment is activated, install the required packages from `requirements.txt`:

```bash
pip install -r requirements.txt
```

> **Note:** If you encounter installation errors, try upgrading `pip` first: `python -m pip install --upgrade pip`

### 4. Run the Project

After installation, you can run: 
' đoạn này chưa biết'
---

## 🤝 Contributing

If you are a team member looking to update the code:

1. Create a new branch (`git checkout -b feature/New-Feature-Name`)
2. Commit your changes (`git commit -m 'Add feature X'`)
3. Push to the branch (`git push origin feature/New-Feature-Name`)
4. Create a Pull Request.
