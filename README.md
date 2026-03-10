🛡️ Financial Fraud Detection System
An End-to-End Machine Learning Solution for Real-Time Risk Assessment

📋 Project Summary
In the modern financial landscape, fraudulent transactions account for billions in annual losses. This project provides a scalable, automated solution to identify suspicious activity within massive datasets.

Using a dataset of over 6.3 million transactions, I developed a machine learning model that successfully identifies fraud with 94% accuracy. The project moves beyond static analysis by providing a live, interactive dashboard where stakeholders can input transaction data to receive an instant risk assessment.

🚀 Key Features
Predictive Intelligence: Leverages a Logistic Regression model optimized for "needle-in-a-haystack" detection in imbalanced data.

Automated Pipeline: Integrated Scikit-Learn pipelines ensure that raw data is scaled and encoded instantly without manual intervention.

Stakeholder Dashboard: A Streamlit-powered interface designed for non-technical users to verify transaction integrity on the fly.

Scalability: Tested on millions of records to ensure high performance and low latency during inference.

🛠️ Tech Stack
Language: Python 3.11

Modeling: Scikit-Learn (Pipelines, Logistic Regression, Standard Scaler)

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

App Framework: Streamlit

Deployment: Streamlit Cloud / GitHub

📊 Methodology & Performance:


Identifying fraud is challenging because 99.8% of transactions are legitimate. To solve this, I implemented:

Class Balancing: Adjusted model weights to prioritize catching the 13% of fraudulent cases.

Feature Selection: Analyzed transaction types, focusing on 'Transfer' and 'Cash Out' activities which showed the highest correlation with fraud.

Performance: The model maintains a high accuracy rate while minimizing "False Positives" to avoid disrupting legitimate customer experiences.


Data visualizations:

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/0633ed0d-69b3-4240-8b49-517649080326" />


<img width="691" height="531" alt="image" src="https://github.com/user-attachments/assets/7404fe0d-1ed1-46fc-898a-d77b7bf5e125" />


<img width="584" height="516" alt="image" src="https://github.com/user-attachments/assets/fde77bd8-e718-42bb-985d-dd38d920201b" />


<img width="597" height="455" alt="image" src="https://github.com/user-attachments/assets/c1f97231-4021-4403-88ce-2acd961ec6fa" />


<img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/6adda32a-5e51-48fe-9f59-9ab1dc4c4b9b" />


<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/dcfd0701-8601-4b95-b263-cbb691e0b099" />


<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/6cab0eb7-877f-4664-9207-b0a95ab9b8b8" />


<img width="616" height="537" alt="image" src="https://github.com/user-attachments/assets/1ba4cca4-b381-4a97-9fee-8f8b3c1e74f5" />


💻 How to Use the App
Access the live app here: http://192.168.1.16:8501


<img width="738" height="851" alt="image" src="https://github.com/user-attachments/assets/7c788b4e-a9fc-44ce-9299-60f04552a5e4" />


Select the Transaction Type.

Enter the Transaction Amount and the Account Balances.

Click Predict to see the system’s risk assessment.

Note: A prediction of "1" indicates a high-risk transaction that requires manual review, while "0" indicates a low-risk, legitimate transaction.
