# AlteryxWeeklyChallengeSolutions
This repo contains solutions to Alteryx Weekly Challenges posted on Alteryx Community page.

# Challenge 135:

There are 1000 lockers in a high school with 1000 students. The problem begins with the first student opening all 1000 lockers; the second student closes lockers 2,4,6,8,10 and so on to locker 1000; the third student changes the state (opens lockers closed, closes lockers open) on lockers 3,6,9,12,15 and so on; the fourth student changes the state of lockers 4,8,12,16 and so on. This goes on until
every student has had a turn.

When all 1,000 students have finished, which locker doors are open?

# Challenge 134:

You have been tasked with finding the amount of days that elapsed from one email to another. Please provide the amount of days between emails (without regard for time) in chronological order according to the data in the "Date:" record for each email.

# Challenge 133:

NASA Lab Location Analysis
Researchers need to understand which NASA research facility is most optimally located. Specifically, which facility has the most other facilities within 200 miles. Once that facility is determined, they want to create a polygon that bounds the spatial points of the facility and the other facilities within 200 miles.

# Challenge 132:

Happy 3rd Anniversary Community! It has been a wild and crazy three years. Now let's see what the future of Community looks like. In the workflow, the data represents the number of posts posted on a monthly basis. Note that the first record contains a count of posts before 2017-01-01 and each record thereafter represents a month between 2017-01-01 and 2018-08-01. Your job is to forecast (ARIMA) in what future month Community will surpass the 1 Million post milestone using the high end of the 80% confidence interval (because we are optimists). Sound off what you got!

# Challenge 131:

“Think like a CSE” series. 
The Case: A co-worker is running into the R error “Append Cluster: Error: cannot allocate vector of size 7531.1 Gb“ in a workflow that uses a couple of the Predictive Clustering Tools. This error is causing the workflow to stop running before completing.
Your Goal: Identify the root cause of the issue, and develop a solution or workaround to help your co-worker get past this error and finish running the workflow. 
Asset Description: Your co-worker can’t share the file with you due to client privacy concerns, but it is about 7 GB in size (3 million records and 30 fields). Using only the provided screenshots, dummy data of your own design, and sheer willpower, can you develop a possible resolution?

# Challenge 130:

You have a source system that doesn't seem to be working quite as expected. The system will frequently take any given word and duplicate it within a string. You job is to clean it up! Below we have a few sample phrases that are indicative of the system's problem. Find all words that have duplicate consecutive words and reduce the duplication to a single word again! 

# Challenge 129:
You are hosting a lunch event and you have 5 possible locations. Your task is to choose the location that minimizes the overall cost (accounting for the benefit) to the company and report the cost.

Assumptions
- A person will only come if the location is under 10 miles from their location.
- The benefit of a person coming to the event is $20.
- The cost of a "missed opportunity" (people you must turn away after capacity is reached) is $5. Note that this only applies to those under 10 miles from the location.

Data
Locations: the 5 potential locations, the fixed price, and the capacity
Customers: the location of your customers and the count of employees that would come to your event

# Challenge 128:

A group of friends are playing their favorite game. Not being a bunch of data analysts and understanding the importance of inputting data in an easy to work with way, they devised an incredibly inefficient way to keep score of their game! In the game, there is 5 rounds of play and 5 players (a,b,c,d,e - first letter of their names). For each lowercase letter under their initial, 1 point is awarded. For each uppercase letter, 1 point is subtracted from their overall score. As the only right and fair arbiter, they call you in to use Alteryx to figure out each players score for each round and their respective totals. Who won?

# Challenge 127:

Your company is dedicated to retaining employees. Your task is to identify the active employees who are most at risk to leave (defined as probability >= .5). To do this, you will build a Decision Tree and a Logistic Regression (using default configuration) and choose the model with the highest accuracy (as shown in the "I" output).

Assumptions
- You will use the field  "Employment_Status" as the target variable in the model.
- You will use existing fields as predictor variables in the models - "Department," Pay_Rate," Marital_Status." Performance_Score." and "Age."
- Create "Days_of_Employment" as a variable for the model as type "Double" and use "days" as the  unit. For current employees, use the date of the Grand Prix (2018-07-05) to calculate days of employment. For terminated employees, use the date of termination instead.
- All records should be used to create the models
- Only active employees should be evaluated for risk to leave


Data
Employee data on current and terminated employees. "Employment_Status" indicates who is still with the company and who has left.


# Challenge 126:

In this week's challenge, we are trying to prep our data for a time lapse visualization of certification exams passed in each country. In order to achieve this visualization, we have to make sure that each country has a running total for every day between 10/1/2018 and today (datetimenow). However, we only have dates for when a certificate was earned by each country. For each country, add in all the date gaps, calculate a running totals and update the running totals to report '0' for a running total in time before the first exam was passed.

# Challenge 125:

Recently the company's Human Resources business partner went on earlier than expected maternity leave and the Human Resources VP has asked you to finalize a dataset for personnel risk assessments. Clean up the data so it is in a useable format for the HR team to use in their initiative and provide a data summary of the new file to the VP for review.

Assumptions
- HR VP said there are two relevant files:
        1. One called 'Personnel' something and was stored as a .csv that contains employee number, name, and other descriptors
        2. One related to employment status, also a .csv, that contains information about active vs terminated employees
- The fields should be stored as their smallest possible size and type.
- Convert "Hire Date" and "Termination Date" to "Date" fields.
- Pay_Rate needs to be a double field type for HR's next steps
- Join the files on "Employee Number"
- The Field Summary tool will provide the necessary report

