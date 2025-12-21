# 🌍Seismo — Real-Time Earthquake Area Analysis and Risk Classification

# 📌 Project Overview
Seismo is a machine learning–based project that analyzes earthquake data to classify seismic events into risk categories based on their magnitude and related features.
The project uses a Random Forest Classifier combined with a machine learning pipeline to ensure structured preprocessing, consistent training, and reliable evaluation.
The primary goal of Seismo is to analyze earthquake activity across different areas and time windows, visualize seismic behavior, and classify events into risk levels in a clear and explainable manner.

# 🎯 Objectives

Analyze earthquake data based on time and area
Classify earthquakes into risk categories
Build a robust ML workflow using a pipeline
Evaluate model performance using accuracy and classification metrics
Visualize recent seismic activity for better understanding

# 🧠 Problem Statement

Earthquake datasets often contain large volumes of historical data but limited events within short time windows.
Manual analysis becomes inefficient when identifying risk-prone seismic events across regions.

This project aims to automate earthquake risk classification using a machine learning model while maintaining interpretability and reliability.

📊 Dataset Description
The dataset consists of historical earthquake records with the following attributes:
Time of occurrence
Magnitude
Geographical area / location
Additional numerical features used for classification
Data is filtered into specific time windows ( last 24 hours) for focused analysis.

# ⚙️ Methodology

--> Data Preprocessing:

Handle missing values,
Convert time features into usable formats,
Select relevant numerical features

--> Pipeline Construction:

Feature scaling ,
Random Forest Classifier integrated into a pipeline

--> Model Training:

Train the model on labeled earthquake data,
Use consistent preprocessing through the pipeline

--> Evaluation:

Evaluate performance using accuracy, confusion matrix, and classification report

--> Visualization:

Plot earthquake magnitudes over time,
Relationship Between Depth and Magnitude (Scatter Plot),
Magnitude Distribution (Box Plot – Last 24 Hours),
Earthquake Events Scatter Plot (Last 24 Hours),

# 📊 Accuracy Achieved:
Accuracy = 99.91%

Total samples = 3238

Classes:

Low Risk

High Risk


# 📌 Conclusion

This project successfully demonstrates the use of data analysis and machine learning techniques to study earthquake activity and classify seismic events into risk categories. Using a structured methodology and a Random Forest model with a pipeline, the system effectively analyzes earthquake magnitudes and related features.
The model achieved high classification accuracy on the available dataset, indicating correct learning of patterns present in historical data. However, the results also highlight the importance of data distribution and availability, as performance is influenced by the quality and balance of the dataset.
Overall, the project emphasizes responsible analysis by combining visualization, model evaluation, and clear interpretation of results. While the current implementation focuses on classification rather than real-time prediction, it provides a strong foundation for future enhancements using larger datasets and advanced techniques.

