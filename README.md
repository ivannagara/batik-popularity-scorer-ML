# batik-popularity-scorer-ML
Web scraped data from online shopping malls, and used ML model to detect if a Batik will be accepted by most people or will it not be a good type of product.

The popularity score is calculated based on the ratings and the amount sold.

I am using the method of the One-Hot Encoding technique to determine if the specific product has that specific feature or not,
and this feature is extracted from the name of the product (Assuming if the product name is equal to the original product).

For the machine learning model itself, I am using the Random Forest Regressor and a scaler of Min-Max Scaler.
