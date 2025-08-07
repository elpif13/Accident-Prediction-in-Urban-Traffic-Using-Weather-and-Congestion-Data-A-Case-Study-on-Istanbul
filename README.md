# Traffic Accident Prediction

## 🚗 **Project Overview**

Welcome to the **Traffic Accident Prediction** project! This project uses machine learning to predict the likelihood of traffic accidents based on traffic density, time of day, and other relevant factors. By analyzing historical traffic data, the goal is to build a predictive model that can help identify when and where accidents are more likely to occur, ultimately contributing to safer and more efficient road networks.

## 📈 Original Dataset Links

- **Traffic Density**: https://data.ibb.gov.tr/dataset/hourly-traffic-density-data-set
- **Traffic Announcement**: https://data.ibb.gov.tr/dataset/ulasim-yonetim-merkezi-trafik-duyuru-verisi
## 🧠 **Methodology**

This project applies a binary classification approach to predict whether an accident occurs or not in a given time period. Initially, the problem was approached as a multi-class classification task, but it was later simplified to a binary classification problem due to low accuracy in the multi-class setup.

The dataset includes information about vehicle counts, average speed, and traffic density, and was preprocessed to focus on relevant features for accident prediction. Several models were tested, including **neural networks** and **gradient-based methods**. The final model achieved an accuracy of **77.95%**, but there is room for improvement through further refinement and advanced techniques.

## 📊 **Features**

- **Traffic Density**: Calculated as the ratio of the average vehicle count to the average speed.
- **Accident Occurrence**: A binary target variable indicating whether an accident occurred (1) or not (0) during a given hour.
- **Time of Day**: Features representing different hours and rush hours.
- **Additional Data**: Weekend, Rush Hour and Holiday indicators

## ⚙️ **Technologies Used**

- **Python**: The primary programming language used for data analysis and model building.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-Learn**: For model training and evaluation.
- **TensorFlow / Keras**: For exploring deep learning models (neural networks).
- **Matplotlib / Seaborn**: For visualizing the data and results.
- **Jupyter Notebook**: For interactive development and data exploration.

## 🚀 **Getting Started**

To run this project locally, follow these steps:

### 1. Clone the repository
```bash
git clone https://github.com/elpif13/Accident-Prediction-in-Urban-Traffic-Using-Weather-and-Congestion-Data-A-Case-Study-on-Istanbul.git
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Jupyter Notebook
```bash
jupyter notebook
```
## 📈 Results

The model achieved an accuracy of 77.95% in predicting accident occurrence. The results were promising, and future work will focus on refining the model, incorporating additional featurestesting more advanced machine learning models to increase accuracy.





