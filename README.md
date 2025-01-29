# Hotel Demand Analysis & Customer Segmentation

## Project Overview
This project analyzes hotel booking demand data to predict cancellation patterns and segment customers for targeted marketing strategies. Using advanced data mining and machine learning techniques, we developed models to forecast booking cancellations and identify high-value customer segments through RFM (Recency, Frequency, Monetary) analysis.

## Research Questions
1. What are the key factors influencing hotel booking cancellations, and how can machine learning algorithms be employed to develop a predictive model for cancellation likelihood?
2. How can customer segmentation techniques, particularly RFM analysis, be applied to identify distinct customer groups and enable targeted marketing strategies?

## Dataset
The analysis uses a comprehensive dataset containing 119,390 hotel bookings with 32 variables, covering:
- Booking details (lead time, stay duration, etc.)
- Customer information (type, previous history)
- Room specifications
- Pricing data (ADR - Average Daily Rate)
- Booking channels and market segments

## Methodology
### Data Preprocessing
- Cleaned and standardized data from 119,390 entries to 83,889 high-quality records
- Handled missing values and outliers
- Reduced dimensions from 32 to 26 relevant variables
- Applied feature engineering and scaling

### Models Implemented
1. **Logistic Regression**
   - Baseline model with stepwise feature selection
   - Achieved accuracy: 0.7462

2. **Random Forest**
   - Best performing model
   - Accuracy: 0.8283
   - Kappa: 0.6304

3. **XGBoost**
   - Competitive performance
   - Accuracy: 0.8022
   - Kappa: 0.5638

4. **Neural Network**
   - Complementary approach
   - Accuracy: 0.7678
   - Sensitivity: 0.7853
   - Specificity: 0.7396

5. **Decision Tree**
   - Interpretable model
   - Accuracy: 0.7662
   - Sensitivity: 0.7994
   - Specificity: 0.7545

### Customer Segmentation
Implemented RFM analysis to categorize customers into:
- High-Value Customers (Type 3)
- Potential Growth Customers (Type 2 and 4)
- Low Engagement Customers (Type 1)

## Key Findings & Recommendations
1. **Model Performance**
   - Random Forest emerged as the superior model for cancellation prediction
   - Decision trees provide transparent insights into cancellation factors

2. **Customer Retention Strategies**
   - Focus on enhancing satisfaction for high-value customers
   - Implement targeted promotions for potential growth segments
   - Develop reactivation strategies for low engagement customers

3. **Operational Insights**
   - Identified critical factors affecting booking cancellations
   - Developed framework for predictive analytics in hotel management

## Technical Requirements
- R programming language
- Key libraries: 
  - Data processing: readr, dplyr, DataExplorer
  - Visualization: ggplot2, ggcorrplot
  - Machine learning: caret, randomForest, xgboost, nnet
  - Analysis: car, ROSE, ROCR, arules

## Contributors
- Yashkumar Kalariya
- Sahil Patel
- Drashti Khatra

