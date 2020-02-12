Ford GoBike System Data dataset



Exploratory:

Step 1: in Figure[1] : I tried to look at duration_sec varible and I found it difficult to see the over all shape so I used log scale in Figure[2] and the data looks normally distributed
Step 2: in Figure[3] : I start asking if the data contains null values or not so I can takecare of this will analyzing and I found that the data have a lot of missing values in member_geder column and member_birth_year column with the same number of missing 
and I can not found the missing data in other columns or sources so I decided to analyze the data related to this two column with giving attention that the analyzing done on members how has gender values in member_gender column and birth year values in 
member_birth_year column
Step 3: in Figure[4]: after step 2 I decided to know what's the percentage of each gender we have in our data and found that 76.9% of our users how fill their genders are male, 21.8% are female, and 1.4% are other
Step 4: in Figure[5]: I decided to know what's the percentage of each user type - Subscriber or Customer- we have in our data and found that 78.7% of our users are Subscribers and 21.3 of our users are Customers
Step 5: in Figure[6]: I tried to know if gender type percentage will change by changing user type or male will still in the first and I found that in Customer type we have 67.8% are male, 30.3 are female, and 1.9% are other and in Subscriber type we have 77.9% are male, 20.7 are Female, and 1.3 are other
Step 6: in Figure[7]: I want to know how many seconds each type of gender spends
Step 7: in Figure[8]: I want to know which gender spends more time in average and I found that Female is the most with 1027.9 second in average
Step 8: in Figure[9]: I want to know how many seconds each type of user spends
Step 9: in Figure[10]: I want to know which user type spends more time in average and I found that Customer is the most with 2557.45 in average
Step 10:in Figure[11], Figure[12]: I tried to see the relation between birth year and member gender or user type and it was difficult to see relation between them
Step 11: I use faceting but can't change label or title so I separate each plot alone in Figure[14] and Figure[15]


Explanatory:

Step 1 : From exploratory step I get some questions to ask like:
1- What's the precentage of each gender type?
2- What's the precentage of user type -cutomers and subscribers-?
3- What's the precentage of each gender type by each user type?
4- What's the average duration was spent by each gender type?
5- What's the average duration was spent by each user type?
6- What's the average dutation was spend by each gender by user type?

Step 2: I move my plots that answer these question in another jupyter notebook and rename it's figure and start answer each question by each plot the write the results.
