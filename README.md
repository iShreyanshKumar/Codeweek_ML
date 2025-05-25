# Coding Week 2025 - ML Tasks
This repository contains the solution of **Task 1 – CampusPulse** & **Task 2 – The Rise of the WeatherMind** of the **IIT Guwahati Coding Week 2025** Project along with project reports in PDF of both tasks explaining my approach, experimentations and results.

## Task 1 – CampusPulse
The notebook is organized as follows:

1. **Importing Libraries**
2. **Loading the Data**
3. **Identifying Anonymous Features**
4. **Data Cleaning and Preprocessing**
5. **Exploratory Data Analysis (EDA)**
6. **Model Training and Classification**
7. **Hyperparameter Tuning**
8. **Visualising Decision Boundaries and SHAP Analysis**
9. **Final Results and Conclusion**
10. **Bonus Level**

#### Approach Summary

- **Data Understanding**: To understand patterns in data and identify anonymous features.
- **Preprocessing**: Encoding categorical variables, handling nulls, normalization and identify missing values.
- **Exploratory Data Analysis (EDA)**: For Exploratory Insight Report and getting more interpretation from the data.
- **Model Building**: Several models were trained including Logistic Regression, Random Forest with hyperparameter tuning (using gridsearchCV and randomsearchCV), Gausian Naive Bayes, KNN.
- **Evaluation**: Performance metrics like accuracy, F1-score, and confusion matrix were used to evaluate model performance and then I chose the best out of them.
- **Model Reasoning & Interpretation**: Created decision boundaries and accessed the features using SHAP.
- **Bonus Section**: Using the created decision boundaries and also reading furthur sources, identified the 5 decision plots for different models.



## Task 2 – The Rise of the WeatherMind
The notebook is organized as follows:

1. **Importing Libraries**
2. **Level 1: Core Activation**
3. **Level 2: Senses of the World**
4. **Level 3: Judgement and Memory**
5. **Level 4: The Architect’s Trial – Multi-Agent Evolution**

#### Approach Summary

- **Level 1**: Constructed a langraph node called chatbot using Gemini API and added a calculator tool to it, also visualised its graph.
- **Level 2**: Added Tavily Search and Open Weather to the chatbot using APIs.
- **Level 3**: Added checkpointer to it so that it would remember previous interactions.
- **Level 4**: Implemented multi-agent support using supervisor, also added some dummy agents like hotel booking and flight booking and alse separated the previously made tools into new different agents ensuring all can collaborate smoothly by implementing routing logic between agents through supervisor.

*The project report expands onto these topics in detail and the notebooks also contain the links to the sources from where any code for the task was brought to.*
