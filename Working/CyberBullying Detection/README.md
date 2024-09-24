# Cyberbullying Detection on Twitter

## Overview
This project analyzes a dataset containing over 47,000 tweets labeled according to different classes of cyberbullying. The primary goal is to create models that can automatically flag potentially harmful tweets and break down the patterns of hatred. Given the rise of social media and the increase in cyberbullying incidents during the Covid-19 pandemic, this project aims to contribute to a safer online environment.

## Motivation
The motivation for this project stems from the alarming rise in cyberbullying incidents, particularly during the Covid-19 pandemic. With increased screen time and decreased face-to-face interactions, the risk of cyberbullying has escalated. According to UNICEF, a significant percentage of middle and high school students have experienced or witnessed cyberbullying. By analyzing this dataset, we hope to develop effective models that can help identify and mitigate cyberbullying online.

## Dataset Features
The dataset contains tweets labeled into the following categories of cyberbullying:
- **Age**: Tweets targeting individuals based on their age.
- **Ethnicity**: Tweets containing hate speech related to ethnicity.
- **Gender**: Tweets that involve gender-based discrimination.
- **Religion**: Tweets that target individuals based on their religious beliefs.
- **Other Types of Cyberbullying**: Any other form of cyberbullying not covered by the above categories.
- **Not Cyberbullying**: Tweets that do not fall into any of the bullying categories.

The data has been balanced to contain approximately 8,000 samples for each class, allowing for effective training of classification models.

## Technical Aspects
In this project, I utilized the following technologies and tools:
- **Languages**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, NLTK (Natural Language Toolkit), TensorFlow/Keras (if using deep learning models)
- **Development Environment**: Jupyter Notebook
- **Data**: The dataset can be accessed from [https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification].

## Package Installation
To run this project, ensure that the following Python packages are installed:
```bash pip install numpy pandas matplotlib seaborn scikit-learn nltk tensorflow```

## Data Loading
Data is loaded from CSV files that contain information about tweets and their associated labels. Initial checks are performed to identify any missing values or data integrity issues.

## Initial Data Exploration
An exploratory data analysis (EDA) is conducted to better understand the dataset, including examining data types, summary statistics, and identifying any missing values.

## Data Preparation and Visualization
Data visualization plays a crucial role in identifying trends and patterns associated with different types of cyberbullying. Text preprocessing techniques are applied to clean and prepare the data for modeling, and visualizations are created to explore word frequencies and patterns.

## Modeling
Machine learning models are developed to predict the type of cyberbullying in tweets. The following models are considered:
- Multi-class classification models to predict the type of cyberbullying.
- Binary classification models to flag potentially harmful tweets.

## Model Evaluation
Models are evaluated using metrics such as accuracy, precision, recall, F1 score, and confusion matrix to assess their performance in detecting cyberbullying.

## Conclusion and Next Steps
The analysis aims to provide insights into patterns of cyberbullying on social media and develop effective models for detection. Future work could include exploring advanced techniques such as deep learning and implementing real-time detection systems.

## Acknowledgements
If you use this dataset in your research, please credit the authors.

### Citation
J. Wang, K. Fu, C.T. Lu, “SOSNet: A Graph Convolutional Network Approach to Fine-Grained Cyberbullying Detection,” Proceedings of the 2020 IEEE International Conference on Big Data (IEEE BigData 2020), December 10-13, 2020.

## License
This project is licensed under the CC BY 4.0 License.

## Contact
For inquiries, please contact [your email address].