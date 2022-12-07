<!-- hide -->
# Boosting Algorithm Project Tutorial
<!-- endhide -->

- Bike sharing system can be a virtual sensor network that can be used for sensing mobility in a city. Hence, it is expected that most of important events in the city could be detected via monitoring these data.

- In this project, practice your new Boosting Algorithm skills trying to predict bike rental in a specific city. 


## 🌱  How to start this project

You will not be forking this time, please take some time to read this instructions:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the recently created repository on Gitpod by using the [Gitpod button extension](https://www.gitpod.io/docs/browser-extension/).
3. Once Gitpod VSCode has finished opening you start your project following the Instructions below.

## 🚛 How to deliver this project

Once you are finished creating your model, make sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

**Predicting bike rental using Boosting Algorithm**


**Step 1:**

The dataset can be found in this project folder as 'bike_sharing_dataset.csv' file. The core data set is related to the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in http://capitalbikeshare.com/system-data. You are also welcome to load it directly from the following link (`https://raw.githubusercontent.com/4GeeksAcademy/random-forest-project-tutorial/main/impressions.csv`), or to download it and add it to your data/raw folder. In that case, don't forget to add the data folder to the .gitignore file.

Time to work on it!

**Step 2:**

Explore and clean the data.

**Step 3:**

Build a first baseline model using Linear Regression. Chose an evaluation metric. Then, use a boosting algorithm and evaluate the performance of both models.

**Step 4:**

Use the app.py to create your pipeline. 

**Step 5:**

To save your model and be able to use it later use the following code:

```py

import pickle

filename = 'finalized_model.sav'
pickle.dump(model, open(filename, 'wb'))
```

In your README file write a brief summary.