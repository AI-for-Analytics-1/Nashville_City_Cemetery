# Nashville City Cemetery

The city of Nashville provides a dataset of known burials in city cemeteries from 1846 through 1979. https://docs.google.com/spreadsheets/d/13Nu6ScrK6FC1EnCaCeYddLTRbIc4S5JE/edit?usp=sharing&ouid=117851103307096970737&rtpof=true&sd=true

We are going to use the assistance of AI (Claude) to help us clean and organize the data.  During this process we will pay close attention to the tasks in which Claude can be used to save time but more importantly, we want to see tasks in which Claude falls short and will require oversight.

1. Create a pivot table with 10 most common causes of death.  Those of you familiar with this data will recognize some of the issues right away.
Think about what the issues are and how you would manually go about fixing them and updating the table.

2. We want to use Claude to handle some of this tedious task.  Ask Claude if it can examine the Cause of Death column and fix some spelling errors
and group some Cause of Deaths together.  (Example liver cancer and lung cancer can both be grouped as cancer and heart disease and heart attack can be grouped together.   However we don't want Scarlet Fever and Yellow Fever grouped because they are different diseases with a common symptom).  You
can tell Claude to ask you for more details when you write your prompt.   When Claude is done cleaning and grouping you can instruct it to add the
updated Cause of Death into a new column named "Cause of Death Updated"

3. Ask Claude for the top 10 known causes of death from your updated column.  You can compare results with other students.  Differences could be due to chance or a slightly different prompt.

4. Ask Claude if there were any years that had a spike in the number of burials.  Claude may have given you an explanation for the results. Does the explanation make sense?  Do the number used as supporting evidence make sense?

5. There seems to be a spike during the Civil War, ask Claude if the Civil War had any impact of the age of those being buried.  Do the values and explanation make sense?

6. Ask Claude to make a new column named 'decade' next to the Year column.  Ask Claude to use this format - 1840's

7. Ask Claude to make a new column named 'age group' next to age.  You want children 5 or less listed as child, 6-17 listed as minors, 18-30 listed as young adults, 31-50 as middle aged, and older than 50 will be older adults.  If there is and blank for age fill in the age group value as unknown.

8. Ask Claude to make a pivot table that shows the count of burials and most common burial decade for each age group.  Was there anything interesting in these results? How is Claude's interpretation?

9. On the same sheet, ask Claude to give a count for the number of burials by age group for each year of the 1860's.  Was there anything interesting in these results?  How is Claude's interpretation?

10. Finally, ask Claude to build you a dashboard. You can either choose a focus or allow Claude to choose important metrics.  End your prompt with "Ask if you have any questions."  Hopefully, Claude will respond with clarification and allow you more control over the finished product.

11. Examine the results.  Check for how well organized the dashboard is.  Check the Axes of charts, do they make sense.  Does all the numeric values make sense.  Are there any changes you would make?  You can ask Claude to make those changes and improve the appearance of the dashboard.  How satisfactory were Claude's corrections?

12. Overall, which tasks were you surprised Claude was able to do quickly, efficiently, and/or accurately.  More important which tasks did Claude surprise you with mistakes and errors - which tasks does it require additional supervision.
