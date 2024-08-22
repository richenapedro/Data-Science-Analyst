# Amazon Product Sales Prediction

## Project Description
This project aims to analyze and forecast future sales of products sold on Amazon, using a dataset that contains information about prices, ratings, availability, and sales volume. Through data science techniques, the project seeks to identify patterns and insights that can help optimize sales and marketing strategies.

## About the Dataset
The dataset includes the following columns:

- **asin**: Amazon Standard Identification Number, a unique identifier for each product.
- **product_title**: Name or title of the product.
- **product_price**: Current price of the product.
- **product_original_price**: Original price of the product before discounts.
- **currency**: Currency in which the product price is listed.
- **product_star_rating**: Average star rating of the product.
- **product_num_ratings**: Number of ratings the product has received.
- **product_url**: URL of the product page on Amazon.
- **product_photo**: Link to the product photo.
- **product_num_offers**: Number of different offers available for the product.
- **product_minimum_offer_price**: Minimum price of the available offers.
- **is_best_seller**: Indicator if the product is a best seller.
- **is_amazon_choice**: Indicator if the product is an Amazon choice.
- **is_prime**: Indicator if the product is eligible for Amazon Prime.
- **climate_pledge_friendly**: Indicator if the product is labeled as climate-friendly.
- **sales_volume**: Sales volume of the product.
- **delivery**: Information about the delivery options for the product.
- **has_variations**: Indicator if the product has variations (e.g., different sizes or colors).
- **product_availability**: Availability status of the product.
- **unit_price**: Price per unit of measurement.
- **unit_count**: Number of units included in the product price.

## Potential Data Analysis and Data Science Techniques

### Descriptive Statistics
- Calculate summary statistics for numerical columns (mean, median, min, max of prices, ratings, sales volume).
- Count frequencies for categorical columns (how many products are best sellers, Amazon choices, Prime eligible).

### Price Analysis
- Compare current prices with original prices to assess discount levels.
- Analyze price trends across different categories or brands.

### Rating Analysis
- Examine the distribution of product ratings.
- Correlate the number of ratings with the average star rating to identify trends.

### Sales Volume Analysis
- Identify best-selling products.
- Analyze sales volume in relation to prices, ratings, and other attributes.

### Product Classification
- Group products based on categories such as best seller, Amazon choice, Prime eligibility, and climate-friendly status.
- Perform clustering to identify patterns or segments among products.

### Predictive Modeling
- **Price Prediction**: Use regression models (e.g., linear regression, decision trees) to predict product prices based on attributes like ratings, number of offers, and best seller status.
- **Sales Volume Prediction**: Apply regression analysis or time series forecasting to predict future sales volumes.
- **Rating Prediction**: Predict product ratings using characteristics such as price, number of ratings, and best seller status.

### Recommendation Systems
- Build recommendation systems based on collaborative filtering or content-based filtering to suggest products to customers based on their preferences and past behavior.

### Sentiment Analysis
- Analyze customer reviews (if available) to assess sentiment and correlate it with ratings and sales volume.

### Visualizations
- **Histograms and Bar Charts**: To visualize the distribution of prices, ratings, and sales volumes.
- **Box Plots**: To compare prices and ratings across different product categories.
- **Scatter Plots**: To visualize relationships between numerical variables (e.g., price vs. sales volume).
- **Heatmaps**: To show correlations between different attributes.

## Data Cleaning and Preprocessing
- Handle missing values (e.g., impute, remove).
- Convert categorical variables into numerical format using techniques like one-hot encoding.
- Normalize or scale numerical features if necessary for certain algorithms.

## Advanced Techniques
- **Feature Engineering**: Create new features from existing data (e.g., percentage discount from original and current prices).
- **Dimensionality Reduction**: Use PCA or other techniques if the dataset has high dimensionality.

These analyses and techniques will help uncover valuable insights, optimize pricing strategies, improve customer satisfaction, and ultimately drive sales and profitability.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- [Other libraries as necessary]

## Contributions
Contributions are welcome! Feel free to open a pull request or report issues.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.