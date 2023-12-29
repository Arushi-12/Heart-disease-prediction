# Heart-disease-prediction

This model uses Linear Regression technique to predict heart diseases in patients.This uses the factors that influence heart disease such as body cholesterol levels, smoking habit,age, gender, heart rate, obesity, family history of illnesses, blood pressure, and work environment. 

It yields the following conclusions:
1.
![image](https://github.com/Arushi-12/Heart-disease-prediction/assets/118588760/0a895a39-6ca8-4a1d-9226-1ec6f49ff282)

Observations from the above plot:

cp {Chest pain}: People with cp 1, 2, 3 are more likely to have heart disease than people with cp 0.
restecg {resting EKG results}: People with a value of 1 (reporting an abnormal heart rhythm, which can range from mild symptoms to severe problems) are more likely to have heart disease.
exang {exercise-induced angina}: people with a value of 0 (No ==> angina induced by exercise) have more heart disease than people with a value of 1 (Yes ==> angina induced by exercise)
slope {the slope of the ST segment of peak exercise}: People with a slope value of 2 (Downslopins: signs of an unhealthy heart) are more likely to have heart disease than people with a slope value of 2 slope is 0 (Upsloping: best heart rate with exercise) or 1 (Flatsloping: minimal change (typical healthy heart)).
ca {number of major vessels (0-3) stained by fluoroscopy}: the more blood movement the better, so people with ca equal to 0 are more likely to have heart disease.
thal {thalium stress result}: People with a thal value of 2 (defect corrected: once was a defect but ok now) are more likely to have heart disease.

2.
![image](https://github.com/Arushi-12/Heart-disease-prediction/assets/118588760/b8e7b523-ec0f-4bb5-9101-dd17470412a5)

Observations from the above plot:

trestbps: resting blood pressure anything above 130-140 is generally of concern
chol: greater than 200 is of concern.
thalach: People with a maximum of over 140 are more likely to have heart disease.
the old peak of exercise-induced ST depression vs. rest looks at heart stress during exercise an unhealthy heart will stress more.

The accuracy of this algortihm is 86.79%.
