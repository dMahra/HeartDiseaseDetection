# HeartDiseaseDetection (Classification Practice)


Heart disease refers to various types of conditions that can affect heart function. These types include: coronary artery (atherosclerotic) disease that affects the blood supply to the heart, valvular heart disease that affects how the valves function to regulate blood flow in and out of the heart, cardiomyopathies that affect heart muscles, heart rhythm disturbances (arrhythmias) that affect the electrical conduction and congenital heart diseases where the heart has structural problems that develop before birth. Heart disease is the major cause of morbidity and mortality globally: Causing 25% of all deaths in the United States. In 2016, around 17.9 million people died from heart diseases (31% of all global deaths). 

It is, however, difficult to identify high risk patients because of the mulfactorial nature of several contributory risk factors such as diabetes, high blood pressure, high cholesterol et cetera. ML proves to be effective in assisting in making decisions and predictions from the large quantity of data produced by the healthcare industry on heart disease.

As of now, I tested two models, a random forest and a SVM. The random forest was more accurate(95%) based on the training data, so I kept that as the primary model for use. I created a confusion matrix with our algorithm and testing data to better understand what type of error was inhibiting the model from being more accurate. 

![image](https://user-images.githubusercontent.com/54589314/123049256-33b4e800-d3b4-11eb-8641-ab70f0a9e3ea.png)

The confusion matrix above shows us that there were three cases where our algorithm said a patient wasn't susceptible to heart disease when they actually were. This means we had 3 type 1 errors. 
