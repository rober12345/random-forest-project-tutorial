<!-- hide -->
# Random Forest Project Tutorial
<!-- endhide -->

- In this project, practice your new Random Forest skills trying to predict the success of your marketing campaign. Then, as always, optimize your hyperparameters.


## 🌱  How to start this project

You will not be forking this time, please take some time to read this instructions:

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template/generate) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template).
2. Open the recently created repository on Gitpod by using the [Gitpod button extension](https://www.gitpod.io/docs/browser-extension/).
3. Once Gitpod VSCode has finished opening you start your project following the Instructions below.

## 🚛 How to deliver this project

Once you are finished creating your model, make sure to commit your changes, push to your repository and go to 4Geeks.com to upload the repository link.

## 📝 Instructions

**Predicting campaign success using Random Forest**

We need to build a project that builds, trains and evaluates a prediction model for the number of ad impressions delivered in a digital marketing campaign.

**Step 1:**

The dataset can be found in this project folder as 'impressions.csv' file. We will use data from past marketing campaigns in order to predict the outcome of future campaigns. Specifically for this project we will try to predict the number of impressions of a single campaign. You are welcome to load it directly from the link (`https://raw.githubusercontent.com/4GeeksAcademy/random-forest-project-tutorial/main/impressions.csv`), or to download it and add it to your data/raw folder. In that case, don't forget to add the data folder to the .gitignore file.

Time to work on it!

**Step 2:**

Explore and clean the data.

**Step 3:**

Build a first predictive model using Random Forest. Chose an evaluation metric and then optimize your model hyperparameters.

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
