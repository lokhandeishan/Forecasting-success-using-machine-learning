<h1>Restaurant Success Prediction</h1>

<h2>Description</h2>

This repository contains a machine learning project focused on predicting the success of restaurants. The project includes data preprocessing, feature engineering, model training, and evaluation.

<h2>Project Overview</h2>

In this project, we leveraged data from a delivery application to predict the likelihood of a restaurant's success. The key steps undertaken include:

- Data preprocessing and exploration.
- Feature engineering, encoding, and selection using pandas and numpy in Python.
- Deployment of machine learning algorithms, such as Decision Tree, Logistic Regression, Random Forest, and K-Nearest Neighbors (KNN).
- Visualization of results using libraries like Seaborn and Plotly.

<h2>Project Walkthrough</h2>
 <br />

<p align="center">
<strong>First, we will see what types of restaurants are present</strong> <br />
<img width="1002" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/54c8467e-7a77-4553-9a24-553f3faec83e"> 
<br />
<br />

<p align="center">
<strong>Based on the previous chart, we can see that most of them can be clustered into 2 types. Let's see their composition when clustered.</strong> <br />
<img width="989" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/5ceb6871-9cfe-4935-8f11-f2d7e978b03b"> 
<br />
<br />

<p align="center">
<strong>Here, we see the most and least popular restaurants based on votes and the average vote count.</strong> <br />
<img width="694" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/9d76bed3-d561-4295-85d0-49c239e871ca"> 
<br />
<br />

<p align="center">
<strong>Now, we see the most and least expensive restaurants and the mean cost of all the restaurants in Bangalore.</strong> <br />
<img width="672" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/d0e7d362-e0a5-434b-93e9-14497145b991"> 
<br />
<br />

<p align="center">
<strong>Now, we need to know which restaurant has a booking service, and subsequently, let's see the binary distribution of them.</strong> <br />
<img width="766" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/686e15a2-8a50-414c-a05e-7453886d6763"> 
<br />
<br />

<p align="center">
<strong>Now, we will see the booking acceptance ratio.</strong> <br />
<img width="953" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/a016768c-99cd-4884-8e67-ea11bbeccf43"> 
<br />
<br />

<p align="center">
<strong>This image shows us how the restaurants are placed in Bangalore. Most of them are located in the center of the city.</strong> <br />
<img width="962" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/62b84069-64a8-44e4-9007-a6156238786a"> 
<br />
<br />

<p align="center">
<strong>Word cloud to see the most popular dishes based on reviews.</strong> <br />
<img width="395" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/3dceb34c-80d2-4e04-bdfa-8407ac418b31"> 
<br />
<br />

<p align="center">
<strong>Word cloud to see the most frequent word used in reviews.</strong> <br />
<img width="637" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/1eae2003-ccfd-48d2-958a-b4c99b7dd69a"> 
<br />
<br />

<p align="center">
<strong>Now, this shows us the ratio of good or bad restaurants, based on the rating threshold that we set (4.75).</strong> <br />
<img width="447" alt="image" src="https://github.com/lokhandeishan/Forecasting-success-using-machine-learning/assets/157990694/58eaaa39-ce2a-4dd8-9019-56a4089f2e69"> 
<br />
<br />




<h2>Model Performance</h2>

We assessed several machine learning models and evaluated their performance using confusion matrices and accuracy scores:

- **Logistic Regression**:
   - Accuracy: 72.14%

- **Naive Bayes**:
   - Accuracy: 67.63%

- **Random Forest**:
   - Accuracy: 79.26%

- **Decision Tree**:
   - Accuracy: 82.77%

- **K-Nearest Neighbors (KNN)**:
   - Accuracy: 80.19%

The Decision Tree model achieved the highest accuracy of approximately 82.77% among the models.

<h2>Usage</h2>

You can explore the code and run the models using the provided Jupyter Notebook or Python script.

Feel free to clone this repository and use it as a reference for similar prediction projects.

<h2>Libraries Used</h2>

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- xgboost
- folium

<h2>Data Source</h2>

The data was sourced from a delivery application and used for analysis and prediction.
