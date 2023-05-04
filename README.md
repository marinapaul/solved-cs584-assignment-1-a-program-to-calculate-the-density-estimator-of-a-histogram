Download Link: https://assignmentchef.com/product/solved-cs584-assignment-1-a-program-to-calculate-the-density-estimator-of-a-histogram
<br>



Question 1

Write a Python program to calculate the density estimator of a histogram.  Use the field <em>x</em> in the NormalSample.csv file.

a.(5 points) According to Izenman (1991) method, what is the recommended bin-width for the histogram of x?

b.(5 points) What are the minimum and the maximum values of the field x?

c.(5 points) Let a be the largest integer less than the minimum value of the field x, and b be the smallest integer greater than the maximum value of the field x. What are the values of a and b?

d.(5 points) Use h = 0.25, minimum = a and maximum = b. List the coordinates of the density estimator. Paste the histogram drawn using Python or your favorite graphing tools.

e.(5 points) Use h = 0.5, minimum = a and maximum = b. List the coordinates of the density estimator. Paste the histogram drawn using Python or your favorite graphing tools.




f.(5 points) Use h = 1, minimum = a and maximum = b. List the coordinates of the density estimator. Paste the histogram drawn using Python or your favorite graphing tools.

g.(5 points) Use h = 2, minimum = a and maximum = b. List the coordinates of the density estimator. Paste the histogram drawn using Python or your favorite graphing tools.

h.(5 points) Among the four histograms, which one, in your honest opinions, can best provide your insights into the shape and the spread of the distribution of the field x? Please state your arguments.

Question 2

Use in the NormalSample.csv to generate box-plots for answering the following questions.

a.(5 points) What is the five-number summary of x? What are the values of the 1.5 IQR whiskers? Ans: Minimum:  3

b.(5 points) What is the five-number summary of x for each category of the group? What are the values of the 1.5 IQR whiskers for each category of the group?

c.(5 points) Draw a boxplot of x (without the group) using the Python boxplot function. Can you tell if the Python’s boxplot has displayed the 1.5 IQR whiskers correctly?

d.(5 points) Draw a graph where it contains the boxplot of x, the boxplot of x for each category of Group (i.e., three boxplots within the same graph frame). Use the 1.5 IQR whiskers, identify the outliers of x, if any, for the entire data and for each category of the group.

Question 3

The data, FRAUD.csv, contains results of fraud investigations of 5,960 cases.  The binary variable FRAUD indicates the result of a fraud investigation: 1 = Fraudulent, 0 = Otherwise.  The other interval variables contain information about the cases.

<ol>

 <li>TOTAL_SPEND: Total amount of claims in dollars</li>

 <li>DOCTOR_VISITS: Number of visits to a doctor</li>

 <li>NUM_CLAIMS: Number of claims made recently</li>

 <li>MEMBER_DURATION: Membership duration in number of months</li>

 <li>OPTOM_PRESC: Number of optical examinations</li>

 <li>NUM_MEMBERS: Number of members covered</li>

</ol>

You are asked to use the Nearest Neighbors algorithm to predict the likelihood of fraud.

a.(5 points) What percent of investigations are found to be fraudulent? Please give your answer up to 4 decimal places.

b.(5 points) Use the BOXPLOT function to produce horizontal box-plots. For each interval variable, one box-plot for the fraudulent observations, and another box-plot for the non-fraudulent observations.  These two box-plots must appear in the same graph for each interval variable.

c.(10 points) Orthonormalize interval variables and use the resulting variables for the nearest neighbor analysis. Use only the dimensions whose corresponding eigenvalues are greater than one.

i. (5 points) How many dimensions are used?

ii. (5 points) Please provide the transformation matrix? You must provide proof that the resulting variables are actually orthonormal.

iii.Proof that the resulting variables are actually orthonormal.

Identity Matrix = Transpose(Transformation of x) * (Transformation of x)

d. Use the NearestNeighbors module to execute the Nearest Neighbors algorithm using exactly <u>five</u> neighbors and the resulting variables you have chosen in c). The KNeighborsClassifier module has a score function.

i.(5 points) Run the score function, provide the function return value

ii.  (5 points) Explain the meaning of the score function return value.

e.For the observation which has these input variable values: TOTAL_SPEND = 7500,

f.(5 points) Follow-up with e), what is the predicted probability of fraudulent (i.e., FRAUD = 1)? If your predicted probability is greater than or equal to your answer in a), then the observation

will be classified as fraudulent.  Otherwise, non-fraudulent.  Based on this criterion, will this observation be misclassified?


