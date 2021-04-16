# STROKE PROJECT by Edwin Pitono and Alan Perfettini
Data Analysis Full-Time FEB2021, Paris

March 26th 2021
Training project of data analysis and hypothesis testing

**Content**

Project Description
Objective
Dataset content
Workflow
Presentation

![Stroke_Web](https://user-images.githubusercontent.com/76606558/114902277-f3fedc80-9e15-11eb-89b5-bb2c342d281a.png)

**Project Description** 

Stroke dataset analytics : Data analysis and hypothesis testing with linear regression.
Dataset obtained from Kaggle.

**Objective**

To learn to test hypothesis with linear regression

**Dataset content**

Demographic and medical data including stroke event of 5110 patients.

**Workflow**

1. Dataset import
2. Data cleaning, data manipulation and data visualization 
3. Hypothesis statement
4. Testing hypothesis with linear regression



**Conclusion**

The features presented in the dataset are not relevant with a linear regression model. The continuous values presented in the dataset (average glucose level, age and BMI) cannot be used to predict the on event of a stroke. 

<img width="415" alt="Capture d’écran 2021-04-15 à 19 46 23" src="https://user-images.githubusercontent.com/76606558/114915016-57dbd200-9e23-11eb-8939-1a6ed7acc5d3.png">
The R-Squared visible in the upper right corner is clearly low (the higher the value the better). This means that clearly the linear regression is not applicable here.

Interestingly we can see two different populations in the plot below. The cloud of points below represents people witout diabetes and the upper cloud of points represents people with higher average blood sugar level (probably persons with diabetes). And the trend line is showing that the more the BMI (Body Mass Index) goes up, the more the average glucose level becomes.

<img width="416" alt="Capture d’écran 2021-04-15 à 18 44 57" src="https://user-images.githubusercontent.com/76606558/114907860-cd43a480-9e1b-11eb-9b05-3cc3c531680c.png">

Thanks to Alan my fellow data analyst work mate who has tremendously helped me in the process. And thanks to our teacher and TA Eldiaas and Mathieu for their time and their energy to help us.

**Contact me**

https://www.linkedin.com/in/edwin-pitono/



