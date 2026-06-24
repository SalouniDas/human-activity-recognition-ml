# Human Activity Recognition using Machine Learning

Classifying human activities from smartphone sensor data using classical Machine Learning techniques.
This project implements an end-to-end Human Activity Recognition (HAR) pipeline using smartphone accelerometer and gyroscope signals to identify everyday human activities such as walking, sitting, standing etc.

It was developed as a quick independent project during my Master's in AI & Robotics to demonstrate end-to-end ML workflow skills.

## Project Highlights

✓ End-to-end Machine Learning workflow  
✓ Sensor-based activity classification  
✓ Feature preprocessing and selection  
✓ Comparative model evaluation  
✓ Reproducible experimentation in Jupyter Notebook 

## 📊 Dataset

**Dataset:** UCI Human Activity Recognition Using Smartphones Dataset
🔗 https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

### Dataset Overview
- Smartphone sensor data collected from participants
- Accelerometer and gyroscope signals
- Multiple labeled human activities
- Preprocessed feature representation


## 🧠 Objective

The objective of this project is to build a lightweight Human Activity Recognition (HAR) system using classical Machine Learning algorithms and evaluate model performance across multiple activity classes.

## ⚙️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Environment | Jupyter Notebook |
| ML | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |

## 🚀 Workflow

```text
Sensor Data
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Model Training
   ↓
Performance Evaluation
   ↓
Result Comparison
```
### Models Implemented
- Random Forest Classifier
- Support Vector Machine (SVM)


## 📈 Results

The models successfully classify activities such as:

* Walking
* Sitting
* Standing
* Laying
* Upstairs/Downstairs

Random Forest achieved the best performance among tested models.

### Model Performance

| Model | Accuracy |
|-------|----------|
| Random Forest | XX% |
| SVM | XX% |

🏆 Best Performing Model: **Random Forest**

> Update the final accuracy values after training.

## Repository Structure

```plaintext
human-activity-recognition-ml/
│
├── human_activity_recognition.ipynb
├── features.txt
├── har_results_summary.csv
├── README.md
└── requirements.txt
```
## Installation

Clone the repository:

```bash
git clone https://github.com/SalouniDas/human-activity-recognition-ml.git
```

Move into the project:

```bash
cd human-activity-recognition-ml
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch notebook:

```bash
jupyter notebook
```
## Future Improvements

- Hyperparameter optimization
- Deep Learning approaches (LSTM / CNN)
- Real-time activity recognition
- Model deployment as a web application
- Integration with wearable or robotic systems

## 🎓 Why I built this

This project was created to strengthen practical understanding of:

- Machine Learning pipelines
- Sensor data processing
- Classification techniques
- Experiment tracking
- Building reproducible AI projects

It also reflects my broader interest in **AI, intelligent systems, and assistive technologies**.


## 👩‍💻 Author
Salouni Das

