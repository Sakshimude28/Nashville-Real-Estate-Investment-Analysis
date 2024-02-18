# Nashville-Real-Estate-Investment-Analysis
This project is aimed at assisting a real estate company in making informed investment decisions in the rapidly growing Nashville area. The company has acquired a dataset of recent sales, and the goal is to build predictive models to identify the best value deals. The concern is that houses might be selling over their asking price, and this dataset will provide insights into such occurrences. The project is structured into several parts, each focusing on different aspects of the data analysis and model building process.

## Project Description

### Problem Statement
The real estate market in Nashville is booming, presenting a lucrative opportunity for investors. However, the challenge lies in identifying properties that are priced below their potential market value to secure profitable deals. This project utilizes a dataset detailing recent sales in the area to develop models capable of predicting whether a house is priced over or under its asking price. The aim is to guide the company in making data-driven investment decisions, maximizing returns by focusing on properties that offer the best value.

### Approach
- **Part 1**: Data cleansing is performed to ensure the integrity and quality of the dataset. This step involves handling missing values, 
    outliers, and ensuring data consistency. The process and decisions made during data cleansing are thoroughly documented.
- **Part 2 to Part 6**: Various predictive models are developed and evaluated:
  - Logistic Regression to classify properties as overpriced or underpriced.
  - Decision Tree to provide insights into the factors affecting property prices.
  - Random Forest to improve prediction accuracy by leveraging multiple decision trees.
  - Gradient Boost to further enhance model performance by optimizing predictions.
  - Neural Network to capture complex nonlinear patterns in the data.
- **Part 7**: The models are benchmarked against multiple metrics to identify the most effective approach.

### Data Dictionary
The analysis is based on selected fields from the dataset to ensure relevance and accuracy in predictions:
- **Land Use**: Classification of the land's purpose.
- **Sale Price**: The selling price of the property.
- **Sold As Vacant**: Indicator if the property was vacant at the sale time.
- **Multiple Parcels Involved in Sale**: Whether the sale included multiple properties.
- **Acreage**: Size of the property in acres.
- **Tax District**: Taxation district of the property.
- **Land Value**: Market value of the land.
- **Building Value**: Market value of the building on the property.
- **Total Value**: Total market value of the property.
- **Finished Area**: Area of the house that is finished and livable.
- **Foundation Type**: Type of foundation the house is built on.
- **Year Built**: The year the property was built.
- **Exterior Wall**: Material of the exterior walls.
- **Grade**: Condition grade of the house.
- **Bedrooms**: Number of bedrooms.
- **Full Bath**: Number of full bathrooms.
- **Half Bath**: Number of half bathrooms.

The project provides a comprehensive framework for analyzing and predicting real estate prices, aiming to equip the real estate company with the knowledge to secure profitable investments in Nashville's competitive market.
