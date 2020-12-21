*This is the public posting of the assignment. See Blackboard for the invite link to make your submission in your own repository in the class organization*
# Homework 6: Data Exploration in R

**Due:** November 10, 2020 by 11:59pm

The goal of this assignment is to practice exploratory data analysis using R. 

## Assignment

The questions and exercises this week come from [Chapter 5 (Data Transformations)](https://r4ds.had.co.nz/transform.html) and [Chapter 7 (Exploratory Data Analysis)](https://r4ds.had.co.nz/exploratory-data-analysis.html) in [*R for Data Science*](https://r4ds.had.co.nz).  You should read and practice the examples in each section before attempting the associated exercises.

Answer each of the questions using RMarkdown. Any R code needed to answer the questions should be runnable and embedded in your report. Make sure to 'Knit' your report to produce Markdown suitable for Github and commit both the .Rmd and .md files (and all images generated by the Knitting process) to your repo.  *It is not sufficient just to answer each question, but you must also explain your answer and describe what you did to arrive at the answer, including necessary code and charts.*

Make sure that you click the links provided to view the questions in the book as some include additional information or figures than what is given below.

*Some of these questions may require significant thought to complete. Do not wait until the last minute to start.*

[Section 5.6.7](https://r4ds.had.co.nz/transform.html#exercises-12)

**Q1.** 4. Look at the number of cancelled flights per day. Is there a pattern? Is the proportion of cancelled flights related to the average delay?

[Section 5.7.1](https://r4ds.had.co.nz/transform.html#exercises-13)

**Q2.** 2. Which plane (`tailnum`) has the worst on-time record?

**Q3.** 4. For each destination, compute the total minutes of delay. *Don't need to answer the 2nd part of the question in the book.*

[Section 7.3.4](https://r4ds.had.co.nz/exploratory-data-analysis.html#exercises-15)

**Q4.** 2. Explore the distribution of `price`. Do you discover anything unusual or surprising? (Hint: Carefully think about the `binwidth` and make sure you try a wide range of values.)

**Q5.** 3. How many diamonds are 0.99 carat? How many are 1 carat? What do you think is the cause of the difference?

[Section 7.5.1.1](https://r4ds.had.co.nz/exploratory-data-analysis.html#exercises-17)

**Q6.** 1. Use what you’ve learned to improve the visualisation of the [departure times of cancelled vs. non-cancelled flights](https://d33wubrfki0l68.cloudfront.net/3b39886be0ed133839461341db7faeb7420c7942/2b3e3/eda_files/figure-html/unnamed-chunk-18-1.png) from the end of [Section 7.4](https://r4ds.had.co.nz/exploratory-data-analysis.html#missing-values-2).

**Q7.** 2. What variable in the diamonds dataset is most important for predicting the price of a diamond? How is that variable correlated with cut? Why does the combination of those two relationships lead to lower quality diamonds being more expensive?

**Extra credit (1 point):** 3. Install the `ggstance` package, and create a horizontal boxplot. How does this compare to using `coord_flip()`?

[Section 7.5.3.1](https://r4ds.had.co.nz/exploratory-data-analysis.html#exercises-19)

**Q8.** 2. Visualise the distribution of carat, partitioned by price.

**Q9.** 3. How does the price distribution of very large diamonds compare to small diamonds? Is it as you expect, or does it surprise you?

**Q10.** 4. Combine two of the techniques you’ve learned to visualise the combined distribution of cut, carat, and price.

## Report

Your report is an important part of this assignment. I expect your report to include your name, CS625-HW6, date, and appropriate headings and Markdown markup for clarity and neatness. You will lose points if there are many spelling or grammatical errors. 

As always, you must include a section titled "References", including links to any examples (other than [*R for Data Science*](https://r4ds.had.co.nz)) that you used in completing this assignment.

## Submission
Make sure that you have committed and pushed your local repo to GitHub.  Include "Ready to grade @weiglemc" in your final commit message. 

Submit the URL of your report in Blackboard:
* Click on HW6 under Assignments in Blackboard
* Under "Assignment Submission", click the "Write Submission" button.
* Copy/paste the URL of your `report.md` file into the edit box (should be something like https<nolink>://github.com/cs625-datavis-fall20/hw6-explore-*username*/blob/master/report.md)
* Make sure to "Submit" your assignment.