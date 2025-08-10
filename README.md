# Drawing to diagnose: A gamified diagnostic tool for Alzheimer’s and Parkinson’s disease

An interactive, gamified drawing-based diagnostic tool for early detection of Parkinson's Disease (PD) and Alzheimer's Disease (AD) using machine learning models.

Overview
This project addresses the critical need for accessible, non-invasive screening tools for neurodegenerative diseases. Current diagnostic processes for PD and AD are often invasive, costly, and inaccessible, leading to delayed diagnosis and treatment. Our solution leverages handwriting and drawing analysis combined with deep learning to provide early screening capabilities in both clinical and home environments.

Key Features
Non-invasive screening through digital drawing analysis
Gamified interface for comfortable user experience
Real-time predictions using trained machine learning models
Dual disease detection for both Parkinson's and Alzheimer's
Low-cost and accessible solution for widespread deployment

Problem Statement
-Parkinson's Disease and Alzheimer's Disease are two of the most common neurodegenerative disorders affecting older populations:
-Parkinson's Disease: Movement disorder causing tremors, muscle rigidity, and balance issues due to dopamine neuron loss
-Alzheimer's Disease: Progressive cognitive decline affecting memory, decision-making, and daily activities
-Both diseases lack definitive diagnostic tests and cures
-Early symptoms are often subtle and misdiagnosed
-Current diagnosis involves lengthy processes with neurologists
-Research suggests these diseases may represent different points on a spectrum called Neurodegenerative Elderly Syndrome (NES), sharing common pathological mechanisms including protein buildup and neural network degeneration.

Data Sources
-Alzheimer's Detection: DARWIN dataset (n=174) containing handwriting samples
-Parkinson's Detection: Multiple datasets with spiral and wave drawing samples

Machine Learning Models
  Alzheimer's Disease Classification
  -Logistic Regression
  -Feedforward Neural Networks (FNN)
  -Random Forest (Best performance: 85.29% accuracy)

  Parkinson's Disease Detection
  -Convolutional Neural Network (CNN) with transfer learning
  -MobileNetV2 architecture
  -Test Accuracy: 81.25%

Data Collection
The system captures:
Digital drawing images (spirals, waves, handwriting)
Pressure values during drawing
Timing and movement metrics
User interaction patterns

Installation Prerequisites
bashpython >= 3.7
PyQt5
numpy
pandas
PIL (Pillow)
openpyxl
tensorflow/keras (for CNN models)
scikit-learn (for traditional ML models)

Install dependencies
pip install -r requirements.txt

Run the application
python UserInterface.py

Usage
GUI Application
Launch the application using python UserInterface.py
Follow the gamified interface prompts
Complete drawing tasks (spirals, waves, handwriting)
Receive real-time risk assessment predictions

Drawing Tasks
Spiral Drawing: Assess motor control and tremor patterns
Wave Drawing: Evaluate coordination and movement smoothness
Handwriting Samples: Analyze cognitive and motor function integration


Clinical Applications
Early screening in primary care settings
Home-based monitoring for at-risk populations
Longitudinal tracking of disease progression
Support for healthcare providers in resource-limited environments

Gamification Features
The interface includes:
-Interactive drawing challenges
-Progress tracking and feedback
-Engaging visual design
-Low-stress testing environment
-Immediate results presentation

Important Notes
Not a diagnostic replacement: This tool is for screening purposes only
Clinical validation required: Results should be confirmed by healthcare professionals
Privacy considerations: All drawing data is processed locally when possible
Accessibility: Designed for users with varying technical abilities

Future Developments
Integration of additional biomarkers
Expansion to other neurodegenerative diseases
Mobile application development
Cloud-based analysis for improved accuracy
Longitudinal study implementations
Multi-language support

Contributing
We welcome contributions from researchers, developers, and healthcare professionals:
Fork the repository
Create a feature branch (git checkout -b feature/new-analysis)
Commit your changes (git commit -am 'Add new analysis method')
Push to the branch (git push origin feature/new-analysis)
Open a Pull Request

📧 Contact
For questions, collaboration opportunities, or technical support, please contact:
Email: [hooriaashfaq1@gmail.com]
Project Lead: [Hooria Ashfaq]
Institution: [University of Calgary]


#Parkinsons Data File
#Use this google drive link to access the data used to build the Parkinsons-CNN Model
https://drive.google.com/file/d/1ck2aPjOhwAjbQAUP-FI11EhECvus7pH9/view?usp=sharing
