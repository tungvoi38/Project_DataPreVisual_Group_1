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
Key steps include:
1.  **Data Cleaning:** Handling missing data, noise, and reformatting structures.
2.  **Exploratory Data Analysis (EDA):** Investigating data distribution characteristics.
3.  **Visualization:** Building charts to illustrate correlations between various factors.

## 🎯 Objectives

* ✅ Build an effective Data Preprocessing pipeline.
* ✅ Visualize data clearly to support decision-making.
* ✅ Detect patterns related to child health and behavior.
* ✅ Practice teamwork and source code management with Git.

Key steps include:
1.  **Data Cleaning:** Handling missing data, noise, and reformatting structures.
2.  **Exploratory Data Analysis (EDA):** Investigating data distribution characteristics.
3.  **Visualization:** Building charts to illustrate correlations between various factors.

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Data Processing:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Tools:** Jupyter Notebook / VS Code

## 💡 Our Approach

To address the challenges of this dataset, our team applied the following process:

1.  **Data Cleaning Strategy:**
    * Handling missing values using specific methods (e.g., Interpolation / Mean Imputation).
    * Removing outliers and normalizing time-series data formats.

2.  **Analysis & Visualization Techniques:**
    * Using **Correlation Heatmaps** to detect relationships between behavioral indicators.
    * Using **Time-series Charts** to track trends over time.
    * Applying **Distribution plots** to assess data skewness.

3.  **Deriving Insights:**
    * Synthesizing key findings from charts to draw conclusions on specific behaviors (e.g., sleep habits, internet usage).

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
