# IPL Score Prediction Using Deep Learning

This repository contains a machine learning project for predicting IPL (Indian Premier League) cricket scores based on historical data. The goal of this project is to build a regression model that can accurately predict the total score of a cricket team based on various features such as venue, batting team, bowling team, batsmen, and bowlers.

![Alt Text](res/1.png)

## Project Overview

### Dataset 📂
You can download the dataset used in this project here:  
[📄 ipl_data.csv](https://github.com/maneeshmkp/your-repo-name/blob/main/ipl_data.csv)

### Features Considered 📌  
- **Venue**  
- **Batting Team**  
- **Bowling Team**  
- **Batsmen**  
- **Bowlers**  
- **Runs Scored**  
- **Wickets Taken**  
- **Overs Played**  
- **Runs and Wickets in the Last 5 Overs**  


Main Steps Involved in This Project:

### 1. Data Preprocessing:

- Cleaning and preparing the dataset.
- Encoding categorical variables using LabelEncoder.
- Scaling numerical features using MinMaxScaler.

### 2. Model Building:

- Utilizing Keras (with TensorFlow backend) to build a neural network model.
- Experimenting with different architectures (number of layers, units per layer) to optimize performance.
- Training the model using historical IPL data.

### 3. Evaluation:

Assessing the model's performance using metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared (R2) Score

Iteratively refining the model to achieve better predictive accuracy.

### 4. Prediction:

- Implementing prediction functionality using the trained model.
- Creating an interactive prediction interface using ipywidgets for selecting venue, batting team, bowling team, batsmen, and bowlers.

### 5. Comparison with Other Models:

- Implementing Gradient Boosting Regressor and Support Vector Regressor from scikit-learn for benchmarking and comparing performance.

## Results

After experimenting with various neural network architectures and model configurations, the final model achieved the following performance metrics on the test dataset:

- Mean Absolute Error (MAE): 11.95
- Mean Squared Error (MSE): 344.24
- R-squared (R2) Score: 0.592

These metrics indicate that the model is able to predict IPL scores with a high degree of accuracy, explaining approximately 59.2% of the variance in the data.

![Alt Text](res/2.png)

## 📂 Repository Structure

- ipl_data.csv              : Dataset used for training and evaluation
- IPLScore.ipynb            : Jupyter notebook containing the entire project code with explanations
- requirements.txt          : List of Python dependencies required to run the project
- README.md                 : Project documentation (this file)


# Usage 🚀

Follow these steps to use this project:

1. **Clone the Repository**  
   ```sh
   git clone https://github.com/maneeshmkp/IPL-Score-Prediction-using-Deep-Learning.git
   cd IPL-Score-Prediction-using-Deep-Learning


2. **Install Dependencies:**
    ```sh
    pip install -r requirements.txt


3. **Run the Jupyter Notebook:**

Open and run the IPLScore.ipynb notebook in Jupyter Notebook or any compatible environment.

4. **Follow the Notebook Instructions:**

- Preprocess the data.
- Build and train the model.
- Evaluate its performance.

Use the interactive widgets to make predictions based on custom inputs.

## Future Improvements 🚀  

- Explore more advanced neural network architectures (e.g., LSTM for sequence data).  
- Incorporate additional features such as player statistics, weather conditions, or match history.  
- Conduct more thorough hyperparameter tuning and model optimization.  
- Deploy the model as a web application or API for real-time predictions.  


## Connect with Me 🚀

[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/ManeeshKum14044)
[![GitHub](https://img.shields.io/badge/GitHub-%2312100E.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maneeshmkp)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maneeshmkp/)



## License 📜  

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

## Keep Learning and Exploring 🚀  

Happy coding! 😊 If you find this project helpful, give it a ⭐ on GitHub!  
