<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Human Activity Recognition Using Time-Series Wearable Sensor Data</h3>

</div>

<!-- ABOUT THE PROJECT -->
## About The Project

This project focuses on Human Activity Recognition (HAR) using the PAMAP2 Physical Activity Monitoring dataset. The dataset includes sensor data collected from wearable devices placed on the hand, chest, and ankle of individuals performing various physical activities such as walking, running, cycling, ironing, and vacuum cleaning.

The main objective is to build machine learning models that can accurately classify the type of physical activity based on the motion and physiological data collected from accelerometers, gyroscopes, magnetometers, and heart rate monitors.

Key steps in the project include:

* Data preprocessing: Cleaning missing values, removing irrelevant features (like orientation), and filtering transient activity.

* Exploratory Data Analysis (EDA): Visualizing feature distributions, correlations, and activity counts to understand sensor behavior.

* Feature Engineering & Outlier Detection: Identifying significant sensor axes and removing noise to improve model performance.

* Modeling: Training multiple classifiers such as Random Forest, XGBoost, and ensemble models, with GroupKFold for subject-wise validation.

* Model Interpretation: Using SHAP to identify the most influential features for each activity class.

This end-to-end approach demonstrates how sensor fusion and machine learning can be leveraged to create intelligent systems for real-time activity recognition, with potential applications in healthcare, fitness tracking, and rehabilitation monitoring.

<p align="right">(<a href="#readme-top">Back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

Set up the project locally by following these simple example steps.

### Usage

1. Clone the repo
   ```sh
   git clone [https://github.com/sandeepjakkaraju/aai510finalproject.git]
   ```
2. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>
