# Predicting Stress in Bangladeshi University Students: A LIME-Interpretable Machine Learning Approach

## Citation

**Chapter:** Predicting Stress in Bangladeshi University Students: A LIME-Interpretable Machine Learning Approach  
**In Book:** *Proceedings of the 2nd International Conference on Big Data, IoT, and Machine Learning: BIM 2023*  
**Authors:** Md. Hamid Hosen, Mohammad Tanvirul Islam, Kahakashan Ashraf, Promila Haque  
**Published:** August 2024

### Full Citation:
Hosen, Md. H., Islam, M. T., Ashraf, K., & Haque, P. (2024). Predicting Stress in Bangladeshi University Students: A LIME-Interpretable Machine Learning Approach. In *Proceedings of the 2nd International Conference on Big Data, IoT, and Machine Learning: BIM 2023*.

---

## Abstract

University students suffer from high levels of stress, which adversely affects their academic performance, mental and physical health, and overall well-being. This research applies machine learning algorithms and explainable artificial intelligence (XAI) techniques, such as LIME, to predict stress levels in Bangladeshi university students. The study uses data from multiple universities in Bangladesh and achieves 90% accuracy using Support Vector Classifier (SVC). LIME is employed to understand model behavior and mitigate biases.

## Keywords

Mental health, Stress, Machine learning, XAI, Lime, University students

---

## Table of Contents

1. [Introduction](#introduction)
2. [Literature Review](#literature-review)
3. [Methodology](#methodology)
   - Data Collection
   - Data Pre-processing
   - Feature Selection
   - Machine Learning Algorithm
4. [Results](#results)
5. [Conclusion & Future Work](#conclusion-future-work)
6. [References](#references)

---

## Introduction

Stress among university students is a major problem globally. This research explores the factors contributing to stress in Bangladeshi students and uses machine learning algorithms to predict their stress levels. By detecting stress early, interventions can be implemented to reduce the negative impacts on students’ academic performance and well-being.

---

## Literature Review

This section explores various studies on stress prediction among university students using machine learning. Previous research highlights the use of algorithms such as Support Vector Machine (SVM), Random Forest, and Decision Trees for predicting stress levels. However, few studies have incorporated explainable AI methods like LIME to enhance model transparency.

---

## Methodology

### Data Collection
Data was gathered from 571 students in Bangladesh using an online survey from September 2022 to January 2023. The survey covered academic details, mental health factors, and personal issues contributing to stress.

### Data Pre-processing
We cleaned the dataset, handled missing values using statistical techniques, and encoded categorical data. 

### Feature Selection
RFE (Recursive Feature Elimination) was used to select the most important features for the prediction models. Random Forest was identified as the best algorithm with an accuracy of 83%.

### Machine Learning Algorithms
We applied several machine learning algorithms, including Random Forest, Support Vector Classifier (SVC), K-Nearest Neighbors (KNN), and Gaussian Naive Bayes. GridSearchCV was used for hyperparameter tuning.

---

## Results

The research shows that SVC achieved the highest accuracy of 90%. Other models, such as Decision Trees and Random Forest, showed lower accuracy rates. The precision, recall, and F1 scores were also calculated to evaluate model performance.

---

## Conclusion & Future Work

The study found that stress significantly impacts students' academic performance and health. By applying machine learning and LIME, we were able to predict stress levels and understand the contributing factors. For future work, the dataset will be expanded to include more universities, and advanced deep learning techniques will be explored.

---

## References

1. Bayram, N., Bilgel, N.: The prevalence and socio-demographic correlations of depression, anxiety, and stress among a group of university students. *Social Psychiatry and Psychiatric Epidemiology*. 43, 8, 667–672 (2008).
2. Mamun, M.A. et al.: Mental health problems and associated predictors among Bangladeshi students. *International Journal of Mental Health and Addiction*. 20, 2, 657–671 (2019).
3. Brenneisen Mayer, F. et al.: Factors associated with depression and anxiety in medical students: A multicenter study. *BMC Medical Education*. 16, 1 (2016).
4. Rois, R. et al.: Prevalence and predicting factors of perceived stress among Bangladeshi university students using machine learning algorithms. *Journal of Health, Population, and Nutrition*. 40, 1 (2021).
5. Mahmud, S. et al.: Machine learning approaches for predicting suicidal behaviors among university students in Bangladesh during the COVID-19 pandemic. (2022).
6. Ahuja, R., Banga, A.: Mental stress detection in university students using machine learning algorithms. *Procedia Computer Science*. 152, 349–353 (2019).
7. Shaw, A., Simsiri, N., Deznaby, I., Fiterau, M., & Rahaman, T.: Personalized student stress prediction with deep multitask network. *arXiv preprint arXiv:1906.11356*. (2019).
8. Disha, S. et al., D.S.: Stress prediction of students using machine learning. *International Journal of Mechanical and Production Engineering Research and Development*. 10, 3, 5609–5620 (2020).
9. Priya, A. et al.: Predicting anxiety, depression, and stress in modern life using machine learning algorithms. *Procedia Computer Science*. 167, 1258–1267 (2020).
10. Lovibond, S.H., Lovibond, P.F.: Depression anxiety stress scales. *PsycTESTS Dataset*. (1995).
11. Alim, S.A. et al.: Translation of DASS 21 into Bangla and validation among medical students. *Bangladesh Journal of Psychiatry*. 28, 2, 67–70 (2017).
12. Gosling, S.D. et al.: A very brief measure of the big-five personality domains. *Journal of Research in Personality*. 37, 6, 504–528 (2003).
13. Guyon, I., & Elisseeff, A.: An introduction to variable and feature selection. *Journal of machine learning research*. 1157-1182 (2003).
14. Chawla, N.V. et al.: SMOTE: Synthetic minority over-sampling technique. *Journal of Artificial Intelligence Research*. 16, 321–357 (2002).
15. Breiman, L.: Machine Learning. *45*, 1, 5–32 (2001).
16. Onan, A.: Sarcasm identification on Twitter: A machine learning approach. *Advances in Intelligent Systems and Computing*. 374–383 (2017).
17. Ribeiro, M.T. et al.: “Why should I trust you?” *Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining*. 1135–1144 (2016).
18. Dieber, J., & Kirrane, S.: Why model why? Assessing the strengths and limitations of LIME. *arXiv preprint arXiv:2012.00093*. (2020).
