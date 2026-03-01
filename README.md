**Behavioural Impulse Risk Detection System**

**Description**
Impulsive financial behaviour is a a common challenge for individuals managing personal finances.
This project develops a behavioural analytics system that detects impulsive spending patterns using machine learning.

The system analyzes transaction behaviour such as:
- Spending deviation from personal baseline
- Transaction timing
- Weekend activity
- Recent spending patterns

Based on these behavioural signals, the system predicts impulsive transactions and generates an Impulse Risk Score (0–100).
The project also provides behavioural insights, user segmentation, and financial recommendations to improve financial decision‑making.

**Features**
- Behavioural feature engineering for financial transactions
- Machine learning models for impulse prediction
- Impulse Risk Score generation
- Behavioural persona clustering
- Explainable AI using SHAP
- Behavioural recommendation engine
- Data visualizations for behavioural insights

Installation
Requirements:
Python 3.8 or higher

Required libraries:
pandas
numpy
scikit-learn
xgboost
lightgbm
catboost
matplotlib
shap

**Install dependencies:**
pip install pandas numpy scikit-learn xgboost lightgbm catboost matplotlib shap

Usage
1. Clone the repository:
git clone https://github.com/AbishekBalaji12/behavioural_impulse_risk_detection.git

2. Navigate to the project directory:
cd behavioural_impulse_risk_detection

3. Launch Jupyter Notebook:
jupyter notebook

4. Open the notebook:
Behavioral_Analytics_Hackathon.ipynb

Run all cells sequentially.

**Example Output**
The system generates:
User 45 – Risk Score 82 – Enable spending alerts
User 17 – Risk Score 55 – Monitor late‑night purchases
User 9 – Risk Score 18 – Normal spending behaviour

**Dataset**
The dataset used in this project is synthetically generated to simulate realistic behavioural spending patterns.
Features include:
1.Transaction timing
2.Spending deviation
3.Rolling spending behaviour
4.Weekend activity
5.Behavioural impulse indicators
Synthetic data was used because no publicly available dataset exists for impulsive financial behaviour detection.

**Behavioural Insights**
Key behavioural patterns identified:
- Late‑night transactions show higher impulse probability
- Weekend spending increases impulsive behaviour
- Spending deviations from personal baseline strongly indicate impulse behaviour

**Support**
GitHub Issues:
https://github.com/AbishekBalaji12/behavioural_impulse_risk_detection/issues

**Email:**
iamabishek1204@gmail.com

**Roadmap**
Future improvements may include:
- Integration with real financial datasets
- Real‑time transaction monitoring
- Mobile financial alert systems
- Deep learning models for behavioural prediction
- API deployment for fintech applications

**Contributing:**
Contributions are welcome.
To contribute:
Fork the repository
Create a feature branch
Submit a pull request
Please ensure that code changes maintain readability and include documentation.

**Author**
Abishek Balaji
VIT Chennai

**License**
This project is intended for educational and research purposes with proper attribution.

**Project Status**
Active development for hackathon submission.
Future improvements may include real-world dataset integration and deployment as a behavioural analytics tool for financial applications.
