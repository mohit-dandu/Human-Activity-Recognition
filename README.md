
 # Human Activity Recognition 
* Human activity recognition (HAR) is an important area of research that has applications in various fields, including healthcare, sports and security. 
* HAR involves identifying and classifying human activities based on sensor data collected from wearable devices or other sources. 
* The objective of this project is to develop a system that can automatically recognize and classify human activities using sensor data collected from various sources. 
* To achieve this goal, the project uses a variety of classification models such as K-Nearest Neighbors, Decision Tree, Support Vector Machines and Naive Bayes, to build models that can recognize different activities, including walking, standing, sitting and laying.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Features](#features)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)


## General Information
The motivation for this project stems from the need for accurate and reliable human activity recognition systems. With the increasing use of wearable devices and smart sensors in various fields, including healthcare, sports and security, the demand for robust and efficient human activity recognition systems has grown significantly. These systems can provide valuable insights into human behavior and help monitor various health conditions, detect anomalies and improve performance. The potential applications of human activity recognition systems are vast and therefore, there is a need for developing accurate and reliable systems that can recognize and classify human activities in real-time.


## Technologies Used
- Python libraries: Scikit-learn, Numpy, Pandas, Matplotlib, Seaborn, Plotly Express


## Setup
The project requirements/dependencies are listed in the import statements at the beginning of the code:
* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* plotly.express

To set up your local environment and get started with the project, you need to follow these steps:

1. Install Python on your computer if you haven't already done so. You can download Python from the official website: https://www.python.org/downloads/

2. Open a command prompt or terminal window and navigate to the directory where you want to store the project files.

3. Clone the project repository using Git or download the project files directly from the repository.

4. Install the required dependencies by running the following commands in your command prompt or terminal window:
`pip install numpy pandas matplotlib seaborn sklearn scipy plotly`

5. Once the dependencies are installed, you can open the Jupyter Notebook file containing the project code and run the code cells to execute the project.


## Features
* Support Vector Machines  (SVM) has  the  highest  accuracy of 98.3% compared to all others.
* Logistic Regression ranks the second best.
* Important features are Gravity accelerometer signal mag area, energy and min. The analysis identified the most important features for accurately predicting human activities, by considering accelerometer data, gyroscope data and time-related features. 
* These features provide valuable insights into the movements and patterns of human activities, such as walking, running and sitting.


## Usage
The project has significant business implications. The developed human activity recognition system can be used in various industries, including healthcare, sports and virtual reality. In healthcare, the system can help healthcare professionals recommend appropriate activities to patients with medical conditions based on their physical activity data. It can also enable personalized healthcare by tailoring recommendations based on individual patient's physical activity data.
In sports, the system can provide real-time feedback to athletes, helping them improve their performance and prevent injuries. It can also help coaches monitor the physical activity of their athletes remotely.
In virtual reality, the system can improve the user experience by enabling more immersive interactions between the user and the virtual environment. It can also help developers create more realistic virtual environments by providing accurate activity recognition data.


## Project Status
Project is: _complete_


## Room for Improvement
Future work can involve testing other machine learning models and exploring the potential of deep learning techniques for this problem. One limitation is that the dataset used in this project was collected from a small number of subjects. Expanding the dataset to include a larger and more diverse group of subjects would allow for better generalization of the model's performance. Another limitation is that the dataset only included accelerometer and gyroscope data. Additional sensor data, such as heart rate and temperature, could provide further insights into a user's physical activity.
Additionally, the current implementation of the model only classifies five different physical activities. Expanding the range of activities that the model can recognize would increase its utility for a wider range of applications.
 
