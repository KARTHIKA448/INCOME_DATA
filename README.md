"INCOME CENSUS DATASET"
- This dataset contains information from the U.S. Census regarding various demographic and socioeconomic factors of individuals.
- The primary focus is on predicting whether an individual earns more than $50,000 per year based on features such as age, education, occupation, and more.

I've finished a project using the dataset "income_data.csv" in the repository "INCOME_DATA".

The data contains 32561 instances with the following attributes. Each feature tells us about:
  - Age: Represents the age of the individual.- Workclass: Describes the type of employment or work class the individual is associated with (e.g., State government, Self-employed, Private).
  - Final Weight (fnlwgt): This is a census-specific weight. It represents the number of people the census believes the entry represents.
  - Education: Indicates the highest level of education achieved by the individual (e.g., Bachelors, HS-grad, Assoc-acdm).
  
  - Education Number (education-num): Corresponds to the education level in numerical form.
  - Marital Status: Specifies the marital status of the individual (e.g., Never-married, Married-civ-spouse, Divorced).
  - Occupation: Refers to the type of work or job the individual is engaged in (e.g., Adm-clerical, Exec-managerial, Handlers-cleaners).
  - Relationship: Indicates the person's role in the family (e.g., Not-in-family, Husband, Wife, Own-child).
  - Race: Represents the racial background of the individual (e.g., White, Black).
  - Sex: Specifies the gender of the individual (Male or Female).
  - Capital Gain: Refers to the monetary gain made by the individual through investments or other financial activities.
  - Capital Loss: Indicates the monetary loss suffered by the individual through investments or other financial activities.
  - Hours per Week: Represents the number of hours the individual works per week.
  - Native Country: Specifies the native country of the individual.
  - Income: Indicates whether the individual's income is above or below $50,000 (<=50K or >50K).

Power Bi and Jupyter Notebook are the tools used for this project.

The steps involved:
      IN JUPYTER NOTEBOOK:
                          1.Importing required libraries.
                          2.Read the dataset.
                          3.Rename the features.
                          4.Clean the data(drop missing values and duplicates).
                          5.Statistical description.
                          6.Visualisation:
                                   - Univariable analysis
                                   - Bivariable analysis.
                          7.Treating imbalanced data(Applying SMOTE).
                          8.Model Training:
                                  - converting categorical datas to numerical datas using feature encoding(label encoder).
                                  - separate independent variable and target variable.
                                  - split the data into training sets and testing sets.
                                  - treating imbalanced data using SMOTE technique.
                                  - standardisation
                                  - machine learning model implementation: 
                                          LOGISTIC REGRESSION
                                          DECISION TREE REGRESSION
                                          K NEAREST NEIGHBORS 
                          9.Evaluation metrices
                          10.Conclusion:
                             **Based on the provided evaluation metrics, the K-Nearest Neighbors (KNN) model appears to be the most suitable for predicting whether an individual earns more than $50,000 or not.**
      
      IN POWER BI: 
The data is cleaned and saved as a new "INCOME_DATA.csv" file after being processed in the Jupyter notebook.IN POWER BI:
                          1.Load the data.
                          2.Create visualisations.
                          3.Arrange visualisations.
                          3.Add filters.
                          4.Add text and text boxes.
                          5.Save the file (extension: "pbix").
