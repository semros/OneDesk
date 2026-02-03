**Project Overview**
OneDesk is a data science project developed using a mjor mobile service provider's customer service data to forecast how long a support ticket will remain in the system before resolution. The project combines exploratory data analysis, data preprocessing, and multiple machine learning regression models. Results are delivered through an interactive Streamlit dashboard for operational and managerial use.

The objective is to enable proactive workload planning, bottleneck detection, and service-level improvements.

**Business Objective**
Customer support teams manage thousands of tickets with varying complexity and resolution times. Accurately predicting ticket duration helps:
- Anticipate workload and staffing needs
- Detect potential delays early
- Improve SLA compliance
- Enhance customer experience

- **Project Components**
**1. Exploratory Data Analysis (EDA)**
- Resolution time distribution analysis
- Workload patterns by category, team, and priority
- Identification of outliers and abnormal delays
**2. Data Cleaning & Wrangling**
- Handling missing and inconsistent records
- Timestamp parsing and duration calculations
- Feature engineering (e.g., ticket age, category frequency, historical workload)
- Encoding categorical variables
- Creation of modeling-ready datasets
**3. Machine Learning Models (Regression)**
 Multiple regression algorithms were trained and compared to forecast ticket resolution duration:
 - Linear Regression 
 - XGBoost Regressor
 - CatBoost Regressor
*Evaluation Metrics:*
 - MAE (Mean Absolute Error)
 - RMSE (Root Mean Squared Error)
 - R² Score
 - Cross-validation for model robustness
**4. Dashboard Application**
An interactive **Streamlit** dashboard enables non-technical stakeholders to:
- Monitor ticket trends and workload
- Explore drivers of long resolution times
- Visualize model predictions
- Test “what-if” scenarios

**Tech Stack**
| Area             | Tools & Libraries           |
| ---------------- | --------------------------- |
| Programming      | Python                      |
| Data Processing  | Pandas, NumPy               |
| Visualization    | Matplotlib, Seaborn, Plotly |
| Machine Learning | Scikit-learn, XGBoost       |
| App Framework    | Streamlit                   |
| Version Control  | Git, GitHub                 |

**Project Structure**
OneDesk/
│
├── data/                # Sample or anonymized datasets
├── notebooks/           # EDA and experimentation notebooks
├── src/                 # Data processing and modeling scripts
├── models/              # Saved trained models
├── app/                 # Streamlit dashboard app
├── requirements.txt     # Dependencies
└── README.md

**Key Outcomes**
- Built predictive models to estimate ticket resolution duration
- Identified key operational drivers behind delays
- Delivered a decision-support dashboard for proactive service management

**Future Improvements**
- Hyperparameter optimization and ensemble modeling
- Real-time prediction integration
- Automated model retraining pipeline
-- Deployment to a cloud environment

**Disclaimer**
This repository contains an adapted version of a real-world project. All sensitive or proprietary data has been anonymized or removed.
