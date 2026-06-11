# Customer Satisfaction Score Prediction using Deep Learning

This project leverages Deep Learning and Artificial Neural Networks (ANN) to predict Customer Satisfaction (CSAT) scores in an e-commerce environment. By analyzing customer interactions, service channels, agent-related information, and transaction details, the model provides actionable insights that help businesses improve customer experience, optimize support operations, and increase customer retention.

The solution focuses on transforming raw customer support data into meaningful predictions using data preprocessing, feature engineering, neural network modeling, and real-time deployment through a Gradio-powered web application.

---

## 🚀 Features

* Predicts Customer Satisfaction (CSAT) scores using Deep Learning
* End-to-end Machine Learning pipeline from data preprocessing to deployment
* Handles large-scale customer support datasets with 85,000+ records
* Automated data cleaning and feature engineering
* One-Hot Encoding for categorical variables
* Feature Scaling using StandardScaler
* Multi-layer Artificial Neural Network (ANN) architecture
* Real-time CSAT prediction through an interactive Gradio interface
* Business-focused insights for customer experience optimization

---

## 🎯 Business Problem

Customer Satisfaction (CSAT) is one of the most important performance indicators in the e-commerce industry. Traditional survey-based methods often fail to provide timely insights into customer experiences.

This project addresses that challenge by building an AI-driven prediction system capable of estimating customer satisfaction scores based on support interactions, agent performance, customer details, and transaction-related information, enabling organizations to proactively improve service quality.

---

## 📊 Dataset Overview

The dataset contains customer support interaction records from an e-commerce platform, including:

* Customer Service Channel
* Product Category
* Customer City
* Item Price
* Agent Information
* Supervisor & Manager Details
* Tenure Bucket
* Agent Shift
* Connected Handling Time
* Survey Response Information
* Customer Satisfaction (CSAT) Score

**Dataset Size:** 85,000+ Records
**Features:** 20+ Business Attributes

---

## 🛠️ Tech Stack

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn
* Gradio

---

## 🔍 Data Processing Pipeline

1. Data Collection & Loading
2. Missing Value Handling
3. Feature Selection
4. Timestamp Conversion
5. Categorical Encoding
6. Feature Scaling
7. Train-Test Split
8. ANN Model Training
9. Model Evaluation
10. Deployment with Gradio

---

## 🧠 Deep Learning Architecture

The prediction model is built using a Multi-Layer Artificial Neural Network (ANN):

* Input Layer
* Flatten Layer
* Multiple Dense Hidden Layers
* LeakyReLU Activation Functions
* Softmax Output Layer
* Sparse Categorical Cross-Entropy Loss
* Adagrad Optimizer

The architecture is designed to learn complex patterns from customer interaction data and generate accurate satisfaction score predictions.

---

## ⚡ Model Optimization Techniques

* Feature Engineering
* One-Hot Encoding
* Standardization using StandardScaler
* LeakyReLU Activation
* Multi-Layer Dense Network
* Train-Validation Splitting
* Performance Monitoring with Accuracy Metrics

These techniques improve learning efficiency and prediction performance across diverse customer interaction scenarios.

---

## 🌐 Deployment

A user-friendly Gradio web application was developed to provide real-time CSAT predictions.

Users can:

* Select interaction channel details
* Choose tenure-related attributes
* Enter item price information
* Receive instant CSAT score predictions

This enables quick decision-making and practical business adoption.

---

## 📈 Business Impact

* Improves customer experience management
* Identifies potential dissatisfaction before survey completion
* Supports proactive customer support strategies
* Assists managers in monitoring service quality
* Enhances customer retention and loyalty
* Enables data-driven operational improvements

---

## 💡 Applications

* Customer Experience Analytics
* E-commerce Support Optimization
* Customer Retention Strategies
* Service Quality Monitoring
* Agent Performance Evaluation
* Customer Feedback Analysis
* Business Intelligence Systems

---

## 📌 Project Highlights

✔ Developed a Deep Learning-based CSAT prediction system using TensorFlow and Keras
✔ Processed and analyzed 85,000+ customer support interaction records
✔ Built a multi-layer ANN architecture for satisfaction score prediction
✔ Implemented feature engineering, encoding, and scaling techniques
✔ Created a real-time prediction dashboard using Gradio
✔ Demonstrated practical application of AI in customer experience management
✔ Converted business interaction data into actionable customer satisfaction insights

---

## 🔮 Future Enhancements

* Advanced NLP analysis of customer remarks
* Integration with Transformer-based Language Models
* Real-time customer sentiment analysis
* Explainable AI (XAI) for prediction transparency
* Cloud deployment using AWS or Azure
* Automated customer dissatisfaction alerts
* Interactive analytics dashboard for business stakeholders

---

## 🏆 Conclusion

This project demonstrates how Deep Learning can be applied to customer service analytics to predict Customer Satisfaction (CSAT) scores with high efficiency. By combining data preprocessing, feature engineering, neural networks, and real-time deployment, the solution provides businesses with a scalable AI-driven framework for enhancing customer experience and operational performance.
