# School_District_Analysis

## Overview of the school district analysis
The purpose of this project is to analyze a city school district's standardized testing data to gain insights and key metrics. This includes analyzing the data on student funding and scores by aggregating testing data and showing trends in school performances. The school district's school board and superintendent will use the analysis in making decisions about school budgets and priorities.

### Problem to solve and analyze
The school board has notified that the reading and math grades for Thomas High School ninth graders have been altered. Therefore, the math and reading scores for Thomas High School will be replaced with "NaNs" while keeping the rest of the data for the high school. After making this change, the school district analysis will be repeated to see how this change affected the overall analysis. This analysis will then be shared to the school district and superintendent to have a more accurate analysis of all the schools within the district.




## Results 

### District summary
* How is the district summary affected? 
   The district summary after dropping 9th grader standardized test scores for Thomas High School slightly affected the metrics of the distract summary. After making this adjustment, the average math score decreased very slightly from 79% to 78.9%. The average reading scored just about the same at 81.9%. For the total student’s percentage passing math decreased from 75% to 74.8% and the percentage passing reading decreased from 86% to 85.7%. Finally, the overall passing percentage went from 65% to 64.9%. The affects to the district summary were not very significant but in general brought down the scores averaging and passing rates for both subject.
   
   ### School summary
* How is the school summary affected?
  The school summary was only affected the for metrics for Thomas High Schools. All the other school’s metrics were not affected in the school summary data frame.
  
  
* How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to other schools?
  Replacing the ninth graders' standardized test scores affected Thomas High School's performance especially in their percentage passing reading and math as well as the overall passing percentage. Below is a list of how the numbers changed after taking out the ninth graders scores. Relative to other schools, Thomas High School stayed the same as they still place second for top 5 schools based on overall passing percentage.
  
                                     Before Change                     After Change  
                                     Avg. Math Score: 83.4%          Avg. Math Score: 83.4%
                                     Avg. Reading Score: 83.8%       Avg. Reading Score: 83.9%
                                     % Passing Math: 93.3%           % Passing Math: 93.2%
                                     % Passing Reading: 97.3%        % Passing Reading: 97.0%
                                     % Overall Passing: 90.9%        % Overall Passing: 90.6%
                                     
                                     
     Dataframe showing top 5 schools based on overall passing percentage:
                     
     ![image](https://user-images.githubusercontent.com/96553992/151630124-60c4fd27-c814-4f60-a515-b332d1586330.png)

  ### Replacing ninth graders effects on categories
* How does replacing the ninth-grade scores affect the following?


  * Math and reading scores by grade
      Replacing the ninth-grade scores did not affect the math and reading scores by grade. All that is seen is that for Thomas High School 9th grade, "nan" is seen as all test scores were taken out.


  * Scores by school spending
  
     Only the ($630 -644) spending per student category range was affected when analyzing scores for spending ranges on students. The change was not significant or consistent. Below are the differences in percentages for before and after for the ($630 - $644) spending range per student.

                                   Before Change                     After Change  
                                     Avg. Math Score: 78.52%         Avg. Math Score: 78.50 (Decrease)
                                     Avg. Reading Score: 81.62       Avg. Reading Score: 81.64 (Increase)
                                     % Passing Math: 73.48%          % Passing Math: 73.46 (Decrease)
                                     % Passing Reading: 84.39%       % Passing Reading: 84.32% (Decrease)
                                     % Overall Passing: 62.86%       % Overall Passing: 62.78% (Decrease)
  * Scores by school size
      Replacing the ninth graders scores had no effect on the scores based on schools grouped into sizes.
  * Scores by school type
      There was no effect on the scores based on schools grouped into district or charter types.
      


### Summary 


Overall, replacing the ninth-grade standardized test scores for Thomas high school had minor effects in some of the results. As seen above, there was not a drastic change for the metrics in the summary data frame but in general decreased the scores and passing percentages. For the school summary, only the Thomas High Schools' metrics were affected but they continue to be in 2nd place for percentage overall passing. Finally, for the metrics based on categories school size, school type, and scores broken down by grades were not impacted. However, metrics on school spending changed for the ($630-$644) category. Thomas High School's school data affected this in this category because their per student budget is $638. It is positive that the changes in results were very minor because that means the results are still accurately capturing the overall analysis of the district schools standardized tests scores. 

