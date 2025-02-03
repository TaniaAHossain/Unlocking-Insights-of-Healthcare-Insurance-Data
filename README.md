# Unlocking-Insights-of-Healthcare-Insurance-Data

![Image](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/52442cb08e74483992b687a1c26885edb3ec0e58/1691610728513.jpeg)

 A study on healthcare insurance charges reveals smoking status and BMI as key cost drivers, with age showing a positive correlation. The regional impact is lesser but present. Insights aim to help insurers refine pricing, healthcare professionals target interventions, and individuals make informed health decisions for better preventive care.
 
## Key Findings:
- **Average Insurance Charge:** $13.27K

- **Impact of Smoking:** Smokers pay significantly higher premiums ($32.05K) than non-smokers ($8.43K), making smoking the most influential cost driver.

- **Regional Variations:** The Southeast has the highest average charges ($15K), while other regions like the Northwest and Southwest have lower costs ($12K).

- **BMI Influence:** Overweight and obese individuals incur higher premiums due to increased health risks.

- **Age Correlation:** Insurance costs generally rise with age, though some younger individuals also face high charges due to other risk factors.

## Analytical Approach:
- **Individual Factor Analysis:** Examines the independent effect of each variable on insurance charges.

- **Combined Effects Visualization:** Explores interactions between factors, such as smoking status and region.

- **Distribution Analysis:** Investigate age groups, smoker prevalence, and risk categories for contextual insights.

- **Multivariate Visualization:** Uses advanced techniques like 3D scatter plots to reveal complex relationships.

- **Correlation Quantification:** Generates a correlation matrix to measure the strength of relationships between variables.

## Objective:
The study seeks to generate actionable insights that enable insurers to enhance risk assessment and optimize pricing strategies. Additionally, it aims to support healthcare professionals in designing targeted interventions while empowering individuals to make informed decisions regarding their health and preventive care.

## Data Source
[Data Source](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance)

## Built With 

-  [Python](https://www.python.org/)
-  [Power BI](https://powerbi.microsoft.com/en-us/)
-  [Excel](https://www.microsoft.com/en-us/)

## Analysis

### Excel Project

![Power BI dashboard link](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/df6357c8e887f551b574674e95d8f8792dbf0bac/Excel%20Project%20using%20Power%20BI/Healthcare%20Insurance%20updated-%20P1.pbix)

![Power BI dashboard Analysis](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/df6357c8e887f551b574674e95d8f8792dbf0bac/Excel%20Project%20using%20Power%20BI/PowerBi%20dashboard%20analysis.md)

![Power Bi dashboard images](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/a0d974c5a081202c4c4fd936206cf4c27ea15a2b/Excel%20Project%20using%20Power%20BI/Healthcare%20insurance%20-%20p1.jpg)

### Python Project
![Python Project ](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/a3a480a9471d47602956c1d2cd94a72862b09d9a/Python%20Project/Healthcare_Insurance_Data_ipynb_Tania_Hossain.ipynb)

## Comparing average charges across age groups and risk categories
![images](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/6a64289e25023b8bd2d087b7f58625af3707777e/Images/Charges%20by%20age%20group%20anad%20risk%20category.png)

This plot effectively communicates the complex interplay between age, risk factors (smoking, BMI), and healthcare costs. It provides valuable insights for insurance providers, healthcare professionals, and individuals to understand the financial implications of health-related behaviors and demographics. Stakeholders can make informed decisions regarding insurance premiums, preventive care, and health interventions by identifying high-risk groups and comprehending the cost trends associated with different age and risk profiles.

#### * Charges by BMI type and risk
![images](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/c8f560983c0a47cb3c0d1b5a1e7b19e638784b2a/Images/Untitled.png)

This analysis reveals that BMI is a key factor in healthcare costs, with higher BMIs correlating with higher insurance charges. Regional variations in costs also exist, likely due to regional factors. The interaction of BMI and region further complicates cost patterns. This information is valuable for insurers (risk assessment and premiums), healthcare providers (targeted interventions), policymakers (public health programs), and individuals (informed health choices).

#### * Combined Visualization for Charges across smoker status and region
![images](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/c8f560983c0a47cb3c0d1b5a1e7b19e638784b2a/Images/Charges%20by%20Region%20and%20smoker%20Status.jpg)

This analysis reveals that smoking status is the primary driver of insurance charges, with smokers consistently facing significantly higher costs than non-smokers across all regions. While regional variations in charges exist, they are less pronounced than the impact of smoking. Specifically, the Southeast region shows slightly higher charges for smokers, and the Northeast shows slightly higher charges for non-smokers compared to other regions.

#### * Correlation Between Age, BMI, Smoker Status, Region, and Charges
![images](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/c8f560983c0a47cb3c0d1b5a1e7b19e638784b2a/Images/Correlation%20between%20Age%20%2C%20BMI%2C%20Smoker%2C%20Region%20and%20Charges.jpg)

This illustration helps to understand how different factors (age, BMI, smoker status, region) relate to insurance charges by calculating and visualizing their correlation coefficients using a heatmap. This can provide valuable insights into which factors have the strongest relationships with insurance costs.

#### * Impact of Age and BMI on Charges
![images](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/c8f560983c0a47cb3c0d1b5a1e7b19e638784b2a/Images/Impact%20of%20Age%20and%20BMI%20on%20Charges.jpg)

This 3D scatter plot illustrates the interplay between age, BMI, and insurance charges. Individual data points are plotted in three-dimensional space, with their position determined by their age, BMI, and corresponding charge amount. A 'plasma' colormap is used to represent the magnitude of the charges, with color intensity varying to depict the range from low to high costs.

#### * Number of Children vs Average Cost

![images](https://github.com/TaniaAHossain/Unlocking-Insights-of-Healthcare-Insurance-Data/blob/c8f560983c0a47cb3c0d1b5a1e7b19e638784b2a/Images/Number%20of%20children%20vs%20average%20cost.png)

The line chart visually represents the relationship between the average insurance cost and the number of children a person has. The chart utilizes circular markers and a solid blue line to highlight the trend. By examining the line's direction, you can determine whether a positive, negative, or no correlation exists between the number of children and average insurance costs. Each circular marker indicates the average cost for a particular number of children. The inclusion of grid lines simplifies the process of reading and comparing values, while the title and axis labels provide essential context for understanding the chart's purpose and data.

## Potential Results & Reasoning

- **Customer Segmentation:** By analyzing customer demographics, purchase history, and risk profiles, the notebook could be used to segment customers into distinct groups. This would enable targeted marketing campaigns, personalized product offerings, and optimized pricing strategies.
  
- **Risk Assessment and Pricing:**
Insurance companies heavily rely on risk assessment to determine premiums. This analysis might employ statistical models or machine learning algorithms to predict the likelihood of claims or losses for individual customers or specific risk categories, leading to more accurate and dynamic pricing models.

- **Fraud Detection:**  Insurance fraud is a major concern. By analyzing claim patterns, customer behavior, and historical data, the notebook could help identify potentially fraudulent activities, reducing losses and protecting the company's interests.
  
- **Claims Management and Automation:**  Streamlining claims processing is crucial for customer satisfaction and operational efficiency. The notebook might automate certain aspects of claims handling, such as claim validation, routing, and initial assessment, based on predefined rules or predictive models.
  
- **Customer Relationship Management:**  Understanding customer needs and preferences is key to building strong relationships. The notebook could be used to analyze customer interactions, feedback, and policy usage to identify areas for improvement in customer service, product offerings, and communication strategies.
  
- **Underwriting Optimization:** Underwriting involves evaluating risks and making decisions on policy issuance. The notebook might provide insights into underwriting processes, identify potential biases or inefficiencies, and recommend improvements for more effective risk selection and pricing.
  
- **Predictive Maintenance:** For property and casualty insurance, the notebook could be used to analyze data from sensors or other sources to predict potential maintenance needs for insured assets. This proactive approach could help prevent losses and improve risk management.

## Closing Remarks

The visualizations establish functions for calculating insurance costs based on critical factors such as age, BMI, smoking status, and geographic region. Leveraging pandas for data processing and matplotlib for visualization, the analysis identifies smoking as the most significant determinant of insurance costs, followed by age and BMI. Furthermore, notable regional variations in premiums are observed. These insights underscore the necessity of incorporating individual health and lifestyle factors into insurance risk assessments and pricing strategies.









