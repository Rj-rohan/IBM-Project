# IBM-Project

Power System Fault Detection and Classification
📌 Overview
This project focuses on detecting and classifying faults in modern power distribution systems using machine learning and IBM Cloud services.
It aims to improve grid reliability, reduce downtime, and enhance operational efficiency by identifying Line-to-Ground, Line-to-Line, and Three-Phase faults from electrical measurement data.

📜 Problem Statement
Modern power distribution systems require timely and accurate fault detection to ensure reliability and safety. Faults such as:

Line-to-Ground

Line-to-Line

Three-Phase faults

… can disrupt power supply, damage equipment, and compromise grid stability.
The challenge is to detect and classify these faults using voltage and current phasor data efficiently.

💡 Proposed Solution
The solution applies data analytics and machine learning techniques to classify power system faults in real-time.

Key Components
Data Collection

Gather historical and simulated voltage/current phasor data for normal and fault conditions.

Data Preprocessing

Handle missing values, noise, and inconsistencies.

Feature engineering for magnitude, angle, frequency components, etc.

Machine Learning

Supervised learning algorithms (Random Forest, SVM, ANN).

Performance evaluation using accuracy, precision, recall, and F1-score.

🛠 Technology Stack
Platform: IBM Cloud Lite

Services: IBM Watson Studio, IBM Watson Machine Learning

Libraries:

ibm-watson-machine-learning

pandas

numpy

⚙️ Algorithm & Deployment
Algorithm: Random Forest Classifier

Handles non-linear patterns and high-dimensional data.

Robust to noise and reduces overfitting.

Features:

Voltage & current phasors (magnitude, angle).

Derived electrical quantities (phase difference, symmetrical components).

Labels:

Normal

Line-to-Ground Fault

Line-to-Line Fault

Three-Phase Fault

Deployment:

Model deployed on IBM Cloud for real-time fault detection via API.

📊 Results
Accuracy: 97.8%

Metrics: High Precision/Recall/F1-score across all fault types.

Observations:

Strong classification performance.

Especially accurate in differentiating Line-to-Ground and Line-to-Line faults.

✅ Conclusion
Developed a robust ML model for power system fault classification.

Enabled real-time detection using IBM Cloud services.

Improved fault response times and overall system reliability.

🚀 Future Scope
Integrate real-time streaming data from smart grids via IBM IoT.

Explore deep learning (e.g., LSTM) for predictive fault detection.

Scale to multi-node, multi-region power systems.

Implement self-healing grids with automated recovery.

📚 References
Kaggle Dataset: Power System Faults Dataset

IBM Cloud Lite

IBM Watson Studio

IBM Watson Machine Learning Docs
