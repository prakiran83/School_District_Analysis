# School_District_Analysis

# Overview
The purpose of this analysis is to root out any discrepancies from the final result of the School District Analysis data. According to the school board, they have suspected that Thomas High School (THS) has altered some of their reading and math scores. But, since they do not have the full extent to which the fraud has been committed, they want us to help them figure it out. So, in order to achieve what the board has asked us for, we are going to replace the math and reading scores for THS with NaNs while keeping the rest of the data in its original form.
Apart from analyzing the scores, we will also be looking at the effect of changing the score to NaN against the score for other categories as school spending, school size, and school type.

# Result

After replacing and reviewing the math and reading scores for 9th graders at THS with NaNs, the only changes that could be observed were the averages and percentage of passing in THS. Although there were changes, none of these changes were significant enough to skew the data. The results can be compared through the tables below:

### Before removing the data:
![1st](https://user-images.githubusercontent.com/100887673/161441682-f4dfa7dd-4e6e-4466-bc3b-9d6a7f18e2f7.png)
### After removing the data:
![2nd](https://user-images.githubusercontent.com/100887673/161441731-3ee34080-2110-4b2c-982d-f5c24e736794.png)

Whereas, the other fields that we analyzed remained the same:

# Score by School Size
  #### Before
  
  ![school_size 1](https://user-images.githubusercontent.com/100887673/161441863-4b591a7a-6e1c-4aee-b499-53cb33fb7a95.png)
  
  #### After
  ![school_size 2](https://user-images.githubusercontent.com/100887673/161441869-f364e952-f974-4a0c-a52c-915311e3bd50.png)
  
# Score by School Type
  #### Before
  ![school_type 1](https://user-images.githubusercontent.com/100887673/161441925-2a3cc446-3646-4a20-8470-abe4f36ab6ee.png)

  #### After
  ![school_type 2](https://user-images.githubusercontent.com/100887673/161441940-42c1b8dc-9e17-4e8e-a687-e60fa81cf635.png)
  
# Score by Spending
  #### Before
  ![spending_range 1](https://user-images.githubusercontent.com/100887673/161441987-9f4d6c5a-3067-45f1-84e1-2e4e47f55b45.png)

  #### After
  ![spending_range 2](https://user-images.githubusercontent.com/100887673/161441993-e43b2a4b-6f6e-42f6-80bf-6c6f795ccaa6.png)

Although the changes were very insignificant, we must consider the fact that we removed just a fraction of a large amount of data to have any significant movement in our database.

# Summary
The four changes in the updated School District Analysis after reading and math scores for the ninth grade at THS have been replaced with NaNs are:
  1. It affected the number of total students,
  2. It affected the number of student in THS,
  3. It changed the average score for math and reading, not significantly, &
  4. It change the percentages for math and reading at THS, also not significantly.
