# Natural-Disaster-Prediction-and-Management
NDPM description
 Project: Flood Prediction and Alert System
This is a Python-based project I developed to predict the likelihood of flooding using basic environmental data inputs such as rainfall, water level, and soil moisture. The goal was to create a simple but effective early warning system that can assist in disaster management and response.

🔍 What It Does:
Trains a Random Forest Classifier on a small dataset to distinguish between flood and non-flood conditions.

Accepts new data (e.g., from sensors) and predicts whether there is a flood risk.

If a flood is likely, it sends an email alert to notify relevant contacts.

💡 Why I Built It:
I wanted to explore how machine learning can be applied to real-world environmental challenges. This project helped me learn more about data processing, model training, and integrating ML with real-time alert systems.

🛠️ Tools & Technologies:
Python

pandas, scikit-learn for data handling and modeling

smtplib for sending email notifications

Environment variables for secure credential management

🔐 Security Note:
In the actual implementation, email credentials are handled using environment variables instead of being hardcoded, making it more secure and closer to real-world application standards.

