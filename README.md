# News Categorization Project

## Overview
This project focuses on news categorization using two datasets: [MIND dataset](https://msnews.github.io/) and [Kaggle News Category dataset](https://www.kaggle.com/datasets/rmisra/news-category-dataset). The combined dataset includes over 500,000 news articles. The project involves data cleaning, combining datasets, and applying machine learning models to classify news articles.

## Project Structure
1. **Data Preparation**: Initial analysis and dataset combination. Addressed column differences and formatted text for consistency.
2. **Data Cleaning**: Removed unnecessary columns and handled missing data. Standardized category text formatting and merged datasets.
3. **Data Analysis**: Conducted frequency analysis, text length distribution, and sentiment analysis.
4. **Model Building**: Created a machine learning model using Spark and Elephas for distributed deep learning.

## Data Sources
- **MIND dataset**: Metadata and article content used for training/testing.
- **Kaggle News Category dataset**: Additional articles in JSON format.
  
## Tools and Libraries
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, TextBlob.
- **Apache Spark**: For large-scale data processing.
- **Elephas**: Distributed deep learning on Spark.
- **Keras**: Used for model building.
- **Google Cloud**: Data storage and computing resources.

## Results
- **Model Performance**: The model showed low accuracy and high validation error, with potential for improvement through techniques such as regularization and additional hyperparameter tuning.
- **Challenges**: Limited computational resources impacted the ability to fully optimize the model.

## Improvements
- Increase number of epochs and explore more efficient hyperparameter tuning techniques.
- Implement over/under sampling techniques for better class distribution balance.

## References
- Fangzhao Wu et al. (2020). MIND: A Large-scale Dataset for News Recommendation. ACL.
- Keras Documentation.
- TextBlob Documentation.
- Elephas Documentation.

## Contact
For any questions or collaboration opportunities, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/mamblls) or [GitHub](https://github.com/mamblls).
