# Global Cybersecurity Threats Analysis (2015-2024)

## Overview
This project performs an exploratory data analysis (EDA) on global cybersecurity threats recorded between 2015 and 2024. Using a dataset containing various attack parameters, this analysis aims to identify trends, common attack types, most vulnerable industries, and the effectiveness of different defense mechanisms.

## Dataset
* **File:** `Global_Cybersecurity_Threats_2015-2024.csv`
* **Source:** Kaggle
* **Content:** The dataset includes information such as:
    * `Country`: Country where the incident occurred.
    * `Year`: Year of the incident.
    * `Attack Type`: e.g., Phishing, Ransomware, DDoS, Malware, SQL Injection, Man-in-the-Middle.
    * `Target Industry`: e.g., Education, Retail, IT, Telecommunications, Banking, Government, Healthcare.
    * `Financial Loss (in Million $)`: Estimated financial impact.
    * `Number of Affected Users`: Count of individuals impacted.
    * `Attack Source`: e.g., Hacker Group, Nation-state, Insider, Unknown.
    * `Security Vulnerability Type`: e.g., Unpatched Software, Weak Passwords, Social Engineering, Zero-day.
    * `Defense Mechanism Used`: e.g., VPN, Antivirus, Firewall, AI-based Detection, Encryption.
    * `Incident Resolution Time (in Hours)`: Time taken to resolve the incident.

## Tools and Technologies
* **Programming Language:** Python
* **Libraries:**
    * `pandas` for data manipulation and analysis.
    * `matplotlib` for data visualization.
    * `seaborn` for enhanced data visualization.
    * `numpy` for numerical operations.
* **Environment:** Jupyter Notebook (`Cyber_Threats.ipynb`)

## Analysis and Methodology
The analysis proceeds through the following steps within the `Cyber_Threats.ipynb` notebook:
1.  **Data Loading and Initial Inspection:** Loading the CSV and examining its structure, data types, and missing values.
2.  **Data Cleaning:** Addressing any inconsistencies or preparing data for analysis (e.g., handling missing values, correcting formats).
3.  **Exploratory Data Analysis (EDA):**
    * Trends in attack types and financial losses over the years.
    * Distribution of attack sources and vulnerability types.
    * Identification of most frequently targeted industries.
    * Correlation between financial loss, affected users, and incident resolution time.
    * Effectiveness of different defense mechanisms.
4.  **Visualization:** Using various plots (bar charts, line plots, histograms, heatmaps) to illustrate findings.

## Key Findings (Examples - Update with your actual findings!)
* [Example]: Ransomware and Phishing attacks consistently represent a significant portion of threats.
* [Example]: The IT and Telecommunications industries are frequent targets due to their critical infrastructure and sensitive data.
* [Example]: Financial losses from cyberattacks show a [trend, e.g., increasing/decreasing/stable] over the analyzed period.
* [Example]: [Specific insight about defense mechanisms, e.g., "VPNs are widely used but show varying effectiveness depending on the attack type."].
* [Example]: [Any other interesting patterns or anomalies you found].

## How to Run the Notebook
To run this analysis on your local machine:
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/prathammehta23/Cyber_Threats_Analysis.git](https://github.com/prathammehta23/Cyber_Threats_Analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Cyber_Threats_Analysis
    ```
3.  **Install necessary Python libraries:**
    ```bash
    pip install pandas matplotlib seaborn numpy
    ```
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  Open `Cyber_Threats.ipynb` in your browser and run the cells.
