![giphy](https://github.com/Tadeshee/Python/assets/124716537/bab6a6ce-09c3-43f4-853b-983fa30d8b21)

# Project Title: Customer Churn Analysis for Telecommunication using Machine Learning 📊🐍

This project focuses on churn analysis in the telecommunication industry, aiming to predict which customers are likely to terminate their services with the provider. By leveraging machine learning techniques, we strive to help telecom providers reduce their churn rates, improve customer retention, and make data-driven decisions.


## Data Source 📂🔢

Adaryl Bob Wakefield, a Data Management Expert, provided the dataset [https://data.world/bob-wakefield/call-center-data] used for this analysis. It is the Customer Signature for Churn Analysis dataset. It contains the following columns:


• **recordid**: uniquely identifies a record in the dataset 

• **customer_id**: uniquely identifies a customer in the dataset

• **state**: state of the customer

• **area_code**: area code of the customer

• **account_length**: Length of the customer's account

• **international_plan**: Indicates whether the customer has an international plan (0 - No, 1 - Yes)

• **voice_mail_plan**: Indicates whether the customer has a voice mail plan (0 - No, 1 - Yes)

• **number_vmail_message**s: Number of voice mail messages

• **total_day_minutes**: Total minutes of day calls

• **total_day_calls**: Total number of day calls

• **total_day_charge**: Total charge for day calls

• **total_eve_minutes**: Total minutes of evening calls

• **total_eve_calls**: Total number of evening calls

• **total_eve_charge**: Total charge for evening calls

• **total_night_minutes**: Total minutes of night calls

• **total_night_calls**: Total number of night calls

• **total_night_charge**: Total charge for night calls

• **total_intl_minutes**: Total minutes of international calls

• **total_intl_calls**: Total number of international calls

• **total_intl_charge**: Total charge for international calls

• **number_customer_service_calls**: Number of customer service calls

• **churn**: Indicates whether the customer churned (0 - No, 1 - Yes)

## Installation Instructions ⚙️📥

To set up and run this project, follow these steps:

1. Clone the repository to your local machine using the following command:

    git clone https://github.com/YOUR-USERNAME/your-repository.git

2. Navigate to the project directory:

   cd your-repository
   
3. Create a virtual environment (optional but recommended) to isolate the project's dependencies:

   python -m venv env

4. Activate the virtual environment:


   For Windows:
   env\Scripts\activate


   For macOS/Linux:
   source env/bin/activate


5. Install the required dependencies from the requirements.txt file:

   pip install -r requirements.txt

6. Once the dependencies are installed, you are ready to run the project.

   python main.py

   Replace main.py with the main script or entry point of your project.


## Exploratory Data Analysis (EDA) 📈🔎

In the EDA phase, I perform data exploration and gain initial insights into the dataset.

• **Importing Libraries**: This section imports the necessary libraries for data analysis and visualization.

• **Loading the Dataset**: The dataset is loaded into a Pandas DataFrame for further analysis.

• **General Information**: I examine the general information about the DataFrame, including the number of rows, columns, and column data types.

• **Checking for Null Values**: I check if there are any null values in the dataset.

• **Dataframe Shape**: The shape of the DataFrame (number of rows and columns) is displayed.

• **Dataframe Column Types**: I check the data types of each column in the DataFrame.

• **Summary Statistics**: Summary statistics on numeric variables are provided.

• **Features**: I print the column names of the DataFrame.
Churn Counts: I count the number of customers who churned and did not churn.

• **Churn Count Plot**: A count plot is created to visualize the churn distribution.

• **Box Plot**: A box plot is created to analyze the relationship between churn and account length.

• **Histogram distribution**: Histograms are created to visualize the distribution of various features in the dataset.

• **Dropping Columns**
Columns such as **recordid**, **customer_id**, **state**, and **area_code** are dropped as they are not pertinent to the analysis and do not provide predictive power.

• **Checking for Correlation**
A correlation matrix is generated to identify highly correlated features. Highly correlated features may not provide additional information and can increase the complexity of the model.


## Machine Learning Workflow 🤖📊

I implemented a comprehensive machine-learning workflow to address the churn prediction problem effectively. The approach encompasses the following steps, ensuring a structured and professional approach:

1. **Feature Selection**:
I  carefully selected the most relevant features while discarding any irrelevant ones. This process helps focus on the key factors influencing churn prediction.

2. **Data Preparation**:
To prepare the data for model training, I employed various encoding techniques. Additionally, I performed feature scaling on the numeric features using StandardScaler to ensure consistent ranges and prevent dominance by certain variables.

3. **AutoML Workflow with PyCaret**:
To determine the most optimal machine learning algorithm, I leveraged the power of the AutoML workflow using PyCaret. This automation tool assisted in comparing and evaluating multiple algorithms, allowing us to identify the best-performing model for churn prediction.

4. **Model Selection**:
I  carefully chose a set of diverse machine-learning models known for their effectiveness in binary classification tasks.

5. **Model Building**:
In this phase, I  constructed predictive models to identify potential churners and evaluate their performance. I  considered popular machine learning models for binary classification, including Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and Support Vector Machine (SVM).


6. **Model Training and Evaluation**:
Each selected model underwent training using cross-validation techniques, and their performance was evaluated using metrics such as accuracy, precision, recall, and F1 score. Furthermore, I created a confusion matrix for each model to gain deeper insights into their predictive capabilities.

7. **Model Comparison**:
By comparing the performance of different models, I identified the best-performing model for accurately predicting customer churn.

8. **Model Tuning**:
After obtaining the results from the machine learning models, I  further enhanced their performance through model tuning. This process involves adjusting hyperparameters to fine-tune the models and gain a better understanding of the key drivers behind customer churn. The goal is to develop a reliable and accurate prediction model that can significantly benefit telecom providers.

9. **Feature Importance Analysis**:
I  analyzed the importance of each feature in the best-performing model. This analysis will help identify the most influential factors contributing to customer churn, enabling providers to prioritize their retention strategies effectively.

## Recommendations and Impact 💡📈

Given the competitive nature of the telecommunication industry and high churn rates, accurately predicting potential churners is crucial for providers to devise effective retention strategies. The project aims to deliver a predictive model and actionable recommendations to telecom providers, helping them reduce churn rates and enhance customer satisfaction.

## Portfolio Development and Future Prospects 📁🚀

This project serves as a valuable opportunity to strengthen my portfolio and demonstrate my skills to potential employers. The experience gained from working on this project will contribute significantly to my professional growth in data science and machine learning.

## Technologies Used 💻🔧

Python

Pandas

Scikit-learn

NumPy

Matplotlib

Seaborn

Microsoft Excel

Power Query

PyCaret (AutoML flow)

## Contributions 🤝🌟

The associated GitHub repository contains the necessary code, documentation, and resources to reproduce the results and findings. I welcome contributions to enhance this Project. If you have any ideas, bug fixes, or feature suggestions, please feel free to open an issue or submit a pull request. Let's collaborate and make this project even better! 🚀🎉

## References 📚🔖

Wakefield, B. (2019, September 28). Customer Signature for Churn Analysis. Data.world; data.world. [https://data.world/bob-wakefield/call-center-data](https://data.world/bob-wakefield/call-center-data)

‌
