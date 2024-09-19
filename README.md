# Welcome to Experiment 4: Data Wrangling and Data Visualization!

## Hello, there! Let me welcome you to the fourth experiment in our Advanced Programming journey!
This time, we're diving deep into the powerful world of Data Wrangling and Data Visualization. If you've ever wondered how raw data trnsforms into meaningful insights, we're now in for a treat!

### In this experiment...
We will be working with the ECE Board Exam Dataset, and we're going to wrangle, analyze, and visualize it like pros. It's not just about crunching numbers... it's also about telling a story through data! Are we ready now? Let's go!

### I. Intended Learning Outcome
1. To identify the codes and functions needed in cleaning and visualizing data.
2. To be able to apply and use the different codes and functions in creating a Python program that will be used in data wrangling and data visualization.

### II. Instructions
Download the ECE Board Exam 2 Dataset and write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter notebook in the dedicated submission bin.

In this notebook, I'll guide you step by step through my thought process, breaking down complex data and making it digestible and visually appealing. By the end of this experiment, you'll see how wrangling the raw data and visualizing it can lead to powerful insights and better decison-making. Way to go, future data engineer!

## Problem 1: Using data wrangling and data visualization technique with storytelling, analyze the data, and present (i) dataframes; and (ii) visuals using dataset given.

        Step 1: Make sure we upload the needed ECE Board Exam 2 csv file on the same data file we'll be doing the code.
        Step 2: Import pandas as pd or just like I did, import pandas to your code which is the core tool used in this experiment for manipulating data.
        Step 3: With the .read_csv() method, the dataset are now being read by our code.
        Step 4: Satisfying the conditions of the problem by calling the student variable and specify 'Hometown' and use == to point the same memory location which is Visayas. Moreover, use the ampersand (&) to add another condition which is the students whose 'Math' is less then 70.
        Step 5: Use Vis to call all variable in one specifically Math which is our previous variable and call only the Name, Gender, Track, and Math on the dataset.
        Step 6: Print everything by entering 'print(Vis)' but since I wanted to make it more presentable, I used .to_string() method ommitting the index with the False key.

  There we go! Check the output for our first example in this experiment.

## Problem 1: Letter A. Use the format Instru = ["Name","GEAS","Electronics>70"]; where track is constant as Instrumentation and hometown Luzon.

        Step 1: Make sure we upload the needed ECE Board Exam 2 csv file on the same data file we'll be doing the code.
        Step 2: Import pandas as pd or just like I did, import pandas to your code which is the core tool used in this experiment for manipulating data.
        Step 3: With the .read_csv() method, the dataset are now being read by our code.
        Step 4: Satisfy the conditions by specifying the 'Hometowm' and use == to point at the memory location of Luzon, then an ampersand to add another condition which is 'Electronics' that has greater than 70, and another ampersand to add another condition which is 'Track' pointing a specific memory location for Instrumentation.
        Step 5: Use Instru to call all variable in one specifically Electronics variable which is our previous variable and call only the Name, GEAS, and Electronics.
        Step 6: Print everything by entering 'print(Instru)' but since I wanted to make it more presentable, I used .to_string() method ommitting the index with the False key.

  Another problem solved! Let's move on to the next one.

## Problem 1: Letter B. Use the format Mindy = ["Name","Track","Electronics","Average >=55"]; where hometown is constant as Mindanao and gender Female. 

        Step 1: Make sure we upload the needed ECE Board Exam 2 csv file on the same data file we'll be doing the code.
        Step 2: Import pandas as pd or just like I did, import pandas to your code which is the core tool used in this experiment for manipulating data.
        Step 3: With the .read_csv() method, the dataset are now being read by our code.
        Step 4: Let's make our own Average since its now given on the dataset with the use of .mean() method to get the mean of specific memory location inside our bracket which are Math, Electronics, GEAD, and Communication. For our column to be read, specify the axis to 1 because 0 is used for rows.
        Step 5: After doing so, call a random variable to make it simple and now specify the 'Hometown' with == to read the same memory location of Mindanao, 'Gender' which is Female, and the 'Average' of the students who acquired >= to 55.
        Step 6: Use Mindy to call all variable in one specifically Constant variable in our code which is our previous variable and call only the Name, Track, and Electronics with the use of brackets.
        Step 7: Print everything by entering 'print(Mindy)' but since I wanted to make it more presentable, I used .to_string() method ommitting the index with the False key.

    Voila! We are now done solving all the situations on the first problem. Shall we go now with Problem 2?

## Problem 2: Create a Visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contribuets to a higher average scores?

        For the general first step, import matplotlib.pyplot as plt.

        Step 1: Call .figure() method to create the bar graph with the figsize of 10 inches for the width and 5 inches for the length. I didn't include the word inches because it's already a norm as we input the values in figsize
        Step 2: After that, call the .bar() method with the specification under the variable of student that we used abovementioned dataset. Specify the Track and Average for the first graph: Gender and Average for the second graph: and Hometown and Average for the third graph. 
        Step 3: To make my output more cutesy and presentable, I set Pink as the color of the first graph, Light Purple for the second graph, and Bright Red for the third graph because the time I am making this experiment, its my birthday in 2 hours! :)
        Step 4: In making the x-axis as Track, Gender, and Hometown, I used the .xlabel() method.
        Step 5: In making the y-axis as Average for all the graphs, I used the y.label() method. I also noticed that interchanging these two on which comes first, the output doesn't change.
        Step 6: With the .title() method, I put "The Correlation of the Chosen Track/Gender/Hometown and Average of the Students" as the introduction for the graph.
        Step 7: Lastly, we input print and .show() method to show the graph for our output. Moreover, we can omit the word "print" and just enter "plt.show()", the same output will be shown. 

      And.. Finally, we are done!

# Wrapping it all up!
## And here we have it! Our journey through Data Wrangling and Data Visualization has come to a successful close! We started with raw dataset, full of potential, and transforme it into something truly insightful and visually engaging output.

### Through wrangling, we cleaned and explored the data, making it ready for deeper analysis. Then, we bought that data to life with stunning visuals that not only tell a story but also spark curiosity and understanding.

I hope this experiment gave you a glimpse of how powerful Python can be when it comes to working data. 

# Reminder!
Behind every dataset lies a story waiting to be discovered! :)

## Thank you for following along, and I hope you enjoyed my coding journey through this experiment as much as I did!

Happy Coding,

Jessie Mae Domigo

2ECE-D
