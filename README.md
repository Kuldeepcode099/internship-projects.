Project 1: Cybersecurity – Suspicious Web Threat Interactions

This project was part of my internship where I worked on analyzing web traffic data to detect suspicious and potentially harmful interactions. The dataset was collected from AWS CloudWatch logs and included information such as source and destination IPs, ports, countries, number of bytes transmitted, and detection rule names.

I started with data cleaning and preprocessing, where I handled missing values, removed duplicates, and converted time columns into a usable format. After that, I performed feature engineering by creating new columns like session duration, average packet size, and throughput. I also created a binary label (is_suspicious) to separate normal traffic from suspicious activities.

To understand the dataset better, I did Exploratory Data Analysis (EDA). I plotted distributions of bytes in/out, checked protocol and port usage, visualized traffic from different countries, and studied time-series patterns. I also created a correlation heatmap and a small sample network graph to visualize connections between IPs.

For the modeling part, I used both unsupervised and supervised learning. I applied Isolation Forest and Local Outlier Factor for anomaly detection. For classification, I trained RandomForest and also experimented with Neural Networks like MLP and Conv1D.

Finally, I evaluated the models using accuracy, precision, recall, F1-score, and ROC-AUC. The RandomForest model gave more than 90% accuracy, while the anomaly detection models helped highlight unusual patterns in the traffic. I also saved the trained models and built a small scoring function to make the project deployment-ready.

This project gave me practical exposure to handling cybersecurity datasets and applying machine learning techniques to detect suspicious web threats.
