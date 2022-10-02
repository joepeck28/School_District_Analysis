# School_District_Analysis
## Comparing average scores, budgets, and enrollment numbers.
### Importing the data
- We started by importing and and preparing the data.

  ![image](https://user-images.githubusercontent.com/110148559/193394908-00c2e4c2-4456-45d7-9641-c0debb85f0dd.png)
- Then checking to make sure the data was in place

  ![image](https://user-images.githubusercontent.com/110148559/193394926-25f5bcd9-a591-46cc-a68e-0e4283b8f2b8.png)
### Cleaning the data
- The data were checked for null values 

  ![image](https://user-images.githubusercontent.com/110148559/193395026-d46540f7-2838-4e0a-9c92-06fede794d1a.png)
- Then verified after the null values were removed 

  ![image](https://user-images.githubusercontent.com/110148559/193395063-dac3211b-bbfa-4347-9af8-fb822d799321.png)
- Then the data were checked for and removal of duplicate values 

  ![image](https://user-images.githubusercontent.com/110148559/193395123-2346b010-4d9d-4fc0-946c-e89b2a6c7cc8.png)
- A little more work was done to ensure proper analysis by making the grade levels recognizeable as numbers and not objects

  ![image](https://user-images.githubusercontent.com/110148559/193395248-4ce811ee-38de-4807-90df-6cd931638240.png)

  ![image](https://user-images.githubusercontent.com/110148559/193395253-dfbfd033-45ff-4004-8a10-cde22ad5a5a5.png)

  ![image](https://user-images.githubusercontent.com/110148559/193395265-f98c6abb-5a9a-4335-a4c5-da9ea6a56d6b.png)
### Data Summary
- We were asked to provide summary of the data uding the .describe function
  ![image](https://user-images.githubusercontent.com/110148559/193395460-8b53f1b2-0e54-4684-aa41-323c630b011d.png)

- Then we really got into the heart of the data and the practical information it could show us.
    * An overview of the performance across the 9th grade at all schools in the dataset
  ![image](https://user-images.githubusercontent.com/110148559/193395616-56c6175d-28c5-4a27-9a72-848c2635091d.png)
    * The lowest reading score

  ![image](https://user-images.githubusercontent.com/110148559/193395771-ea112d0a-9c97-493d-b3fb-8c885aaf7e03.png)
    * The mean of the reading scores across grades 11 and 12
  ![image](https://user-images.githubusercontent.com/110148559/193395809-4f252e45-5bdc-461d-9ca0-f34ee842e226.png)

### Comparisons
We looked at the school types, and their respective reading and math scores
  ![image](https://user-images.githubusercontent.com/110148559/193395944-bd310531-fbd1-4acd-b0ea-05ecbc45cba2.png)

Then we examined the the budget and enrollment numbers at each school.
  ![image](https://user-images.githubusercontent.com/110148559/193396019-a7bcfa1d-4210-44b4-9cf2-28ec061a6697.png)

The last piece of data was very interesting, showing a sharp decrease in math scores from grade 9 to 12 in the charter schools and a relatively steady performance in the public shools.

  ![image](https://user-images.githubusercontent.com/110148559/193396112-20ce5e8f-9055-45f2-965f-e09caf535881.png)
  
  ## Project Overview
  I am confident that my code is correct, but I am fairly certain that it isn't pretty. I struggled with the groupby and sort_values section. I find it interesting that charter schools seem to perform better with a smaller budget. I think that additional data on SES and population density would prove to add context to the results of this analysis. The test scores in comparison to budget alone cannot reflect the efficacy of a school to the community it serves.
  
### Addendum
I added a new version of the enrollment counter that I think is much better, I wanted to leave the original, but there is an additional one that shows my improved version. I was helping a classmate to understand the problem and solution and I was able to rework the code and make it better.  
