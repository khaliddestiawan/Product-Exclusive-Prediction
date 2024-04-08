# Project Overview : Product Exclusive Classification
The goal of this project is to develop a predictive model that can determine whether a product is exclusive or not based on its features. The project aims to analyze various variables associated with a product and identify which variables have the most significant impact on determining its exclusivity.

The main objective of the project is to build a robust model that can accurately predict the exclusivity of a product. By analyzing and understanding the key variables that influence product exclusivity, the model will be able to make predictions based on these factors.

The project will involve the following steps:

1. Data Collection: Gather a dataset containing information about various products, including their features and whether they are classified as exclusive or not.

2. Data Analysis: Perform exploratory data analysis to gain insights into the variables and their relationships with product exclusivity. Identify which variables have the most significant impact on determining exclusivity.

3. Feature Selection: Select the most relevant features for the classification task. This step involves identifying the variables that have the highest correlation or predictive power for determining exclusivity.

4. Model Development: Build a classification model using machine learning algorithms. Train the model on the labeled dataset, using the selected features as input and the product's exclusivity as the target variable.

5. Model Evaluation: Assess the performance of the developed model using appropriate evaluation metrics such as accuracy, precision, recall, and F1 score. Validate the model's predictive capabilities through cross-validation and other techniques to ensure its generalizability.

## Data Collection:

- the data is acquired from assignments that i get from Datascience Course

## Data Analysis:

### Insight for Data Preprocessing:

Univariate:
- Most numerical columns, except for the rating, exhibit outliers.
- The majority of numerical columns have skewed distributions.
- There are noticeable variations in the distribution shapes among the numerical columns, particularly in the `price` column.
- The categorical columns have relatively balanced distributions, with the largest category proportion being less than 10%.

Multivariate:
- There is multicollinearity between the `price` and `value_price` columns, indicating that one of them could be omitted.
- The `love` and `review` columns show a high correlation, but it is not strong enough to warrant the removal of either column.
- No numerical column demonstrates a strong correlation with the target variable (`exclusive`).
- The pairplot does not reveal distinct patterns or clusters, suggesting the potential need for a nonlinear model.

### Business Insight:

- The average price for non exclusive product are higher than the exclusive product `54.986 : 35.123`.

- Exclusive product that have a rating `5.0` have an average price of `40.330` this average rating price is also the highest compared to other rating (1.0 - 4.5). meanwhile average price rating `5.0` for non exclusive product is significantly higher `72.406`, this rating 5.0 average price is the second highest for non exclusive product rating. rating `2.0` have the highest average price which is `75.188`.

- The categories with the highest number of exclusive products are `Perfume, Moisturizers, Face Serums, Value & Gift Sets, Face Wash & Cleansers, Face Masks, Hair Styling Products, Rollerballs & Travel Size, Face Brushes, and Eye Creams & Treatments`. Among these categories, Perfume stands out with the highest product count of `619`. 

- In the categories examined, the Lid Shadow Brush stands out with the highest average rating of `5.0`, reflecting exceptional customer satisfaction. Additionally, Body Products and Cologne have received significantly high average ratings, indicating their strong popularity and positive reception among consumers.

- For the brands, that have been assessed. Montblanc, Aether Beauty, and Four Sigmatic have attained a flawless average rating of `5.0`, signifying exceptional customer satisfaction. Furthermore, Golde, ReFa, and RODIN olio lusso have received notably high average ratings, underscoring their popularity and positive reception among consumers.

- When evaluating the brands, Buxom, stila, Makeup Eraser, Rosebud Perfume Co., and NARS emerged as the top 5 brands that received the highest number of customer reviews. Notably, Buxom garnered the maximum number of reviews, with an impressive count of `4759`, showcasing a significant level of customer engagement. On the other hand, NARS received a considerable number of reviews as well, with a minimum count of `1469`, reflecting the active participation of customers in providing feedback for these brands.

- The analysis reveals the top 5 most expensive brands based on the average price of their products. Dyson takes the lead with an average price of `$436.50`, followed by ReFa at `$223.33`, LightStim at `$209.00`, Jillian Dempsey at `$195.00`, and NuFACE at `$184.15`.

## Feature Selection:

## Model Development:

## Model Evaluation: