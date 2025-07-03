# log-anomaly-detector
A Python-based system for detecting anomalies in log files using machine learning
📘 Log-Based Anomaly Detection System
🔍 Overview
This project is a Python-based system for detecting anomalies in log files using machine learning. It helps identify suspicious patterns, failed login attempts, or irregular access behavior—making it useful for SOC environments and threat hunting.

💡 Project Highlights
Uses Isolation Forest for unsupervised anomaly detection

Preprocesses log files to extract meaningful features

Flags events based on deviation from normal behavior

Built with readability and modularity for easy improvement

🛠️ Tools & Libraries
Python

Pandas

scikit-learn

Matplotlib (optional for visualization)

📁 Folder Structure
log-anomaly-detector/
├── data/
│   └── sample_logs.csv
├── src/
│   └── detector.py
├── notebooks/
│   └── anomaly_detection.ipynb
├── README.md
├── requirements.txt
└── LICENSE
🚀 How to Run
Clone the repo

bash
git clone https://github.com/VascoSh0t/log-anomaly-detector.git
cd log-anomaly-detector
Install dependencies

bash
pip install -r requirements.txt
Run the detector

bash
python src/detector.py
View results

Anomalous log entries will be printed to your terminal

For visualization, use the notebook in /notebooks

📊 Sample Output
Hour	Status	Anomaly
02	Fail	-1
03	Fail	-1
Note: -1 indicates an anomaly detected.

✨ Future Improvements
Add support for multiple log formats (syslog, JSON)

Integrate visualization dashboards

Use advanced ML models (One-Class SVM, Autoencoders)

Build a real-time log monitoring pipeline

📄 License
Licensed under the MIT License. Feel free to use and improve!
