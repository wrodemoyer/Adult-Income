# Adult-Income

## Exploring the possibility in predicting income level based on the individual’s personal information
William Rodemoyer

## Data
https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, and etc.

## Data Analysis Visuals
![image](https://github.com/wrodemoyer/Adult-Income/assets/128072861/9fb696d1-f031-4b44-92b7-79399b6f024a)

Of the individuals who make greater than 50k, clearly are older in age on average.

!![image](https://github.com/wrodemoyer/Adult-Income/assets/128072861/788e50c3-e905-4fa5-985e-a4d55b61893e)

Both Genders who make more than 50k, work more hours per week than those who make 50k or less.

On average, males work more hours per week compared to females when comparing their respectable income categories.

## Models
I used 2 models to predict the income
  - Logistic Regression Model
  - KNN Model
              
           Model Name       Precision    Recall      F1 Score     Accuracy

           LR Tuned Train   0.737003     0.602072    0.662740     0.852826
           
           LR Tuned Test    0.732665     0.605663    0.663138     0.853815
          
           
           Model Name       Precision    Recall      F1 Score     Accuracy
                                              
           KNN Tuned Train   0.773205    0.586132    0.666796     0.859307

           KNN Tuned Test    0.725936    0.562500    0.633852     0.845611
 
 ## Final Model Results
 After comparing the models, my recommendation is:
 - Logistic Regression Model
  - Both models scored very close, but we want the highest scoring model possible
  - This model gave us an 85% chance of correctly predicting an individuals income. 
 
 ## For Further Informtion
For any additional questions, please contact wrodemoyer@gmail.com
