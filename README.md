### **USE Tasks.ipynb**  
### ***[DO NOT USE] Tasks-old-includes kmeans.ipynb which followed original Assignment Specification. Specification was revised.***
---

# MLS_Tasks      
GMIT Higher Diploma Data Analytics  
Machine Learning and Statistics Module 52954  
Assignment: ML Tasks  
Lecturer: Ian McLoughlin  
Student: Fiona O'Riordan
Due Date: 01 January 2020  

## Purpose  

The purpose of this repository is to implement four tasks as follows:  

1. October 5th, 2020: Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library1 or otherwise. You should research the task first and include references and a description of your algorithm.  

2. November 2nd, 2020: The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.  

3. November 16th, 2020: The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))^2)/len(x)) . However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x) . Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.  

4. December 16th, 2020:Use scikit-learn to apply k Nearest Neighbours clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.  

## Contents
1. gitignore 
2. README.md
3. **Tasks.ipynb**
4. ***[DO NOT USE]*** Tasks-old-includes kmeans.ipynb ***[DO NOT USE]****

Note: "Tasks-old-includes kmeans.ipy" should not be used.  This is an older file that I wished to keep to keep record of my work on Kmeans. This file is not for submission.  Please use tasks.ipynb

## Prequisites
The following will need to be installed on your machine.
Python ( I have used Python 3.8.3 for this project). I would recommend anaconda installation [Anaconda](https://www.anaconda.com/products/individual).   
Python, Jupyter notebooks comes with Ananconda.  

Python libraries: decimal, re,scipy.stats, matplotlib.pyplot, numpy, pandas, seaborn, sklearn, sklearn.cluster.  

## Cloning the repository
Cloning allows you to create and use a copy of this repositiory on your local machine. 

1. In this [repository](https://github.com/fionaoriordan/MLS_Tasks). 
2. Click on the green button "Code". Select "Clone with HTTPS". Copy the URL.  
3. In your terminal on your machine navigate to your preferred directory (folder). Type git clone https://github.com/fionaoriordan/MLS_Tasks.git ( this is the URL you have copied). 
4. The repository is now installed

## Executing the repository
1. In your terminal navigate to the the folder where you cloned this repository.
2. jupyter notebook
3. jupyter notebook will launch.
4. Click on Tasks.ipynb 
5. You are now ready to use this repository.

## Viewing the repository on GitHub.
Click on Tasks.ipynb in this repository in GitHub will allow you to view this project without the need to clone or install Anaconda or any of the other prequisites.

Best Wishes,
Fiona



