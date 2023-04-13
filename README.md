[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/Hf055y1F)
# Final Project - Data Cleaning
### Machine Learning Foundations with Python (90-803)
#### Spring 2023


**DUE DATE: Thursday, March 30th, 2023 before 11:59 PM**


---

Please read the following instructions carefully and do one submission per team!

Same as in Lab 8, make sure to join this submission as a team. In this case name your teams as follows: `team#_initalsMember1_initalsMember2_initalsMember3`

- For example: If I'm team 1 (on Canvas) and my initials are `GGS`, and my team member 2's initials are `JF`, we would name our group for this assignment: `team1_GGS_JF`.

**Remember that one of you has to create the team name on GitHub classroom and then the rest of you must join the same team**

---

### Tasks To Do

For this delivery, you must dive deeper into your datasets, by performing three main tasks:

1. Reading and Cleaning your dataset/s 

	- Explore if your dataset/s has NAs and deal with them (or provide an explanation for keeping them and how you will deal with them moving forward)
	- If you are doing a classifier take note of how many data points per class you have (and what are you going to do with them).
	- Any other necessary conversation such as dealing with categorical variables, verifying each variable is the right type.
	-  If you have more than one dataset make sure to clean ALL of your datasets!

2. Decide whether you are merging your datasets or keeping them separate.
	- If you are keeping your datasets separate provide a brief explanation of how you are going to use each dataset.
	- If you are joining your datasets check that you are not losing relevant data and you are joining your dataset correctly.

3. Provide at least two initial visualizations that describe your data. These can be a correlation plot of all the variables, a boxplot or density plots of the variables, or even a plot specific to any of the questions you are trying to tackle.

4. Define your classification or prediction variables (or none if you're doing unsupervised learning). 

5. Refine the 2-3 questions you want to answer with your datasets (based on the feedback you received from your previous assignment)

6. Do a pre-liminary test. Train a model (prediction or classification) with your clean dataset. Report how good is this initial test. You only need to do this for one of your questions.



The idea - by the end of this delivery - is to have a clean source of data that the whole team can use moving forward. If you discover you don't have enough data or the specific problem you choose is not enough for modeling then use this assignment to change your topic and datasets. You still need to submit a cleaned dataset by the end of this assignment.

---

### Submission

- Include your Jupyter Notebook/s in this repo
- Include your data inside the `data` folder
- Modify the last section of this README to include your revised questions and any additional instructions.

In each Jupyter notebook include:

- The class and assignment (first cell)
- The name of your team (first cell)
- The full names of your teammates (first cell)
- Explanations where needed for your tasks. Include enough comments and markdown cells for use to follow your cleaning process.
- Remember to only use packages we have seen in this class (or 90-800)
- A section with References at the end of the notebook


### Warnings (read carefully):

- You will receive 0 points if you do not submit your Jupyter notebook (.ipynb) and/or I'm not able to run it.
- List any references you used, even if they are one of the books assigned for this class. If this section is incomplete you will be deducted 30% of your final grade.
- If there are no comments to explain your code you will receive 0 in this assignment.

---

### Revised Questions - Please fill in
In this section list out your revised questions.

We have revised our questions to the following:

- Q1. Why did major cities experience different population losses during the pandemic? (target variable: population change percentage 2019-2020)
	- What are the most important factors that help us predict where people want to live?
	- What are the most important factors that help us predict current demographic changes?

- Q2. How can we predict crime rates in a city based on the available data? (target variable: crime rate per 100,000 people)

- Q3. What are some ways we can cluster cities into categories based on all available data, and will this reveal any geographical patterns about city development? (unsupervised learning, clustering)

---

### Notes - Please fill in

- In this section, include any last clarification notes about your project.
- If you have more than one notebook include instructions as to how to run them (in which order) and a brief description of what each notebook has.

1. Besides the packages we use in class, we also use the following packages for downloading data:
	- us: https://pypi.org/project/us/
	- census: https://pypi.org/project/census/
	- Please install these packages before running the notebooks.

2. For detailed instructions on how to download the data and run the notebooks, please refer to the **DATA CLEANING README** file.





