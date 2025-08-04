# ai_salary_prediction

##  What I Did

1.  **Exploratory Data Analysis (EDA)**  
   - Analyzed salary distributions, experience levels, job locations, and remote work trends  
   - Visualized relationships between salary and features like company size, skills, and geography

2.  **Data Preprocessing**  
   - Handled missing values and outliers  
   - Encoded categorical variables (e.g., experience level, employment type)  
   - Normalized numerical features for model compatibility

3.  **ANN Model Building**  
   - Built an Artificial Neural Network using TensorFlow/Keras  
   - Defined input layers, hidden layers, activation functions, and output node for regression

4.  **Model Training & Evaluation**  
   - Split data into training and test sets  
   - Trained the model and evaluated performance using MAE, RMSE, and R² metrics

5.  **Hyperparameter Tuning**  
   - Tuned batch size, epochs, learning rate, and number of layers to improve accuracy  
   - Used GridSearch-like approach and monitored validation loss

6.  **Final Report & Explanation**  
   - Documented model performance and feature importance  
   - Interpreted the results in the context of global AI job trends  
   - Provided insights and recommendations based on findings


 Global AI Job Market & Salary Trends 2025

 Complete Analysis of 15,000+ Positions

📘 Dataset Overview

This comprehensive dataset provides an in-depth view of the global AI and machine learning job landscape across 50+ countries, covering 15,000+ real job postings collected from major job platforms worldwide. It is ideal for data scientists, career researchers, and market analysts.

 What's Inside

This dataset includes detailed salary information, job requirements, company insights, and geographic trends. Below are its key features:

✔️ 15,000+ job listings from 50+ countries

✔️ Salary data in multiple currencies (normalized to USD)

✔️ Experience level categorization (Entry, Mid, Senior, Executive)

✔️ Company size impact analysis

✔️ Remote work trends and patterns

✔️ Skills demand analysis

✔️ Geographic salary variations

✔️ Time-series data showing market evolution


🧾 Columns Description


Column	Description	Type

job_id	Unique identifier for each job posting	String

job_title	Standardized job title	String

salary_usd	Annual salary in USD	Integer

salary_currency	Original salary currency	String

salary_local	Salary in local currency	Float

experience_level	EN (Entry), MI (Mid), SE (Senior), EX (Executive)	String

employment_type	FT (Full-time), PT (Part-time), CT (Contract), FL (Freelance)	String

job_category	ML Engineer, Data Scientist, AI Researcher, etc.	String

company_location	Country where company is located	String

company_size	S (Small <50), M (Medium 50-250), L (Large >250)	String

employee_residence	Country where employee resides	String

remote_ratio	0 (No remote), 50 (Hybrid), 100 (Fully remote)	Integer

required_skills	Top 5 required skills (comma-separated)	String

education_required	Minimum education requirement	String

years_experience	Required years of experience	Integer

industry	Industry sector of the company	String

posting_date	Date when job was posted	Date

application_deadline	Application deadline	Date

job_description_length	Character count of job description	Integer

benefits_score	Numerical score of benefits package (1-10)	Float


🎯 Potential Use Cases

 Salary Prediction Models

• Build ML models to predict AI job salaries

• Analyze factors affecting compensation

• Compare salaries across different locations

 Market Trend Analysis

• Track the evolution of AI job market

• Identify emerging job roles and skills

• Analyze remote work adoption patterns

 Career Planning

• Understand skill requirements for different positions

• Compare opportunities across countries

• Plan career progression paths

 Business Intelligence

• Company hiring patterns analysis

• Skills gap identification

• Market competition insights

 Geographic Studies

• Cost of living vs. salary analysis

• Regional market maturity assessment

• Immigration pattern correlations

 Data Collection Methodology

Data was collected through ethical web scraping from major job platforms including:

- LinkedIn Jobs
- Indeed
- Glassdoor
- AngelList
- Stack Overflow Jobs
- Company career pages

📅 Time Period: January 2024 - May 2025

🔁 Update Frequency: Monthly

✅ Data Quality: All entries manually verified and standardized
