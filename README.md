# Student Alcohol Consumption

## Overview
This project analyzes a dataset containing social, gender, and study information from secondary school students to explore the factors influencing their alcohol consumption and academic performance. The goal is to conduct exploratory data analysis (EDA) and potentially predict students' final grades based on various attributes.

## Motivation
The motivation for this project stems from the interest in understanding how social and educational factors affect students' behavior, particularly their alcohol consumption. By analyzing this data, we can gain insights that may help in developing strategies to support students' well-being and academic success.

## Dataset Features
The dataset includes the following features for both the math (`student-mat.csv`) and Portuguese language (`student-por.csv`) courses:

- **school**: Student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
- **sex**: Student's sex (binary: 'F' - female or 'M' - male)
- **age**: Student's age (numeric: from 15 to 22)
- **address**: Student's home address type (binary: 'U' - urban or 'R' - rural)
- **famsize**: Family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
- **Pstatus**: Parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
- **Medu**: Mother's education (numeric: 0 - none, 1 - primary education, 2 – 5th to 9th grade, 3 – secondary education, 4 – higher education)
- **Fedu**: Father's education (numeric: 0 - none, 1 - primary education, 2 – 5th to 9th grade, 3 – secondary education, 4 – higher education)
- **Mjob**: Mother's job (nominal: 'teacher', 'health' care related, 'services', 'at_home' or 'other')
- **Fjob**: Father's job (nominal: 'teacher', 'health' care related, 'services', 'at_home' or 'other')
- **reason**: Reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
- **guardian**: Student's guardian (nominal: 'mother', 'father' or 'other')
- **traveltime**: Home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, 4 - >1 hour)
- **studytime**: Weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, 4 - >10 hours)
- **failures**: Number of past class failures (numeric: n if 1<=n<3, else 4)
- **schoolsup**: Extra educational support (binary: yes or no)
- **famsup**: Family educational support (binary: yes or no)
- **paid**: Extra paid classes within the course subject (binary: yes or no)
- **activities**: Extra-curricular activities (binary: yes or no)
- **nursery**: Attended nursery school (binary: yes or no)
- **higher**: Wants to take higher education (binary: yes or no)
- **internet**: Internet access at home (binary: yes or no)
- **romantic**: In a romantic relationship (binary: yes or no)
- **famrel**: Quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
- **freetime**: Free time after school (numeric: from 1 - very low to 5 - very high)
- **goout**: Going out with friends (numeric: from 1 - very low to 5 - very high)
- **Dalc**: Workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
- **Walc**: Weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
- **health**: Current health status (numeric: from 1 - very bad to 5 - very good)
- **absences**: Number of school absences (numeric: from 0 to 93)
- **G1**: First period grade (numeric: from 0 to 20)
- **G2**: Second period grade (numeric: from 0 to 20)
- **G3**: Final grade (numeric: from 0 to 20, output target)

## Source Information
P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th Future Business Technology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.

Fabio Pagnotta, Hossain Mohammad Amran.
Email: fabio.pagnotta@studenti.unicam.it, mohammadamra.hossain@studenti.unicam.it
University Of Camerino

Dataset available at: [Kaggle](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption?select=student-por.csv)

## Technical Aspects
In this project, I used the following technologies and tools:
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Development Environment**: Jupyter Notebook
- **Data**: The dataset was obtained from the UCI Machine Learning Repository.

## To Do
Here are some improvements and features I plan to implement in the future:
- Conduct detailed exploratory data analysis (EDA).
- Develop predictive models for students' final grades.
- Improve the documentation and visualization of findings.
- Investigate the relationship between alcohol consumption and academic performance.

## Credits
Special thanks to [mention any person or resource that helped with the project, such as tutorials, articles, or colleagues who collaborated with you]. 
- [Resource or author's name] - [Description of what you learned or how it was helpful]
